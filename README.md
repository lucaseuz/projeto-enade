# Projeto de engenharia de dados ETL - ENADE 2019

Este projeto visa construir um pipeline de ETL (Extract, Transform, Load) para processar e analisar os dados do Exame Nacional de Desempenho dos Estudantes (ENADE) de 2019. O ENADE é uma avaliação que mede o desempenho dos estudantes concluintes de cursos de graduação em relação aos conteúdos programáticos, habilidades e competências necessárias para o exercício da profissão.

## Objetivo

O objetivo principal deste projeto é extrair dados brutos do ENADE 2019, transformá-los para adequação às necessidades analíticas e carregá-los em uma base de dados estruturada para facilitar a exploração e visualização. O projeto busca responder a perguntas-chave sobre o desempenho dos estudantes, identificar padrões e fornecer insights valiosos sobre a educação superior no Brasil.

## Descrição do Pipeline

1. Extração (Extract): Os dados foram extraídos dos arquivos CSV disponibilizados pelo INEP. Nesta etapa os dados foram coletados de um banco de dados access. Essa etapa envolveu a leitura e coleta dos dados brutos.

2. Transformação (Transform): Na fase de transformação, os dados foram limpos, normalizados e formatados. Isso incluiu a correção de valores ausentes, padronização de categorias e criação de novas variáveis derivadas para enriquecer a análise.

3. Carga (Load): Após a transformação, os dados foram carregados em um banco de dados SQLite, onde foram organizados em tabelas adequadas para consultas eficientes e criação de relatórios.

## Ferramentas Utilizadas

* Python: Para a implementação do pipeline de ETL, utilizando bibliotecas como pandas e sqlite3.
* GitHub: Para versionamento e compartilhamento do código.

## Resultados Esperados

O projeto resulta em um conjunto de dados limpo e estruturado, pronto para ser utilizado em análises mais aprofundadas. Com este pipeline, é possível realizar estudos sobre o desempenho acadêmico, identificar fatores que influenciam o desempenho dos estudantes, e apoiar a tomada de decisões na educação superior.

Segue exemplos de algumas perguntas que conseguimos responder:

1. Qual é a nota geral média dos alunos da Região Nordeste?
2. Qual é a média da nota componente específico dos alunos do Rio Grande do Sul de instituições privadas?
3. Qual é a média da nota geral de alunas do sexo feminino, de instituições públicas, da região centro-oeste?
