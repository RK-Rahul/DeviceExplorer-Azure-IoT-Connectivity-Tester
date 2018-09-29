# DeviceExplorer-Azure-IoT-Connectivity-Tester
This is the extended version of Device Explorer Twin utility.  

Please refer below link for all the basic guide line for this utility.

https://github.com/Azure/azure-iot-sdk-csharp/tree/master/tools/DeviceExplorer

One new tab added in existing Device explorer utility with the name of "**Send Device to Cloud Message**".

I don't know why this functionality is not there in existing utility as this is one of the major feature that every developer wants to test once they done with the basic set up of Azure IoT hub on Microsoft azure portal.

***

**How to use new Tab** : 

So this tab basically needs few information in order to send device telemetry to cloud and at the same time you can use Data tab to check whether message received by cloud or not.

Below are the some Input fields that needs to be filled before sending data to cloud.

1. **IoTHubHost Name** : This can be easily get from the portal under overview menu.
1. **SAS Token** : Device explorer itself generate SAS token on Configuration Tab. (Note : Both SAS like device specific or for all devices can be used here).
1. **Device Name**: Specific device name you can get this under Management tab.
1. **Payload** : Data/Telemetry that you want to send on cloud.
1. Click on **Send button** to send data to cloud if message sent successfully you will see confirmation message on Send Status section.
