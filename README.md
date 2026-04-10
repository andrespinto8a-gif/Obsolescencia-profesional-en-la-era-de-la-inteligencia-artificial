from docx import Document

doc = Document()

content =  🎯 Risk Prioritization System

## 📌 Overview
This project implements a structured approach to risk prioritization based on impact and probability criteria. It helps classify risks into four treatment categories: Accept, Reduce, Avoid, and Share.

## ⚙️ Methodology
Risks are evaluated using:
- Probability (likelihood of occurrence)
- Impact (severity of consequences)

A risk matrix is used to determine priority levels:
- Low Risk → Accept
- Medium Risk → Reduce
- High Risk → Avoid or Share

## 📊 Risk Treatment Strategies
- Accept: No action required, risk is tolerable.
- Reduce: Implement controls to minimize impact or likelihood.
- Avoid: Eliminate the activity causing the risk.
- Share: Transfer risk (e.g., insurance or outsourcing).

## 🚀 Usage
1. Identify risks.
2. Assign probability and impact scores.
3. Classify using the risk matrix.
4. Apply appropriate treatment strategy.

## 📁 Project Structure
- README.md → Documentation
- risk_matrix.xlsx → Risk evaluation tool
- analysis_report.docx → Detailed analysis

## 🧠 Author
Andrés Eduardo Pinto Olalla


for line in content.split("\n"):
    doc.add_paragraph(line)

file_path = "/mnt/data/README_GitHub.docx"
doc.save(file_path)

file_path
