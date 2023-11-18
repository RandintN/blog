+++
author = "Robson Cassiano"
title = "Gerenciando a Instalação da JDK no Linux com SDKMAN"
date = "2018-02-23"
description = "Gerenciando a Instalação da JDK no Linux com SDKMAN"
tags = ["java", "linux"]
+++
![SDKMAN](https://sdkman.io/assets//img/logo.png)

{{< youtube cOBMViq3KnM >}}


Se você é um desenvolvedor de software que trabalha com Java e usa um ambiente Linux, o SDKMAN é uma ferramenta essencial que simplificará o processo de instalação e gerenciamento das versões do Java Development Kit (JDK). Neste artigo, exploraremos os benefícios do SDKMAN e forneceremos instruções básicas para instalá-lo e configurá-lo no seu sistema.

## Por que usar o SDKMAN?

O SDKMAN é uma ferramenta de gerenciamento de software que facilita a instalação e o uso de várias versões do JDK, bem como outras ferramentas relacionadas, como Groovy, Kotlin e Gradle. Aqui estão alguns dos principais benefícios de usar o SDKMAN:

- **Simplicidade**: O SDKMAN simplifica a instalação de várias versões do JDK com um único comando. Isso é particularmente útil se você trabalha em diferentes projetos que requerem versões diferentes do Java.

- **Facilidade de Uso**: A interface do SDKMAN é amigável e fácil de usar. Você não precisa se preocupar com variáveis de ambiente ou configurações complexas.

- **Atualizações e Rollbacks**: Com o SDKMAN, você pode facilmente atualizar para as versões mais recentes do JDK ou reverter para versões anteriores, se necessário.

- **Outras Ferramentas**: Além do JDK, o SDKMAN suporta várias outras ferramentas de desenvolvimento, permitindo que você as instale e gerencie com a mesma facilidade.

## Instalação do SDKMAN

A instalação do SDKMAN é simples e direta. Siga as etapas abaixo para configurá-lo no seu sistema Linux(é necessário ter o **zip** e o **unzip** instaldo na sua Distribuição Linux):

1. Abra um terminal e execute o seguinte comando para baixar e instalar o SDKMAN:

```shell
curl -s "https://get.sdkman.io" | bash
```

Após essa instalação, reinicie o terminal.

## Instalando o JDK com o SDKMAN
Agora que o SDKMAN está instalado, você pode usar o comando sdk para instalar e gerenciar várias versões do JDK. Por exemplo, para instalar a versão mais recente do OpenJDK, execute o seguinte comando:

```shell
sdk install java
```

Para instalar uma versão específica do JDK, você pode fornecer o número da versão, como:

```shell
sdk install java 21-amzn
```
Após a instalação, você pode alternar entre as versões do JDK usando o comando use:

```shell
sdk use java 21-amzn
```

## Conclusão

O SDKMAN é uma ferramenta poderosa para simplificar o gerenciamento de diferentes versões do JDK no ambiente Linux. Com sua interface fácil de usar e comandos simples, ele permite que os desenvolvedores de software economizem tempo e esforço na configuração do ambiente de desenvolvimento.

Para obter mais informações e recursos, visite [o site oficial do SDKMAN](https://sdkman.io/).

Neste artigo, destacamos os benefícios do SDKMAN e fornecemos instruções básicas para instalá-lo e configurá-lo. Agora você pode começar a usar o SDKMAN para simplificar seu fluxo de trabalho de desenvolvimento Java no Linux.
