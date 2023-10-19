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





# Create Detection RUle For Cybersecurity Threats




# Create User Account in Azure For SIEM Investigation






# Infiltrating User Account To Generate Incidents In SIEM




# Exploring Created Cybersecurity Threats In SiEM




# How to Remediate Cybersecurity Incident
