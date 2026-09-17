
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
   | Managed Instance for Apache Cassandra | Serviço totalmente gerenciado para Clusters Apache Cassandra. | <a href="https://learn.microsoft.com/en-us/azure/managed-instance-apache-cassandra/introduction"> Apache Cassandra </a> |
   | Managed Redis | Armazenamento de dados em Memória. | <a href="https://learn.microsoft.com/en-us/azure/redis/overview"> Managed Redis </a> | 
   | SQL Database | Banco de Dados PaaS | <a href="https://learn.microsoft.com/en-us/azure/azure-sql/database/sql-database-paas-overview?view=azuresql"> SQL Database </a> | 
   | Table Storage | Armazenamento de dados NoSQL estruturados na Nuvem. | <a href="https://learn.microsoft.com/en-us/azure/storage/tables/table-storage-overview"> Table Storage </a> |
   | Boards | Serviço Web para times planejaram, acompanharem e discutirem ciclo de vida de desenvolvimento. | <a href="https://learn.microsoft.com/en-us/azure/devops/boards/get-started/what-is-azure-boards?view=azure-devops"> Azure Boards </a> |
   | DevOps | Plataforma em Nuvem que fornece ferramentas integradas para desenvolvimento de software. | <a href="https://learn.microsoft.com/en-us/azure/devops/user-guide/what-is-azure-devops?view=azure-devops&toc=%2Fazure%2Fdevops%2Fget-started%2Ftoc.json"> DevOps </a> | 
   | DevTest Labs | Provisionamento rápido e gerenciamento de VMs para Desenvolvimento / Teste. | <a href="https://learn.microsoft.com/en-us/azure/devtest-labs/devtest-lab-overview"> DevTest Labs </a> | 
   | Azure Pipelines | Parte do Azure DevOps, combinando CI, CT e CD. | <a href="https://learn.microsoft.com/en-us/azure/devops/pipelines/get-started/what-is-azure-pipelines?view=azure-devops"> Pipelines </a> | 
   | Microsoft Dev Box | Descontinuado (Microsoft 365) | <a href="https://learn.microsoft.com/en-us/azure/dev-box/overview-what-is-microsoft-dev-box"> Dev Bos </a> | 
   | Playwright Workspaces | Plataforma para teste de aplicações | <a href="https://learn.microsoft.com/en-us/azure/app-testing/playwright-workspaces/overview-what-is-microsoft-playwright-workspaces"> Playwright </a> |
   | App Testing | Testes de performance e funcionais em alta escala.  | <a href="https://learn.microsoft.com/en-us/azure/app-testing/overview-what-is-azure-app-testing"> App Testing </a> |
   | Azure Artifacts | Armazenamento de pacotes como npm, NuGet, Maven, Cargo, etc.  | <a href="https://learn.microsoft.com/en-us/azure/devops/artifacts/start-using-azure-artifacts?view=azure-devops"> Artifacts </a> |
   | Deployment Environments | Descontinuado | <a href="https://learn.microsoft.com/en-us/azure/deployment-environments/overview-what-is-azure-deployment-environments"> Deployment Environments </a> | 
   | Azure Managed Grafana | Serviço operado e suportado pela MS, integração com ecossistema Azure. | <a href="https://learn.microsoft.com/en-us/azure/managed-grafana/overview"> Managed Grafana </a> |
   | Azure Monitor | Serviço de Observabilidade Unificado para coletar, analisar e agir sobre telemetria. | <a href="https://learn.microsoft.com/en-us/azure/azure-monitor/fundamentals/overview"> Monitor </a> |
   | Azure Repos | Conjunto de ferramentas de controle de versionamento, para gerenciamento de código. | <a href="https://learn.microsoft.com/en-us/azure/devops/repos/get-started/what-is-repos?view=azure-devops"> Repos </a> |
   | Test Plans | Ferramentas para qualidade e colaboração durante processo de desenvolvimento. | <a href="https://learn.microsoft.com/en-us/azure/devops/test/overview?view=azure-devops"> Test Plans </a> |
   | Azure Arc | Plataforma de gerenciamento e governança de data centers, múltiplas nuvens / multicloud e Edge. | <a href="https://learn.microsoft.com/en-us/azure/azure-arc/overview"> Arc </a> |
   | ExpressRoute | Conectividade entre redes On-Premises e Microsoft Cloud, sobre conexão privaa. | <a href="https://learn.microsoft.com/en-us/azure/expressroute/expressroute-introduction"> ExpressRoute </a> | 
   | IoT Edge | Runtime para provisionamento, execução e monitoramento de aplicações Linux contêinerizadas. | <a href="https://learn.microsoft.com/en-us/azure/iot-edge/about-iot-edge"> IoT Edge </a> |
   | AKS Edge Essentials | Execuçao automatizada de aplicações contêinerizadas em escala, com baixo resquício e instalação simples. | <a href="https://learn.microsoft.com/en-us/azure/aks-hybrid-edge/edge-essentials/aks-edge-overview"> AKS Edge </a> | 
   | Azure Local | Estende as capacidades do Azure para ambientes do cliente. Facilita o provisionamento de aplicações modernas e legadas. | <a href="https://learn.microsoft.com/en-us/azure/azure-local/overview?view=azloc-2609"> Local </a> |
   | Operator Nexus | Plataforma para operadores de Telecomunicação. | <a href="https://learn.microsoft.com/en-us/azure/operator-nexus/overview"> Operator Nexus </a> | 
   | Operator Service Manager | Orquestração em nuvem para automatizar ciclo de vida de worklods móveis no Operator Nexus. | <a href="https://learn.microsoft.com/en-us/azure/operator-service-manager/azure-operator-service-manager-overview"> Operator Service Manager </a> | 
   | Stack Edge | Dispositivo de Hardware (Appliance), enviado da MS para instalações do cliente, levando processamento, armazenamento, e IA para a boarda da rede. | <a href="https://learn.microsoft.com/en-us/azure/databox-online/"> Stack Edge </a> |
   | Stack Hub | Extensão do Azure que providencia execução de Apps em ambientes On-Premises e entrega serviços Azure no seu Datacenter. | <a href="https://learn.microsoft.com/en-us/azure-stack/operator/azure-stack-overview?view=azs-2604"> Stack Hub </a> |
   | Defender for Cloud | Solução unificada que combina múltiplas ferramentas de segurança para proteção das aplicações no seu ciclo de vida. | <a href="https://learn.microsoft.com/en-us/azure/defender-for-cloud/defender-for-cloud-introduction"> Defender for Cloud </a> | 
   | Sentinel | Solução SIEM Cloud-Native, combinando AI, automação e inteligência de ameaça para suportar detecção, investigação e resposta às ameaças. | <a href="https://learn.microsoft.com/en-us/azure/sentinel/overview?tabs=defender-portal"> Sentinel </a> | 
   | Information Protection | Descontinuado (Microsoft Purview) | <a href="https://learn.microsoft.com/en-us/azure/information-protection/what-is-information-protection"> Information Protection </a>
   | Entra Domain Services | Gerenciamento de serviços de domínio, como Join, Group Policy, LDAP, autenticação Kerberos / NTLM. Sem precisar de DCs | <a href="https://learn.microsoft.com/en-us/entra/identity/domain-services/overview"> Entra Domain Services </a> | 
   | Entra External ID | Gerenciamento de Identidades Terceiras (B2B). | <a href="https://learn.microsoft.com/en-us/entra/external-id/external-identities-overview"> Entra External ID </a> | 
   | Microsoft Entra | Produtos de Identidade e Acesso | <a href="https://learn.microsoft.com/en-us/entra/fundamentals/what-is-entra"> Microsoft Entra </a> | 
   | API Management | Plataforma para Ciclo de Vida de API. | <a href="https://learn.microsoft.com/en-us/azure/api-management/api-management-key-concepts"> API Management </a> |
   | API for FHIR | Descontinuado (Azure Health Data Services FHIR service) | <a href="https://learn.microsoft.com/en-us/azure/healthcare-apis/azure-api-for-fhir/overview"> API for FHIR </a> | 
   | Data Manager for Agriculture | Descontinuado | <a href="https://learn.microsoft.com/en-us/azure/data-manager-for-agri/overview-azure-data-manager-for-agriculture"> Data Manager for Agriculture </a> |
   | Health Data Services | Solução que ajuda a coletar, armazenar e analisar dados de saúde de diferentes formatos e origens. | <a href="https://learn.microsoft.com/en-us/azure/healthcare-apis/healthcare-apis-overview"> Health Data Services </a> |
   | Web PubSub | Serviço para desenvolvimento de aplicações e que entrega atualizações em tempo real. | <a href="https://learn.microsoft.com/en-us/azure/azure-web-pubsub/overview"> Web PubSub </a> |
   | Event Grid | Serviço de Publicação / Subscrição para distribuilção de mensagens. | <a href="https://learn.microsoft.com/en-us/azure/event-grid/overview"> Event Grid </a> | 
   | Logic Apps | Plataforma de criação de Workflows e integração de serviços, sistemas, apps e dados. | <a href="https://learn.microsoft.com/en-us/azure/logic-apps/logic-apps-overview"> Logic Apps </a> | 
   | Data Manager for Energy | Plataforma de dados para a indústria da energia. | <a href="https://learn.microsoft.com/en-us/azure/energy-data-services/overview-microsoft-energy-data-services"> Data Manager for Energy </a> |
   | Service Bus | Agente gerenciável de fila de mensagens e tópicos de publicação / assintura. | <a href="https://learn.microsoft.com/en-us/azure/service-bus-messaging/service-bus-messaging-overview"> Service Bus </a> | 
   | Digital Twins | Plataforma que permite a criação de modelos digitais de ambientes (fazendas, cidades, construções, etc.) | <a href="https://learn.microsoft.com/en-us/azure/digital-twins/overview"> Digital Twins </a> |
   | Azure IoT | Serviços para conectar, gerenciar e derivar inteligência de dispositivos IoT e equipamentos industriais. | <a href="https://learn.microsoft.com/en-us/azure/iot/iot-introduction"> Azure IoT </a> | 
   | Azure IoT Central | Plataforma de aplicação, análise de cenário IoT dentro da empresa. | <a href="https://learn.microsoft.com/en-us/azure/iot-central/core/overview-iot-central"> IoT Central> </a> |
   | Azure IoT Hub | Comunicação em escala entre aplicação IoT e os dispositivos conectados. | <a href="https://learn.microsoft.com/en-us/azure/iot-hub/iot-concepts-and-iot-hub"> IoT Hub </a> |
   | Azure IoT Operations | Plano de Dados para Edge. Serviços de dados escaláveis e modulares em cluster Azure Erc-enabled Kubernetes. | <a href="https://learn.microsoft.com/en-us/azure/iot-operations/overview-iot-operations"> IoT Operations </a> |
   | Machine Learning | Gerenciamento do projeto de ciclo de vida de ML. | <a href="https://learn.microsoft.com/en-us/azure/machine-learning/overview-what-is-azure-machine-learning?view=azureml-api-2"> Machine Learning </a> |
   | Azure Maps | Serviços Geoespaciais que usam dados geográficos, e fornece contexto geográficos para aplicações web e móveis. | <a href="https://learn.microsoft.com/en-us/azure/azure-maps/about-azure-maps"> Azure Maps </a> |
   | Azure Sphere | Plataforma de aplicação com comunicação e segurança embutida, para dispositivos conectados na internet. | <a href="https://learn.microsoft.com/en-us/azure-sphere/product-overview/what-is-azure-sphere?view=azure-sphere-integrated"> Sphere </a> | 
   | Microsoft Defender for IoT | Solução de segurança para dispositivos IoT. | <a href="https://learn.microsoft.com/en-us/azure/defender-for-iot/organizations/overview"> Defender for IoT </a> | 
   | Notification Hubs | Permite envio de notificações push para qualquer plataforma, de qualquer back-end. | <a href="https://learn.microsoft.com/en-us/azure/notification-hubs/notification-hubs-push-notification-overview"> Notification Hubs </a> | 
   | Windows 10 IoT Core Services | Serviços essenciais para comercializar dispositivos que usam o W10 | <a href="https://learn.microsoft.com/en-us/previous-versions/windows/iot-core/manufacture/iotcoreservicesoverview"> W10 IoT Core Services </a> | 
   | Windows for IoT | Família de SO Windows para dispositivos embarcados e de propósito específico. | <a href="https://learn.microsoft.com/en-us/windows/iot/iot-enterprise/overview"> Windows for IoT </a> |
   | Azure Resource Manager (ARM) Templates | Arquivo JSON que define infraestrutura e configuração do projeto. | <a href=https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/overview"> ARM Templates </a> |
   | Azure Automation | Serviço de automação que ajuda a automatizar processos e suporta gerenciamento consistente através do Azure e ambientes não Azure. | <a href="https://learn.microsoft.com/en-us/azure/automation/overview"> Azure Automation </a> |
   | Advisor | Assistente digital que ajuda a seguir melhores práticas para otimizar provisionamentos Azure. | <a href="https://learn.microsoft.com/en-us/azure/advisor/advisor-overview"> Advisor </a> | 
   | Azure Backup | Serviço que ajuda a proteger dados e restaurar quando necessário. | <a href="https://learn.microsoft.com/en-us/azure/backup/backup-overview"> Backup </a> | 
   | 

<br>

  </div>
  </details>           

</div> 
</details>

----


