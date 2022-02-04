# solution-pack-connectors-updates-notifier

## Overview
Playbook to notify SOC admins about connectors which have to be updated

## Prerequisites:
- Internet connection (to retrieve the latest connectors data)

## Import:
- Download the solution pack zip file
- Browse to FortiSOAR **Import Wizard** and import the pack. This will create a new playbook collection 
- Make sure the global variables : 
  - Server_fqhn: (host or IP address of FortiSOAR)
  - Default_Email: The recipient email address receiving the report
- Schedule the playbook to be sent daily or weekly
