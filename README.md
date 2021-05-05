# DevOps Resume Deploy
This project idea comes from this site here: https://cloudresumechallenge.dev/instructions/  , however, I implemented the solutions using Azure services instead. I built a serverless static resume website with a visitor counter, serverless service to store the visitor’s count (Azure Cosmos DB), a serverless service to retrieve and update the visitor’s count from our store(Azure Functions), a serverless service to host our static resume website (Azure Storage) and an additional service to cache and make static website load faster (Azure CDN).

Goal:
- Host resume on Azure storage and use Azure CDN for caching and custom domain change, Cosmo DB to store visitor's count and Function App to retrieve the count. 

Live demo:
https://brianlam.azureedge.net/

## Architecture:
<img src="https://user-images.githubusercontent.com/5561950/117124241-15dce680-ad66-11eb-8347-316d9f700ced.png" />

## Azure services used here:
<img src="https://user-images.githubusercontent.com/5561950/117123890-9c44f880-ad65-11eb-8cda-cc58eb98626d.png" />

## Keeping track of visitor count test here:
<img src="https://user-images.githubusercontent.com/5561950/117124067-d9a98600-ad65-11eb-8d48-58df12d3916f.png" />



