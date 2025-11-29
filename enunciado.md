## Objetivo
Construir uma narrativa visual replicável sobre o comportamento de um conjunto de dados à escolha do grupo. O trabalho deve abordar:

* **Variações temporais** relevantes ao dataset (ex: hora, dia, semana, sazonalidade).
* **Composição de variáveis** de interesse.
* **Métodos de análise** pertinentes.
* (Opcional) Auditoria de qualidade de dados e decisões de pré-processamento, desde que documentadas e justificadas com visualizações de diagnóstico.

## Escopo de Dados
* **Seleção:** O grupo deve escolher um dataset contendo informações **espaciais**, **temporais** e outras variáveis adequadas para análise exploratória visual.
* **Justificativa:** A escolha do dataset e do recorte temporal deve ser justificada com base em padrões ou questões relevantes observadas nas visualizações.
* **Formato:** O dataset deve permitir processamento direto na ferramenta implementada.
* **Dica:** Explore o máximo de atributos possível para enriquecer as análises.

## Entregáveis

### 1. Código-fonte
* **Formato:** Arquivo compactado (**APENAS .ZIP**).
* **Envio:** Apenas via **Google Classroom**.
    * Não enviar links do GitHub, Google Drive, Dropbox, etc.
    * A pasta `node_modules` **NÃO DEVE** ser enviada.
* **Responsável:** Apenas um componente do grupo deve realizar o envio.

### 2. Relatório
* **Formato:** Arquivo **PDF** (não enviar .doc, .txt, etc.).
* **Tamanho:** Máximo de **4 páginas**.
* **Conteúdo:** Análises produzidas e imagens das visualizações que as fundamentam.

## Requisitos Técnicos

1.  **Processamento:**
    * Os dados **não podem** ser pré-processados em códigos externos.
    * Todo o processamento e construção das visualizações devem ocorrer no sistema desenvolvido.
2.  **Banco de Dados:**
    * O sistema deve carregar os arquivos originais obrigatoriamente em uma instância do **DuckDB**.
    * *Nota:* Para grandes volumes de dados, carregue porções individualmente para selecionar o período de interesse.
3.  **Visualização:**
    * As visualizações devem ser feitas obrigatoriamente com a biblioteca **D3.js**.
4.  **Avaliação:**
    * Não há um número fixo de visualizações exigidas.
    * Espera-se que os alunos demonstrem domínio sobre os assuntos técnicos e teóricos vistos em sala através da execução.

## Grupos

> **Atenção:**
> * O trabalho deve ser feito em grupos de **4 ALUNOS**.
> * **NÃO SERÃO PERMITIDOS** trabalhos individuais, em duplas ou em trios.

## Prazos e Apresentação

* **Entrega do material:** Até o dia **30/11/2025**.
* **Apresentações:** Dias **01/12/2025** e **03/12/2025**.
* **Ordem:** A ordem de apresentação será definida por sorteio.