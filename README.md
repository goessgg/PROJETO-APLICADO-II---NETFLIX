# PROJETO-APLICADO-II---NETFLIX

Análise Exploratória e Insights sobre Recomendação de Filmes e Séries

## Objetivo:
Este projeto tem como foco a análise exploratória e a construção de um sistema de recomendação de filmes e séries utilizando dados estruturados sobre conteúdo audiovisual. A proposta é identificar padrões em gêneros, descrições e tipos de produção, fornecendo recomendações personalizadas aos usuários com base em similaridade textual e categorizada. Os resultados serão apresentados por meio de dashboards interativos e relatórios analíticos.

## Sobre a Base de Dados

- Descrição: A base de dados utilizada neste projeto contém informações detalhadas sobre filmes e séries, incluindo gêneros, descrições e tipos de produção. Essa base permite explorar relações entre diferentes conteúdos e desenvolver modelos de recomendação eficientes.

**Fonte e Estrutura dos Dados:** 
Os dados analisados foram obtidos de fontes abertas e contêm as seguintes informações principais:

- ID: Identificador do título.

- Title: Nome do filme ou série.

- Type: Classificação entre "Filme" ou "Série".

- Genre: Gênero(s) associados ao título.

- Description: Sinopse detalhada do título.

Esses atributos são essenciais para a construção de modelos de recomendação baseados em similaridade textual e categórica.

## Metodologia e Abordagem Analítica

**Exploração dos Dados:**
Para compreender melhor a distribuição e relação entre os títulos, serão aplicadas técnicas de análise exploratória, incluindo:

Análise de frequência dos gêneros mais comuns.

Visualização da distribuição entre filmes e séries.

Estudo da relevância de palavras na descrição dos títulos.

Construção de uma nuvem de palavras para destacar temas recorrentes.

## Tratamento dos Dados:

- Remoção de valores nulos e dados inconsistentes.

- Tokenização e remoção de stopwords.

- Aplicar stemming e lemmatization para uniformização textual.

- Transformar as descrições em vetores numéricos utilizando TF-IDF.

## Modelo de Recomendação

Serão implementadas técnicas de recomendação baseada em conteúdo, incluindo:

- TF-IDF e Similaridade do Cosseno: Mede a proximidade semântica entre as descrições.

- KNN (K-Nearest Neighbors): Recomenda títulos similares considerando proximidade vetorial.

- Modelo Híbrido: Combina informações de gênero e descrição para aumentar a precisão das sugestões.

A validação será feita utilizando Top-N Precision e Recall@K, avaliando a precisão das recomendações feitas para diferentes perfis de usuários.

