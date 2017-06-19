The purpose of this GitHub repository is to help **startups** quickly engage and get up and running on Azure services.  You'll find links to key documentation, tutorials and code packets.  If you have feedback on the content please submit an **[issue](https://github.com/Azure-for-Startups/Content/issues)**.

<br><br>

## Table of Contents

<table class="table table-bordered table-striped table-hover border-0px">

<td valign="top" width="50%"><a href="./README.md#new-and-notable-in-azure"><b>- New and notable in Azure</b></a>&nbsp;&nbsp;Check out new feature releases and updates applicable for Start-Ups updated monthly.<br><br><a href="./README.md#getting-started-on-azure"><b>- Getting started on Azure</b></a>&nbsp;&nbsp;Learning paths, tutorials, videos, and all you need to know to get ramped up on Azure<br><br><a href="./README.md#migrating-to-azure"><b>- Migrating to Azure</b></a>&nbsp;&nbsp;Tools &amp; services, tutorials, and official information on how to move your existing solution to Azure.<br><br><a href="./README.md#additional-useful-tools--links"><b>- Tools and links</b></a>&nbsp;&nbsp;Azure price calculator, Azure Trust Center, and other useful additions to help your success on Azure.<br><br></td>  
<td valign="top" width="50%"><a href="./README.md#infrastructure-services-iaas"><b>- Infrastructure Services</b></a><br>&nbsp;&nbsp;&nbsp;Compute, Networking, Storage<br><br><a href="./README.md#platform-services-paas"><b>- Platform Services</b></a><br>&nbsp;&nbsp;&nbsp;Web &amp; Mobile, Data, <br>&nbsp;&nbsp;&nbsp;Intelligence &amp; Analytics, IoT<br><br><a href=""><b></b></a><a href="./README.md#cloud-architecture"><b>- Cloud Architecure</b></a>&nbsp;&nbsp;patterns, practices, and architecture blueprints. <br><br><a href="./README.md#azure-resource-manager-arm"><b>- Azure Resource Manager</b></a>&nbsp;&nbsp;overview and availability chart<br><br><a href="./README.md#feature-highlights"><b>- Feature highlights</b></a>&nbsp;&nbsp;Get beyond the basics. Helpful features in Azure for Start-ups<br><br></td>
</tr>
</table>  

## New and notable in Azure  
  

[Visual Studio: **Gain powerful info about your web app by using new tools in Microsoft Azure Application Insights**](https://azure.microsoft.com/en-us/blog/new-tools-for-understanding-user-behavior-with-application-insights/)  
Which features of your web app are most popular and most frequently used? Do your users achieve their goals with your app? Microsoft has released new tools in Application Insights to help you understand user behavior and empower your development team to better understand how customers use your web apps.  Every time you update your app, you can assess how well it works for users. You can get rich performance monitoring, powerful alerting, and easy-to-consume dashboards to help ensure your applications are available and performing as you expect.  
  
  
[Azure compute: **Your Microsoft-managed admin machine in Azure, for Azure**](https://azure.microsoft.com/en-us/blog/public-preview-of-azure-cloud-shell/)  
Microsoft has announced the public preview of Azure Cloud Shell. Cloud Shell provides an interactive, browser-accessible, pre-configured shell experience for managing Azure resources without the overhead of installing, versioning, and maintaining a machine yourself. The authenticated shell experience is hosted in the cloud and accessible from virtually anywhere. It enables you to use common tools and programming languages in a shell that’s updated and maintained by Microsoft. You can also persist your files across sessions by using attached Azure File storage.


  
[Azure Advisor: **Optimize Azure resources with personalized guidance from Azure Advisor**](https://azure.microsoft.com/en-us/blog/announcing-azure-advisor-azure-monitor-and-resource-health/)  
The recently announced Azure Advisor is a personalized cloud consultant that helps you follow best practices to optimize your Azure deployments at no additional cost. You can use it to scan your Azure resources and get actionable recommendations based on configuration and usage patterns. It also guides you through the implementation of each recommendation, so you can make the adjustments you want quickly and easily.  
  

[Cosmos DB: **Build fast, scalable, globally distributed applications by using Azure Cosmos DB**](https://azure.microsoft.com/en-us/blog/azure-cosmos-db-microsofts-globally-distributed-multi-model-database-service/)  
Microsoft has announced the general availability of Azure Cosmos DB, a globally distributed multimodel database. Azure Cosmos DB is the first globally-distributed data service that lets you elastically scale throughput and storage across any number of geographical regions while guaranteeing low latency, high availability, and consistency—and it’s backed by the most comprehensive SLAs in the industry. Azure Cosmos DB is the right solution for your globally distributed mission-critical applications—including web, mobile, gaming, and IoT applications—when predictable throughput, high availability, low latency, and a schema-free data model are key requirements.  
  
  
[Database Systems: **Microsoft extends Azure managed database services with the introduction of MySQL and PostgreSQL**](https://azure.microsoft.com/en-us/blog/microsoft-extends-azure-managed-database-services-with-introduction-of-mysql-and-postgresql/)  
MySQL and PostgreSQL databases are among the popular open-source choices used by developers to build and deploy a variety of applications, including web, mobile, content management system (CMS), and customer relationship management (CRM) apps. Microsoft has announced the preview of managed database services with two additions to the Azure relational database platform: Azure Database for MySQL and Azure Database for PostgreSQL. Your developers can now choose their favorite database engines delivered as managed services on Azure. These services seamlessly integrate with most common open-source programming languages—like PHP, Python, and Node.js—and application development frameworks like WordPress, Magento, Drupal, Django, and Ruby on Rails. 
  
  

[IoT: **Learn to quickly design and develop IoT solutions with Azure IoT training**](https://azure.microsoft.com/en-us/blog/microsoft-launches-azure-iot-technical-training-developers-can-start-quickly-with-iot/)  
Sometimes it can be challenging for an enterprise developer to start an IoT project, especially with the overwhelming amount of technical information available online. To simplify IoT development, Microsoft has created training—Developing IoT Solutions with Azure IoT—designed to help developers learn how to connect and manage devices, analyze data, and extract insights by using a flexible IoT platform. The structured curriculum of this training will help developers become familiar with Azure IoT and enable them to start a proof of concept in no time. The training uses a combination of videos and hands-on labs to help developers quickly become familiar with the Azure IoT platform.  
  
  
[Hyper scale compute: **Microsoft brings container orchestration for Windows Server Containers to Azure Service Fabric**](https://azure.microsoft.com/en-us/blog/announcing-windows-server-container-orchestration-with-azure-service-fabric/)  
Running a traditional application inside containers is an easy first step to gain some of the benefits of a microservices architecture, such as improved density and easier application lifecycle management. Azure Service Fabric is the Microsoft microservices platform, and Microsoft has announced the release of Service Fabric 5.6 runtime and 2.6 SDK, which support the orchestration of Windows Server Containers. This release includes many new features targeted at container orchestration, including a DNS service, resource governance, Microsoft Operations Management Suite integration, and more. It also contains support for Docker Compose for deploying containerized apps to Service Fabric with Microsoft Visual Studio 2017 tooling integration.  
  
  
[Azure Video Services: **Video Indexer—a cloud service that lets you easily extract insights from your videos** ](https://azure.microsoft.com/en-us/blog/introducing-video-indexer-a-cloud-service-to-unlock-insights-from-your-videos/)  
When video and audio content lacks human-understandable, time-stamped metadata, it can be difficult to find. Generating such metadata for video and audio is expensive and next to impossible when you have a high volume of this type of content. Microsoft has announced the public preview of a cloud service called Video Indexer as part of Microsoft Cognitive Services. Video Indexer enables organizations with digital video and audio content to automatically extract metadata and use it to build intelligent, innovative applications. It builds upon media AI technologies to make it easier for you to extract insights from video and audio. You can use Video Indexer to power new forms of content discovery, like searching for spoken words, faces, characters, and emotions, and to enrich your apps with embedded video insights to drive user engagement.  
  
  
[Azure: **Massive-scale cloud rendering with Autodesk on Azure** ](https://azure.microsoft.com/en-us/blog/massive-scale-cloud-rendering-with-autodesk-on-azure/)  
When implementing a rendering project, it’s hard to find the right infrastructure, set up a render farm made up of high-performance compute clusters, and then manage the render farm. Even small projects can take anywhere from days to weeks to complete. The cloud is perfectly suited for variable-length and long-running rendering projects. Microsoft has announced the preview of Azure Batch Rendering and its integration with Autodesk.  When used together with Autodesk, Azure opens doors for artists, engineers, designers, and developers. Built on top of Azure Batch, a mature production service, this new rendering platform will allow you to seamlessly submit rendering jobs by using Autodesk’s suite of products—including Autodesk Maya, 3ds Max, and Arnold—together with the agility, flexibility, and scalability of Azure compute.  
  


## Getting Started on Azure  
- **[Get started on Azure](https://azure.microsoft.com/en-us/get-started/)** – Link to Azure.com Getting Started page.
- **[Interactive Azure Map](https://aka.ms/azmap)** - Interactive overview of services available on Azure. Click on a service to learn about it.
- **[Azure Learning Paths](https://azure.microsoft.com/en-us/documentation/learning-paths/)** - Get started with these learning paths for different Azure Services.
- **[Azure on Microsoft Virtual Academy](https://mva.microsoft.com/training-topics/cloud-app-development)** - Virtual courses on cloud development.
- **[Azure on Channel9](https://channel9.msdn.com/AzurAdditione)** - Video tutorials about Azure services.
- **[Startup Offers](https://azure.microsoft.com/en-us/pricing/member-offers/bizspark-startups/)** - Get free cloud credits and offers through Microsoft’s BizSpark program.
- **[Microsoft Azure for Amazon AWS Cloud professionals: Getting Started](https://channel9.msdn.com/Shows/TechNet+Radio/TNR1667)** - Showcase and demo of Microsoft Azure features and comparison to Amazon Web Services to see how they match up.

   <table class="table table-bordered table-striped table-hover">
<tr>
          <td valign="top">
  <h3><i> Getting started on Azure video series</i></h3>
    -    <a href="https://channel9.msdn.com/Series/BizSpark-StartUp-Stories/Getting-Started-on-Azure-Overview-of-the-Azure-portal"><b>Getting Started on Azure:  *Overview of the Azure portal*</b></a>- An introduction to the Azure portal, covering navigation and key elements of the portal including the Azure dashboard, marketplace, and resources.<br>
    -    <a href="https://channel9.msdn.com/Series/BizSpark-StartUp-Stories/Getting-Started-on-Azure-Resource-Groups"><b>Getting Started on Azure:  *Resource Groups*</b></a> - Learn what to consider and how to create and manage a resource group on the Azure portal.<br>
    -    <a href="https://channel9.msdn.com/Series/BizSpark-StartUp-Stories/Getting-Started-on-Azure-Storage-Accounts"><b>Getting Started on Azure:  *Storage Accounts*</b></a> - Learn how to create and manage a storage account on the Azure portal and select the storage option that is right for you.<br>
    -    <a href="https://channel9.msdn.com/Series/BizSpark-StartUp-Stories/Getting-Started-on-Azure-Virtual-Networks"><b>Getting Started on Azure:  *Virtual Networks*</b></a> - Learn how to set up a virtual network including IP address blocks, DNS settings, security policies, and routing tables on the Azure portal.<br>
    -    <a href="https://channel9.msdn.com/Series/BizSpark-StartUp-Stories/Getting-Started-on-Azure-Virtual-Machines"><b>Getting Started on Azure:   *Virtual Machines*</b></a> - Learn how to set up and configure an Ubuntu virtual machine on the Azure portal.<br>
    -    <a href="https://azure.microsoft.com/en-us/get-started/"><b>Additional Getting Started on Azure videos</b></a> - View additional Getting Started on Azure videos such as Windows Server Virtual Machines, Web Apps, SQL Database on Azure and more.<br>
	   </td>
</tr>
    </table> 


![](./Content/media/AzureMap.png)<p> </p>  
<p> </p>  
  
## Feature highlights  
### Storage  
[**Storage Service Encryption (SSE) for Azure File Storage**](https://docs.microsoft.com/en-us/azure/storage/storage-service-encryption). When enabled, SSE automatically encrypts data at rest using a 256-bit encryption key—helping organizations meet organizational security and industry compliance requirements.  
  
### Backup  
[**Instant File Recovery from Cloud using Azure Backup**](https://azure.microsoft.com/en-us/blog/instant-file-recovery-from-cloud-backups-using-azure-backup/). Restore as a service (RaaS) enhances your Azure Backup capabilities by instantly restoring files and folders from multiple recovery points in the cloud or on-premises. RaaS enables you to maintain business continuity in addition to high availability.  
  
  
### Azure Linux  
[**Easily scale with Kubernetes, now available on Azure Container Service (ACS)**](https://azure.microsoft.com/en-us/blog/kubernetes-now-generally-available-on-azure-container-service/)  
Kubernetes lets you scale without increasing your ops team. Startups that focus on cloud-native application development, mobile application development, gaming, or e-commerce can quickly deploy container-based applications to enable agility, portability, and scalability.  
  
### Service Bus  
[**Boost cloud security with Azure Relay Hybrid Connections** ](https://docs.microsoft.com/en-us/azure/service-bus-relay/relay-what-is-it) 
In the past, this was only available for WCF services. Hybrid Connections removes the dependency upon WCF by using open standards-based protocols. Now you can establish bi-directional connections from any on-premises service, in any language, to your cloud-based clients.  
   
### Azure CLI  
[**Manage VMs with commands in Azure CLI 2.0**](https://docs.microsoft.com/en-us/cli/azure/get-started-with-azure-cli) Create and manage your Azure virtual machines, containers, and more with Azure Command-Line Interface (CLI) 2.0 on your operating system of choice.  This enables startups to script and automate Azure resources from their native environments, including macOS, Linux, and Windows.  
  
### Azure Stream Analytics  
[**Track data with real-time geospatial analytics in Azure Stream Analytics**](https://azure.microsoft.com/en-us/blog/announcing-real-time-geospatial-analytics-in-azure-stream-analytics/) Azure Stream Analytics now offers real-time geospatial analytics, with production-grade quality and just a few lines of code.  The new capabilities include native functions to compute geospatial operations (such as overlap between polygons, intersection between paths, and more), as well as the ability to join multiple streams for more complex calculations.  
  
### Networking  
[**Adapt content for global users with Azure Traffic Manager Geographic Routing**](https://azure.microsoft.com/en-us/blog/announcing-the-general-availability-of-geographic-routing-capability-in-azure-traffic-manager/) Azure Traffic Manager Geographic Routing lets you get the right content to the right users by customizing it for the location of your customer, by country or region. This means you can make your service compliant with local data access or privacy mandates. Your startup will be able to easily maintain a global presence and direct user traffic to specific endpoints based on geographic location.  
  
### Azure Resource Manager (ARM)  
[**Simplify VM deployment using custom templates in Azure Resource Manager (ARM)**](https://docs.microsoft.com/en-us/azure/templates/)Custom Azure Resource Manager (ARM) templates are a great way to make deploying virtual machines and resources a repeatable, easy-to-automate process. The template reference documentation explains the available resource types you can use to create custom templates for various Azure resources—including what values to use in your template.  

## Working with Azure
- **[Azure Portal](https://portal.azure.com/)** - The best way to get started is with the Azure portal, a web based interface for managing Azure.
- **[Azure SDKs & Tools](https://azure.microsoft.com/en-us/downloads/)** - SDKs for many common languages such as .NET, Java, Node.js, Python, Ruby and other tools.

- **[Azure PowerShell](https://msdn.microsoft.com/en-us/library/jj156055.aspx)** - Work with PowerShell cmdlets to perform Azure operations.
- **[Azure CLI](https://azure.microsoft.com/en-us/documentation/articles/xplat-cli-install/)** – Create/manage Azure resources using a set of open-source shell-based commands.
- **[Azure API Reference](https://msdn.microsoft.com/en-us/library/azure/mt420159.aspx)** - Reference for Azure REST and .NET APIs.
- **[Azure Solutions](https://azure.microsoft.com/en-us/solutions/?v=3)** - A listing of top Azure solutions and their brief descriptions
- **[Azure Products and services](https://azure.microsoft.com/en-us/services/)** – A searchable list of all Azure products and services

![](./Content/media/PortalImage.png)

## Migrating to Azure 
-	**[AWS to Azure mapping](https://azure.microsoft.com/en-us/campaigns/azure-vs-aws/mapping/)** - Map between Azure and AWS services
-	**[AWS to Azure migration](https://azure.microsoft.com/en-in/documentation/articles/site-recovery-migrate-aws-to-azure/)** - Migrate virtual machines in Amazon Web Services (AWS) to Azure with Azure Site Recovery
-	**[MongoDB to Azure Migration resources](./Content/MongoDB%20Azure%20Migration.md)**  

  <h3><i> Tutorials and Sample code</i></h3>
     <table class="table table-bordered table-striped table-hover">
	<tr>
	  <td valign="top"><a href="Content/AWS VM to Azure VM Migration.md"><b>AWS VM to Azure VM migration</b></a></td>
	  <td valign="top"><a href="Content/AWS RDS to Azure SQL migration.md"><b>AWS CDN to Azure CDN Migration</b></a></td>
	  <td valign="top"><a href="https://github.com/Azure-for-Startups/Amazon-S3-to-Azure-Storage-demo"><b>AWS S3 to Azure Blob Storage migration</b></a></td>
	  <td valign="top"><a href="Content/Amazon CDN to Azure CDN migration.md"><b>AWS CDN to Azure CDN Migration</b></a></td>
	  <td valign="top"><a href="Content/ASP.NET Web App migration from AWS to Azure.md"><b>ASP.NET Web App migration from AWS to Azure</b></a></td>
	 </tr>
     </table>

   ### *Tools & Services*
   - **[AWCopy](https://github.com/cicorias/AWCopy)** - Azure service that provides parallelized copies of S3 files in Amazon Web Services to Azure blobs.
   - **[CloudBerry Cloud Migrator](http://www.cloudberrylab.com/cloud-migrator.aspx)** - service to transfer files from one cloud storage to another (Amazon S3 & Glacier, Windows Azure Blob Storage, Rackspace Cloud Files and FTP servers).
   - **[Azure Import/Export Service](https://azure.microsoft.com/en-us/documentation/articles/storage-import-export-service/)** - Transfer Data to Blob Storage.

# Infrastructure Services (IaaS)
Infrastructure as a service (IaaS) refers to the compute, networking and storage building blocks which allow you to build any kind of cloud solution. IaaS allows you to have maximum control on how you manage virtual machines, network configuration but requires you to invest in attaining robustness, availability and scalability in the cloud.  

## Compute 
-	**[Learning Path for Azure VMs](https://azure.microsoft.com/en-us/documentation/learning-paths/virtual-machines/)** - Learn how to deploy and manage VMs. 
-	**[Linux VM](https://azure.microsoft.com/en-us/documentation/articles/virtual-machines-linux-quick-create-portal/)** – Get started creating a Linux VM on the Azure Portal and utilize [proven practices](https://azure.microsoft.com/en-us/documentation/articles/guidance-compute-single-vm-linux/) to run the Linux VM.
-	**[Windows VM](https://azure.microsoft.com/en-us/documentation/articles/virtual-machines-windows-hero-tutorial/)** – Get started creating a Windows VM on the Azure Portal
-	**[VM Extensions](https://azure.microsoft.com/en-us/documentation/articles/virtual-machines-windows-extensions-features/)** - Gain an overview of extensions to virtual machines such as the Chef, Docker or custom script extensions.  Direct link to [Docker VM Extension](https://docs.microsoft.com/en-us/azure/virtual-machines/virtual-machines-linux-dockerextension?toc=%2fazure%2fvirtual-machines%2flinux%2ftoc.json)
-	**[VM Scale Sets Overview](https://azure.microsoft.com/en-us/documentation/articles/virtual-machine-scale-sets-overview/)** - Learn about deploying and managing VM scale sets.
-	**[Service Fabric Overview](https://azure.microsoft.com/en-us/documentation/services/service-fabric/)** – a distributed systems platform that makes it easy to package, deploy, and manage scalable, reliable microservices.
-	**[Choose between App Services, Service Fabric and VMs](https://azure.microsoft.com/en-us/documentation/articles/choose-web-site-cloud-service-vm/)** - including scenarios and recommendations.
-	**[Docker Documentation](https://docs.docker.com/)** - Starting point for documentation on Dockers including Docker for MAC, Windows, Linux, etc.
-	**[Docker VM Extension](https://docs.microsoft.com/en-us/azure/virtual-machines/virtual-machines-linux-dockerextension?toc=%2fazure%2fvirtual-machines%2flinux%2ftoc.json)** - Create a Docker environment in Azure using the Docker VM extension.

  <h3><i> Tutorials and Sample code</i></h3>
     <table class="table table-bordered table-striped table-hover">
	<tr>
	  <td valign="top"><a href="https://github.com/Azure-for-Startups/Containers-on-Azure-demo"><b>Containers on Azure</b></a> - Perform heavy computational tasks (for example video or audio encoding, hash calculation, data encryption, etc.) and make the process scalable and cost effective using Docker containers.</td>
	  <td valign="top"><a href="https://azure.microsoft.com/en-us/documentation/articles/virtual-machines-linux-dockerextension/"><b>Deploy to Azure using the Docker VM Extension</b></a> - use Resource Manager templates to deploy the Docker VM Extension in a custom, production-ready environment that you define</td>
	  <td valign="top"><a href="https://github.com/Azure-for-Startups/Amazon-S3-to-Azure-Storage-demo"><b>AWS S3 to Azure Blob Storage migration</b></a></td>
	  <td valign="top"><a href="https://azure.microsoft.com/en-us/documentation/articles/virtual-machines-linux-classic-ruby-rails-web-app/"><b>Ruby on Rails web app on Azure VM</b></a></td>
	 </tr>
     </table>

## Networking
-	**[Virtual Networks (Vnets) Overview](https://azure.microsoft.com/en-us/documentation/articles/virtual-networks-overview/)** – Learn about Azure Virtual Networks and how to create them.
-	**[Network Security Groups](https://azure.microsoft.com/en-us/documentation/articles/virtual-networks-nsg/)** – Learn about Network Security Groups (NSGs) and how to configure them.
-	**[Load-Balancers](https://azure.microsoft.com/en-us/documentation/articles/load-balancer-overview/)** – Learn about Azure Load Balancer and to configure one.

## Storage

- **[Introduction to Azure Storage](https://azure.microsoft.com/en-us/documentation/articles/storage-introduction/)** – Learn the basics of Azure Storage including Blob, Table, Queue, and File storage.
- **[Azure Backup](https://azure.microsoft.com/en-us/services/site-recovery/)** – Learn about and how to implement Azure Backup to back up (or protect) and restore your data in the Microsoft cloud.
- **[Azure Site Recovery](https://azure.microsoft.com/en-us/services/site-recovery/)** – Orchestrate your disaster recovery plan.
- **[Create a storage account](https://azure.microsoft.com/en-us/documentation/articles/storage-create-storage-account/)** – Learn how to create a general purpose or blob storage account with links to getting started on Blob, Table, Queue, and file storage accounts.

# Platform Services (PaaS)
Platform as a Service (PaaS) resources are Azure services which are built for most cases and allow you to enjoy high availability, scalability and robustness out of the box. Instead of managing VMs directly, let Azure manage the underlying infrastructure and focus on building your applications and solutions. 

## Web & Mobile
- **[Azure App Service overview](https://azure.microsoft.com/en-us/documentation/services/app-service/)** – Learn about Web Apps, Mobile Apps, API apps.
- **[Azure Web Apps](https://azure.microsoft.com/en-us/services/app-service/web/)** – Create and deploy mission-critical web apps that scale with your business.
- **[Azure Mobile Apps](https://docs.microsoft.com/en-us/azure/app-service-mobile/app-service-mobile-value-prop)** – Build engaging iOS, Android, and Windows apps.
- **[Getting Started with Xamarin](https://azure.microsoft.com/en-us/features/xamarin/)** - Create cloud-powered mobile apps faster across iOS, Android, and Windows.  Overview of Xamarin and how to use it.
- **[Notification Hub overview](https://azure.microsoft.com/en-us/documentation/services/notification-hubs/)** - An easy-to-use, multiplatform, scaled-out push infrastructure.
- **[Azure Search](https://azure.microsoft.com/en-us/documentation/articles/search-what-is-azure-search/)** - Ready-to-use service that you can populate with your data and then use to add search to your web or mobile apps.
- **[Azure Mobile Services REST API Reference MSDN](https://msdn.microsoft.com/en-US/library/azure/jj710108.aspx)** – Documentation on Mobile Services REST API and the available operations.
- **[Azure Deployment Using Git](./Content/Azure-Deployment-using-Git.md)** – Learn the basics and understand available resources to support publishing web applications on Azure using Git workflows.
- **[Azure Media Services (AMS) Overview](https://azure.microsoft.com/en-us/documentation/articles/media-services-overview/)** – Learn about Azure Media Services and how to build scalable media management and delivery apps.

  <h3><i> Tutorials and Sample code</i></h3><table class="table table-bordered table-striped table-hover">
        <tr>
          <td valign="top"><a href="https://github.com/Azure-for-Startups/Notification-Hub-demo"><b>Notification Hub demo</b></a> - Deliver push notification messages to mobile applications on iOS, Android and Windows Phone platforms using Azure Notification Hub</td>
          <td valign="top"><a href="./Content/Deploy%20Node.js%20PHP%20and%20Python%20Web-apps-on-Azure.md"><b>PHP, Node.js, and Python</b></a> - Deploy PHP, Node.js and Python web apps on Azure and learn how to configure Azure App service</td>
         </tr>
     </table>
## Data 
- **[Azure SQL Overview](https://azure.microsoft.com/en-us/documentation/articles/sql-database-technical-overview/)** – Gain an overview on SQL and how to create a SQL DB on Azure.
- **[Azure SQL (PaaS) vs. SQL Server on Azure VMs (IaaS)](https://azure.microsoft.com/en-us/documentation/articles/sql-database-paas-vs-sql-server-iaas/)** - Learn what scenarios are better for an IaaS vs. PaaS SQL solution.
- **[DocumentDB](https://azure.microsoft.com/en-us/documentation/services/documentdb/)** – Learn about this fully managed NoSQL database service and how to build and manage DocumentDB applications.
- **[MongoDB on Azure](https://docs.mongodb.com/ecosystem/platforms/windows-azure/)** – Learn about MongoDB on Azure and deployment recommendations.

  <h3><i> Tutorials and Sample code</i></h3>
     <table class="table table-bordered table-striped table-hover">
        <tr>
          <td valign="top"><a href="https://azure.microsoft.com/en-us/documentation/articles/documentdb-import-data/"><b>Import data to DocumentDB with the Database Migration tool</b></a> – Learn how to use the open source DocumentDB data migration tool to import data to Azure DocumentDB</td>
          <td valign="top"><a href="https://azure.microsoft.com/en-us/documentation/articles/virtual-machines-windows-classic-install-mongodb/"><b>Install MongoDB on a Windows VM</b></a> - Learn how to install MongoDB on a Linux VM in Azure.</td>	  
          <td valign="top"><a href="https://docs.mongodb.com/v3.0/administration/install-on-linux/"><b>Install MongoDB on Linux</b></a> - Learn how to install MongoDB on a Linux VM in Azure.</td>
          <td valign="top"><a href="https://azure.microsoft.com/en-us/documentation/articles/web-sites-dotnet-store-data-mongodb-vm/"><b>Create a web app that connects to MongoDB</b></a> – Learn how to create a web page in Azure that connects to MongoDB running on a VM.</td>
	  </tr>
     <tr>
          <td colspan="4" valign="top" align="left"><b>[SQL DB and Elastic pool feature tutorials](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-explore-tutorials)</b> – simple step-by-start tutorial for different SQL feature areas</td>
     <tr>	
</table>
     
## Intelligence & Analytics *(incl. Machine learning and Cognitive services)*
- **[Azure HDInsight](https://azure.microsoft.com/en-us/services/hdinsight/)** - An introduction to Hadoop on Azure HDInsight, its ecosystem, and big data. Learn about the Hadoop components, common terminology, and scenarios for big data analysis.
- **[Stream Analytics](http://azure.microsoft.com/en-us/services/stream-analytics/)** - Overview of Azure stream analytics, low-cost solutions to gain real-time insights from devices, sensors, infrastructure, and applications 
- **[Additional Intelligence and Analytics services](https://azure.microsoft.com/en-us/services/?sort=popular&filter=intelligence-analytics)** – HDInsight, Machine Learning, Data Factory, Log Analytics, Data Catalog, Power BI Embedded, Data Lake store and much more.
- **[Machine Learning Overview](https://azure.microsoft.com/en-us/documentation/articles/machine-learning-what-is-machine-learning/)** - Overview and tutorial on Machine Learning.  Or explore further [Machine Learning](https://azure.microsoft.com/en-us/services/machine-learning/)
- **[Azure Machine Learning Studio](https://azure.microsoft.com/en-us/documentation/articles/machine-learning-what-is-ml-studio/)** - A collaborative, drag-and-drop tool you can use to build, test, and deploy predictive analytics solutions.
- **[Get started with Microsoft Cognitive Services](https://channel9.msdn.com/Events/Connect/2016/102)** – Learn how to easily add powerful artificial intelligence capabilities to your applications with Microsoft Cognitive Services.  See [Cognitive Services](http://www.microsoft.com/cognitive) for more information.
- **[Cognitive Services: Making AI Easy](https://channel9.msdn.com/Events/Machine-Learning-and-Data-Sciences-Conference/Data-Science-Summit-2016/MSDSS08)** – The rise of machine learning has produced an explosion of APIs to make your applications more intelligent.  Learn about more than 20 Cognitive Services APIs.  You'll see powerful demos, experience the simplicity of calling this code, and get ideas for adding this functionality to your own applications.

  <h3><i> Tutorials and Sample code</i></h3>
    <table class="table table-bordered table-striped table-hover">
        <tr>
	  <td valign="top"><b>[Data Science and Machine Learning](https://github.com/MSFTImagine/computerscience/tree/master/Complimentary%20Course%20Content/Module5)</b> – Microsoft Imagine course content - learn fundamental concepts of machine learning and use Spark to predict the trend and patterns of massive data sets</td>
	</tr>
     </table>


## Internet of Things
- **[Azure IoT suite documentation](https://azure.microsoft.com/en-us/documentation/suites/iot-suite/)** - Starting point to learning and using the Azure IoT suite.

  <h3><i> Tutorials and Sample code</i></h3>
    <table class="table table-bordered table-striped table-hover">
        <tr>
	  <td valign="top"><b>[IoT Microsoft Imagine course content](https://github.com/MSFTImagine/computerscience/tree/master/Complimentary%20Course%20Content/Module6)</b> – learn how to collect streaming data from IoT devices and analyze the streaming data</td>
	  <td valign="top"><b>[MyDriving App IoT sample](https://azure.microsoft.com/en-us/campaigns/mydriving/)</b> – MyDriving app uses a wide range of Azure services to process and analyze car telemetry data for both real-time insights and long-term patterns and trends</td>
</tr>
     </table>

# Cloud Architecture
-	**[Cloud Patterns & Practices](https://aka.ms/mspnp)** - Best practices for building cloud solutions. Including checklists and design patterns. 
-	**[Architecture Blueprints](https://msdn.microsoft.com/architects-blueprints-msdn)** - Architectures for an array of different cloud scenarios.

# Additional Useful Tools & Links
-	**[Azure Price Calculator](https://aka.ms/azurecalc)** - Easily calculate pricing of Azure Services. 
-	**[Azure Trust Center](https://azure.microsoft.com/en-us/support/trust-center/)** - Learn about Azure security, compliance, privacy and transparency.
-	**[Azure Subscription Service Limits](https://azure.microsoft.com/en-us/documentation/articles/azure-subscription-service-limits/)** - Learn about Azure subscription and service limits, quotas, and constraints.
-	**[Azure Resource Explorer](http://resources.azure.com/)** - A very useful web application to explore the Azure REST API.
-	**[Azure Storage Explorer](http://storageexplorer.com/)** - A client application for Linux, Mac or Windows to easily work with storage accounts on Azure.

# Azure Resource Manager (ARM)
The Azure Resource Manager is at the core of the Azure platform and is used to deploy and manage Azure services. Every resource in Azure managed under ARM can be described and managed in a consistent way. It's very helpful to understand the Azure Resource Manager and how to work with Resource Groups.
-	**[ARM Overview](https://azure.microsoft.com/en-us/documentation/articles/resource-group-overview/)** - Get an overview of the Azure Resource Manager.
-	**[ARM vs. Classic](https://azure.microsoft.com/en-us/documentation/articles/resource-manager-deployment-model/)** - Understand the difference between ARM and the Classic (ASM) deployment model.
-	**[Azure portal availability chart](https://azure.microsoft.com/en-us/features/azure-portal/availability/)** – use the availability chart to determine what services are supported by ARM and the Azure portal

## ARM Templates
ARM templates are JSON descriptions of ARM deployments which can be used for "Infrastructure as Code".
-	**[Deploying ARM Templates](https://azure.microsoft.com/en-us/documentation/articles/resource-group-template-deploy/)** – Learn how to deploy ARM templates using PowerShell, Azure CLI or REST API.
-	**[Quick Start Templates](https://github.com/Azure/azure-quickstart-templates)** - A Github maintained, vast collection of templates for common use cases to help you get started authoring your own templates or deploying simple solutions.
-	**[Template Authoring](https://azure.microsoft.com/en-us/documentation/articles/resource-group-authoring-templates/)** - How to author custom templates.
