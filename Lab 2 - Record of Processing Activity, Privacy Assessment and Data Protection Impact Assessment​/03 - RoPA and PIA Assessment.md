## 03 - RoPA and PIA Assessment

In this lab, you will act as two distinct personas:

- **Data Asset Owner**: Responsible for creating, providing information, and maintaining the asset.
- **Data Privacy Officer**: Responsible for assessing the asset's privacy risk and determining whether further assessment is required.

> ⚠️ Please pay close attention to which persona you are acting as during each step.

---

### ❓ Request Additional Information

**🛡️ Persona: Data Privacy Officer**

As a Data Privacy Officer, every time the **Data Privacy Workflow** is triggered, it will appear in your task list.

1. **Access Your Tasks**  
   Return to the home page. Notice the new task assigned to you.  
   Click on **My Task** to review your current assignments.  
   ![My Task Navigation](https://github.com/Client-Engineering-Indonesia/IBM-PDP-workshop/blob/main/assets/img/op/8.png?raw=true)

2. **Open the Assigned Data Asset**  
   Locate and click on the data asset assigned to you (this should be the asset you created earlier).  
   ![Assigned Asset](https://github.com/Client-Engineering-Indonesia/IBM-PDP-workshop/blob/main/assets/img/op/9.png?raw=true)

3. **Review the Asset Page**  
   You are now viewing the **Customer Data Asset** page. Take time to review all available information.
![alt text](https://github.com/Client-Engineering-Indonesia/IBM-PDP-workshop/blob/main/assets/img/op/10.png?raw=true)
4. **Check Metadata Integration**  
   If your environment integrates **Watson Knowledge Catalog (WKC)** with **OpenPages**, you will see metadata details under the **Watson Knowledge Catalog Information** section.

5. **Request Additional Information**  
   After reviewing the asset, you determine that there is insufficient information to proceed with a privacy assessment.  
   Click the **Actions** button, then select **Request Additional Information**. Choose **Continue** to go to the next step.
   This will notify the asset owner to provide more details.
![alt text](https://github.com/Client-Engineering-Indonesia/IBM-PDP-workshop/blob/main/assets/img/op/11.png?raw=true)

---
### ✏️ Responding to Privacy Officer Request   
**🧑‍💼 Persona: Data Owner**

You’ve been asked to provide additional information for the data asset you created earlier. Notice that the stage indicator on the right-hand menu has changed to **Additional Information Required**.

1. **Update the Asset Description**  
   Edit the asset’s description to provide more context about the dataset.

2. **Add Integration Information**  
   In the **Integration Information** section, include a link to your data table from the Lab 1 environment.  
   Add relevant metadata, for example:  
   ```Personal Data classification on PDP catalog. Data quality score 99.2%```

3. **Set Criticality and Confidentiality**  
   Since this asset contains customer personal data, update both fields to:  
   ```High```

4. **Add Tags (Optional)**  
   Include relevant tags to improve asset discoverability.  
   ![Integration Info Update](https://github.com/Client-Engineering-Indonesia/IBM-PDP-workshop/blob/main/assets/img/op/12.png?raw=true)

5. **Save Your Changes**  
   Click **Save** on the right-hand side to apply updates.  
   ![Save Button](https://github.com/Client-Engineering-Indonesia/IBM-PDP-workshop/blob/main/assets/img/op/13.png?raw=true)

6. **Navigate Back to the Asset Page**  
   Use the hamburger menu to go to:  
   `IT Governance → Assets`  
   Locate your data asset and open its page.

7. **Complete Privacy Information**  
   Scroll down to the **Privacy Information** section.  
   Answer all questions related to the privacy characteristics of the data.  
   Once completed, a sensitivity score will be generated to assist the Data Privacy Officer in their assessment.  
   ![Privacy Info Section](https://github.com/Client-Engineering-Indonesia/IBM-PDP-workshop/blob/main/assets/img/op/14.png?raw=true)

8. **Fill in RoPA (Record of Processing Activities)**  
   In compliance with GDPR or PDP Law, complete the **RoPA** section with the following details:
   - **Department/Function**: `Finance`
   - **Type of Individuals**: `Customer`
   - **Retention Period**: `< 1 Year`
   - **Processing Location**: `Indonesia`
   - **Purpose of Processing**: `Loan Approval`
   - **Type of Personal Information**: `Name, Address`
   - **Source of Personal Data**: `Individu`
   - **Type of Records**: `Electronic`
   - **Legal Basis for Processing Data**: `Consent`  
   ![RoPA Section](https://github.com/Client-Engineering-Indonesia/IBM-PDP-workshop/blob/main/assets/img/op/15.png?raw=true)

9. **Submit to Data Privacy Officer**  
   Click the **Save** button in the top-right corner to finalize your updates and transfer the assignment back to the Data Privacy Officer.

---
## 🔍 Review Data Asset for Privacy Assessment  
**🛡️ Persona: Data Privacy Officer**

The Data Owner has completed all required fields. Now it's your responsibility to review the asset and determine whether further assessment is needed or if it can be approved and forwarded to the Chief Risk Officer.

1. **Review the Customer Data Asset Page**  
   Carefully examine the asset details:
   - Assess the importance of the data
   - Evaluate its business impact
   - Determine whether it qualifies as high-risk data

2. **Evaluate the PPIA-TS Score**  
   The **Pre-Protection Impact Assessment (PPIA-TS)** score helps determine whether a full Privacy Impact Assessment is required.  
   In this example, the data is deemed critical, so we will proceed with further assessment.  
   Set the **PIA Status** under the **Privacy Information** section to:  
   ```Needed```  
   ![PIA Status Update](https://github.com/Client-Engineering-Indonesia/IBM-PDP-workshop/blob/main/assets/img/op/16.png?raw=true)

3. **Initiate a Questionnaire Assessment**  
   Scroll to the **Assessment, Issues and Mappings** section.  
   Click on **New add-hoc question questionnaire assessment**.  
   ![Add Questionnaire](https://github.com/Client-Engineering-Indonesia/IBM-PDP-workshop/blob/main/assets/img/op/17.png?raw=true)

4. **Fill Out the Questionnaire Assessment Form**  
   On the **New Questionnaire Assessment** page, enter the following details:
   - **Description**: `Questionnaire Assessment for customer data`
   - **Lifecycle Due Date**: `9/30/2025`
   - **Assignee**: `<<your username>>`
   - **Questionnaire Templates**:  
     - `GDPR - DPIA Requirement Identification`  
     - `GDPR - Records of processing activities - Article 30`  
   ![Questionnaire Form](https://github.com/Client-Engineering-Indonesia/IBM-PDP-workshop/blob/main/assets/img/op/18.png?raw=true)

   Click **Save** to assign the questionnaire to the Data Owner.

5. **Associate Relevant Regulations**  
   For documentation purposes, associate applicable laws:
   - Click on **Mandates** → **Associate**
   - Select `GDPR` as the governing regulation  
   - Click **Done**  
   ![Mandates Association](https://github.com/Client-Engineering-Indonesia/IBM-PDP-workshop/blob/main/assets/img/op/19.png?raw=true)  
   ![Mandates Confirmation](https://github.com/Client-Engineering-Indonesia/IBM-PDP-workshop/blob/main/assets/img/op/20.png?raw=true)

6. **Mark the Record for Privacy Assessment**  
   After saving, return to the asset record.  
   Click **Action** in the top-right corner and select **Privacy Assessment Needed** to notify the Data Owner.

7. **Launch the Questionnaire**  
   Before submitting the asset for final approval, ensure the questionnaire is completed.  
   Either the Data Owner or the DPO (with Data Owner assistance) must fill out all required fields.  
   Click **Launch** to begin the questionnaire.  
   ![Launch Questionnaire](https://github.com/Client-Engineering-Indonesia/IBM-PDP-workshop/blob/main/assets/img/op/21.png?raw=true)

---

### 🧾 Conclusion

In this lab, you acted as:

1.  A Data Privacy Officer
- Access and review assigned data assets
- Evaluate metadata and asset completeness
- Trigger a request for additional information when necessary
- Interpret risk indicators like the PPIA-TS score
- Trigger additional assessments using GDPR-compliant templates
- Associate legal mandates for documentation
- Assign and launch privacy questionnaires

2.  A Data Owner responding to a privacy review request. You’ve learned how to:

- Enrich asset metadata and classification
- Provide integration and privacy-related details
- Fulfill legal documentation requirements under GDPR/PDP

This process ensures that your data asset is properly documented, assessed, and compliant with internal governance and external regulations.