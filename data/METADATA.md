## **Documentação dos metadados**
Este arquivo serve como a documentação central para os dados utilizados neste projeto.

Preencha cada seção da forma mais completa possível. Se uma pergunta não for relevante para o seu conjunto de dados, sinta-se à vontade para responder com 'N/A' (Não se aplica).

### 1. Motivação
**1.1. Qual o propósito da criação deste conjunto de dados?**
Descreva os objetivos da pesquisa original. Que pergunta ou problema os autores queriam investigar? A coleta foi motivada por alguma lacuna específica na literatura ou necessidade de tarefa?

**1.2. Quem criou e quem financiou o conjunto de dados?**
Identifique a equipe, grupo de pesquisa ou organização que criou o conjunto de dados. Se aplicável, informe o nome da agência de fomento e o número da bolsa/processo.

### 2. Composição
**2.1. O que o conjunto de dados contém?**
Descreva os tipos de dados (ex: arquivos de texto, áudios, planilhas, transcrições) e o conteúdo que representam (ex: tweets, artigos de notícias, sentenças judiciais, diálogos).

**2.2. Quantos exemplos existem no total?**
Forneça estatísticas descritivas básicas, como número total de documentos, sentenças, tokens, ou qualquer que seja a unidade de medida principal.

**2.3. Existem rótulos (labels) ou anotações?**
Descreva os rótulos ou anotações associados a cada exemplo (ex: classes de sentimento, entidades nomeadas, tags de POS). Quem forneceu essas anotações (ex: especialistas, crowdsourcing)?

**2.4. Existem divisões de dados recomendadas (ex: treino/validação/teste)?**
Descreva as divisões padrão, se existirem. Como elas foram criadas (ex: divisão aleatória 80/10/10, por data)?

**2.5. Existem erros, fontes de ruído ou redundâncias conhecidas no conjunto de dados?**
Descreva quaisquer problemas de qualidade conhecidos, exemplos duplicados, erros de rotulagem ou artefatos do processo de coleta que possam impactar a modelagem.

**2.6. O conjunto de dados contém informações sensíveis?**
O conjunto de dados contém informações que podem identificar indivíduos (PII - Personally Identifiable Information) ou informações confidenciais (ex: dados de saúde, opiniões políticas)?

### 3. Coleta de Dados
**3.1. Como os dados foram coletados?**
Detalhe a metodologia de coleta. Foi web scraping (de quais sites?), uso de API (qual?), um experimento de laboratório, entrevistas, ou reuso de um conjunto de dados já existente? Indique o período (datas) em que a coleta ocorreu.

**3.2. Quem ou o que os dados representam (e o que não representam)?**
Descreva a população amostrada (ex: falantes de português do Brasil, postagens de uma rede social específica). Reflita sobre as limitações dessa amostra. Que grupos, contextos ou características estão ausentes? Isso é crucial para identificar vieses e definir os limites de generalização.

### 4. Pré-processamento, Limpeza e Rotulagem
**4.1. Quais etapas de processamento foram aplicadas?**
Descreva todas as transformações aplicadas aos dados brutos. Isso inclui limpeza (ex: remoção de HTML, normalização de texto), tokenização, lematização, remoção de stopwords, anonimização, etc.

**4.2. O software de processamento/rotulagem está disponível?**
Se scripts foram usados para processar ou rotular os dados, indique onde eles podem ser encontrados (ex: na pasta src/data/ deste repositório).

### 5. Usos
**5.1. Para quais tarefas este conjunto de dados deve ser usado?**
Descreva os usos pretendidos (ex: "Este corpus é destinado ao treinamento de modelos de classificação de sentimento binário para o domínio de avaliações de produtos").

**5.2. Para quais tarefas este conjunto de dados NÃO deve ser usado?**
Existem usos que os criadores desencorajam? (ex: "Não deve ser usado para fazer inferências sobre demografia", "Não deve ser usado para aplicações de alto risco devido ao viés conhecido X").

### 6. Distribuição, Ética e Licenciamento
**6.1. Onde e como os dados podem ser acessados?**
Indique se os dados estão publicamente disponíveis e forneça o link (URL ou DOI) para o repositório. Se os dados brutos não puderem ser incluídos neste repositório (ex: devido ao tamanho), forneça o link aqui.

**6.2. Qual é a licença de uso?**
Descreva a licença (ex: Creative Commons CC-BY 4.0, MIT, etc.). Se o acesso for restrito, explique como seria o processo para solicitá-lo.

**6.3. Quais considerações éticas foram levadas em conta?**
O artigo original menciona aprovação por um comitê de ética? Os participantes assinaram um Termo de Consentimento Livre e Esclarecido (TCLE)? Que medidas foram tomadas para garantir o anonimato e a privacidade?