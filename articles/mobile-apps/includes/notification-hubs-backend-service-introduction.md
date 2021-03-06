---
 author: mikeparker104
 ms.author: miparker
 ms.date: 07/27/2020
 ms.service: mobile-services
 ms.topic: include
---

An [ASP.NET Core Web API](https://dotnet.microsoft.com/apps/aspnet/apis) backend is used to handle [device registration](https://docs.microsoft.com/azure/notification-hubs/notification-hubs-push-notification-registration-management#what-is-device-registration) for the client using the latest and best [Installation](https://docs.microsoft.com/azure/notification-hubs/notification-hubs-push-notification-registration-management#installations) approach. The service will also send push notifications in a cross-platform manner. 

These operations are handled using the [Notification Hubs SDK for backend operations](https://www.nuget.org/packages/Microsoft.Azure.NotificationHubs/). Further detail on the overall approach is provided in the [Registering from your app backend](https://docs.microsoft.com/azure/notification-hubs/notification-hubs-push-notification-registration-management#registration-management-from-a-backend) documentation.
