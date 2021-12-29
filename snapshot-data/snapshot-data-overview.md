# Snapshot Data  

## Overview  

Rich data about packages is currently stored in four data bases as detailed on this page.  

- Foundry VTT Database  
- Bazaar Database  
- Bazaar Creators Database  
- Foundry Hub Database  

Some information is updated every 5 minutes, some is updated every 24 hours.  The information about packages is stored in the manifest file, which can be extended to [Manifest+](https://foundryvtt.wiki/en/development/manifest-plus).

To create the most detailed analytics, I want to take the information from the Foundry Hub Database on a recurring schedule.  

I am intending to start by doing a variance of the 'package universe' each month so there is not need for fast-moving data.   


## Stage 1: Comparing two points in time

In the first stage, we will iterate on the content of the database extract and the transformations needed for analytics.  


<iframe allowfullscreen frameborder="0" style="width:640px; height:480px" src="https://lucid.app/documents/embeddedchart/904a5f82-7c68-4f34-83b3-9b8001244504" id="0xbFsed-CJje"></iframe>

### The snapshot extract  

The extract from the Foundry Hub Database should have these qualities:  




## Stage 2: Creating the recurring data pipeline  

In the second stage, we will automate workloads and move the process to cloud.  

## Stage 3: Opening up the dataset  

In the third stage, we will look to store the snapshot analytics in a way that the community can access. This could be a dedicated database, or a section in the existing Foundry Hub database.  
