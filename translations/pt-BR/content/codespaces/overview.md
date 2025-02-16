---
title: Visão geral do GitHub Codespaces
shortTitle: Visão Geral
product: '{% data reusables.gated-features.codespaces %}'
intro: 'Este guia apresenta {% data variables.product.prodname_codespaces %} e fornece informações sobre como ele funciona e como usá-lo.'
allowTitleToDifferFromFilename: true
redirect_from:
  - /codespaces/codespaces-reference/about-codespaces
  - /github/developing-online-with-github-codespaces/about-github-codespaces
  - /github/developing-online-with-codespaces/about-codespaces
  - /codespaces/getting-started-with-codespaces/about-codespaces
  - /codespaces/about-codespaces
versions:
  fpt: '*'
  ghec: '*'
type: overview
topics:
  - Codespaces
---

## O que é um codespace?

Um codespace é um ambiente de desenvolvimento hospedado na nuvem. Você pode personalizar o seu projeto para {% data variables.product.prodname_codespaces %}, fazendo commit de [arquivos de configuração](/codespaces/customizing-your-codespace/configuring-codespaces-for-your-project) para o seu repositório (geralmente conhecido como configuração como código), que cria uma configuração de código reproduzível para todos os usuários do seu projeto.

{% data variables.product.prodname_codespaces %} é executado em uma série de opções de computação baseadas em VM, hospedadas por {% data variables.product.product_location %}, que você pode configurar a partir de 2 a 32 máquinas centrais. Você pode conectar-se aos seus codespaces a partir do navegador ou localmente usando o {% data variables.product.prodname_vscode %}.

![Um diagrama que mostra como {% data variables.product.prodname_codespaces %} funciona](/assets/images/help/codespaces/codespaces-diagram.png)

## Usando codespaces

Você pode criar um codespace a partir de qualquer branch ou commit no seu repositório e começar a desenvolver usando recursos de computação baseados na nuvem. {% data reusables.codespaces.links-to-get-started %}

To customize the runtimes and tools in your codespace, you can create one or more dev container configurations for your repository. Adding dev container configurations to your repository allows you to define a choice of different development environments that are appropriate for the work people will do in your repository.

If you don't add a dev container configuration, {% data variables.product.prodname_codespaces %} will clone your repository into an environment with the default codespace image that includes many tools, languages, and runtime environments. Para obter mais informações, consulte "[Introdução a contêineres de desenvolvimento](/codespaces/setting-up-your-codespace/configuring-codespaces-for-your-project)".

Você também pode personalizar aspectos do ambiente do seu codespace usando um repositório público do [dotfiles](https://dotfiles.github.io/tutorials/) e [Sincronização de configurações](https://code.visualstudio.com/docs/editor/settings-sync). A personalização pode incluir preferências de shell, ferramentas adicionais, configurações de editor e extensões de código VS. Para obter mais informações, consulte[Personalizando seu codespace](/codespaces/customizing-your-codespace)".

## Sobre a cobrança do {% data variables.product.prodname_codespaces %}

Para informações sobre os preços, o armazenamento e o uso para {% data variables.product.prodname_codespaces %}, consulte "[Gerenciando a cobrança para {% data variables.product.prodname_codespaces %}](/billing/managing-billing-for-github-codespaces/about-billing-for-codespaces)".

{% data reusables.codespaces.codespaces-spending-limit-requirement %} Para informações sobre como as organizações proprietários e gerentes de cobrança podem gerenciar o limite de gastos de {% data variables.product.prodname_codespaces %} para uma organização, consulte "[Gerenciar o seu limite de gastos para {% data variables.product.prodname_codespaces %}](/billing/managing-billing-for-github-codespaces/managing-spending-limits-for-codespaces)".
