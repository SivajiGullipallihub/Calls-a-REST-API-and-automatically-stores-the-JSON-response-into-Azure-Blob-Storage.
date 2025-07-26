# 🌐 Azure Data Factory – Ingest REST API to Blob Storage

## ✅ Project Overview

This project demonstrates how to use **Azure Data Factory (ADF)** to automate data ingestion from a **REST API** and store the JSON response in **Azure Blob Storage**.

The use case simulates a real-world scenario where external systems (such as vendor APIs or public data sources) need to be integrated with internal data pipelines for storage, analysis, or auditing.

---

## 🚀 Workflow Summary

1. ADF pipeline triggers a **GET request** to a public REST API (`https://jsonplaceholder.typicode.com/posts`).
2. The JSON response is captured using the **Copy Data** activity.
3. The response is stored in **Azure Blob Storage** in `.json` format.
4. The pipeline supports **parameterized endpoints and filenames**, making it reusable and dynamic.

---

## 🛠️ Tools & Services Used

- Azure Data Factory
- Azure Blob Storage
- REST API (Public)
- JSON Dataset
- Web & Copy Activities

---

## 🔧 Real-Time Applications

- Ingest daily exchange rates, stock prices, or news data
- Store vendor API responses for further processing
- Archive data from partner systems for audits or compliance
- Trigger downstream pipelines for transformation and analytics

---

## 📁 File Output Example

