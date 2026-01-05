# Lista de Estudos por Fase - Big Data

## FASE 1: Fundamentos (4-6 semanas)

### Python Básico
- [ ] Variáveis e tipos de dados (int, float, string, boolean)
- [ ] Operadores (aritméticos, lógicos, comparação)
- [ ] Estruturas condicionais (if, elif, else)
- [ ] Loops (for, while)
- [ ] Listas, tuplas e dicionários
- [ ] Funções (definição, parâmetros, retorno)
- [ ] List comprehensions
- [ ] Manipulação de strings
- [ ] Tratamento de exceções (try, except)
- [ ] Leitura e escrita de arquivos

### SQL Básico
- [ ] SELECT, FROM, WHERE
- [ ] ORDER BY, LIMIT
- [ ] Funções agregadas (COUNT, SUM, AVG, MAX, MIN)
- [ ] GROUP BY e HAVING
- [ ] INNER JOIN
- [ ] LEFT JOIN e RIGHT JOIN
- [ ] DISTINCT
- [ ] Operadores IN, BETWEEN, LIKE
- [ ] Subconsultas básicas

### Matemática e Estatística Básica
- [ ] Média, mediana, moda
- [ ] Desvio padrão e variância
- [ ] Percentis e quartis
- [ ] Correlação básica
- [ ] Conceitos de probabilidade
- [ ] Distribuição normal
- [ ] Gráficos básicos (histogramas, boxplots)

---

## FASE 2: Bancos de Dados e Análise (6-8 semanas)

### Python Intermediário
- [ ] NumPy (arrays, operações matriciais)
- [ ] Pandas (DataFrames, Series)
- [ ] Leitura de CSV, Excel, JSON
- [ ] Limpeza de dados (valores nulos, duplicados)
- [ ] Transformação de dados (merge, join, concat)
- [ ] Groupby e agregações
- [ ] Matplotlib (gráficos básicos)
- [ ] Seaborn (visualizações estatísticas)

### SQL Avançado
- [ ] UNION, UNION ALL
- [ ] Window Functions (ROW_NUMBER, RANK, LEAD, LAG)
- [ ] CTEs (Common Table Expressions)
- [ ] CASE WHEN
- [ ] Subconsultas complexas
- [ ] Índices e otimização de queries
- [ ] Transações (BEGIN, COMMIT, ROLLBACK)
- [ ] Normalização (1NF, 2NF, 3NF)
- [ ] Views e Stored Procedures

### Bancos de Dados NoSQL
- [ ] Conceitos de NoSQL vs SQL
- [ ] MongoDB: documentos, coleções
- [ ] MongoDB: CRUD operations
- [ ] MongoDB: agregações e pipelines
- [ ] Cassandra: conceitos básicos
- [ ] Redis: cache e estruturas de dados
- [ ] Quando usar SQL vs NoSQL

### Estatística Avançada
- [ ] Testes de hipótese (t-test, chi-square)
- [ ] Valor-p e nível de significância
- [ ] Regressão linear simples
- [ ] Regressão linear múltipla
- [ ] Análise de resíduos
- [ ] Intervalos de confiança
- [ ] Amostragem e populações

---

## FASE 3: Ecossistema Big Data (8-10 semanas)

### Hadoop Ecosystem
- [ ] Conceitos de computação distribuída
- [ ] HDFS: arquitetura e funcionamento
- [ ] HDFS: comandos básicos
- [ ] MapReduce: conceito e paradigma
- [ ] MapReduce: implementação em Python/Java
- [ ] YARN: gerenciamento de recursos
- [ ] Hive: HiveQL básico
- [ ] Hive: particionamento e bucketing
- [ ] Pig: Pig Latin básico
- [ ] HBase: tabelas e operações

### Apache Spark
- [ ] Arquitetura do Spark (Driver, Executors)
- [ ] RDDs: criação e transformações
- [ ] RDDs: ações (collect, count, reduce)
- [ ] DataFrames e Datasets
- [ ] Spark SQL: queries e otimização
- [ ] Transformações (map, filter, flatMap)
- [ ] Ações (collect, take, first)
- [ ] Joins em Spark
- [ ] Agregações e groupBy
- [ ] Particionamento e reparticionamento
- [ ] Cache e persist
- [ ] Broadcast variables e accumulators

### PySpark
- [ ] Instalação e configuração
- [ ] SparkSession e SparkContext
- [ ] Leitura de dados (CSV, JSON, Parquet)
- [ ] Transformações de dados
- [ ] UDFs (User Defined Functions)
- [ ] Window functions em PySpark
- [ ] Otimização de jobs Spark

---

## FASE 4: Cloud e Engenharia de Dados (10-12 semanas)

### AWS (escolha uma plataforma)
- [ ] S3: buckets, upload, download
- [ ] S3: versionamento e lifecycle policies
- [ ] EMR: criação de clusters
- [ ] EMR: execução de jobs Spark
- [ ] Redshift: data warehouse
- [ ] Redshift: modelagem dimensional
- [ ] Glue: ETL e Data Catalog
- [ ] Athena: queries em S3
- [ ] Kinesis: streaming de dados
- [ ] Lambda: funções serverless
- [ ] IAM: permissões e segurança

### Google Cloud Platform (alternativa)
- [ ] Cloud Storage: buckets e objetos
- [ ] BigQuery: queries e otimização
- [ ] BigQuery: particionamento e clustering
- [ ] Dataflow: pipelines Apache Beam
- [ ] Dataproc: clusters Spark
- [ ] Pub/Sub: mensageria
- [ ] Cloud Functions: serverless
- [ ] IAM e segurança

### Azure (alternativa)
- [ ] Blob Storage: armazenamento
- [ ] Data Lake Storage Gen2
- [ ] Synapse Analytics: data warehouse
- [ ] Databricks: Spark gerenciado
- [ ] Data Factory: ETL/ELT
- [ ] Event Hubs: streaming
- [ ] Azure Functions: serverless

### Engenharia de Dados
- [ ] Conceitos de ETL vs ELT
- [ ] Data pipelines: design e implementação
- [ ] Apache Airflow: DAGs
- [ ] Airflow: operators e sensors
- [ ] Airflow: scheduling e monitoring
- [ ] Apache Kafka: producers e consumers
- [ ] Kafka: topics e partitions
- [ ] Kafka: Kafka Connect
- [ ] Data quality e validação
- [ ] Logging e monitoramento
- [ ] Data lineage
- [ ] Versionamento de dados

### Formatos de Dados
- [ ] CSV, JSON, XML
- [ ] Parquet: formato colunar
- [ ] Avro: serialização
- [ ] ORC: otimização
- [ ] Delta Lake: ACID transactions
- [ ] Compressão de dados

---

## FASE 5: Machine Learning e Arquiteturas (12-14 semanas)

### Machine Learning Básico
- [ ] Aprendizado supervisionado vs não supervisionado
- [ ] Regressão linear e logística
- [ ] Árvores de decisão
- [ ] Random Forest
- [ ] K-Means clustering
- [ ] K-Nearest Neighbors (KNN)
- [ ] Support Vector Machines (SVM)
- [ ] Naive Bayes
- [ ] Feature engineering
- [ ] Feature scaling (normalização, padronização)
- [ ] Train/test split
- [ ] Validação cruzada (cross-validation)
- [ ] Métricas: accuracy, precision, recall, F1-score
- [ ] Métricas: MSE, RMSE, MAE, R²
- [ ] Overfitting e underfitting
- [ ] Regularização (L1, L2)

### Scikit-learn
- [ ] Pipeline de ML
- [ ] Preprocessamento de dados
- [ ] Seleção de features
- [ ] GridSearchCV e RandomizedSearchCV
- [ ] Ensemble methods

### Spark MLlib
- [ ] Vetorização de features
- [ ] Modelos de classificação em Spark
- [ ] Modelos de regressão em Spark
- [ ] Clustering em Spark
- [ ] Pipelines de ML em Spark
- [ ] Avaliação de modelos distribuídos

### Arquiteturas de Big Data
- [ ] Lambda Architecture: conceito
- [ ] Lambda: batch layer
- [ ] Lambda: speed layer
- [ ] Lambda: serving layer
- [ ] Kappa Architecture: conceito
- [ ] Kappa: streaming único
- [ ] Data Lake: conceito e implementação
- [ ] Data Warehouse: modelagem
- [ ] Lakehouse: Delta Lake, Iceberg
- [ ] Data Mesh: conceitos
- [ ] Medallion Architecture (Bronze, Silver, Gold)

### Streaming de Dados
- [ ] Spark Streaming: DStreams
- [ ] Structured Streaming
- [ ] Windowing operations
- [ ] Watermarking
- [ ] Checkpointing
- [ ] Kafka + Spark integration

---

## FASE 6: Produção e Avançado (14-16 semanas)

### MLOps
- [ ] CI/CD para Machine Learning
- [ ] Versionamento de modelos
- [ ] MLflow: tracking experiments
- [ ] MLflow: model registry
- [ ] MLflow: deployment
- [ ] DVC: versionamento de dados
- [ ] Monitoramento de modelos em produção
- [ ] Detecção de data drift
- [ ] A/B testing de modelos
- [ ] Feature stores

### Containerização e Orquestração
- [ ] Docker: conceitos básicos
- [ ] Docker: Dockerfile
- [ ] Docker: build e push de imagens
- [ ] Docker Compose
- [ ] Kubernetes: conceitos básicos
- [ ] Kubernetes: Pods, Services, Deployments
- [ ] Kubernetes: ConfigMaps e Secrets
- [ ] Kubernetes: Persistent Volumes
- [ ] Helm: gerenciamento de pacotes
- [ ] Kubeflow: ML em Kubernetes

### APIs e Deployment
- [ ] REST APIs: conceitos
- [ ] Flask: criação de APIs
- [ ] FastAPI: APIs modernas
- [ ] Serialização de modelos (pickle, joblib)
- [ ] Deployment de modelos como API
- [ ] Load balancing
- [ ] Rate limiting
- [ ] Autenticação e autorização

### Deep Learning (Opcional)
- [ ] Redes neurais: conceitos
- [ ] TensorFlow: básico
- [ ] Keras: construção de modelos
- [ ] PyTorch: básico
- [ ] CNNs: redes convolucionais
- [ ] RNNs e LSTMs
- [ ] Transfer learning
- [ ] Distributed training

### Tópicos Avançados
- [ ] GraphX: processamento de grafos
- [ ] Graph analytics
- [ ] Time series analysis em escala
- [ ] Real-time analytics
- [ ] Data governance
- [ ] LGPD/GDPR compliance
- [ ] Segurança em Big Data
- [ ] Criptografia de dados
- [ ] Auditoria e logs
- [ ] Performance tuning avançado
- [ ] Cost optimization em cloud
- [ ] Disaster recovery

### Ferramentas de Monitoramento
- [ ] Prometheus: coleta de métricas
- [ ] Grafana: visualização
- [ ] ELK Stack (Elasticsearch, Logstash, Kibana)
- [ ] CloudWatch (AWS)
- [ ] Stackdriver (GCP)

---

## HABILIDADES COMPLEMENTARES (Contínuo)

### Soft Skills
- [ ] Comunicação técnica
- [ ] Documentação de código
- [ ] Apresentação de resultados
- [ ] Trabalho em equipe
- [ ] Gestão de tempo
- [ ] Resolução de problemas

### Ferramentas de Desenvolvimento
- [ ] Git: comandos básicos
- [ ] Git: branches e merge
- [ ] GitHub/GitLab: colaboração
- [ ] Pull requests e code review
- [ ] Terminal Linux: comandos básicos
- [ ] Shell scripting básico
- [ ] SSH e conexões remotas
- [ ] Jupyter Notebooks
- [ ] VS Code ou PyCharm

### Conhecimento de Negócio
- [ ] KPIs e métricas de negócio
- [ ] ROI de projetos de dados
- [ ] Storytelling com dados
- [ ] Business Intelligence básico
- [ ] Análise de requisitos

---

## CERTIFICAÇÕES RECOMENDADAS

### AWS
- [ ] AWS Certified Cloud Practitioner
- [ ] AWS Certified Data Analytics - Specialty
- [ ] AWS Certified Solutions Architect - Associate

### Google Cloud
- [ ] Google Cloud Professional Data Engineer
- [ ] Google Cloud Associate Cloud Engineer

### Azure
- [ ] Microsoft Certified: Azure Data Engineer Associate
- [ ] Microsoft Certified: Azure Fundamentals

### Outras
- [ ] Databricks Certified Data Engineer Associate
- [ ] Cloudera Certified Professional (CCP)
- [ ] Apache Spark Certification

---

## DICAS DE ESTUDO

1. **Pratique diariamente**: Reserve pelo menos 2 horas por dia
2. **Projetos práticos**: Aplique cada conceito em um projeto real
3. **Comunidades**: Participe de fóruns (Stack Overflow, Reddit)
4. **Kaggle**: Resolva competições e explore datasets
5. **GitHub**: Contribua com projetos open source
6. **Blog/Portfolio**: Documente seu aprendizado
7. **Networking**: Conecte-se com profissionais da área
8. **Revisão**: Revise conceitos anteriores regularmente
9. **Não pule etapas**: Fundamentos são essenciais
10. **Seja consistente**: Melhor estudar 1h/dia do que 7h em 1 dia