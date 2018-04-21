# Requirements
## Bot Framework (https://github.com/underwms/BotApplication)

* Bot Framework Emulator: https://github.com/Microsoft/BotFramework-Emulator/releases/download/v3.5.35/botframework-emulator-Setup-3.5.35.exe
* Visual Studio: https://www.visualstudio.com/thank-you-downloading-visual-studio/?sku=Community&rel=15 
* Visual Studio Project Types:  The following directions can be in the Prerequisites section in the follow document https://docs.microsoft.com/en-us/bot-framework/dotnet/bot-builder-dotnet-quickstart
* Bot Application Project Templates: http://aka.ms/bf-bc-vstemplate
* Bot Controllers: http://aka.ms/bf-bc-vscontrollertemplate
* Bot Dialogs: http://aka.ms/bf-bc-vsdialogtemplate
* Install the project template by copying Bot Application.zip to your Visual Studio 3017 project templates directory.  
  - Install the item templates by copying Bot Controller.zip and Bot Dialog.zip to your Visual Studio 2017 item templates directory.
The Visual Studio 2017 project templates directory is typically located at
%USERPROFILE%\Documents\Visual Studio 2017\Templates\ProjectTemplates\Visual C#\ 
and the item templates directory is at 
%USERPROFILE%\Documents\Visual Studio 2017\Templates\ItemTemplates\Visual C#\

## Data Lake (https://github.com/akhilmahajan96/Usql/tree/master/Azure%20BootCamp)

No additional requirements

## Service Fabric (https://github.com/jamessmith119/azurebootcamplabs)
* Visual Studio
* Service Fabric SDK
  - Instructions for VS 2017 and VS 2015 can be found here - https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-get-started
* Powershell
  - Execution policy may need to be updated via Set-ExecutionPolicy
o	See https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-get-started#enable-powershell-script-execution for more details

## Serverless functions and logic apps

* VS Code https://code.visualstudio.com/
* VS Code Ext: Azure Functions
* .NET Core 2 https://www.microsoft.com/net/core
* Node/npm https://www.npmjs.com/get-npm 
* .NET Core Tools
  - MacOS (sudo npm install -g azure-functions-core-tools@core --unsafe-perm true)
  - Windows (npm install -g azure-functions-core-tools@core)
