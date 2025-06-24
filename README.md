# Urban OSCUR Experiments

This repository contains experiments and tools for working with the **OSCUR** (Open Source City Urban Research) project. The project focuses on urban data analysis, visualization, and integration with tools such as [**UrbanMapper**](https://github.com/VIDA-NYU/UrbanMapper), [**Auctus**](https://auctus.vida-nyu.org/), [**Hugging Face**](https://huggingface.co/oscur), [**Data Formulator**](https://github.com/microsoft/data-formulator), and **Ollama**.

## Repository Structure
```
OSCUR-experiments/
├── Data_Formulator/           # Comprehensive guide to setting up and using Data Formulator with Ollama
├── HF_Auctus_integration/     # Add exploratory examples for future Hugging Face–Auctus integration)
└── Profilers/                 # Test Python-based data profilers)
```
### 1. `Data_Formulator`
This folder contains Jupyter notebooks and scripts for setting up and using the **Data Formulator** tool. Data Formulator bridges natural language and data visualization, allowing users to describe their analysis needs and automatically generate visualizations. However, it lacks a public API and relies on LLMs for functionality. It's designed for interactive use via its interface and natural language, not for external programmatic access.

- **Key Features**:
  - Integration with **Ollama**, a local AI inference engine for running large language models.
  - Sample workflows for creating, saving, and analyzing datasets.
  - Troubleshooting guides for common issues like port conflicts and server connectivity.

- **Notable Files**:
  - `data_formulator_with_Ollama.ipynb`: A comprehensive guide to setting up and using Data Formulator with Ollama for local data analysis.

### 2. `HF_Auctus_integration`
Begin adding exploratory examples for future Hugging Face–Auctus integration.

- **Notable Files**:
  - `Crawl_oscur_organization.ipynb`: Demonstrates how to retrieve datasets published by the "oscur" organization on Hugging Face and download specific files.
  - `Auctus_from_UrbanMapper.ipynb`: Using Auctus from UrbanMapper: Leverage Auctus to enhance urban data analysis by integrating geospatial datasets and AI-driven insights. 

### 3. `Profilers`
Comparison of different profiling tools for structured and unstructured data.

- **Profiling Tools**:
  - **Pandas `df.dtypes`**: Quickly checks the schema of a dataset by returning the data type of each column.
  - **Datamart Profiler**: Lightweight profiler focused on metadata extraction for integration into data discovery pipelines.
  - **YData Profiling**: Generates detailed HTML reports with statistics, correlations, and visualizations for structured datasets.
  - **DataProfiler**: Comprehensive profiling tool for both structured and unstructured data, including PII detection and data drift analysis.

- **Notable Files**:
  - `profilers.ipynb`: Demonstrates the use of various profiling tools, including Pandas, Datamart Profiler, YData Profiling, and DataProfiler, with examples of metadata extraction and visualization.

## License
This repository is open-source and available under the MIT License.

