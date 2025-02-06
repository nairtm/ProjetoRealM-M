# ProjetoRealM-M

## 📊 Análise de Assinantes e Não Assinantes da Meio & Mensagem

Este projeto consiste na aplicação de técnicas de Análise Exploratória de Dados (AED) em uma base real da Meio & Mensagem, com o objetivo de compreender o perfil dos usuários assinantes e não assinantes da plataforma. A partir de dados como cargos, área de atuação, segmento, conteúdos mais acessados e participação em eventos, foram definidas personas e identificadas oportunidades estratégicas para expandir a base de assinantes, além de sugerir benefícios e ações para aumentar o engajamento

## 🎯 Objetivo

→ Analisar o perfil de assinantes e não assinantes utilizando dados da Meio & Mensagem

→ Identificar padrões de comportamento, cargos e segmentos de atuação

→ Gerar insights personalizados baseados em personas

→ Análise de eventos e impacto na adesão à plataforma

→ Identificação dos conteúdos mais consumidos

→ Métricas Acervo e Portfólio Agências

→ Propor estratégias para aumentar a base de assinantes

## 🖥️ Tecnologias e Ferramentas Utilizadas

→ Extração: Google Colab, Python

→ Transformação e Ajustes: Pandas, NumPy, Statistics, Matplotlib, Scipy

→ Armazenamento: BigQuery

→ Visualização: Qlik, Power BI, Looker Studio

## 🔍 Passo a Passo da Análise no Python
Este projeto utilizou o Google Colab para manipulação e análise dos dados, aplicando técnicas de ETL (Extração, Transformação e Carregamento), além de visualizações exploratórias.

### ➡️ 1. Importação das Bibliotecas
import pandas as pd
from statistics import mean
from scipy.stats import ttest_ind
import numpy as np
import matplotlib.pyplot as plt

### ➡️ 2. Carregamento da Base de Dados
Os dados foram importados diretamente para o Colab, seja a partir de arquivos CSV. São sete arquivos: Perfil M&M ID, Eventos, Administradores, Portfólio de agências, Digital Pass, Webinar, Acervo.

### ➡️ 3. Tratamento de Dados
Antes da análise, foi necessário limpar e tratar os dados brutos, como renomear algumas colunas, resetar o índice e conversão dos tipos de variáveis.

### ➡️ 4. Análise Exploratória dos Dados (EDA)
Para entender o comportamento dos usuários, exploramos estatísticas descritivas e visualizações. Separamos por assinantes e não assinantes e exploramos os dados com relação à cargos, área de atuação, segmento, conteúdos mais acessados e participação em eventos.

### ➡️ 6. Exportação dos Dados Tratados
Após a análise e tratamento, os dados foram armazenados no BigQuery para criação de dashboards em ferramentas de BI.

## 📈 Principais Insights

→ Participação significativa em eventos sem cadastro completo

→ Possibilidade de crescimento por meio de conteúdo segmentado e benefícios exclusivos

→ Estratégias sugeridas incluem personalização de conteúdos, benefícios em eventos e comunicação segmentada

# 🚀 Conclusão
A análise detalhada dos perfis e comportamentos revela oportunidades significativas para aumentar a base de assinantes e melhorar o engajamento. As estratégias propostas podem auxiliar na otimização, conversão e retenção de clientes.



