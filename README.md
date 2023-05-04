# Cloud-NSWI152

- poznámky:
    - během dělání úkolů jsem použil dva různé Microsoft účty
    - u některých screenshotů jde špatně vidět text, proto se hodí je otevřít v novém okně

## Lab 1
- podle instrukcí jsem založil a publikoval jednoduchou webovou aplikaci

![lab01-1](Lab1-AppServicesDeployment/Lab1-01-VS-publish.png)

![lab01-2](Lab1-AppServicesDeployment/Lab1-02-Published-page.png)


## Lab 2

- do projektu z předchozího labu jsem přidal WebJob

![lab02-1](Lab2-AzureSQL/Lab-2-03-Web-Job.png)

- vytvořil jsem Azure SQL databázi

![lab02-2](Lab2-AzureSQL/Lab-2-01-Database-Created.png)

- vytvořil jsem tabulku

![lab02-3](Lab2-AzureSQL/Lab-2-02-Database-Query.png)

- aplikace s kódem ze zadání se úspěšně přeloží a běží

![lab02-3](Lab2-AzureSQL/Lab-2-04-App-Builded.png)


## Lab 3
- založil jsem Azure Storage a container

![lab03-1](Lab3-AzureBlobStorage/Lab3-01-Storage-Created.png)

![lab03-2](Lab3-AzureBlobStorage/Lab3-02-Container-Created.png)

- přidal jsem connection string do poskytnutého kódu a aplikace úspěšně funguje

![lab03-3](Lab3-AzureBlobStorage/Lab3-03-Successful-build.png)

![lab03-4](Lab3-AzureBlobStorage/Lab3-04-Web-Page.png)


## Lab 4
- podle zadaného [tutoriálu](https://learn.microsoft.com/en-us/azure/cosmos-db/nosql/quickstart-dotnet?tabs=azure-portal%2Cwindows%2Cpasswordless%2Csign-in-azure-cli) jsem založil Azure Cosmos DB

![lab04-1](Lab4-AzureCosmosDB/Lab-4-01-CreateCosmosDB.png)

- přidal jsem do Visual Studia svůj cosmos endpoint a primary key, abych se odtud mohl připojit ke svému Azure Cosmos DB

![lab04-2](Lab4-AzureCosmosDB/Lab-4-02-Authentication.png)

- vytvořil jsem databázi, kontejner a přidal do něj item, pak tento item nahradil a updatnul

![lab04-3](Lab4-AzureCosmosDB/Lab-4-03-SimpleDatabase.png)

- získal jsem informace o vloženém itemu z databáze

![lab04-4](Lab4-AzureCosmosDB/Lab-4-04-ItemRead.png)

- na konec jsem vykonal jednoduchý dotaz pro získání všech itemů z dané partitiony a potom dotaz pro získání itemů podle určitých podmínek

![lab04-5](Lab4-AzureCosmosDB/Lab-4-05-ItemQuery.png)


## Lab 5

- založil jsem Application Insights

![lab05-1](Lab5-ApplicationInsights/Lab5-01-Applications-Insights-created.png)

- mimo jiné jsem přidal telemetry

![lab05-2](Lab5-ApplicationInsights/Lab5-02-Telemetry-added.png)

- v Azure portalu vidím informace o své webové aplikaci

![lab05-3](Lab5-ApplicationInsights/Lab5-03-App-Insight.png)

## Lab 6

- založil jsem KeyVault a vytvořil key a secret s hodnotou "hello"

![lab06-1](Lab6-AzureKeyVault/Lab6-02-create-key.png)

![lab06-2](Lab6-AzureKeyVault/Lab6-01-create-secret.png)

- v aplikaci jsem získal očekávaný secret z Azure portalu

![lab06-3](Lab6-AzureKeyVault/Lab6-03-code-execution.png)

- aplikaci jsem přidal příslušná oprávnění

![lab06-4](Lab6-AzureKeyVault/Lab6-04-permission-settings.png)

- aplikace s poskytnutým kódem se úspěšně přeloží a běží

![lab06-5](Lab6-AzureKeyVault/Lab6-05-AppBuilded.png)


## Lab 7a

- založil jsem Event Hub

![lab07a-1](Lab7-Serverless/Lab7a-01-EventHubCreated.png)

- zprovoznil jsem posílání zpráv mezi poskytnutými aplikacemi EventHubPublisher a EventHubConsumer
- v Azure portalu u Event Hubu vidím posílané události

![lab07a-2](Lab7-Serverless/Lab7a-02-EventHubMessage.png)


## Lab 7b

- založil jsem Azure function

![lab07b-1](Lab7-Serverless/Lab7b-01-FunctionCreated.png)

- lokálně jsem spustil funkci s poskytnutým kódem (při neplatném požadavku kód vrátí instanci třídy BadRequestObjectResult)

![lab07b-2](Lab7-Serverless/Lab7b-02-FunctionLocal.png)

- funkci jsem publikoval

![lab07b-3](Lab7-Serverless/Lab7b-03-FunctionPublished.png)

- nyní je funkce veřejně přístupná

![lab07b-4](Lab7-Serverless/Lab7b-04-FunctionPublic.png)

- v Azure portalu vidím informace o této funkci

![lab07b-5](Lab7-Serverless/Lab7b-05-FunctionPublic2.png)


## Lab 7c

- založil jsem Logic app

![lab07c-1](Lab7-Serverless/Lab7c-01-LogicAppCreated.png)

- v Logic app jsem vytvořil požadovaný trigger

![lab07c-2](Lab7-Serverless/Lab7c-02-Workflow.png)


- použil jsem poskytnutou EventHubPublisher aplikaci pro poslání eventu do Event hubu, který aktivoval vytvořený trigger a poslal mi email

![lab07c-3](Lab7-Serverless/Lab7c-03-Email.png)


## Lab 8a

- založil jsem Computer vision

![lab08a-1](Lab8-CognitiveServices/Lab8a-01-ComputerVisionCreated.png)

- použil jsem obrázek této třídy pro otestování

![lab08a-2](Lab8-CognitiveServices/classroom.jpg)

- aplikace s poskytnutým kódem mi pro tento obrázek vrátilá následující výstup

![lab08a-3](Lab8-CognitiveServices/Lab8a-02-ComputerVisionClassroom.png)

- spustil jsem to samé v konzoli

![lab08a-4](Lab8-CognitiveServices/Lab8a-03-ComputerVisionConsole.png)


## Lab 8b

- vyzkoušel jsem Optical Character Recognition pro rozpoznání textu na obrázku

![lab08b-1](Lab8-CognitiveServices/ocr_1_image.jpg)

![lab08b-2](Lab8-CognitiveServices/Lab8b-01-OCR.png)


## Lab 8c

- založil jsem Face API

![lab08c-1](Lab8-CognitiveServices/Lab8c-01-FaceAPICreated.png)

- aplikaci s poskytnutým kódem jsem dal na vstup fotku svého obličeje

![lab08c-2](Lab8-CognitiveServices/face.png)

![lab08c-3](Lab8-CognitiveServices/Lab8c-02-Output.png)


## Lab 8d

- založil jsem Speech service

![lab08d-1](Lab8-CognitiveServices/Lab8d-01-SpeechServiceCreated.png)

- vyzkoušel jsem projekt Speech SDK [(repo)](https://github.com/Azure-Samples/cognitive-services-speech-sdk)

- nahrál jsem do něj svůj klíč ze Speech service, použil modul pro rozpoznávání řeči a pokusil se v angličtině říct "NSWI152"

![lab08d-2](Lab8-CognitiveServices/Lab8d-02-SpeechServiceTest.png)
