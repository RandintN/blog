+++
author = "Robson Cassiano"
title = "Nala: uma alternativa mais amigável ao gerenciador de pacotes APT"
date = "2023-02-01"
description = "Nala: uma alternativa mais amigável ao gerenciador de pacotes APT"
tags = ["linux"]
+++

O Nala é um gerenciador de pacotes frontend para o APT, o gerenciador de pacotes padrão para sistemas operacionais Linux baseados em Debian, como Ubuntu e Mint. 

O Nala fornece uma interface mais amigável e fácil de usar para o APT, com recursos como:

* **Saída colorida e formatada:** O Nala fornece uma saída colorida e formatada que é mais fácil de ler e entender.
* **Completamento de tabulação:** O Nala suporta o preenchimento de tabulação, o que torna mais fácil digitar comandos.
* **Suporte para pesquisa e filtragem:** O Nala permite que você pesquise e filtre pacotes, o que facilita encontrar o que você precisa.

## Instalação do Nala

Para instalar o Nala, você precisará ter o Python 3 instalado em seu sistema. Em seguida, você pode usar o seguinte comando para instalar o Nala:

```shell
sudo apt install nala
```

## Uso do Nala
O Nala usa os mesmos comandos básicos do APT. Por exemplo, para atualizar o índice de pacotes, você usaria o seguinte comando:

```shell
nala update
```
Para instalar um pacote, você usaria o seguinte comando:

```shell
nala install <nome do pacote>
```
Para remover um pacote, você usaria o seguinte comando:

```shell
nala remove <nome do pacote>
```

## Servidor mais rápido

O Nala pode selecionar os servidores mais rápidos pra você e baixar vários pacotes ao mesmo tempo, basta usar o comando:

```shell
sudo nala fetch
```
E selecione os servidores mais rápidos.

## Comparação com o APT
O Nala oferece uma série de vantagens sobre o APT, incluindo:

**Interface mais amigável:** O Nala é mais fácil de usar do que o APT, pois fornece uma interface mais colorida e formatada.

**Completamento de tabulação:** O Nala suporta o preenchimento de tabulação, o que torna mais fácil digitar comandos.

**Suporte para pesquisa e filtragem:** O Nala permite que você pesquise e filtre pacotes, o que facilita encontrar o que você precisa.

## Conclusão
O Nala é uma excelente opção para usuários que procuram uma alternativa mais amigável ao gerenciador de pacotes APT. O Nala oferece uma série de recursos que o tornam mais fácil de usar e mais poderoso.