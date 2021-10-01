// Alexis Lopez

// link to deployed app: https://gray-sky-0c586db10.azurestaticapps.net/

// https://devblogs.microsoft.com/aspnet/azure-static-web-apps-with-blazor/

// https://docs.microsoft.com/en-us/aspnet/core/tutorials/build-a-blazor-app?view=aspnetcore-5.0&pivots=server

This is an application website that I developed using Azure and Blazor with the tutorials listed above. On the website you have several pages that all have their own functionality. Most of the pages are for data processing but there is even a ToDo list page that helps you make a todo list. 

## Template Structure

- **Client**: The Blazor WebAssembly sample application
- **API**: A C# Azure Functions API, which the Blazor application will call
- **Shared**: A C# class library with a shared data model between the Blazor and Functions application

## Deploy to Azure Static Web Apps

This application can be deployed to [Azure Static Web Apps](https://docs.microsoft.com/azure/static-web-apps), to learn how, check out [our quickstart guide](https://aka.ms/blazor-swa/quickstart).

![blazor 1](https://user-images.githubusercontent.com/74120068/135549630-01b665db-0eae-4223-9d3f-c99151276d04.png)

![blazor2](https://user-images.githubusercontent.com/74120068/135549637-cf0bb7df-e475-4ea8-839d-a6b582905d73.png)
