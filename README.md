
----

<div align="center">
<h4>

███╗░░██╗██╗░░░██╗██╗░░░██╗███████╗███╗░░██╗░██████╗
████╗░██║██║░░░██║██║░░░██║██╔════╝████╗░██║██╔════╝
██╔██╗██║██║░░░██║╚██╗░██╔╝█████╗░░██╔██╗██║╚█████╗░
██║╚████║██║░░░██║░╚████╔╝░██╔══╝░░██║╚████║░╚═══██╗
██║░╚███║╚██████╔╝░░╚██╔╝░░███████╗██║░╚███║██████╔╝
╚═╝░░╚══╝░╚═════╝░░░░╚═╝░░░╚══════╝╚═╝░░╚══╝╚═════╝░
</div>
</h5>

----

<details>
  <summary><b> 1. Azure </b></summary>
<div align="Left"> 

<br>

  <details>
  <summary> 1.1 Azure Products </summary>
  <div>

<br> 

   | Serviço | Descrição | Documentação |
   |---------|-----------|--------------|
   | VMs | Privisionamento de Máquinas Virtuais | <a href="https://learn.microsoft.com/en-us/azure/virtual-machines/overview"> Virtual Machines </a> |
   | Spot VMs | VMs para uso de capacidade inutilizada do Azure | <a href="https://learn.microsoft.com/en-us/azure/virtual-machines/spot-vms"> Spot VMs </a> |
   | VMs Scale Sets  | Grupo de Máquinas Virtuais com LB | <a href="https://learn.microsoft.com/en-us/azure/virtual-machine-scale-sets/overview"> Scale Sets </a> |
   | Compute Fleet  | Frota de Máquinas Virtuais | <a href="https://learn.microsoft.com/en-us/azure/azure-compute-fleet/overview"> Compute Fleet </a> |   
   | App Service  | Plataforma para Aplicações Web, APIs e Back Ends para Mobiles | <a href="https://learn.microsoft.com/en-us/azure/app-service/overview"> App Service </a> |      
   | Container Instances (ACI) | Execução de Contêineres no Azure | <a href="https://learn.microsoft.com/en-us/azure/container-instances/container-instances-overview"> Container Instances </a> |       
   | CycleCloud  | Orquestração de Ambientes HPC (High Performance Computing) | <a href="https://learn.microsoft.com/en-us/azure/cyclecloud/overview?view=cyclecloud-8"> CycleCloud </a> |      
   | Dedicated Hosts  | Servidores Físicos para Hospedagem de VMs | <a href="https://learn.microsoft.com/en-us/azure/virtual-machines/dedicated-hosts"> Dedicated Hosts </a> |
   | Functions  | Solução Serverless com Foco em Código | <a href="https://learn.microsoft.com/en-us/azure/azure-functions/functions-overview"> Functions </a> |      
   | Kubernetes Fleet Manager  | Gerenciamento de Múltiplos Clusters Kubernetes | <a href="https://learn.microsoft.com/en-us/azure/kubernetes-fleet/overview"> K8s Fleet Manager </a> | 
   | Kubernetes Service  | Serviço Gerenciado de K8s | <a href="https://learn.microsoft.com/en-us/azure/aks/what-is-aks"> Kubernetes </a> |      
   | Quantum  | Serviço de Computação Quântica | <a href="https://learn.microsoft.com/en-us/azure/quantum/overview-azure-quantum"> Quantum </a> |      
   | Service Fabric  | Plataforma de Sistemas Distribuídos | <a href="https://learn.microsoft.com/en-us/azure/service-fabric/service-fabric-overview"> Service Fabric </a> |      
   | Virtual Desktop | Serviço de Virtualização de Desktop e App. | <a href="https://learn.microsoft.com/en-us/azure/virtual-desktop/overview"> Virtual Desktop </a> |   
   | VMware Solution | Nuvens Privadas que possuem clusters vSphere. | <a href="https://learn.microsoft.com/en-us/azure/azure-vmware/introduction"> VMware Solution </a> |
   | Batch  | Execução de serviços batch paralelizados em alta escala, e processamento de alta performance. | <a href="https://learn.microsoft.com/en-us/azure/batch/batch-technical-overview"> Batch </a> |   
   | SQL Server on VMs | Permite usar versão completa do SQL Server sem hardware on-prem. | <a href="https://learn.microsoft.com/en-us/azure/azure-sql/virtual-machines/windows/sql-server-on-azure-vm-iaas-what-is-overview?view=azuresql&toc=%2Fazure%2Fvirtual-machines%2Fwindows%2Ftoc.json"> SQL Server VM </a> |
   | Static Web Apps  | Serviço que provisiona stack inteira de Aplicações Web através de um repositório de código. | <a href="https://learn.microsoft.com/en-us/azure/static-web-apps/overview"> Web Apps </a> |   
   | Analysis Services | PaaS inteiramente gerenciável que fornece Data Models em nível empresarial. |  <a href="https://learn.microsoft.com/en-us/analysis-services/azure-analysis-services/analysis-services-overview?view=sql-analysis-services-2025"> Analysis Services </a> |
   | Chaos Studio  | Teste de Resiliência do Azure | <a href="https://learn.microsoft.com/en-us/azure/chaos-studio/chaos-studio-workspaces-overview"> Chaos Studio </a> |   
   | Data Explorer  | Plataforma Analytics de Big Data  | <a href="https://learn.microsoft.com/en-us/azure/data-explorer/data-explorer-overview"> Data Explorer </a> |   
   | Data Factory  | Serviço Cloud de ETL - Extract Transform Load / ELT - Extract Load Transform.  | <a href="https://learn.microsoft.com/en-us/azure/data-factory/introduction"> Data Factory </a> |
   | Data Lake Storage  | Repositório para armazenamento de dados estruturados e não estruturados.   | <a href="https://learn.microsoft.com/en-us/azure/storage/blobs/data-lake-storage-introduction"> Data Lake Storage </a> |
   | Data Share | Compartilhamento de Dados / Arquivos com múltiplos clientes e parceiros. | <a href="https://learn.microsoft.com/en-us/azure/data-share/overview"> Data Share </a> | 
   | Databricks | Plataforma em Nuvem, escalável, de Análise de Dados | <a href="https://learn.microsoft.com/en-us/azure/databricks/introduction/"> Databricks </a> | 
   | Stream Analytics | Processamento de Dados em Tempo Real | <a href="https://learn.microsoft.com/en-us/azure/stream-analytics/stream-analytics-introduction"> Stream Analytics </a> | 
   | Synapse Analytics | Plataforma unificada de Data Warehousing e Big Data | <a href="https://learn.microsoft.com/en-us/azure/synapse-analytics/overview-what-is"> Synapse Analytics </a> | 
   | Data Lake Analytics | Descontinuado | <a href="https://learn.microsoft.com/en-us/previous-versions/azure/data-lake-analytics/data-lake-analytics-overview"> Data Lake Analytics </a> |
   | Event Hubs | Ingestão de Dados em grande escala. Recebe e processa milhões de eventos por segundo. | <a href="https://learn.microsoft.com/en-us/azure/event-hubs/event-hubs-about"> Event Hubs </a> |
   | HDInsight | Plataforma de cluster gerenciável para uso de Frameworks de Dados (Apache Spark, Hive, LLAP, Kafka, Hadoop) | <a href="https://learn.microsoft.com/en-us/azure/hdinsight/hdinsight-overview"> HDInsight </a> |
   | Fabric | Plataforma de Análise de Dados All in One | <a href="https://learn.microsoft.com/en-us/fabric/fundamentals/microsoft-fabric-overview"> Fabric </a> |
   | Purview | Governança de Dados e Proteção. | <a href="https://learn.microsoft.com/en-us/purview/purview"> Purview </a> |
   | Power BI | Transformação de Dados em Relatórios e Dasbhboards | <a href="https://learn.microsoft.com/en-us/power-bi/fundamentals/power-bi-overview"> Power BI </a> |
   | App Configuration | Gerenciamento Central de Aplicações | <a href="https://learn.microsoft.com/en-us/azure/azure-app-configuration/overview"> App Configuration </a> |
   | Container Apps | Plataforma Serverless para Execução de Aplicações Contênerizadas | <a href="https://learn.microsoft.com/en-us/azure/container-apps/overview"> Container Apps </a> | 
   | Container Registry | Armazenamento e Gerenciamento de Imagens de Contêineres. | <a href="https://learn.microsoft.com/en-us/azure/container-registry/container-registry-intro"> Container Registry </a> | 
   | Container Storage | Gerenciamento de Volume para Contêineres. | <a href="https://learn.microsoft.com/en-us/azure/storage/container-storage/container-storage-introduction"> Container Storage  </a> |  
   | Azure Ret Hat OpenShift | Provisionamento de cluster OpenShift totalmente gerenciável. | <a href="https://learn.microsoft.com/en-us/azure/storage/container-storage/container-storage-introduction"> ARO </a> |
   | Cache for Redis | Descontinuado (Azure Managed Redis) | <a href="https://learn.microsoft.com/en-us/azure/azure-cache-for-redis/cache-overview"> Cache for Redis </a> |
   | Confidential Ledger | Serviço de BD gerenciado pela MS, armazena registros de dados de forma imutável e à prova de adulteração. | <a href="https://learn.microsoft.com/en-us/azure/confidential-ledger/overview"> Confidential Ledger </a> |
   | Cosmos DB | BD NoSQL gerenciado e multimodelo da MS, projeto para baixa latência global, alta disponibilidade e escalabilidade elástica. | <a href="https://learn.microsoft.com/en-us/azure/cosmos-db/overview"> Cosmos DB </a> |
   | Database for Maria DB | Descontinuado (Azure Database for MySQL) | <a href="https://learn.microsoft.com/en-us/previous-versions/azure/mariadb/overview"> Maria DB </a> |
   | Database for MySQL | BD Relacional baseado no MySQL Community Edition. | <a href="https://learn.microsoft.com/en-us/azure/mysql/flexible-server/overview"> Database for MySQL </a> |
   | Database for Postgre | BD Relacional que usa versões de Community | <a href="https://learn.microsoft.com/en-us/azure/postgresql/overview"> Database for Postgre </a> |
   | Database Migration Service (DMS) | Migração de Bancos On-Premises ao Azure | <a href="https://learn.microsoft.com/en-us/azure/dms/dms-overview"> Database Migration Service </a> |
   | DocumentDB | Banco de Dados compatível com MongoDB | <a href="https://learn.microsoft.com/en-us/azure/documentdb/overview"> DocumentDB </a> |




<br>

  </div>
  </details>           

</div> 
</details>

----


