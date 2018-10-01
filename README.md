Welcome to the DeviceExplorer-Azure-IoT-Connectivity-Tester wiki!
# DeviceExplorer-Azure-IoT-Connectivity-Tester
This is the extended version of Device Explorer Twin utility.  

Please refer below link for all the basic guide line for this utility.(Note : All source codes are copied from this link only for this version)

https://github.com/Azure/azure-iot-sdk-csharp/tree/master/tools/DeviceExplorer

Default Device Explorer : 

![capture](https://user-images.githubusercontent.com/14991805/46290026-4a81d380-c5a8-11e8-8b8f-390b6287556f.PNG)

Extended/Current Device Explorer:
One new tab added in existing Device explorer utility with the name of "**Send Device to Cloud Message**".

![capture1](https://user-images.githubusercontent.com/14991805/46290296-10fd9800-c5a9-11e8-87ca-311c96a811ab.PNG)


I don't know why this functionality is not there in existing utility as this is one of the major feature that every developer wants to test once they done with the basic set up of Azure IoT hub on Microsoft azure portal.

Detail view of this new tab : 

![capture3](https://user-images.githubusercontent.com/14991805/46290399-6043c880-c5a9-11e8-9bbb-38892c8d9846.PNG)


 

**How to use new Tab** : 

So this tab basically needs few information in order to send device telemetry to cloud and at the same time you can use Data tab to check whether message received by cloud or not.

Below are the some Input fields that needs to be filled before sending data to cloud.

1. **IoTHubHost Name** : This can be easily get from the portal under overview menu.
1. **SAS Token** : Device explorer itself generate SAS token on Configuration Tab. (Note : Both SAS like device specific or for all devices can be used here).
1. **Device Name**: Specific device name you can get this under Management tab.
1. **Payload** : Data/Telemetry that you want to send on cloud.
1. Click on **Send button** to send data to cloud if message sent successfully you will see confirmation message on Send Status section.
