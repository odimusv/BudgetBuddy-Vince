# 📊 Budget Buddy – Smart Finance Assistant

<!-- BADGES:START -->
[![curtin](https://img.shields.io/badge/-curtin-f57c00?style=flat-square)](https://github.com/topics/curtin)
[![ai-assistant](https://img.shields.io/badge/-ai--assistant-blue?style=flat-square)](https://github.com/topics/ai-assistant)
[![chatbot](https://img.shields.io/badge/-chatbot-blue?style=flat-square)](https://github.com/topics/chatbot)
[![finance](https://img.shields.io/badge/-finance-blue?style=flat-square)](https://github.com/topics/finance)
[![financial-tools](https://img.shields.io/badge/-financial--tools-blue?style=flat-square)](https://github.com/topics/financial-tools)
[![budgeting](https://img.shields.io/badge/-budgeting-4caf50?style=flat-square)](https://github.com/topics/budgeting)
[![gradio](https://img.shields.io/badge/-gradio-blue?style=flat-square)](https://github.com/topics/gradio)
[![jupyter-notebook](https://img.shields.io/badge/-jupyter--notebook-blue?style=flat-square)](https://github.com/topics/jupyter-notebook)
[![python](https://img.shields.io/badge/-python-3776ab?style=flat-square)](https://github.com/topics/python)
[![rag](https://img.shields.io/badge/-rag-blue?style=flat-square)](https://github.com/topics/rag)
<!-- BADGES:END -->

Welcome to my project repository for the **ISYS2001 Final Programming Project**.

This project is called **Budget Buddy**, a Smart Finance Assistant designed to help students and young adults in Australia understand their spending habits, identify budgeting patterns, and receive practical money management suggestions.

---

## 📖 Project Overview

**Budget Buddy** is a personal finance assistant built using Python, AI tools, RAG retrieval, a custom savings calculator, and a Gradio interface.

The aim of the project is to make budgeting easier and less overwhelming for students and young adults by allowing users to upload transaction data and receive clear, supportive financial insights.

Budget Buddy can:

- Load and clean transaction CSV files
- Analyse spending by category
- Detect refunds and calculate net spending
- Identify top spending categories
- Generate practical budgeting recommendations
- Provide a finance-focused chatbot
- Retrieve budgeting information using RAG
- Calculate savings goal timelines
- Present everything in a simple Gradio web interface

Budget Buddy does **not** provide personal financial advice. It is intended for budgeting education and general money management support only.

---

## 🧠 Problem Being Solved

Many students and young adults struggle to understand where their money is going. Transaction data can be confusing, especially when it includes refunds, subscriptions, eating out, transport costs, and flexible spending.

Budget Buddy helps solve this problem by turning raw transaction data into easy-to-understand summaries and recommendations.

For example, it can help users answer questions such as:

- How much did I spend overall?
- Which category did I spend the most on?
- How much did refunds reduce my spending?
- What spending areas could I reduce first?
- How long will it take me to reach a savings goal?
- What small budgeting actions can I take next?

---

## 🛠️ Technologies Used

This project uses:

- **Python** for data processing and application logic
- **Pandas** for loading, cleaning, and analysing transaction data
- **hands-on-ai** for chatbot, RAG, and agent tool features
- **Gradio** for the user interface
- **Google Colab** for notebook development
- **Assert-based testing** for validating the main functions

---

## ✅ Main Features

### 1. Transaction Data Cleaning

Budget Buddy can load transaction data from a CSV file or pandas DataFrame.

It handles:

- Dollar signs in amounts
- Commas in large numbers
- Refunds shown as negative amounts
- Missing values
- Invalid dates
- Invalid amount formats
- Blank rows
- Missing required columns

Required columns:

```text
Date, Amount, Category, Description
