## 03 - Create Metadata, Data Enrichment, Profiling Data

### Adjust metadata enrichment settings

1. Go to project that you have created in lab 0 -> click Manage tab -> click Metadata enrichment
   <img width="1728" height="952" alt="image" src="https://github.com/user-attachments/assets/193c6d01-b966-4f0b-81b1-2c132f9dbf6a" />

2. Adjust the settings as below:
   
   ```
   Categories: PDP Category
   Assignment threshold (%): 75
   Suggestion threshold (%): 25
   Assignment threshold (%): 90
   Suggestion threshold (%): 85
   Term assignment methods to use (select at least one): select Machine Learning and Name Matching
   Assign classifications automatically: select "When a related term is automatically assigned"
   ```

4. Ensure your view is same as below:

   <img width="1460" height="761" alt="image" src="https://github.com/user-attachments/assets/e7f9c7c3-992d-41eb-8787-ff4aff2d144c" />

   <img width="1449" height="681" alt="image" src="https://github.com/user-attachments/assets/d33900ee-aecc-4b3e-997d-f08d698279c6" />

### Perform metadata import

1. Go to Assets tab -> click New asset button -> type "import" into search field -> select Import metadata for data assets

   <img width="1512" height="795" alt="image" src="https://github.com/user-attachments/assets/46ffd128-2125-44f0-86d1-bf736ae4ae80" />

2. Click Discover
   <img width="1512" height="795" alt="image" src="https://github.com/user-attachments/assets/177e7838-c1f0-4b66-a324-66c356d24b6c" />
   
3. Set Name to "import db2" -> click Next button
   <img width="1512" height="796" alt="image" src="https://github.com/user-attachments/assets/846fffb4-61af-4215-aaff-9f2a50fb63fa" />

4. Select "This Project" as target -> click Next button
   <img width="1512" height="795" alt="image" src="https://github.com/user-attachments/assets/a7fca619-f891-4ade-8186-506c94f8744d" />

5. Select Connection that already created before
   <img width="1512" height="795" alt="image" src="https://github.com/user-attachments/assets/1a990ff0-8c6c-431a-9ea3-41ba7ece7a4a" />
   <img width="1512" height="796" alt="image" src="https://github.com/user-attachments/assets/c05466b5-0754-4811-929a-e48d6d8e5923" />

6. Preview the Connection -> click Next button
   <img width="1512" height="794" alt="image" src="https://github.com/user-attachments/assets/82017771-3257-49f1-bdd1-1feb3dd73372" />

7. We can also schedule the job, but for this workshop choose Run Job After Creation -> Next
   <img width="1512" height="794" alt="image" src="https://github.com/user-attachments/assets/50a7d147-22fd-4d36-afad-f65738025b7f" />

8. Review the metadata import
   <img width="1512" height="796" alt="image" src="https://github.com/user-attachments/assets/47729f27-6b01-4d53-9208-b01c21f6a21a" />
   <img width="1512" height="792" alt="image" src="https://github.com/user-attachments/assets/053f64c4-c3a9-44de-8e01-c28693a05764" />

9. Wait until the process completed as below:
   <img width="1512" height="794" alt="image" src="https://github.com/user-attachments/assets/a56eabd1-5292-4dc0-a162-2bc5598dfa32" />

### Perform metadata enrichment

1. Go back to your project -> click New asset button -> type "enrich" into search field -> select Enrich data assets with metadata

<img width="1592" height="552" alt="image" src="https://github.com/user-attachments/assets/aaa4993e-00c5-4282-a1da-382d99b2c4a7" />

2. Set Name to "Db2 Metadata Enrichment for PDP" -> click Next button

<img width="1627" height="882" alt="image" src="https://github.com/user-attachments/assets/b0d30ac9-cf99-4ea7-9aa1-809798d33103" />

3. Click Select data from project button <img width="243" height="47" alt="image" src="https://github.com/user-attachments/assets/24f23136-934d-469f-aa48-d099c76b9d56" /> -> Select Metadata import -> select db2 metadata import -> select all available metadata (CUSTOMER, CUSTOMER_ACTIVITY, CUSTOMER_OFFERS)

<img width="1547" height="841" alt="image" src="https://github.com/user-attachments/assets/20d77818-1fd9-44db-8626-3ecf572adf42" />

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




