# power_bi_emprego_sergipe
Emprego Industrial em Sergipe — RAIS e Power BI

Projeto de portfólio para explorar o emprego formal na indústria de Sergipe com dados da RAIS. A proposta combina consulta SQL no BigQuery, preparação de dados em R e visualização no Power BI, com recortes por ano, setor CNAE, município e perfil dos trabalhadores.

## O produto

O relatório final contém uma capa e duas páginas analíticas:

### Panorama

- Indicadores de vínculos ativos no último ano, remuneração média, variação percentual do estoque e variação nominal da remuneração.
- Série anual de vínculos ativos entre 2010 e 2024.
- Comparação dos vínculos no último ano entre os segmentos industriais B, C, D e E.
- Filtros por período, município e território de Sergipe.

### Mapa e Perfil

- Mapa de marcadores para explorar a distribuição municipal dos vínculos.
- Ranking dos dez municípios com maior quantidade de vínculos e participação no total estadual.
- Perfil dos vínculos por faixa etária, escolaridade e sexo.
- Filtros por período e segmento industrial.

## Objetivo

Responder a perguntas como:

- Como evolui o estoque de vínculos formais ativos na indústria sergipana?
- Como os vínculos se distribuem entre os segmentos industriais e os municípios?
- Qual é o perfil dos trabalhadores por sexo, faixa etária e escolaridade?

Fonte e escopo

- **Fonte:** microdados de vínculos da RAIS disponibilizados pela [Base dos Dados](https://basedosdados.org/dataset/3e7c4d58-96ba-448e-b053-d385a829ef00?table=dabe5ea8-3bb5-4a3e-9d5a-3c7003cd4a60), consultados no BigQuery.
- **Cobertura planejada:** Sergipe, de 2010 a 2024.
- **Unidade analisada:** vínculos ativos em 31 de dezembro, agregados por ano, município, CNAE, sexo, faixa etária e escolaridade.
- **Setores:** seções industriais B a E da CNAE 2.0 — indústrias extrativas, indústrias de transformação, eletricidade e gás, e água, esgoto e resíduos.

