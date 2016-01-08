Apache Cordova plugin for Azure Mobile Apps
=============================

With Microsoft Azure Mobile Apps you can add a scalable backend to your connected client applications in minutes.

To learn more, visit our [Developer Center](http://azure.microsoft.com/en-us/services/app-service/mobile/).

## Getting Started

If you are new to Mobile Apps, you can get started by following our tutorials for connecting your Mobile Apps cloud backend to [Cordova apps](http://azure.microsoft.com/en-us/documentation/articles/mobile-services-javascript-backend-phonegap-get-started/).

### Sample usage ###
The following code creates a new client object to access the *todolist* mobile apps backend and create a new proxy object for the *TodoItem* table.

    var mobileAppsClient = new WindowsAzure.MobileServiceClient(
            "https://todolist.azurewebsites.net"
        );

    var todoTable = mobileAppsClient.getTable('TodoItem');

### Quickstart ###
Refer [README.md](https://github.com/Azure/azure-mobile-services-quickstarts/blob/MobileApp/README.md) for detailed quickstart instructions.

## Need Help?

Be sure to check out the Mobile Services [Developer Forum](http://social.msdn.microsoft.com/Forums/en-US/azuremobile/) if you are having trouble. The Azure Mobile Apps product team actively monitors the forum and will be more than happy to assist you.

## Contribute Code or Provide Feedback

If you would like to become an active contributor to this project please follow the instructions provided in [Microsoft Azure Projects Contribution Guidelines](http://azure.github.com/guidelines.html).

If you encounter any bugs with the library please file an issue in the [Issues](https://github.com/Azure/azure-mobile-apps-js-client/issues) section of the project.

## Learn More
[Microsoft Azure Mobile Apps Developer Center](http://azure.microsoft.com/en-us/services/app-service/mobile/)
