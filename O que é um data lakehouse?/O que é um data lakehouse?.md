# O que é um data lakehouse? 
## A história do gerenciamento de dados.


Neste vídeo, você aprenderá sobre a origem e a finalidade do data lakehouse e os desafios do gerenciamento de big data.
Para entender o que é um data lakehouse, você precisará explorar a história do gerenciamento de dados e da análise. No final da década de 1980, as empresas queriam aproveitar insights orientados por dados para decisões de negócios e inovação. 
Para fazer isso, as organizações tiveram que passar de bancos de dados relacionais simples para sistemas que pudessem gerenciar e analisar dados que estavam sendo gerados e coletados em grandes volumes e em um ritmo mais rápido. 
Os armazéns de dados foram projetados para coletar e consolidar esse fluxo de dados e fornecer suporte para análise e inteligência de negócios em geral. 
Os dados em um data warehouse são estruturados e limpos com esquemas predefinidos.

No entanto, os data warehouses não foram projetados com dados semiestruturados ou não estruturados em mente e tornaram-se muito caros ao tentar armazenar e analisar quaisquer dados que não o fizessem. 
À medida que as empresas cresciam e o mundo se tornava mais digital, a coleta de dados aumentou drasticamente em volume, velocidade e variedade, desfavorecendo os data warehouses. 
Levava muito tempo para processar dados e fornecer resultados, e havia capacidade limitada para lidar com a variedade e velocidade dos dados.

No início dos anos 2000, o advento do big data impulsionou o desenvolvimento de data lakes onde dados estruturados, semiestruturados e não estruturados poderiam viver simultaneamente, coletados nos volumes e velocidades necessários.
Vários tipos de dados podem ser armazenados lado a lado em um data lake.
Os dados criados a partir de muitas fontes diferentes, como logs da Web ou dados de sensores, podem ser transmitidos para o data lake de forma rápida e barata em armazenamentos de objetos na nuvem de baixo custo.
No entanto, embora os data lakes resolvessem o dilema do armazenamento, eles apresentavam preocupações adicionais e careciam dos recursos necessários dos data warehouses.


Primeiro, os data lakes não oferecem suporte a dados transacionais e não podem impor a qualidade dos dados; portanto, a confiabilidade dos dados armazenados no datalake é questionável, principalmente devido aos vários formatos.

Em segundo lugar, com um volume tão grande de dados, o desempenho da análise é mais lento e a pontualidade dos resultados que afetam a decisão nunca se manifestou.

E terceiro, a governança sobre os dados em um datalake cria desafios com segurança e aplicação de privacidade devido à natureza não estruturada do conteúdo de um data lake.


Como os data lakes não substituíram totalmente os datawarehouses por informações confiáveis de BI, as empresas implementaram ambientes complexos de pilha de tecnologia, incluindo data lakes, data warehouses,
e sistemas especializados adicionais para streaming, séries temporais, gráficos e bancos de dados de imagem, para citar alguns.
Mas esse ambiente introduzia complexidade e atraso, pois as equipes de dados ficavam presas em silos, concluindo um trabalho desarticulado.
Os dados precisavam ser copiados entre os sistemas e, em alguns casos, copiados de volta, impactando a supervisão e a governança do uso de dados, sem mencionar o custo de armazenar as mesmas informações duas vezes com sistemas desarticulados.
A implementação bem-sucedida da IA foi.
E os resultados acionáveis exigiam dados de vários lugares.
O valor por trás dos dados foi perdido.

Em um estudo recente da Accenture, apenas 32% das empresas relataram valor mensurável a partir dos dados.
Algo precisava mudar porque as empresas precisavam de um sistema único e flexível de alto desempenho para dar suporte aos casos de uso cada vez maiores para exploração de dados, modelagem preditiva e análise preditiva.
As equipes de dados precisavam de sistemas para oferecer suporte a aplicativos de dados, incluindo análise SQL, análise em tempo real, ciência de dados e aprendizado de máquina.

Para atender a essas necessidades e abordar as preocupações e desafios.
Uma nova arquitetura de gerenciamento de dados surgiu: o data lakehouse.
O data lakehouse foi desenvolvido como uma arquitetura aberta, combinando os benefícios de um data lake com o poder analítico e os controles de um data warehouse.
Construído em um data lake, um data lakehouse pode armazenar todos os dados de qualquer tipo juntos, tornando-se uma única fonte confiável de verdade, fornecendo acesso direto para IA e BI juntos.

Data lakehouses como a Databricks Lakehouse Platform oferecem vários recursos importantes, como **suporte a transações**, incluindo transações de ativos para interações simultâneas de leitura/gravação,
**aplicação e governança de esquemas** para integridade de dados e necessidades robustas de auditoria, **governança de dados** para dar suporte à regulamentação de privacidade e métricas de uso de dados,
**Suporte de BI** para reduzir a latência entre a obtenção de dados e o desenho de insights.
Além disso, o data lakehouse oferece **armazenamento desacoplado da computação**, o que significa que cada um opera em seus próprios clusters, permitindo que eles sejam dimensionados de forma independente para dar suporte a necessidades específicas.

**Formatos de armazenamento abertos** como o Apache Parquet, que são abertos e padronizados, ao que uma variedade de ferramentas e mecanismos podem acessar os dados de forma direta e eficiente **suporte para diversos tipos de dados**,
para que uma empresa possa armazenar, refinar, analisar e acessar dados semiestruturados, estruturados e não estruturados em um único local.
**Suporte para diversas cargas de trabalho**, permitindo uma variedade de cargas de trabalho, como ciência de dados, aprendizado de máquina e análise SQL.
Usar o mesmo repositório de dados e **streaming de ponta a ponta** para relatórios em tempo real elimina a necessidade de um sistema separado dedicado a aplicativos de dados em tempo real.

O lakehouse oferece suporte ao trabalho de analistas de dados, engenheiros de dados e cientistas de dados em um único local.
O lakehouse é essencialmente a versão modernizada de um data warehouse, fornecendo todos os benefícios e recursos sem comprometer a flexibilidade em profundidade de um data lake.

##

# What is a data lakehouse?  
## The history of data management.


In this video, youll learn about the originand purpose of the data lakehouse and the, challenges of managing big data.
To understand what a data lakehouse is, youllneed to explore the history of data management, and analytics.
In the late 1980s, businesses wanted to harnessdata-driven insights for business decisions and innovation.
To do this, organizations had to move pastsimple relational databases to systems that could manage and analyze data that was beinggenerated and collected at high volumes and at a faster pace.
Data warehouses were designed to collect andconsolidate this influx of data and provide support for overall business intelligence and analytics.
Data in a data warehouse is structured and clean with predefined schemas.

However, data warehouses were not designed with semi-structured or unstructured data in mind, and became very expensive when tryingto store and analyze any data that didnt, 
As companies grew and the world became moredigital, data collection drastically increased in volume, velocity, and variety, pushing data warehouses out of favor.
It tooktoo much time to process data and provide results, and there was limited capabilityto handle data variety and velocity.


In the early 2000s, the advent ofbig data drove the development of data lakes where structured, semi-structured, and unstructured data could live simultaneously, collected in the volumes and speeds necessary.
Multiple data types could be stored side-by-side in a data lake.
Data created from many different sources,such as web logs or sensor data, could be streamed into the data lake quickly and cheaply inlow cost cloud object stores.
However, while data lakes solved the storage dilemma, it introduced additional concerns and lacked necessary features from data warehouses.

First, data lakes are not supportive of transactional data and cant enforce data quality, so the, reliability of the data stored in the datalake is questionable, mostly due to the various formats.

Second, with such a large volume of data, the performance of analysis is slower, and the timeliness of decision-impacting results has never manifested.

And third, governance over the data in a datalake creates challenges with security and privacy enforcement due to the unstructured nature of the contents of a data lake.

Because data lakes didnt fully replace datawarehouses for reliable BI insights, businesses, implemented complex technology stack environments, including data lakes, data warehouses, 
and additional specialized systems for streaming, time series, graph, and image data bases to name a few.

But such an environment introduced complexity and delay as data teams were stuck in silos, completing disjointed work.
Data had to be copied between the systems and in some cases copied back, impacting oversight and data usage governance, not to mention the cost of storing the same information twice with disjointed systems.
Successful AI implementation was.
And actionable outcomes required data from multiple places.
The value behind the data was lost.

In a recent study by Accenture, only 32% of companies reported measurable value from data.
Something needed to change because businesses needed a single, flexible high performance system to support the ever increasing usecases for data exploration, predictive modeling, and predictive analytics.
Data teams needed systems to support data applications, including SQL analytics, real-time analysis, data science, and machine learning.

To meet these needs and address the concerns and challenges.
A new data management architecture emerged: the data lakehouse.
The data lakehouse was developed as an openarchitecture, combining the benefits of a data lake with the analytical power and controlsof a data warehouse.
Built on a data lake, a data lakehouse can store all data of any type together, becoming a single reliable source of truth, providing direct access for AI and BI together.

Data lakehouses like the Databricks Lakehouse Platform offer several key features, such as **transaction support**, including asset transactionsfor concurrent read/write interactions, 
**schema enforcement and governance** for data integrity, and robust auditing needs, **data governance** to support privacy regulationand data use metrics, 
**BI support** to reduce the latency between obtaining data and drawing insights.
Additionally, the data lakehouse offers **decoupled storage from compute**, meaning each operates on their own clusters, allowing them to scalein dependently to support specific needs.

**Open storage formats** such as Apache Parquet, which are open and standardized, ao a variety of tools and engines can access the data directly and efficiently **support for diverse data types**, 
so a business can store, refine, analyze, and access semi-structured, structured, and unstructured data in one location.
**Support for diverse workloads**, allowing arange of workloads such as data science, machine learning, and SQL analytics.
To use the same data repository and **end-to-end streaming** for real-time reports removes the need for a separate system dedicated to real-time data applications.  

The lakehouse supports the work of data analysts, data engineers, and data scientists all in one location.
The lakehouse essentially is the modernized version of a data warehouse, providing all the benefits and features without compromising the flexibility in depth of a data lake.

