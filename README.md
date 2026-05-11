# Awesome-Vertical-AI-ERP

# Top Synthetic Data Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Privacy-Safe & Simulation Data for AI Training and Testing*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** building **synthetic data generation tools**. These platforms create realistic yet privacy-safe artificial data that mirrors the statistical properties of real datasets. They are used for AI/ML model training, software testing, analytics development, and compliance (GDPR, HIPAA, etc.) without exposing sensitive personal information.

**Examples** include Gretel.ai, MOSTLY AI, K2view, Tonic.ai, Syntho, and Hazy (the category leaders). Tools listed here emphasize **high-fidelity data**, privacy guarantees (differential privacy), support for tabular, relational, time-series, and multimodal data, and scalability for enterprise use.

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, local execution, full customization, fine-tuning, and zero licensing costs — ideal for researchers, developers, and organizations prioritizing data sovereignty and cost control.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS Products](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS Products

### Core Platforms (Synthetic Data Generation)

- **[Gretel.ai](https://gretel.ai/)**  
  Leading privacy engineering platform for generating high-fidelity synthetic tabular, time-series, and unstructured data with strong differential privacy guarantees.

- **[MOSTLY AI](https://mostly.ai/)**  
  Enterprise-grade synthetic data platform known for high statistical fidelity and privacy-safe generation of structured and relational datasets.

- **[K2view](https://www.k2view.com/)**  
  Synthetic data management platform combining AI generation, intelligent masking, and data cloning for test and development environments.

- **[Tonic.ai](https://www.tonic.ai/)**  
  Popular synthetic data solution focused on realistic test data generation while preserving referential integrity and statistical properties.

- **[Syntho](https://www.syntho.ai/)**  
  AI-powered synthetic data platform with strong support for complex relational data and privacy compliance.

- **[Hazy](https://hazy.com/)**  
  Synthetic data platform specializing in high-quality generation for financial services and other regulated industries.

### Advanced & Specialized Platforms

**Other notable mentions**: YData, MDClone (healthcare), and various cloud-native solutions from big tech providers.

## Open-Source GitHub Projects

### Dedicated Synthetic Data Generation Projects

- **[SDV (Synthetic Data Vault)](https://github.com/sdv-dev/SDV)**  
  The most comprehensive open-source Python library for synthetic data. Supports single-table, multi-table relational, and time-series data with multiple models (Copulas, CTGAN, TVAE, etc.) and built-in evaluation metrics.

- **[mostlyai/mostlyai](https://github.com/mostly-ai/mostlyai)**  
  Open-source Synthetic Data SDK for high-fidelity, differentially private tabular data generation. Can run fully locally with excellent statistical quality.

- **[ydataai/ydata-synthetic](https://github.com/ydataai/ydata-synthetic)**  
  Python library focused on generating synthetic tabular and time-series data using GANs and other deep learning models.

- **[synthcity](https://github.com/vanderschaarlab/synthcity)**  
  Comprehensive library for generating and evaluating synthetic tabular data with strong focus on privacy, fairness, and data augmentation.

- **[DataDesigner (NVIDIA NeMo)](https://github.com/NVIDIA-NeMo/DataDesigner)**  
  Powerful tool for generating high-quality synthetic datasets from scratch or using seed data, optimized for LLM fine-tuning and AI training.

- **[argilla-io/synthetic-data-generator](https://github.com/argilla-io/synthetic-data-generator)**  
  Tool for building high-quality datasets for LLM training and fine-tuning using natural language instructions.

- **[meta-llama/synthetic-data-kit](https://github.com/meta-llama/synthetic-data-kit)**  
  Official toolkit from Meta for generating high-quality synthetic datasets, including reasoning traces and QA pairs for LLM fine-tuning.

- **[Synner](https://github.com/huda-lab/synner)**  
  Visual open-source tool for generating realistic synthetic data by specifying dataset properties through an intuitive interface.

### Additional Strong Open-Source Options

- **[Faker](https://github.com/joke2k/faker)** — Industry-standard library for generating fake data (names, addresses, etc.) in multiple languages.
- **[DoppelGANger](https://github.com/fjxmlzn/DoppelGANger)** — GAN-based synthetic time-series data generator.
- **[Synthea](https://github.com/synthetichealth/synthea)** — Realistic synthetic patient/medical record generator widely used in healthcare.
- **[Mimesis](https://github.com/lk-geimfari/mimesis)** — Fast, multilingual fake data generator.
- **Distilabel** — Framework for synthetic data and AI feedback pipelines.
- **Copulas & CTGAN** (part of SDV ecosystem) — Specialized libraries for multivariate and conditional tabular synthesis.

**Frameworks for building custom solutions**: Combine **SDV** + **mostlyai SDK** with **LangChain/LangGraph** for agentic synthetic data pipelines, or use **Hugging Face Diffusers** for image/multimodal synthetic data.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Synthetic data quality should always be evaluated against your specific use case (fidelity, privacy risk, downstream model performance). Differential privacy does not guarantee absolute anonymity.
- For regulated industries (healthcare, finance), validate compliance with relevant standards (HIPAA, GDPR, etc.).

---

**Made for data scientists, ML engineers, privacy officers, and software testing teams.**  
Let's make AI development more privacy-safe, accessible, and data-abundant.


## 📈 Star History

<div align="center">
	<a href="https://www.star-history.com/?repos=ishandutta2007%2FAwesome-Vertical-AI-ERP&type=date&legend=bottom-right">
	 <picture>
	   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/chart?repos=ishandutta2007/Awesome-Vertical-AI-ERP&type=date&theme=dark&legend=bottom-right" />
	   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/chart?repos=ishandutta2007/Awesome-Vertical-AI-ERP&type=date&legend=bottom-right" />
	   <img alt="Star History Chart" src="https://api.star-history.com/chart?repos=ishandutta2007/Awesome-Vertical-AI-ERP&type=date&legend=bottom-right" />
	 </picture>
	</a>
</div>
