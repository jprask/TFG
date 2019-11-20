# Implementação

Este diretório contém a implementaão do trabalho. Os arquivos podem ser visualisados online via github ou via jupyter notebooks.
Sugerimos o uso da distribuição [anaconda](https://www.anaconda.com/distribution/). Para o uso, referir a documantação da plataforma [jupyter](https://jupyter.org/documentation).

## Arquivos

### 00-explore.ipynb

Contém uma analise exploratória dos dados da plataforma Kennis a partir do arquivo *Kennis.xls* e alguns testes preliminares de possíveis metodos de clusterização.

### 01-preproc-a.ipynb

Contém a clusterização dos titulos de obras conforme discutido no artigo. Lê o arquivo *Kennis.xls* e cria um arquivo *kennis_ids_#.csv*, onde *#* representa o bandwidth usado. Depende de recursos computacionais (memória RAM, Disco e processador).

### 01-preproc-b.ipynb

Contém uma análise da clusterização de *01-preproc-a.ipynb*  e a filtragem de obras que são irrelevantes ao trabalho, além de outros pormenores do pré-processamento.

### 02-trust-metrics.ipynb

Contém código para estimativas de confiança via implementação de formulas discutidas no artigo e testes exploratórios das implementações.


### 03-recommendations.ipynb

Contém codigo para recomendação baseada em conteúdo e a prova de conceito da arquitetura sugerida no artigo
