## 02 - Create/Import Data Asset

### 🗂️ Data Asset Creation

1. **Access the Assets Section**  
   Open the hamburger menu on the left sidebar, then navigate to:  
   `IT Governance → Assets`  
   ![IT Governance Navigation](https://github.com/Client-Engineering-Indonesia/IBM-PDP-workshop/blob/main/assets/img/op/3.png?raw=true)

2. **Create a New Asset**  
   In the Assets menu, click the **New** button to initiate asset creation.

3. **Fill in Required Fields**  
   Complete the form with the following values:
   - **Name**: `CUSTOMER_<Acronym>` (e.g., `CUSTOMER_RI`)
   - **Description**: `Customer data asset from the Catalog`
   - **Resource Type**: `Data Asset`
   - **Parent Information**:  
     - Business Entity: `WKCLibrary`  
     - Or Path: `Library > DPM > DPMLibrary > WKCLibrary`  
     ![Parent Information](https://github.com/Client-Engineering-Indonesia/IBM-PDP-workshop/blob/main/assets/img/op/4.png?raw=true)
   - **Contact Section**:  
     - Set **Primary Owner** to yourself  
     - Optionally, add details such as asset owner, criticality, and other metadata  
     ![Contact Section](https://github.com/Client-Engineering-Indonesia/IBM-PDP-workshop/blob/main/assets/img/op/5.png?raw=true)

4. **Save the Asset**  
   Click **Save** to finalize and create the new asset.

---

### ✅ What Happens Next?

Once the asset is successfully created—either manually or via automation—it will trigger a workflow. This workflow can be customized to align with your organization's business processes.

> 💡 *Advanced Tip:*  
You can automate asset creation by integrating IKC with the GRC platform **OpenPages**. This enables seamless ingestion and workflow initiation for new data assets.

---

### 🔄 Workflow Review 
In this section, we'll explore an example of a workflow that is automatically triggered when a new data asset is loaded into the platform. Specifically, we’ll review the **Data Privacy Assessment Workflow**, which ensures each asset undergoes proper evaluation.

1. **Access Workflow Settings**  
   Click the **Settings** menu in the top-right corner. Expand **Solution Configuration**, then select the **Workflows** menu.  
   ![Workflow Settings](https://github.com/Client-Engineering-Indonesia/IBM-PDP-workshop/blob/main/assets/img/op/6.png?raw=true)

2. **Open the Data Privacy Assessment Workflow**  
   On the Workflows page, locate and open the **Data Privacy Assessment** workflow.

3. **Review Workflow Details**  
   On the workflow page, observe how the asset is reviewed:
   - Assigned reviewers and responsible parties
   - Due dates and timelines
   - Defined process steps

4. **Audit the Workflow (Read-Only)**  
   Take a moment to review each process defined in the workflow.  
   ⚠️ **Do not modify any values.**  
   ![Workflow Details](https://github.com/Client-Engineering-Indonesia/IBM-PDP-workshop/blob/main/assets/img/op/7.png?raw=true)

---

### 🧾 Conclusion
In this lab, you’ve learned how to:
- Create a new data asset
- Trigger and review a workflow to ensure compliance with company policy

By leveraging automated workflows like the Data Privacy Assessment, your organization can:
- Streamline documentation and approval processes
- Ensure accountability through clearly defined roles and deadlines
- Maintain consistent governance across all data assets

This approach not only reduces manual effort but also strengthens auditability and policy enforcement across the data lifecycle.