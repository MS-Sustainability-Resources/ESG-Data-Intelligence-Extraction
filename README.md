# 📊 ESG Data Extraction and Intelligence

**Extract ESG data from documents using OpenAI and Microsoft Fabric. Accelerate ESG reporting, compliance, and sustainability analysis with AI-powered data extraction.**

---

## 📄 Overview

This repository provides a **ready-to-use notebook** that demonstrates how to extract **structured ESG-related data** from documents using **OpenAI**, fully integrated into the **Microsoft Fabric** ecosystem.

🔗 **Related Work:**  
This solution is closely related to and complements [UtilityInsights](https://github.com/WeaveAnalytics/UtilityInsights/tree/main).

---

## ⚡ Scope of This Repository

> **Focus:**  
> This notebook demonstrates the **data extraction** step only.  
> It does **NOT** implement a full end-to-end pipeline.  
> Customers and partners are encouraged to **extend** this foundational work to fit their specific use cases and downstream workflows.

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

## 🧽 Notebook Workflow

1. **Setup & Configuration**  
   Load dependencies, Fabric utilities, and API keys.

2. **Helper Functions**  
   Utilities for retrieving secrets, extracting text, and interacting with OpenAI.

3. **Data Ingestion**  
   Read documents (PDFs, images, text files) from Fabric Data Lake.

4. **AI-Powered Data Extraction**  
   Extract structured JSON data from document content using OpenAI.

5. **Output & Next Steps**  
   Transform extracted data into DataFrames for analysis, reporting, or integration into ESG management tools.

---

## 🏗️ Architecture Illustration

> *![image](https://github.com/user-attachments/assets/4bd6f7ae-f15d-4bb9-9cc7-42aac0b5f52b)
*

---

## 🚀 Getting Started

1. Clone this [cross-linked repository](https://github.com/WeaveAnalytics/UtilityInsights/tree/main) into your Microsoft Fabric workspace.
2. Deploy a GPT-4 model in AI Foundry and obtain the API Key and Endpoint URL.
3. Define your extraction schema based on the ESG data you want to extract.
4. Configure the notebook with your API Key, endpoint, and schema.
5. Update secrets and file paths to match your environment.
6. Run the notebook end-to-end or integrate it into your existing data workflows.
7. Customize prompts or post-processing steps as needed to meet your extraction goals.

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

---

## 🔮 Extensibility Ideas

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
