# 📊 ESG Data Intelligence and Extraction 

**Extract ESG data from documents using OpenAI and Microsoft Fabric. Accelerate ESG reporting, compliance, and sustainability analysis with AI-powered data extraction.**

---

## 📄 Overview

This repository provides resources that demonstrate how to extract **structured ESG-related data** from documents using **OpenAI**, fully integrated into the **Microsoft Fabric** ecosystem.

🔗 **Related Work:**  
This solution is closely related to and complements [UtilityInsights](https://github.com/WeaveAnalytics/UtilityInsights/tree/main).

---

## ✨ Benefits

- **Simplified Extraction Process:**  
  Azure OpenAI simplifies document extraction by converting files into images and using generative AI to locate and extract relevant fields—no extensive manual markup required.

- **Flexible Schema Definitions:**  
  Easily define and modify schemas to suit various document types, making it ideal for multiple industries.

- **No Training Required:**  
  Leverages predefined prompts and schemas, eliminating the need for model training.

- **Format Flexibility:**  
  Seamlessly handle PDFs, scanned images, and text files. Extend to new document types like sustainability reports, invoices, manifests, and compliance documents.

---

## 🏗️ Architecture Illustration

> *![image](https://github.com/user-attachments/assets/4bd6f7ae-f15d-4bb9-9cc7-42aac0b5f52b)*

---

## 🚀 What gets deployed?

- Azure OpenAI service
- Azure KeyVault to store secrets
- Azure Fabric Capacity to use in the process
- A new Entra ID App Registration that creates the right Fabric items
- A new Fabric Workspace with the items (Lakehouse and Notebook) required to test UtilityInsights

---

## 🌍 Potential Use Cases

- **Utility Data Analysis:**  
  Extract and analyze electricity, water, and other utility usage from scanned bills and invoices to calculate environmental impact.

- **Supply Chain Insights:**  
  Extract logistics data (shipping invoices, manifests) to map your supply chain’s carbon footprint.

- **Sustainability Benchmarking:**  
  Analyze sustainability reports and compare performance against industry benchmarks to drive ESG goal setting.

- **Regulatory Compliance:**  
  Automate document verification processes to streamline compliance reporting for environmental regulations.

- **Social and Governance Data Extraction:**  
  Identify and store critical ESG-related insights from financial reports, press releases, and internal documents.

- **Integration with ESG Management Tools:**  
  Feed extracted data into ESG solutions like Microsoft Sustainability Manager for tracking and reporting.

- **Safety data Extraction:**  
Extract and structure chemical safety data to support safe handling, emergency response, and process optimization in manufacturing.

---

## 🔮 Extensibility Ideas

- Adapt invoice and/or document storage locations present in Blob storage, SharePoint doc libraries, Emails, Lakehouse, and other storage locations. 
- Adapt workflows for other document types (e.g., safety data sheets, transport logs).
- Automate extractions via Data Factory pipelines.
- Create workflows with Power Automate:
  - Set up alias email accounts to receive documents.
  - Automatically save attachments to SharePoint.
  - Integrate documents into OneLake for downstream processing.

---

## 🤝 Questions or Contributions?

We welcome feedback, ideas, and community contributions!  
If you extend or adapt this solution for your organization, feel free to **fork** and **share** your innovations.

---

## 📬 Contact

For questions or collaboration opportunities, please reach out to:

- Amanda Giglio — [giglioamanda@microsoft.com](mailto:giglioamanda@microsoft.com)
- Sachin Yelkar — [sachin.yelkar@microsoft.com](mailto:sachin.yelkar@microsoft.com)
- Ravi Gangadharan — [raving@microsoft.com](mailto:raving@microsoft.com)

---
