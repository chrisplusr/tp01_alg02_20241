# Trabalho Prático 01 - Geometria Computacional

Christian Rodrigues de Oliveira - 2019041817
# Problema da Galeria de Arte

## Descrição

Este projeto aborda aspectos práticos de algoritmos de geometria computacional, com foco na aplicação de algoritmos para triangulação de polígonos no contexto do problema da galeria de arte. O objetivo é determinar o menor número de câmeras de segurança necessárias para cobrir completamente uma galeria, representada como um polígono simples em um arquivo de entrada.

## Problema da Galeria de Arte

O problema da galeria de arte consiste em encontrar a configuração mínima de câmeras de segurança que assegure que toda a galeria, representada por um polígono simples, seja completamente monitorada. Para resolver este problema, aplicamos os seguintes passos:

1. **Triangulação do Polígono:** Dividimos o polígono em triângulos não sobrepostos de maneira que a cobertura total da galeria seja garantida.
2. **Coloração dos Vértices:** Aplicamos um algoritmo de coloração para determinar o número mínimo de câmeras necessárias, onde cada cor representa uma câmera diferente e a ideia é minimizar o número total de cores necessárias.

## Algoritmos e Técnicas

O projeto explora dois algoritmos principais:

1. **Algoritmo de Triangulação de Polígonos:** Converte o polígono simples em vários triângulos diagonalizando cada um deles e inserindo as arestas no grafo.
   
2. **Algoritmo de Coloração de Vértices:** Após a triangulação, aplicamos um algoritmo de coloração para encontrar o menor número de cores necessárias para garantir que vértices adjacentes não compartilhem a mesma cor. Cada cor representa uma câmera de segurança, e cores diferentes significam que são necessárias câmeras diferentes para cobrir vértices adjacentes.

## Estrutura do Projeto

O trabalho junto com o relatório está em formato .ipynb na home do repositório, os arquivos utilizados como entrada para leitura do polígono estão dentro da pasta sample_data
