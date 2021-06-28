# tshirts-api

Exersice resolution:
Item 1:
  - API designed using Mulesoft's design center
  - Inventory local MySQL Database Structure :
             productCode: string
             size: string
             description: string             
             count: integer
  - API Methods:
              GET: Lists all elements in inventory
              POST: Adds a specific item to inventory
              GET/{element productCode}: Gets specific item from inventory
              PUT/{element productCode}: Updates a specific item from inventory
              DELETE/{element productCode}: Removes specific item from inventory
  

  - Ansible script: ansible-playbook.yml
      
      -To execute ansible playbook, run the following command with the derired parameters in your cmd:
       ansible-playbook ansible-playbook.yml -e myServer="{{yourServerName}}" -e myToken="{{yourToken}}"
  
  - Jenkins Script: jankinsfile

Item 2:
  - Presentation found in Tshirts-API Presentation.pptx.

Optional items:  
    1- Added the "Client-ID Enforcement Policy" security policy.
