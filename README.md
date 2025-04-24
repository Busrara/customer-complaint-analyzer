# customer-complaint-analyzer

This is a NLP-based tool to identify and summarize the most frequent customer complaints from support ticket data and visualize the result by matplotlib.

## 🚀 Features

- Analyzes support ticket datasets (CSV)
- Finds out most common complaint categories
- Visualizes complaint frequency using bar charts
- Gives a short summary for reporting

## 🧠 Example Output

> **Most reported problem:**
> 
> `Unable to operate menu from remote` – **520 cases**
> 
> **Summary:**  
> This report identifies 'Unable to operate menu from remote' as the most frequent customer complaint with 520 cases.

## 📁 Input Format

The tool expects a CSV file with at least the following columns:

- `PROBLEM_TYPE`: Description of the issue
- `number_of_cases`: Number of times the problem was reported

## 📦 Installation

```bash
pip install -r requirements.txt
