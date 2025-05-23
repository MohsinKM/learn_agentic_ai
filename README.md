# 🧠 Agentic Data Pipeline with CrewAI

This repository contains a **minimal working example** of an agentic data pipeline built using [CrewAI](https://github.com/joaomdmoura/crewai). It simulates how multiple AI agents can collaborate on a structured data analysis workflow—without manual handoffs or glue code.

---

## 📊 What Does It Do?

This pipeline includes two agents:

- 🛰️ **Ingestion Agent**: Fetches the Iris dataset  
- 📊 **Visualization Agent**: Generates a scatter plot of sepal length vs petal length

The goal is to demonstrate **agent coordination**, which is a foundational concept for building scalable **Agentic AI systems**.

---

## 🚀 Try It in Google Colab

You can run both versions of the notebook directly in Colab:

---

### 🧩 Part 1: Agentic Data Pipeline using CrewAI (Iris Dataset)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/MohsinKM/learn_agentic_ai/blob/main/agentic_data_pipeline_crewai_updated_colab.ipynb)

> 📘 *Loads a static CSV dataset and plots a simple scatter chart using agents.*

---

### 🌐 Part 2: CrewAI with MCP Integration (Live Weather Data)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/MohsinKM/learn_agentic_ai/blob/main/agentic_data_pipeline_crewai-part2.ipynb)

> 🌦️ *Fetches live hourly temperature data from a public weather API and visualizes it with agents—demonstrating basic MCP (Model Context Protocol) integration.*

---

💡 *For both notebooks: Go to `File → Save a copy in Drive` to run and edit your own version.*


---

## 🧱 Built With

- [CrewAI](https://github.com/joaomdmoura/crewai)
- Python, Pandas, Matplotlib
- Google Colab

---

## 🔜 Coming Next

- 🔁 Full A2A communication using FastAPI
- 🌐 MCP integration for live API data access
- 📤 Reporting agent pushing insights to Slack or Notion

---

## 👤 Author

Built by [Dr. K.M. Mohsin](https://www.linkedin.com/in/km-mohsin/)  
Follow for more drops on **Agentic AI, LLMs, LangGraph, and Autonomous Pipelines**

---

## 🏷️ Tags

`Agentic AI` · `CrewAI` · `A2A` · `MCP` · `AI Agents` · `LLM` · `Data Science` · `FastAPI` · `Colab`
