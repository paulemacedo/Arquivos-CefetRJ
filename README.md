# Organização de Estruturas de Arquivos

Bem-vindo ao repositório dos algoritmos desenvolvidos durante a disciplina de Organização de Estruturas de Arquivos. Este repositório contém uma coleção de algoritmos implementados em C como parte das atividades e projetos do curso.

## Índice

- [Descrição](#descrição)
- [Estrutura do Repositório](#estrutura-do-repositório)
- [Algoritmos Implementados](#algoritmos-implementados)
- [Como Usar](#como-usar)
- [Requisitos](#requisitos)
- [Instalação](#instalação)

## Descrição

Este repositório contém uma série de algoritmos que foram desenvolvidos para a disciplina de Arquivos. A disciplina foca em ensinar os fundamentos da organização e manipulação de estruturas de arquivos, além da criação de algoritmos eficientes para lidar com dados armazenados em arquivos.

## Estrutura do Repositório

A estrutura do repositório está organizada da seguinte forma:

```
Arquivos-CefetRJ/
│
├── src/
│   ├── copiar_arquivo.cpp
│   ├── netppm_converter_escala_de_cinza.c
│   ├── contagem_caracteres.cpp
│   ├── conversor_quebra_linha.cpp
│   └── ...
│
└── README.md
```

## Algoritmos Implementados

Aqui está uma lista dos algoritmos implementados neste repositório:

1. Copiar Arquivo (`copiar_arquivo.c`)
2. Conversor de Imagem PPM para Escala de Cinza (`netppm_converter_escala_de_cinza.c`)
3. Contagem de Caracteres em Arquivo (`contagem_caracteres.c`)
4. Conversor de Quebra de Linha (`conversor_quebra_linha.c`)
5. Outros algoritmos diversos

Cada algoritmo está localizado na pasta `src/` com um arquivo C ou C++ correspondente.

## Como Usar

Para compilar e executar qualquer um dos algoritmos, basta clonar este repositório e usar um compilador C ou C++, como `gcc` ou `g++`. Por exemplo:

```bash
git clone https://github.com/seu-usuario/OEA-Algoritmos.git
cd OEA-Algoritmos/src
gcc netppm_converter_escala_de_cinza.c -o netppm_converter_escala_de_cinza
./netppm_converter_escala_de_cinza entrada.ppm saida.ppm
```

Para compilar um arquivo C++:

```bash
g++ copiar_arquivo.cpp -o copiar_arquivo
./copiar_arquivo arquivo_origem arquivo_destino
```

## Requisitos

- Compilador C (como `gcc`)

## Instalação

Para instalar um compilador C no seu sistema, siga as instruções específicas para o seu sistema operacional. Por exemplo, no Ubuntu, você pode usar:

```bash
sudo apt-get update
sudo apt-get install build-essential
```
