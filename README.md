Steps to Install and Configure

1. Download the PO_CSV_IDM_EMAIL_Dataflow.zip and extract the file somewhere easily accessible.
3. From within the extracted folder, import the dataflow into your tenant.
4. Import the IDM_AddItem_Response.zip into Object schemas.
5. Import IDM_AddItem_JSON.zip into Object schemas.
6. Import the IDM_API_SyncPurchaseOrder_1.json into scripting in IONDesk.
7. In the IDM_API_SyncPurchaseOrder_1 script, activate the script.
8. ** If Connection points are missing, please reache out to rob.thayer@nsacom.com to advise.
9. Otherwise, in the AddItemToIDM_1, upload your own service account on the connection tab.
10. In the same Connection point under the Documents tab, select AddItemToIDM in the grid and then under Output Document, you will need to change the to: email address as well as the subject and body if you wish.
   ![image](https://github.com/NSA-Computer-Exchange/TUG_2024_PO_CSV_IDM_EMAIL_Dataflow/assets/15594519/fc77f703-d8c5-47ce-b244-749f20cd8933)
11. In the IDMSendEmail_1 connection point, upload your service accout on the connection tab.
12. Save and activate the dataflow.

If you encounter any issues, feel free to reach out to rob.thayer@nsacom.com

    
