# Microsoft Sentinel Deployment
- Click on link to deploy Sentinel in Microsoft Azure
 https://github.com/Azure/Azure-Sentinel/tree/master/Tools/Sentinel-All-In-One








# Create SIEM in Azure

- Configuration > Choose the location closest to you > Daily ingestion limit 10
  
  ![image](https://github.com/ali0999109/Microsoft/assets/145396907/863e986a-02d4-44fe-83b6-c84c977924e3)
  ---
- Settings > Enable sentinel health diagnostics>
- Content hub > Select all for all the 3 categories
- Data connectors > Select All
- Analytics Rules > Check box > Select All > Review and Create






# Exploring Deployed Cybersecurity Artifacts
- Go to resource group on Azure click on it > click on the resource group artifact it should have the same name as your resource group > scroll down and click diagnostic settings on the 
  left > click add diagnostic setting > Select allLogs, AllMetrics, and send to  log analytics workspace. Select Save on top left
  
   ![image](https://github.com/ali0999109/Microsoft/assets/145396907/5e91f673-6bde-4ba9-a7ab-2e6b045d29fa)
  ----
   ![image](https://github.com/ali0999109/Microsoft/assets/145396907/b4c41f36-92e7-4620-a4f9-de8b386c5cd4)
  --

  




# Exploring Created Cloud SIEM Solution
 - Search for Microsoft sentinel and select your resource deployment. You should land here
   ![image](https://github.com/ali0999109/Microsoft/assets/145396907/b4ca2a61-1944-442d-a171-1e72b8fb0ce2)
 - Click on logs you can search for your data using KQL > Log Management > Azure Activity this tracks who took action in your portal and other properties
   
   ![image](https://github.com/ali0999109/Microsoft/assets/145396907/133c9c1d-dce6-4a5b-9206-7ae16d012c45)
   ----
   - Move to data connectors you will see all the data sources connected to Microsoft sentinel by clicking on them you can see the types of data being collected, the number of logs 
     received, and the tables that are populated
   
     ![image](https://github.com/ali0999109/Microsoft/assets/145396907/8126cff7-c687-454d-be33-93b428d6949c)
     ----

   - Move to the analytics tab to see all the analytics rules that were deployed and enabled automatically to detect vulnerabilities and threats
   - 
     ![image](https://github.com/ali0999109/Microsoft/assets/145396907/52b069b2-87f5-45ed-8f37-c034ff1ff2a6)
       --------
     

     





# Enable Artifact Intelligence in SIEM
- Go to the settings section all the way on bottom left > settings > Select the Set UEBA button > Turn on > select Azure active directory > apply > select all and apply >

  ![image](https://github.com/ali0999109/Microsoft/assets/145396907/3760ac9f-0d43-4c7d-8d79-0b7e57c70aa8)
  ------------
  ![image](https://github.com/ali0999109/Microsoft/assets/145396907/5fd4b515-098d-4f7c-a515-9b1b079f6a69)
  ----

  - Go to playbook permissions to configure sentinel to use automation playbooks > configure permissions > select the RG where your sentinel is deployed
  - 
    ![image](https://github.com/ali0999109/Microsoft/assets/145396907/c48bbe09-5f1d-4b3f-8529-484efc8f547e)
    ---






# Create a Watchlist to Detect Cybersecurity Threats
- Scroll down to watchlist on the left > add new > name Tor-Ip-Addresses > alias use the same as name > source local type > Download this file   [Tor+Exit+Nodes (1).csv](https://github.com/ali0999109/Microsoft/files/13048328/Tor%2BExit%2BNodes.1.csv) drag and drop it inside > searchkey ipAddress  > review and create
 
  
  ![image](https://github.com/ali0999109/Microsoft/assets/145396907/1874efdd-50f3-464a-b54b-623952d5628e)
  ----------



   - Select the watchlist you created > view in logs
    
    ![image](https://github.com/ali0999109/Microsoft/assets/145396907/da8028e2-6111-41d6-bd1f-3bf125ae0534)
    ---

    - Kql query syntax
      
      ![image](https://github.com/ali0999109/Microsoft/assets/145396907/b0817c8d-79a4-4c26-a8f3-b55d236683bf)




# Create Detection Rule For Cybersecurity Threats
- Scroll down and select the anayltics tab > create > scheduled query rule > name* succesful sign in's from tor-network > tactics and techinques uncheck everything first, click on 
 inital access > external remote services > Next go to severity change to high
- Go to set rule logic type in the following KQL query
  ![image](https://github.com/ali0999109/Microsoft/assets/145396907/07232271-ee88-4889-8c3d-e32cf8d106a0)
  ---
  - Next select entity mapping > entity type > account > sid > userid > click on add identifier > Display name > UserDisplayName Add another entity type > IP > address > ip address
    
    ![image](https://github.com/ali0999109/Microsoft/assets/145396907/c8c0863a-cf7b-436b-b1c6-f8c5b2dd3ea8)
    -----

  - Next select custom details type in the following
    
    ![image](https://github.com/ali0999109/Microsoft/assets/145396907/1f4bfc33-74ee-4c6d-98d0-14769116ba4a)
    --

  - Next go to alert details > alert name successful sign-ins from tor network > Alert property confidence score and Risk state

  - Next select query scheduling change to every 5 minutes
    ![image](https://github.com/ali0999109/Microsoft/assets/145396907/cfc615c8-4e6b-464b-85e9-2131e6170f2f)

  - Next incident settings > alert grouping enabled > skip automated response > review and create
    
    ![image](https://github.com/ali0999109/Microsoft/assets/145396907/d2dd2460-3525-478f-9319-390da855ad86)
    -----

    - The anayltics rule should be created
    ![image](https://github.com/ali0999109/Microsoft/assets/145396907/62ce7374-0416-4ee8-983c-fc136f43af6b)


  
 
 

 



    

 







# Create User Account in Azure For SIEM Investigation






# Infiltrating User Account To Generate Incidents In SIEM




# Exploring Created Cybersecurity Threats In SiEM




# How to Remediate Cybersecurity Incident
