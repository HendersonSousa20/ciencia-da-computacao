### Database Administrator (DBA)

Administração de Banco de Dados (Database Administration) é a área da Computação responsável pelo projeto, implementação, configuração, monitoramento, otimização, segurança e manutenção de Sistemas Gerenciadores de Banco de Dados (SGBDs), garantindo que os dados de uma organização estejam disponíveis, íntegros, seguros e com desempenho adequado às aplicações que os consomem. O Administrador de Banco de Dados (DBA) atua na interseção entre infraestrutura, engenharia de software e negócio, sendo responsável por tarefas como modelagem de dados, escrita e otimização de consultas (queries), definição de rotinas de backup e recuperação de desastres, implementação de alta disponibilidade e replicação, controle de acesso e segurança da informação, além do apoio a iniciativas de Big Data e Business Intelligence. É uma das carreiras mais valorizadas e estáveis da área de Tecnologia da Informação, pois toda aplicação de software, independentemente do porte, depende de uma camada de persistência de dados bem projetada e administrada.

> Esta trilha reúne cursos gratuitos e abertos, em português, espanhol e inglês, que cobrem desde os fundamentos teóricos de banco de dados até tópicos avançados de administração, performance, segurança, alta disponibilidade, Big Data e computação em nuvem, seguindo o nível esperado de uma pós-graduação (lato sensu) em Administração de Banco de Dados. Cursos em outros idiomas além do Português foram incluídos por serem referências de altíssima qualidade técnica e não possuírem equivalente nacional com o mesmo nível de profundidade.

**Áreas de aplicação**: `administração de banco de dados` `modelagem e organização de tabelas` `otimização de querys` `segurança de dados` `criação de rotinas de bd` `backup e recuperação` `alta disponibilidade e replicação` `big data` `data warehouse e ETL` `bancos NoSQL` `bancos de dados na nuvem` `e mais`

---

#### 1. Fundamentos de Banco de Dados e Modelagem de Dados

Antes de administrar qualquer SGBD, o futuro DBA precisa dominar os conceitos fundamentais de bancos de dados relacionais: modelo Entidade-Relacionamento (ER), álgebra relacional, normalização e projeto físico de dados. Esta é a base teórica sobre a qual toda a carreira de DBA é construída.

Curso | Duração | Dedicação | Conteúdos
:-- | :--: | :--: | :--:
[Curso de Modelagem de Dados](https://www.youtube.com/playlist?list=PLucm8g_ezqNoNHU8tjVeHmRGBFnjDIlxD) | 8 semanas | 4 horas / semana | Modelo Entidade-Relacionamento; Diagramas DER; Dicionário de Dados; Formas Normais; Projeto Conceitual, Lógico e Físico.
[Curso Completo de Modelagem de Bancos de Dados com Projeto Prático](https://www.youtube.com/watch?v=Kd1yqYjylCg) | 1 semana | 6 horas | Modelagem do Zero ao Avançado; Cardinalidade; Projeto Prático Guiado.
[Curso de Modelagem Relacional - Banco de Dados](https://www.youtube.com/playlist?list=PLg5-aZqPjMmAo-kX-1l6BQS_yIIObGc3C) | 3 semanas | 3 horas / semana | Modelo Relacional; Chaves Primárias e Estrangeiras; Integridade Referencial.
[Banco de Dados do ZERO: Como seus dados são guardados?](https://www.youtube.com/watch?v=PmyLTRjjjlc) | 1 hora | 1 semana | Conceitos Introdutórios; Armazenamento em Disco; Estruturas Internas de um SGBD.

---

#### 2. Linguagem SQL (Structured Query Language)

SQL é a linguagem padrão para manipulação e consulta de dados em bancos relacionais e é o principal instrumento de trabalho de qualquer DBA. Aqui o aluno aprenderá desde comandos básicos de `SELECT`, `INSERT`, `UPDATE` e `DELETE` até tópicos avançados como subconsultas, funções de janela (window functions), procedures e triggers.

Curso | Duração | Dedicação | Conteúdos
:-- | :--: | :--: | :--:
[CURSO GRATUITO SQL PARA ANALISTAS](https://www.youtube.com/playlist?list=PLmOO8X35BgB1G8zcrw3toMm8YrVqF2z12) | 4 semanas | 4 horas / semana | SQL na Prática; Consultas; Filtros; Agregações.
[Curso Completo de SQL com PostgreSQL - Do Zero ao Avançado](https://www.youtube.com/watch?v=9cAKQWodpvM) | 2 semanas | 8 horas / semana | DDL; DML; DQL; Joins; Subqueries; Funções; Índices.
[Curso Completo de SQL com SQL Server para Iniciantes do Básico ao Avançado](https://www.youtube.com/watch?v=KOhd3R5kLks) | 2 semanas | 8 horas / semana | T-SQL; Stored Procedures; Triggers; Views; Transações.
[Curso de Banco de Dados MySQL (Curso em Vídeo)](https://www.youtube.com/playlist?list=PLHz_AreHm4dkBs-795Dsgvau_ekxg8g1r) | 3 semanas | 3 horas / semana | Instalação; PHPMyAdmin; SELECT Avançado; JOINs; Chaves Estrangeiras.
[SQL Full Course for Beginners (30 Hours) – From Zero to Hero](https://www.youtube.com/watch?v=SSKVgrwhzus) ¹ | 4 semanas | 8 horas / semana | SQL Avançado; Window Functions; CTEs; Otimização de Consultas; Data Engineering.
[Essence of Linear Algebra](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab) ¹ | 2 semanas | 4 horas / semana | Vetores; Matrizes; Transformações (base matemática para índices, otimização de consultas e algoritmos de bancos de dados analíticos).

---

#### 3. PostgreSQL – Administração de Banco de Dados

PostgreSQL é um dos SGBDs open-source mais robustos e utilizados no mercado. Este módulo cobre a administração completa do PostgreSQL: instalação, configuração, tablespaces, controle de concorrência multiversão (MVCC), tuning, backup, segurança e alta disponibilidade.

Curso | Duração | Dedicação | Conteúdos
:-- | :--: | :--: | :--:
[Curso PostgreSQL Administração Básico](https://www.youtube.com/watch?v=E-IWizc4sDM) | 1 semana | 4 horas | Instalação; pgAdmin; Estrutura de Diretórios; Configuração Inicial.
[Curso de PostgreSQL - Bancos de Dados](https://www.youtube.com/playlist?list=PLucm8g_ezqNoAkYKXN_zWupyH6hQCAwxY) | 6 semanas | 4 horas / semana | Administração; Backup e Restauração; Tipos de Dados; Funções; Índices.
[Learn PostgreSQL Database Administration (DBA) for Beginners | Full Course](https://www.youtube.com/watch?v=DZuuBcUbSb4) ¹ | 2 semanas | 6 horas / semana | Instalação; Usuários e Roles; Tablespaces; Vacuum; Monitoramento.
[PostgreSQL DBA Tutorials for Beginners](https://www.youtube.com/playlist?list=PLCNIKwM6iuv5o8V6xdCypEnJXy20TIs99) ¹ | 4 semanas | 4 horas / semana | Arquitetura Interna; MVCC; WAL (Write-Ahead Log); Configuração de Performance.

---

#### 4. MySQL / MariaDB – Administração de Banco de Dados

MySQL é o SGBD relacional open-source mais popular do mundo, amplamente utilizado em aplicações web e sistemas corporativos. O módulo aborda desde a instalação até rotinas avançadas de administração, replicação e tuning de engine (InnoDB).

Curso | Duração | Dedicação | Conteúdos
:-- | :--: | :--: | :--:
[Curso MySQL (Curso em Vídeo - Gustavo Guanabara)](https://www.youtube.com/playlist?list=PLHz_AreHm4dkBs-795Dsgvau_ekxg8g1r) | 3 semanas | 3 horas / semana | Estrutura de Tabelas; Cópias de Segurança; PHPMyAdmin; Modelo Relacional.
[MySQL Brasil - Playlists](https://www.youtube.com/c/MySQLBrasil/playlists) | 8 semanas | 4 horas / semana | Administração Avançada de MySQL; Replicação; Performance; Boas Práticas de DBA.
[Curso gratuito de Bases de Datos en MySQL](https://www.youtube.com/playlist?list=PL954bYq0HsCXRLMMnOU6wxBGWoPRiHqh9) | 4 semanas | 4 horas / semana | Instalação; Workbench; Modelagem; Consultas.

---

#### 5. Microsoft SQL Server – Administração e Alta Disponibilidade

SQL Server é o SGBD corporativo da Microsoft, amplamente adotado em ambientes empresariais Windows. O módulo cobre T-SQL avançado, administração via SSMS, backup/restore, replicação, clustering e o recurso Always On para alta disponibilidade.

Curso | Duração | Dedicação | Conteúdos
:-- | :--: | :--: | :--:
[SQL Full Course | SQL Tutorial For Beginners (SQL Server)](https://www.youtube.com/playlist?list=PLjNd3r1KLjQtFEklcPDhidqC_2lmpjk5H) ¹ | 4 semanas | 4 horas / semana | Fundamentos de DBMS; T-SQL; SSMS; Consultas Estruturadas.
[SQL Server DBA Full Course Online](https://www.youtube.com/playlist?list=PL2UfVCyiPs-3MM9TV02kMTC1c-i8geHyZ) ¹ | 6 semanas | 4 horas / semana | Instalação; Backup e Restore; Segurança; Manutenção de Índices; Jobs e Automação.
[Free SQL Server Training Videos - Brent Ozar Unlimited](https://www.brentozar.com/free-sql-server-training-videos/) ¹ | 3 semanas | 3 horas / semana | Índices Clusterizados; Parameter Sniffing; Plano de Execução; First Responder Kit (scripts open-source de diagnóstico).

---

#### 6. Oracle Database – Administração (DBA)

Oracle Database é o SGBD líder em ambientes corporativos de grande porte e missão crítica. Este módulo cobre a arquitetura interna do Oracle, criação e administração de instâncias, gerenciamento de tablespaces, tuning de SQL e backup/recuperação com RMAN (Recovery Manager).

Curso | Duração | Dedicação | Conteúdos
:-- | :--: | :--: | :--:
[Curso de Oracle Completo: Banco de dados Oracle](https://www.youtube.com/watch?v=UeBk3azahW4) | 4 semanas | 4 horas / semana | Instalação Oracle 12c em Linux; Arquitetura; Administração Básica.
[Oracle Database Administration - Complete Tutorials](https://www.youtube.com/playlist?list=PLhiNPw_JwRBDEdy0OzAh2kTPSF75revpI) ¹ | 6 semanas | 4 horas / semana | Instâncias; Tablespaces; Usuários e Privilégios; Undo e Redo Logs.
[Oracle DBA Tutorial Videos](https://www.youtube.com/playlist?list=PLHJyc8Uv34HjJZnqM-2TV8KQBOHLwNBes) ¹ | 6 semanas | 4 horas / semana | Administração Avançada; PL/SQL; Gerenciamento de Memória e Processos.
[RMAN Backup and Recovery | Oracle Backup](https://www.youtube.com/watch?v=EGANSHUzKo8) ¹ | 1 semana | 3 horas | Backup Completo e Incremental; Recovery Catalog; Restauração de Falhas.
[RMAN Level 0 & Level 1 Backups & Restore/Recover](https://www.youtube.com/watch?v=7RUNO1d13EQ) ¹ | 1 semana | 2 horas | Backups Incrementais Nível 0 e 1; Estratégias de Recuperação.

---

#### 7. Segurança de Banco de Dados

A segurança da informação é uma das responsabilidades mais críticas de um DBA: controle de acesso, criptografia, auditoria e proteção contra ataques como SQL Injection, que figura entre as principais vulnerabilidades da OWASP Top 10.

Curso | Duração | Dedicação | Conteúdos
:-- | :--: | :--: | :--:
[Segurança de Banco de Dados - M4P3](https://www.youtube.com/watch?v=CAW_q9BlYpU) | 1 semana | 2 horas | Controle de Acesso; Perfis e Privilégios; Auditoria de Dados.
[SQL Injections: The Full Course (freeCodeCamp)](https://www.youtube.com/watch?v=fiq59DuhY68) ¹ | 2 semanas | 4 horas / semana | Fundamentos de SQL Injection; Tipos de Ataque (In-Band, Blind, Union-Based); Boas Práticas de Prevenção e Codificação Segura.

---

#### 8. Otimização de Consultas e Performance Tuning

Um dos diferenciais mais valorizados de um DBA sênior é a capacidade de identificar gargalos de performance e otimizar consultas SQL. Este módulo aborda planos de execução, índices, estatísticas e técnicas avançadas de tuning.

Curso | Duração | Dedicação | Conteúdos
:-- | :--: | :--: | :--:
[Otimização de Consultas – Bancos de Dados 2020.2](https://www.youtube.com/watch?v=JjcX8zgytyQ) | 1 semana | 2 horas | Processamento de Consultas; Árvore de Consulta; Álgebra Relacional Aplicada.
[Desempenho do Oracle Database: otimização de consultas (Alura)](https://www.alura.com.br/conteudo/desempenho-oracle-database-otimizacao-consultas) | 2 semanas | 4 horas / semana | Plano de Execução; Índices; Estatísticas; Tuning de SQL em Oracle.
[How to Think Like the SQL Server Engine (Brent Ozar)](https://www.brentozar.com/free-sql-server-training-videos/) ¹ | 2 semanas | 3 horas / semana | Índices Clusterizados e Não Clusterizados; Estimativa de Cardinalidade; Estratégias de Indexação.

---

#### 9. Backup, Recuperação de Desastres, Replicação e Alta Disponibilidade

Garantir a continuidade dos negócios é uma responsabilidade central do DBA. Este módulo cobre estratégias de backup (full, incremental, diferencial), Point-in-Time Recovery, replicação síncrona/assíncrona e arquiteturas de alta disponibilidade (HA) e cluster.

Curso | Duração | Dedicação | Conteúdos
:-- | :--: | :--: | :--:
[Backup and Recovery (playlist)](https://www.youtube.com/playlist?list=PLUyvpMtrnS-B9XLrKVxFdpTfs3Un4_Nm0) ¹ | 3 semanas | 3 horas / semana | Estratégias de Backup; Restore; Recuperação de Desastres.
[RMAN command to Backup Oracle database and recovery](https://www.youtube.com/watch?v=EvE3rUflvKc) ¹ | 1 semana | 2 horas | RMAN na Prática; Backup Completo; Recuperação de Falhas.
[DB Recovery from RMAN Full backup](https://www.youtube.com/watch?v=WLuhrb39bFQ) ¹ | 3 dias | 1 hora | Restauração a partir de Backup Completo; Cenários de Falha.
[Always On no SQL Server (artigo/vídeo complementar)](https://medium.com/@joaoluizr/always-on-no-sql-server-15ffc2f2eaa3) | 1 semana | 3 horas | Grupos de Disponibilidade; Réplicas Síncronas e Assíncronas; Políticas de Failover.

---

#### 10. Sistemas Operacionais Linux para DBAs

A maior parte dos servidores de banco de dados em produção roda sobre Linux. É indispensável que o DBA domine linha de comando, gerenciamento de processos, permissões, agendamento de tarefas (cron) e monitoramento do sistema operacional.

Curso | Duração | Dedicação | Conteúdos
:-- | :--: | :--: | :--:
[Curso de Linux - Primeiros Passos (Curso em Vídeo)](https://www.youtube.com/watch?v=6nN2EglOqCM) | 4 semanas | 3 horas / semana | História do Linux; Distribuições; Instalação; Interfaces de Usuário.
[Sistemas Operacionais e Você: Tornando-se um Usuário Avançado (Google/Coursera)](https://www.coursera.org/lecture/sistemas-operacionais/linux-gerenciador-de-pacotes-apt-0iSJT) | 4 semanas | 5 horas / semana | Gerenciamento de Pacotes; Usuários e Permissões; Configuração de Hardware.

---

#### 11. Bancos de Dados NoSQL (MongoDB e Ecossistema)

Com o crescimento do volume e da variedade de dados, os bancos NoSQL se tornaram essenciais no portfólio de um DBA moderno. Este módulo apresenta os principais modelos NoSQL (documentos, chave-valor, colunar e grafos), com foco prático em MongoDB, o banco NoSQL mais utilizado no mundo.

Curso | Duração | Dedicação | Conteúdos
:-- | :--: | :--: | :--:
[Introdução ao NoSQL e MongoDB](https://www.youtube.com/watch?v=04gyv76r_Ts) | 1 semana | 2 horas | Diferenças entre SQL e NoSQL; Modelos de Dados Não-Relacionais.
[MongoDB - Do básico ao avançado](https://www.youtube.com/playlist?list=PLfvOpw8k80WpKTtloa7fMbfPWL7D6X5cC) | 4 semanas | 4 horas / semana | CRUD; Agregações; Índices; Arquitetura do MongoDB.
[MongoDB Tutorial In 6 Hours | Full MongoDB Course](https://www.youtube.com/watch?v=d2MnfyV20hk) ¹ | 2 semanas | 3 horas / semana | Instalação; Replica Sets; Sharding; Boas Práticas.

---

#### 12. Big Data (Hadoop, Spark e Ecossistema Distribuído)

Big Data trata do armazenamento e processamento distribuído de grandes volumes de dados. Este módulo apresenta o ecossistema Hadoop (HDFS, MapReduce, YARN) e o Apache Spark, ferramenta de processamento distribuído mais utilizada atualmente, essenciais para DBAs que atuam com dados em larga escala.

Curso | Duração | Dedicação | Conteúdos
:-- | :--: | :--: | :--:
[Curso de Big Data - Principais Ferramentas (Hadoop, HBase e Spark)](https://www.youtube.com/watch?v=CjRkEywm1go) | 1 semana | 2 horas | Google FileSystem; MapReduce; Visão Geral do Ecossistema Big Data.
[Big Data Hadoop Tutorial for Beginners](https://www.youtube.com/playlist?list=PLlgLmuG_KgbasW0lpInSAIxYd2vqAEPit) ¹ | 5 semanas | 4 horas / semana | HDFS; MapReduce; YARN; Hive; Sqoop.
[The Spark Series | Fundamentos: Apache Hadoop](https://www.youtube.com/watch?v=bFwxZPXRlQc) | 1 semana | 2 horas | Fundamentos de Armazenamento e Processamento Distribuído.
[Introduction to Big Data with Spark and Hadoop](https://www.youtube.com/watch?v=vHlwg4ciCsI) ¹ | 3 semanas | 4 horas / semana | Definições de Big Data; Impacto em Aplicações Reais; Spark e Hadoop na Prática.

---

#### 13. Data Warehouse, ETL e Business Intelligence

DBAs frequentemente dão suporte a ambientes analíticos. Este módulo cobre modelagem dimensional, arquitetura de Data Warehouse (Inmon x Kimball) e processos de ETL (Extract, Transform, Load), fundamentais para projetos de Business Intelligence.

Curso | Duração | Dedicação | Conteúdos
:-- | :--: | :--: | :--:
[O processo completo de ETL](https://www.youtube.com/watch?v=k1JkGZrXizs) | 1 semana | 2 horas | Extração, Transformação e Carga de Dados; Projetos de BI.
[Arquitectura Data Warehouse - Curso DW + BI](https://www.youtube.com/watch?v=mNwRPxzsMQc) | 2 semanas | 3 horas / semana | Arquiteturas Inmon e Kimball; Modelagem Dimensional.
[ETL & Data Warehousing | Complete Beginner to Advanced Tutorial](https://www.youtube.com/watch?v=b5dEtHNcth4) ¹ | 1 semana | 1 hora | Conceitos de ETL; Data Warehouse na Prática.

---

#### 14. Bancos de Dados em Nuvem (Cloud Databases)

A administração de bancos de dados na nuvem (DBaaS) é uma competência cada vez mais exigida do DBA moderno. Este módulo cobre o Amazon RDS (Relational Database Service), serviço gerenciado de bancos relacionais mais utilizado no mercado.

Curso | Duração | Dedicação | Conteúdos
:-- | :--: | :--: | :--:
[Relational Database Service in AWS | Amazon RDS Tutorial](https://www.youtube.com/watch?v=QwXXvFK68cs) ¹ | 2 semanas | 4 horas / semana | Fundamentos do RDS; Labs Práticos com Bancos Open Source e Comerciais.
[Amazon/AWS RDS Tutorial for Beginners | Setup, Security, Backup & Connect with EC2](https://www.youtube.com/watch?v=yVVBpCddG40) ¹ | 1 semana | 3 horas | Provisionamento; Segurança; Backup Automatizado; Integração com EC2.
[AWS RDS Tutorials (playlist)](https://www.youtube.com/playlist?list=PLl8w8gCvr4jKmPCHDKQrKof7QMNh9Tzrd) ¹ | 3 semanas | 3 horas / semana | Multi-AZ; Read Replicas; Monitoramento com CloudWatch.

---

#### 15. Estatística e Fundamentos Matemáticos para Análise de Dados

Embora não seja o foco central da rotina de um DBA, uma base sólida em estatística é altamente recomendada para o profissional que deseja apoiar áreas de Big Data, Data Warehouse e tomada de decisão orientada a dados dentro do currículo de pós-graduação.

Curso | Duração | Dedicação | Conteúdos
:-- | :--: | :--: | :--:
[Estatística Descritiva Básica](https://www.youtube.com/playlist?list=PLw9ZE443YE45QSRr576gk6ZfhbWVjiIbr) | 2 horas | 1 semana | Associações; Tipos de Variáveis; Variância e Desvio; Tipos de Gráficos.
[Estatística Computacional](https://www.youtube.com/playlist?list=PLUUx2DlFul6LjL3K9AZT2nTlyZ4o38tE7) | 5 semanas | 4 horas / semana | Razão e Distribuição; Geração de Variáveis; Monte Carlo; AIC e BIC.

---

¹ Curso ministrado em idioma diferente do Português (Inglês/Espanhol), com legendas automáticas disponíveis na plataforma do YouTube. Foram incluídos por serem referências de altíssima qualidade técnica e ainda não possuírem equivalente nacional com o mesmo nível de profundidade, conforme discutido e votado pela comunidade [nesta issue](https://github.com/Universidade-Livre/ciencia-da-computacao/issues/6). Caso faça uso do mesmo e queira fazer algum feedback, ficaremos felizes em receber sua contribuição.
