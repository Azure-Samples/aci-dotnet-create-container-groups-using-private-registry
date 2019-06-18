---
services: Container-Instance
platforms: dotnet
author: yaohaizh
---

# Create Container Group using images from a private registry using C# #

          Azure Container Instance sample for managing container groups with private image repositories.
           - Create an Azure Container Registry to be used for holding the Docker images
           - If a local Docker engine cannot be found, create a Linux virtual machine that will host a Docker engine
               to be used for this sample
           - Use Docker DotNet to create a Docker client that will push an image to Azure Container Registry
           - Create a new container group with one container instance from the image that was pushed in the registry


## Running this Sample ##

To run this sample:

Set the environment variable `AZURE_AUTH_LOCATION` with the full path for an auth file. See [how to create an auth file](https://github.com/Azure/azure-libraries-for-net/blob/master/AUTH.md).

    git clone https://github.com/Azure-Samples/aci-dotnet-create-container-groups-using-private-registry.git

    cd aci-dotnet-create-container-groups-using-private-registry

    dotnet restore

    dotnet run

## More information ##

[Azure Management Libraries for C#](https://github.com/Azure/azure-sdk-for-net/tree/Fluent)
[Azure .Net Developer Center](https://azure.microsoft.com/en-us/develop/net/)
If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212)

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.