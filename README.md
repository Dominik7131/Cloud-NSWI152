# Cloud-NSWI152

- poznámka: během dělání úkolů jsem použil dva různé Microsoft účty

## Lab 1
- podle instrukcí jsem založil a publikoval jednoduchou aplikaci

![lab01-1](Lab1-AppServicesDeployment/Lab1-01-VS-publish.png)

![lab01-2](Lab1-AppServicesDeployment/Lab1-02-Published-page.png)


## Lab 2

- do projektu z předchozího labu jsem přidal WebJob

![lab02-1](Lab2-AzureSQL/Lab-2-03-Web-Job.png)

- vytvořil jsem Azure SQL databázi

![lab02-2](Lab2-AzureSQL/Lab-2-01-Database-Created.png)

- pomocí příkazu jsem vytvořil tabulku

![lab02-3](Lab2-AzureSQL/Lab-2-02-Database-Query.png)

- aplikace úspěšně funguje

![lab02-3](Lab2-AzureSQL/Lab-2-04-App-Builded.png)


## Lab 3
- založil jsem Azure Storage a container

![lab03-1](Lab3-AzureBlobStorage/Lab3-01-Storage-Created.png)

![lab03-2](Lab3-AzureBlobStorage/Lab3-02-Container-Created.png)

- přidal jsem connection string a aplikace úspěšně funguje

![lab03-3](Lab3-AzureBlobStorage/Lab3-03-Successful-build.png)

![lab03-4](Lab3-AzureBlobStorage/Lab3-04-Web-Page.png)


## Lab 4
- podle zadaného [tutoriálu](https://learn.microsoft.com/en-us/azure/cosmos-db/nosql/quickstart-dotnet?tabs=azure-portal%2Cwindows%2Cpasswordless%2Csign-in-azure-cli) jsem vytvořil svou Azure Cosmos DB

![lab04-1](Lab4-AzureCosmosDB/Lab-4-01-CreateCosmosDB.png)

- přidal jsem do Visual Studia svůj cosmos endpoint a primary key, abych se odtud mohl připojit ke svému Azure Cosmos DB

![lab04-2](Lab4-AzureCosmosDB/Lab-4-02-Authentication.png)

- vytvořil jsem databázi, kontejner a přidal do něj item, pak ho nahradil a updatnul

![lab04-3](Lab4-AzureCosmosDB/Lab-4-03-SimpleDatabase.png)

- získal jsem informace o vloženém itemu z databáze

![lab04-4](Lab4-AzureCosmosDB/Lab-4-04-ItemRead.png)

- na konec jsem vykonal jednoduchý dotaz pro získání všech itemů z dané partitiony a potom dotaz pro získání itemů podle určitých podmínek

![lab04-5](Lab4-AzureCosmosDB/Lab-4-05-ItemQuery.png)


## Lab 5

- založil jsem Application Insights

![lab05-1](Lab5-ApplicationInsights/Lab5-01-Applications-Insights-created.png)

- přidal jsem telemetry

![lab05-2](Lab5-ApplicationInsights/Lab5-02-Telemetry-added.png)

- aplikace úspěšně funguje

![lab05-3](Lab5-ApplicationInsights/Lab5-03-App-Insight.png)

## Lab 6

- založil jsem KeyVault a vytovřil key a secret

![lab06-1](Lab6-AzureKeyVault/Lab6-02-create-key.png)

![lab06-2](Lab6-AzureKeyVault/Lab6-01-create-secret.png)

![lab06-3](Lab6-AzureKeyVault/Lab6-03-code-execution.png)

- aplikaci jsem přidal příslušná oprávnění

![lab06-4](Lab6-AzureKeyVault/Lab6-04-permission-settings.png)

- aplikace úspěšně funguje (bohužel jsem zapomněl udělat screenshot a v ten den mi vypršelo předplatné)

![lab06-5](Lab6-AzureKeyVault/Lab6-05-Code.png)