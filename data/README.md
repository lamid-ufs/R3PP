# **Dados**
Na pasta `data`, são armazenados todo o conjunto de dados utilizado no projeto. Idealmente, estruturados em três subpastas principais:

### 📁 raw
Contém os dados originais, tais como foram extraídos/baixados/coletados. 

### 📁 processed
Armazena os dados processados, ou seja, que passaram por alguma transformação: pré-processamento, limpeza, normalização, etc.

### 📁 finalized
Contém os dados finalizados. Os dados armazenados nesta pasta são aqueles utilizados para as análises, geração de visualizações, inputs para treinamento, etc.

#### ⚠️ **Atenção**
Caso o conjunto de dados seja muito pesado para ser disponibilizado no repositório:
1. Hospede os arquivos de dados em um repositório de arquivamento persistente que forneça um DOI (Digital Object Identifier). Recomendações: Zenodo ou Open Science Framework (OSF);
2. Insira neste arquivo as instruções para a obtenção dos dados:
   * **URL/DOI**: `{link}`
   * **Instruções**: Faça o download do arquivo `exemplo` no link acima e descompacte seu conteúdo na pasta `data/raw/`.

Caso os dados não possam ser redistribuídos publicamente devido a restrições de licença, privacidade, ou considerações éticas, NÃO os inclua no repositório.
1. Declare explicitamente neste arquivo que os dados são restritos e o motivo;
2. Forneça um processo claro para solicitação de acesso para fins de pesquisa, caso a solicitação seja possível.

> ❗ Mesmo que os arquivos de dados não estejam neste repositório, a documentação sobre eles deve estar. Então, o arquivo `METADATA.md` deve ser sempre preenchido e inserido na pasta `data`.