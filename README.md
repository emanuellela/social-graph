<h3>Análise e Projeto de Algoritmos  - UNIPAMPA 2024/2 :computer: </h3> 
<h4>Prof. Paulo Silas Severo de Souza</h4>


Com base em um conjunto de dados de uma rede social fictícia, crie e analise um grafo baseado em dados dos usuários e suas relações de amizade, visando prover recomendações de amizades.

## Parte 1 — Criação do Grafo
- Dataset JSON em ambiente Python.
- Grafo com os dados (usando a biblioteca NetworkX).
- Pesos calculados para as arestas baseados em um ou mais dos seguintes fatores:
1. Quantidade de Mensagens: Número de mensagens trocadas entre os dois usuários.
2. Tempo de Amizade: Duração da amizade.
3. Amigos em Comum: Número de usuários (ou outros indicadores) de amigos de ambos.

## Parte 2 — Visualização do Grafo

- Visualização do grafo com atributos visuais (espessura e cor das arestas) para representar os pesos.

## Parte 3 — Análise e Sugestão de Amizades

3.1 Análise de Amigos em Comum. Dado um determinado usuário, identifica:
- Lista de amigos diretos.
- Número de amigos em comum com cada um de seus amigos.
  
3.2 Recomendação de Amizades. Sugira amizades para um usuário (pelo menos) com base em:
- Amigos em Comum: Usuários que não são amigos diretos, mas têm amigos em comum.
- Afinidade: Potencial afinidade entre usuários com base em informações disponíveis no dataset.

## Dados Disponíveis
O conjunto de dados compreende o arquivo JSON com as seguintes informações:

    Usuários: Lista de usuários com seus dados.
    Amizades: Lista de amizades entre usuários.
    Mensagens: Histórico de mensagens.

Integrantes: Eduardo, Emanuelle, Gabriel e João Emilio.
