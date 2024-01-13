# Projeto Python IA: Inteligência Artificial e Previsões

## Case: Score de Crédito dos Clientes

A proposta deste projeto é desenvolver um modelo de Inteligência Artificial (IA) para prever o score de crédito dos clientes de um banco. O objetivo é analisar as informações de cada cliente e automaticamente classificar o score de crédito como Ruim, Ok ou Bom. A seguir, é apresentado um resumo do passo a passo do projeto:

### Passo a Passo

#### Passo 0 - Entender o Desafio da Empresa
O desafio proposto pela empresa é compreender e definir o score de crédito dos clientes utilizando análise de dados e inteligência artificial.

#### Passo 1 - Importar a Base de Dados
A base de dados dos clientes é importada do arquivo "clientes.csv". Essa base será utilizada para treinar o modelo de IA.

#### Passo 2 - Preparar a Base de Dados para a Inteligência Artificial
A base de dados é preparada para ser utilizada em algoritmos de aprendizado de máquina. Isso inclui a transformação de variáveis categóricas em numéricas utilizando o LabelEncoder.

#### Passo 3 - Criar um Modelo de IA > Score de Crédito: Ruim, Médio, Bom
São criados modelos de IA, como árvore de decisão (Random Forest) e KNN, para prever o score de crédito dos clientes.

#### Passo 4 - Escolher o Melhor Modelo
Os modelos são testados e comparados utilizando métricas como a acurácia. O modelo de árvore de decisão (Random Forest) é escolhido como o melhor para o problema.

#### Passo 5 - Usar a Nossa IA para Fazer Novas Previsões
O modelo treinado é utilizado para fazer previsões em uma nova base de dados de novos clientes, chamada "novos_clientes.csv". As previsões são exibidas para indicar o score de crédito estimado.

### Conclusão

Este projeto demonstra a aplicação prática de técnicas de análise de dados e criação de modelos de IA para resolver um desafio empresarial específico. A utilização de algoritmos de aprendizado de máquina permite automatizar a avaliação de crédito dos clientes, facilitando a tomada de decisões por parte do banco.
