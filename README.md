# AZ900-Azure-Health-Services
Non SLA app to check health status on services

**Azure service health**

  1) Search for "Service health" in the search bar in portal.azure.com

  ![image](https://user-images.githubusercontent.com/105960409/172705125-c5822a11-629b-43bc-bf57-442a3f477bfb.png)

  2) This will take you to the service health landing page

  ![image](https://user-images.githubusercontent.com/105960409/172705322-72ec1b14-e924-47b1-a867-a0986be1979d.png)

    1 - Here you can choose which subscription to check services on
    2 - Here you can filter the results by region
    3 - Here you can filter the results by service
    4 - Here you can choose a previously saved view(previously saved search)
    5 - Here you can add service alerts

  **Create an Azure service health alert**
 
  1) Click on +Add Service Health Alert(Number 5 in previous screenshot)
  
  2) In the next window choose the parameters required for the alert:

  ![image](https://user-images.githubusercontent.com/105960409/172707297-2e637794-9778-4bb2-bc95-5c4175b1b036.png)

  3) Scroll down and select the actions that are needed by clicking in "select action groups"

  ![image](https://user-images.githubusercontent.com/105960409/172707908-c9965de4-3507-40f5-8d49-e727bd3e52d1.png)

  4) A pop-up window will appear, you can then select pre-existing actions or create new ones by clicking on +Create action groups

  ![image](https://user-images.githubusercontent.com/105960409/172708116-c733f6bc-375b-4ede-9205-d9a49563543e.png)

  5) In the "basics" tab you will choose your subscription, resource group and name of the notification

  ![image](https://user-images.githubusercontent.com/105960409/172708357-49bd30e6-d809-4888-9590-c4d712aec085.png)

  6) In the "notifications" tab you will set up the way the notifications will be sent and introduce the contact info(Mail, Phone#, etc):

  ![image](https://user-images.githubusercontent.com/105960409/172709001-42b612ba-d0c9-4830-8c15-2b23330db336.png)

  7) Fill out the contact info in the pop-up and click OK in the bottom of the pop-up

  ![image](https://user-images.githubusercontent.com/105960409/172709217-6347d479-a49e-4a25-bd98-1a046faff057.png)

  8) Actions and Tags are optional, fill them out as needed

  ![image](https://user-images.githubusercontent.com/105960409/172709409-402bd2a7-3945-414d-98cc-1f4c895b9b51.png)

  9) Click on review and create

  ![image](https://user-images.githubusercontent.com/105960409/172709471-3203deda-4f9e-409b-8964-acd91afe8bf6.png)

  10) Alert example:

  ![image](https://user-images.githubusercontent.com/105960409/172709907-a9681e70-f1cb-4aea-8797-5cda2769c6b0.png)



  
