# 🚀 Data Pilot — Intelligent Sales Analytics

Dashboard de Vendas e Assistente Inteligente para Análise de Dados

## 📌 Sobre o projeto

O Data Pilot é uma aplicação de análise de dados comerciais desenvolvida para facilitar o acompanhamento de indicadores de vendas e transformar dados em informações úteis para a tomada de decisões.

O projeto combina um dashboard interativo com uma interface de assistente conversacional, permitindo consultar indicadores, analisar resultados e comparar o desempenho das categorias de produtos por meio de perguntas em linguagem natural.

A proposta é evoluir a aplicação para um agente de Inteligência Artificial capaz de interpretar perguntas, selecionar ferramentas de análise e apresentar respostas fundamentadas em dados calculados pelo Python.

## 🎯 Objetivo

Desenvolver uma solução de análise comercial que integre:

Visualização de indicadores de desempenho.

Análise de receita e vendas por categoria.

Acompanhamento de resultados mensais.

Consultas em linguagem natural.

Automação de análises por meio de ferramentas Python.

Inteligência Artificial aplicada à interpretação de dados.

✨ Funcionalidades

## 1. Dashboard de Vendas

Painel interativo para acompanhamento dos principais indicadores comerciais:

Receita total: valor total das vendas.

Total de pedidos: quantidade de pedidos registrados.

Ticket médio: receita dividida pelo número de pedidos.

Produtos vendidos: quantidade total de unidades comercializadas.

Visualizações disponíveis:

Gráfico de receita mensal.

Gráfico de distribuição de vendas por categoria.

Tabela de desempenho comercial.

Filtro por categoria.

## 2. Assistente Inteligente — Data Pilot AI Agent

Interface conversacional para realizar perguntas sobre os dados de vendas.

O agente possui uma lógica inicial de interpretação de perguntas em português e identifica diferentes tipos de análises.

Exemplos de perguntas:

Qual foi a receita total?

Qual categoria teve maior receita?

Qual foi o ticket médio?

Qual foi o melhor mês?

Compare as categorias de vendas.

Quantos pedidos foram realizados?

## 3. Ferramentas de análise planejadas

A aplicação apresenta as funções que serão utilizadas pelo agente na futura integração com Python:

calcular_receita_total()

Calcular a receita total

contar_pedidos()

Contabilizar os pedidos

calcular_ticket_medio()

Calcular o ticket médio

receita_por_categoria()

Analisar a receita por categoria

receita_por_mes()

Analisar a receita mensal

identificar_melhor_categoria()

Identificar a categoria de maior receita

## 🛠️ Tecnologias utilizadas

Tecnologia

Aplicação

HTML5

Estrutura da aplicação

CSS3

Estilização e layout responsivo

JavaScript

Interatividade e processamento das perguntas

Chart.js

Construção dos gráficos

Font Awesome

Ícones da interface

Google Fonts

Tipografia

## Tecnologias previstas para a evolução do projeto:

Python para processamento e análise de dados.

Pandas para manipulação de bases de vendas.

API de Inteligência Artificial para interpretação das perguntas e seleção de ferramentas.

Backend para comunicação entre o frontend, Python e o modelo de IA.

## 4. Abrir a aplicação

Abra o arquivo index.html diretamente no navegador ou utilize a extensão Live Server no Visual Studio Code.

Requisito: conexão com a internet para carregar as bibliotecas e fontes externas utilizadas pela interface.

## 🧠 Arquitetura e lógica do agente

O projeto foi planejado com uma arquitetura em que cada componente possui uma responsabilidade específica.

Fluxo proposto:

Usuário
   |
   v
Pergunta em linguagem natural
   |
   v
Agente de Inteligência Artificial
   |
   v
Seleção da ferramenta adequada
   |
   v
Execução da função Python
   |
   v
Processamento e cálculo dos indicadores
   |
   v
Retorno dos resultados
   |
   v
IA interpreta e explica a resposta

## Princípio fundamental

Python calcula. A IA interpreta e explica.

O modelo não deve inventar, estimar ou alterar indicadores. As respostas devem ser fundamentadas nos resultados efetivamente retornados pelas funções de análise.

## 📊 Dados utilizados

O protótipo utiliza uma base de vendas demonstrativa, com registros distribuídos entre 12 meses e quatro categorias:

Eletrônicos.

Informática.

Acessórios.

Móveis.

Os dados são fictícios e foram utilizados exclusivamente para demonstrar as funcionalidades da aplicação.

## 🚧 Próximas etapas

O Data Pilot está em desenvolvimento incremental.

Criação do backend em Python
Integração com Pandas e base CSV

Integração com API de Inteligência Artificial

Implementação da seleção automática de ferramentas

Testes e validação das respostas

## 💡 Diferencial do projeto

O Data Pilot busca demonstrar como a combinação de análise de dados e Inteligência Artificial pode tornar as informações comerciais mais acessíveis.

Em vez de depender exclusivamente de consultas manuais ou da interpretação de gráficos, o usuário poderá interagir com os dados por meio de perguntas em linguagem natural.

A proposta é transformar indicadores em respostas contextualizadas, mantendo a confiabilidade dos cálculos e a transparência das análises.

## 👩‍💻 Autoria

Projeto desenvolvido por Camila Silva como iniciativa prática de aprendizagem e aplicação de conhecimentos em:

Análise de Dados.

Inteligência Artificial.

Desenvolvimento Web.

Automação de processos.

Business Intelligence.

Data Pilot — Intelligent Sales Analytics

Transformando dados em decisões inteligentes.

