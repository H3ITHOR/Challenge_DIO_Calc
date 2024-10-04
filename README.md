# Calculadora de Partidas Rankeadas

## Descrição

Este projeto é uma **Calculadora de Partidas Rankeadas** que permite calcular o saldo de vitórias e derrotas de um jogador e determinar seu nível em um sistema de classificação. O objetivo é ajudar os jogadores a entenderem melhor sua performance em partidas e como isso afeta seu nível.

## Tecnologias Utilizadas

- JavaScript
- Node.js
- Módulo `readline` do Node.js para entrada de dados

## Como Funciona

O programa pede ao usuário para inserir a quantidade de vitórias e derrotas que o jogador teve. Com base nesses dados, ele calcula o saldo de vitórias e determina o nível do jogador de acordo com as seguintes regras:

- **Ferro**: menos de 10 vitórias
- **Bronze**: entre 11 e 20 vitórias
- **Prata**: entre 21 e 50 vitórias
- **Ouro**: entre 51 e 80 vitórias
- **Diamante**: entre 81 e 90 vitórias
- **Lendário**: entre 91 e 100 vitórias
- **Imortal**: 101 ou mais vitórias

## Instalação

1. Clone o repositório:
   ```bash
   git clone <URL_DO_REPOSITORIO>
