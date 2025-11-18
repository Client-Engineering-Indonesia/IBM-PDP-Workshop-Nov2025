## 03 - Import Metadata 

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

10. Go back to Projects, this is asset that we currently done: 
    <img width="1512" height="796" alt="image" src="https://github.com/user-attachments/assets/459d6ab5-80aa-43a6-991e-6f9fd8432c8f" />
