# Treinamento Plataforma GoodData (MFX)

## Objetivo:
Treinamento consiste na qualificação da plataforma GoodData, através dos seus recursos, para criação de modelos de dados, worflow de transformações e carregamentos dos dado, parametrizaçõe via plataforma SaaS, bem como a criação de relatórios, dashboard, KPI, e analise quantitivas e qualitativas sobre os dados.
## Carga Horária: 
> 12 Horas
#
## Cronograma: 

> 1 - Dia (One Day):
#
*Topicos*:
* Descomplicando o conceito de ***BI*** vs ***BA***
* Entendendo a modelagem ***SnowFlack*** /***StarSchema***
* Entendendo o conceito de Fato e Dimensão (***Cubo OLAP***)
* Entendendo o fluxo de dados do GoodData
* Entendendo sobre o extrator ***Agent***
* Acessando o Painel do Analytics (GoodData)
* Baixando e configurando o ***CloudConnect***
* Inicializando o projeto
  
> 2 - Dia (Two Day):
#
*Topicos*:

* Entendendo a modelagem de dados
* Configurando o atributos de fato e dimensão
* Entendendo os relacionamentos dos dados
* Criando um dataset de *Fato* e *Dimensão*
* Criando workflow de dados (ETL)
* Entendendo sobre os ***graph*** e seus componentes
* Entendendo sobre os componentes de Escrita de dados:
    * Trash
    * GD_Dataset_Write
    * CSV_Write
* Entendendo sobre os componentes de leitura de dados:
    * CSV_Reader
    * HTTP_Connector
    * REST_Connector
    * SpreadSheetReader
    * JSON_Reader

* Entendendo os componentes de Transformação:
    * FastSort
    * Reformat
    * Concatenate
    * SimpleCopy
* Etendendo os componentes de worflow:
    * File Download
    * File Delete
* Exportando worflow para o plataforma GoodData
> 3 - Dia (Three Day): 
#
*Topicos*:

* Acessando os dados via Plataforma
* Configuração de acesso e permissionamento de usuários
* Configuração de variaveis de ambientes
* Analisando o ***Data Console Integration***
* Criando ***schedules*** a partir workflow (ETL)
* Criando métricas (MAQL / SQL )
* Criando relatórios customizados 
* Criando e customizando dashboards
* Estilizando os dashboards

<br>

# Documentações:

* [Documentação oficial - GoodData](https://help.gooddata.com/doc/enterprise/en)
* [Documentação CloudConnect](https://link-url-here.org)

  * [Criando Projeto](https://help.gooddata.com/cloudconnect/manual/gooddata-project.html)
  * [Estrutura do Workspace](https://help.gooddata.com/cloudconnect/manual/standard-structure-of-all-cloudconnect-projects.html)
  * [Configuração do Ambiente (Variaveis)](https://help.gooddata.com/cloudconnect/manual/workspace-prm-file.html)
  * [Configurando Perspectivas](https://help.gooddata.com/cloudconnect/manual/opening-cloudconnect-perspective.html)
  * [Navigator](https://help.gooddata.com/cloudconnect/manual/designer-navigator.html)
  * [Server Explore](https://help.gooddata.com/cloudconnect/manual/designer-server-explorer.html)
  * [Paleta de Componentes](https://help.gooddata.com/cloudconnect/manual/graph-editor-with-palette.html)
  * [Tabs](https://help.gooddata.com/cloudconnect/manual/designer-tabs.html)
* [Criando Graphs (ETL)](https://help.gooddata.com/cloudconnect/manual/creating-empty-graphs.html)
  * [Utilizando o modelador de graphs](https://help.gooddata.com/cloudconnect/manual/creating-transformation-graph.html)
  * [Componentes - Readers](https://help.gooddata.com/cloudconnect/manual/readers.html)
  * [Componentes - Wirtes](https://help.gooddata.com/cloudconnect/manual/writers.html)
  * [Componentes - Transforms](https://help.gooddata.com/cloudconnect/manual/transformers.html)
  * [Componentes - Joiners](https://help.gooddata.com/cloudconnect/manual/joiners.html)
  * [Componentes - Others](https://help.gooddata.com/cloudconnect/manual/others.html)
  * [Conectores - Edges](https://help.gooddata.com/cloudconnect/manual/edge.html)
    * [Conectado compoenentes](https://help.gooddata.com/cloudconnect/manual/connecting-by-edges.html)
    * [Tipos de conectores](https://help.gooddata.com/cloudconnect/manual/types-of-edges.html)
    * [Atribuindo metadata aos conectores](https://help.gooddata.com/cloudconnect/manual/assigning-metadata.html)
    * [Habilitando o modo "Debugging"](https://help.gooddata.com/cloudconnect/manual/debug-edges.html)
  * [Metadatas](https://help.gooddata.com/cloudconnect/manual/metadata.html)
    * [Extraindo metadatas](https://help.gooddata.com/cloudconnect/manual/metadata-from-flat-file.html)
    * [Extraindo metadatas para datasets](https://help.gooddata.com/cloudconnect/manual/metadata-from-gooddata.html)
    * 
  * [Executando um graph](https://help.gooddata.com/cloudconnect/manual/running-graphs.html)
  * [Importando graphs](https://help.gooddata.com/cloudconnect/manual/import-graphs.html)
* [Fazendo deploy de um projeto](https://help.gooddata.com/cloudconnect/manual/ch10.html)
* [Importando um projeto](https://help.gooddata.com/cloudconnect/manual/ch11.html)
* [Escrenvendo dados em Datasets - (GDDataset)](https://help.gooddata.com/cloudconnect/manual/hr-example.html)
* [Carregado dados do Google Analytics](https://help.gooddata.com/cloudconnect/manual/ch15.html)
* [Carregado dados via API REST](https://help.gooddata.com/cloudconnect/manual/ch16.html)
* [Carregando dados do Facebook](https://help.gooddata.com/cloudconnect/manual/ch30s01.html)
* [Carregando dados de Bancos de Dados](https://help.gooddata.com/cloudconnect/manual/creating-internal-database-connections.html)
* [Utilizando Gray pages do GoodData](https://help.gooddata.com/cloudconnect/manual/ch19.html)
  * [Configurando "Scheduling" do projeto](https://help.gooddata.com/cloudconnect/manual/ch20.html)
* [Configurando niveis de log](https://help.gooddata.com/cloudconnect/manual/program-and-vm-arguments.html)
* [Overview da plataforma GoodData](https://help.gooddata.com/doc/enterprise/en/expand-your-gooddata-platform/gooddata-platform-overview)

* [Link text Here](https://link-url-here.org)

* [Carregando dados externos](https://help.gooddata.com/start/load-data-81961907.html)
* [Importando CSV](https://help.gooddata.com/start/import-csv-files-into-a-gooddata-workspace-81961908.html)
* [Criando relacionamento dos Datasets](https://help.gooddata.com/start/create-a-relationship-between-datasets-81968623.html)
* [Publicando seu Data Model](https://help.gooddata.com/start/publish-your-logical-data-model-81968630.html)
  * [Entendendo mais sobre a modelagem de dados](https://help.gooddata.com/doc/enterprise/en/data-integration/data-modeling-in-gooddata)
* [Criando Métricas Customizadas](https://help.gooddata.com/start/create-and-save-a-metric-81961865.html)
* [Utilizando o "Data Integration"](https://help.gooddata.com/doc/enterprise/en/data-integration)
* [Formatação de dados numéricos](https://help.gooddata.com/doc/enterprise/en/dashboards-and-insights/analytical-designer/work-with-metrics/format-numbers)
* [Criando Dashboars](https://help.gooddata.com/doc/enterprise/en/dashboards-and-insights/dashboards/create-dashboards)
  * [Editando Dashboards](https://help.gooddata.com/doc/enterprise/en/dashboards-and-insights/dashboards/edit-items-on-dashboards)
  * [Compartilhando Dashboards](https://help.gooddata.com/doc/enterprise/en/dashboards-and-insights/dashboards/share-dashboards)
  * [Duplicando Dashboards](https://help.gooddata.com/doc/enterprise/en/dashboards-and-insights/dashboards/duplicate-dashboards)
  * [Aplicando "Schedule" para envio de dashboards por email](https://help.gooddata.com/doc/enterprise/en/dashboards-and-insights/dashboards/schedule-automatic-emailing-of-dashboards)
  * [Aplicando "Drill Down"](https://help.gooddata.com/doc/enterprise/en/dashboards-and-insights/dashboards/drilling-in-dashboards)
  * [Aplicando customização de tema](https://help.gooddata.com/doc/enterprise/en/dashboards-and-insights/create-custom-themes)
  * [Exemplos de temas](https://help.gooddata.com/doc/enterprise/en/dashboards-and-insights/create-custom-themes/theme-examples)
  * [Customizando paleta de cores](https://help.gooddata.com/doc/enterprise/en/dashboards-and-insights/importing-custom-color-palettes)
  * [MAQL - Sintaxe](https://help.gooddata.com/doc/enterprise/en/dashboards-and-insights/maql-analytical-query-language)
