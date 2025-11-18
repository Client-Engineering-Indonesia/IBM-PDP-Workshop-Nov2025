## 04 - Create Metadata, Data Enrichment, Profiling Data

### Perform metadata enrichment

1. Go back to your project -> click New asset button -> type "enrich" into search field -> select Enrich data assets with metadata

   <img width="1512" height="796" alt="image" src="https://github.com/user-attachments/assets/eb37f4ba-93d5-41e4-9032-ecdc11ce104b" />

2. Set Name to "Db2 Metadata Enrichment for PDP" -> click Next button
   <img width="1512" height="795" alt="image" src="https://github.com/user-attachments/assets/a442d432-1648-405d-991e-feee174748bb" />

3. Click Select data from project button
   <img width="1512" height="795" alt="image" src="https://github.com/user-attachments/assets/c6e8b02d-26e9-469b-97fd-2f02deb20c56" />

4. Click Metadata import -> import db2 -> click select -> click Next
   <img width="1512" height="795" alt="image" src="https://github.com/user-attachments/assets/72eab78c-be3b-4cfd-85f2-7cbb77266ad9" />
   
   <img width="1510" height="793" alt="image" src="https://github.com/user-attachments/assets/8a6c1b30-00c7-45da-a861-1527c1f290a5" />

5. Select Profile Data > Select Assign Terms and Classifications > Select Run Basic Quality Analysis -> Click Next
   <img width="1510" height="795" alt="image" src="https://github.com/user-attachments/assets/25e258d9-bf09-4dbe-a37b-74f5086ef62b" />

6. Select Schedule, for this workshop click Run after job scheduler -> click Next
   <img width="1512" height="795" alt="image" src="https://github.com/user-attachments/assets/6de2925e-066b-4914-a76d-019d9f6096fa" />

7. Review the process -> click Create
   <img width="1512" height="794" alt="image" src="https://github.com/user-attachments/assets/f3ff00e3-57df-4bbc-97f4-193023cb58fd" />

8. Review the enrichment results
   <img width="1512" height="795" alt="image" src="https://github.com/user-attachments/assets/b0fc4504-dca2-44a8-b80e-9e6f087d53f3" />



### Enrichment results
1. 






4. Click Next button

<img width="1624" height="880" alt="image" src="https://github.com/user-attachments/assets/9d47866e-517b-407e-9bb7-e6f2781340a2" />

5. For Enrichment objective, select Profile data, Assign terms and classifications, and Run basis quality analysis

<img width="1311" height="258" alt="image" src="https://github.com/user-attachments/assets/8693519e-cebb-4672-abbd-072487ecb5b5" />

6. For Categories select Personal Data Protection

<img width="1317" height="169" alt="image" src="https://github.com/user-attachments/assets/991a522f-4cdb-442d-bbab-2e598e1b9c46" />

7. For Sampling select Basic then click Next button

<img width="1358" height="392" alt="image" src="https://github.com/user-attachments/assets/a90786e9-f2aa-4d3e-ae24-a6ba423f575f" />

8. Leave the settings as default -> click Next button

<img width="1621" height="880" alt="image" src="https://github.com/user-attachments/assets/04256f27-b44c-418d-9ff6-d5df1e542aa4" />

9. Review the activity then click Create button

<img width="1617" height="881" alt="image" src="https://github.com/user-attachments/assets/b887d102-67c7-4d1f-a24d-7f9276ee3e82" />

### Review metadata enrichment

1. After the process completed go to Columns tab -> click Filter icon <img width="27" height="26" alt="image" src="https://github.com/user-attachments/assets/35a3576a-8345-4e58-ae81-2cee648f42ca" /> -> expand Classifications section -> select personal data -> click Apply button -> you will find columns that have been identified as Personal Data

<img width="1399" height="778" alt="image" src="https://github.com/user-attachments/assets/e54195d9-7e47-43a1-b819-c2aba4be95c4" />

2. Hover your mouse to GENDER column -> click 3 dots icon <img width="31" height="30" alt="image" src="https://github.com/user-attachments/assets/e49ca703-caa5-4c9c-bed0-c8c73dd889f7" /> -> select View data profile -> you will see the distribution of gender in the data

<img width="1593" height="915" alt="image" src="https://github.com/user-attachments/assets/e088f646-b154-41f7-9908-53deed2905ef" />

3. Select all columns -> click More -> select Mark as reviewed

<img width="1401" height="884" alt="image" src="https://github.com/user-attachments/assets/be1907a7-d347-427b-93ce-55ad957da178" />

4. Go to Assets tab -> hover your mouse to CUSTOMER table -> click 3 dots icon <img width="31" height="30" alt="image" src="https://github.com/user-attachments/assets/e49ca703-caa5-4c9c-bed0-c8c73dd889f7" /> -> select View data quality -> you will find result of data quality assessment for CUSTOMER table

<img width="1591" height="905" alt="image" src="https://github.com/user-attachments/assets/6a6a4ed4-90d1-4dee-9484-6ebe27bdc46e" />

5. From the analysis from step 2, we know that all personal data are identified in CUSTOMER and CUSTOMER_OFFERS. Based on this information you should assign those tables as "Personal Data" classifications -> click View Mode link inline with CUSTOMER table -> click Governance tab in right section -> click Assign classifications icon <img width="30" height="26" alt="image" src="https://github.com/user-attachments/assets/52923f18-b2e6-4fca-8fa8-daf17ad53b8b" /> -> select Personal Data -> redo the activity to CUSTOMER_OFFERS table -> you can see the image below for reference:

<img width="1727" height="633" alt="image" src="https://github.com/user-attachments/assets/56616992-0a5e-4578-9528-2cb380565e52" />

6. Select all tables -> click More -> select Mark as reviewed

<img width="1396" height="574" alt="image" src="https://github.com/user-attachments/assets/9245d2a2-c1d3-40bd-a722-ba9c46968c4a" />
