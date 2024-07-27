# Calculadora de Lucro para Elunium Perfeito

Este é um projeto simples de uma calculadora de lucro para criar Elunium Perfeito no jogo Ragnarok Online. A calculadora utiliza inputs de quantas moedas um item vale e o valor do item em dinheiro para calcular o custo e o lucro de criar Elunium Perfeito.

## Funcionalidades

- Calcula o custo total para criar Elunium Perfeito com base no valor do item e a quantidade de moedas.
- Exibe o lucro ou prejuízo obtido ao criar Elunium Perfeito.

## Pré-requisitos

Você precisará de um navegador web moderno para abrir o arquivo HTML.

## Como usar

1. Clone o repositório ou faça o download dos arquivos.
2. Abra o arquivo `index.html` em seu navegador.
3. Insira o valor do item (em moedas) e o valor do item (em dinheiro).
4. Clique no botão "Calcular" para ver o custo total e o lucro/prejuízo.

## Estrutura do Projeto

```bash
.
├── assets
│   ├── favicon.ico  # Ícone do site
│   ├── sniper.png   # Imagem de fundo do arqueiro
├── index.html       # Página principal da calculadora
└── README.md        # Este arquivo
```

## Cálculo Envolvido
Para calcular o custo total e o lucro, a calculadora utiliza as seguintes fórmulas:

Custo do Elunium Enriquecido = (400 / Moedas por Item) * Valor do Item em Dinheiro

Custo Total para Criar o Elunium Perfeito = Custo do Elunium Enriquecido + 3.080.000

Lucro = 5.500.000 - Custo Total para Criar o Elunium Perfeito

