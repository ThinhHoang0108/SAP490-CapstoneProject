# **SAP490-CapstoneProject**  

🚀 **Capstone Project - SAP ABAP Workflow, GR Report, and PO Form Customization**  

📌 **Description:**  
This project focuses on **SAP ABAP development and customization**, specifically in:  
1. **SAP Workflow** – Implementing a **2-level approval process** for purchase orders.  
2. **Goods Receiving (GR) Report** – Generating **Excel-based reports** using **OLE Object**.  
3. **Purchase Order (PO) Form** – Designing **SmartForms for PDF printing** of PO documents.  

The project enhances SAP ERP by **automating approvals, optimizing report generation, and improving document management**.  

---

## **👥 Our Team**
- **Team Leader:** Đỗ Đức Thịnh (HS170111)  
- **Team Members:**  
  - Hoàng Xuân Thịnh (HE161617)  
  - Khúc Xuân Hoà (HE163890)  
  - Đỗ Đức Thắng (HE160174)  
  - Nguyễn Lan Ngọc (HE160359)  

**Project Duration:** September 2024 – December 2024  

---

## **📂 Repository Structure**  

```plaintext
SAP490-CapstoneProject/
│── workflow/            # SAP Workflow for PO approval (2-level)
│── gr_report/           # GR Report using OLE Object (Excel output)
│── po_form/             # PO Form using SmartForms (PDF output)
│── docs/                # Documentation, functional specs, and test cases
│── README.md            # Project overview and setup guide
```

---

## **📝 Project Details**  

### **1️⃣ SAP Workflow - 2-Level Approval Process**  
🔹 Automates purchase order approvals via **two levels of authorization**.  
🔹 Reduces manual intervention and ensures compliance with company policies.  
🔹 Implemented using **SAP Business Workflow (SWDD)**.  


### **2️⃣ Goods Receiving (GR) Report - Excel Output with OLE Object**  
#### **Personal Tasks:**
- View and print the GR report with Excel.  
- Check user plant authorize access to ensure they can only view reports for their assigned.  
- Automatically suggests the plants the user can access.  
- Document Reversal: When a document is canceled, it will not be included in the GR report.  
🔹 Generates **Excel-based GR reports** for better usability and flexibility.  
🔹 Uses **OLE Object in ABAP** to format and export reports dynamically.  
🔹 Ensures **user-based authorization**, restricting access based on plant assignments.  
🔹 Implements **automatic plant suggestion** based on user roles.  
🔹 **Document Reversal Handling**: Excludes canceled documents from reports. 

### **3️⃣ Purchase Order (PO) Form - SmartForms PDF Output**  
🔹 Custom **SmartForms layout** for printing purchase orders.  
🔹 Generates professional **PDF documents** for vendor communication.  
🔹 Includes company branding and **dynamic PO data fetching**.  

---

## **🖼️ Preview Screenshots**  

<div align="center">
<img src="https://github.com/ThinhHoang0108/SAP490-CapstoneProject/blob/main/workflow/sap%20workflow%201.jpg" alt="SAP Workflow Approval Process" width="45%"></img>
<img src="https://github.com/ThinhHoang0108/SAP490-CapstoneProject/blob/main/workflow/sap%20workflow%202.jpg" alt="SAP Workflow Approval Process" width="45%"></img>
<p> SAP Workflow Approval Process</p>
<img src="https://github.com/ThinhHoang0108/SAP490-CapstoneProject/blob/main/po_form/po%20form.jpg" alt="PO Form in PDF" width="45%"></img>
<img src="https://github.com/ThinhHoang0108/SAP490-CapstoneProject/blob/main/po_form/po%20form%202.jpg" alt="PO Form in PDF" width="45%"></img>
<img src="https://github.com/ThinhHoang0108/SAP490-CapstoneProject/blob/main/po_form/po%20form%203.jpg" alt="PO Form in PDF" width="45%"></img>
<p> PO Form in PDF</p>
<img src="https://github.com/ThinhHoang0108/SAP490-CapstoneProject/blob/main/gr_report/gr%201.jpg" alt="GR Report in Excel" width="45%"></img>
<img src="https://github.com/ThinhHoang0108/SAP490-CapstoneProject/blob/main/gr_report/gr%202.jpg" alt="GR Report in Excel" width="45%"></img>
<p> Goods Receiving (GR) Report in Excel</p>
</div>

---

## **🛠 Technologies Used**  

### **1. SAP Workflow (PO Approval)**  
🔹 **Transaction Codes:** SWDD, SWI1, PFTC  
🔹 **Approval Logic:** Multi-level user authorization  

### **2. GR Report (Excel Export)**  
🔹 **Transaction Code:** MB51, ZGR_REPORT  
🔹 **Technology:** OLE Object for Excel automation  
🔹 **Security:** User-specific report access control  

### **3. PO Form (PDF Output)**  
🔹 **Transaction Code:** ME21N, ZPO_FORM  
🔹 **Technology:** SAP SmartForms for professional document printing  

---

## **🎯 Functional Requirements**  

### **1️⃣ SAP Users (End Users & Procurement Team)**  
✅ Approve purchase orders via **SAP Workflow** (2-level)  
✅ Generate **Excel-based GR reports** with user-specific data  
✅ Print **PO forms as PDFs** using SmartForms  

### **2️⃣ SAP Administrators**  
✅ Configure & manage **SAP Workflow processes**  
✅ Set up **OLE automation for Excel reporting**  
✅ Customize & deploy **SmartForms for PO printing**  

---

## **📚 References & Resources**  
*Personal Documents*
| # | Name | Description |
|---|------|------------|
| 1 | [eSlide](https://github.com/ThinhHoang0108/SAP490-CapstoneProject/blob/main/docs/SAP490-Global%20Pharma.pdf) | IntrodIntroduce to GR report structure and design. |
| 2 | [Technial Specifications](https://github.com/ThinhHoang0108/SAP490-CapstoneProject/blob/main/docs/%5BSAP490-Group4%5DTS_GR%20Report_v1.0.xlsx) | Technical blueprint Excel reports in SAP ABAP |
| 3 | [Functional Specifications](https://github.com/ThinhHoang0108/SAP490-CapstoneProject/blob/main/docs/%5BSAP490-Group4%5DFunctional_Specification_GR%20Report_V1.0.xlsx) | Detailed requirements and logic for GR report in SAP. |

