![CAMEL: Clavien-Dindo Assessment from Medical EHR using Large Language Models](assets/CAMEL.png)


![Python](https://img.shields.io/badge/python-3.7+-blue.svg)

A repository for automated extraction and classification of postoperative complications from medical EHR (Electronic Health Records) using Large Language Models (LLMs) according to the Clavien-Dindo classification system.



## 📋 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Citation](#citation)

## 🔍 Overview

The Clavien-Dindo classification is a standardized system for grading postoperative complications based on the therapeutic consequences. This tool leverages Large Language Models to automatically extract and classify complications from medical documents (e.g., discharge letters, operative reports) into appropriate Clavien-Dindo grades.

### Supported Classification Types

- **Fine-grained Classification**: Direct classification into specific Clavien-Dindo grades (0, I, II, IIIa, IIIb, IV, V)
- **Binary Classification**: Categorizes complications into two groups:
  - **Category A**: Minor to moderate complications (Grades 0-IIIa)
  - **Category B**: Severe complications (Grades IIIb-V)


## ✨ Features

- 🤖 **LLM-powered**: Uses state-of-the-art language models for accurate classification
- 🔄 **Asynchronous processing**: Efficient batch processing of multiple documents
- 📝 **Multiple input formats**: Supports single files or entire directories
- 📊 **CSV output**: Results exported to structured CSV format
- 🌐 **Flexible endpoints**: Compatible with various LLM API endpoints
- 🎯 **Two classification modes**: Binary and fine-grained classification options



## 📚 Citation

If you use this tool in your research, please cite our paper:

**Paper**: [Link to paper explaining the methodology and validation results will be published, as soon as it was accepted]

