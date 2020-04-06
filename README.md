# Trailhead Module: Salesforce Connect
[Module Home](https://trailhead.salesforce.com/en/content/learn/modules/lightning_connect?trail_id=force_com_dev_intermediate)

Access, display, and integrate data from an external data source in real time.

1. [Introduction to Salesforce Connect](https://trailhead.salesforce.com/en/content/learn/modules/lightning_connect/lightning_connect_introduction?trail_id=force_com_dev_intermediate)
1. [Set up Salesforce Connect](https://trailhead.salesforce.com/en/content/learn/modules/lightning_connect/lightning_connect_setup?trail_id=force_com_dev_intermediate)
1. [Integrate External Data](https://trailhead.salesforce.com/en/content/learn/modules/lightning_connect/lightning_connect_integrate?trail_id=force_com_dev_intermediate)

## Notes:
- to get metadata from org
  - `sfdx force:source:retrieve --metadata CustomObject:phone_plan__x,CustomField:Cost__c,Data_Limit__c,Id__c,Name__c,Text_Limit__c`
  - `sfdx force:source:retrieve --metadata CustomObject:phone__x,CustomField:Brand__c,ID__c,PhoneNumber__c,UUID__c`