# FDA Complete Response Letters (CRL) – Structured Repository

This repository contains a collection of **FDA Complete Response Letters (CRLs)**, converted from public domain PDF files into clean, searchable, and structured **Markdown files with YAML front matter**. The goal is to enable easier access, navigation, and large language model (LLM)-ready use of document set provided by the U.S. Food and Drug Administration.

---

## Repository Structure

Each CRL is stored as an individual Markdown (`.md`) file under the `/crl/` directory.

Each file includes:
- **YAML Front Matter**: machine-readable metadata such as application number, drug name, sponsor, document date, document type, and FDA contact.
- **Critical Data Summary**: a human-readable list of key fields extracted from the letter.
- **Clean Markdown Body**: converted from the original FDA PDF, preserving the original structure, formatting, and section headers.

---

## Use Cases

This repository is designed to support the following:

- **Regulatory Intelligence**  
  Identify common deficiencies, patterns in application types, and frequent issues cited by FDA divisions.

- **LLM-Ready Data**  
  Train or fine-tune GPTs, Claude, or open-source LLMs on structured FDA CRL content.

- **Search and Indexing**  
  Each Markdown file is structured for embedding-based search, GPT indexing, or use with tools like Obsidian, Dendron, or Weaviate.

- **Consulting and Compliance Review**  
  Reference past FDA responses when preparing applications or responses for biologics, small molecules, or cell therapies.

---

## 📈 What's Included (Initial Phase)

- ✅ 200+ CRLs released publicly by the FDA on 10 JULY 2025
- ✅ Metadata extraction including application type, product name, and FDA division
- ✅ Clean Markdown format with standardized headers and section structure


---

## 📦 How to Use

You can:
1. Clone or fork the repo and browse documents locally or with a Markdown viewer.
2. Index the data into your own GPT or RAG-powered tool.
3. Use Obsidian or another Markdown-based knowledge tool for personal reference.

---

## 📜 License

**Creative Commons Attribution 4.0 International (CC BY 4.0)**

> This project makes use of publicly available U.S. government documents which are in the public domain. The transformation, formatting, and metadata structuring are licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). You are free to use, modify, and distribute the content with appropriate attribution.

**Attribution Requested:**  
If referencing this project, please attribute to:

FDA CRL Markdown Repository, curated by [GMPKit](https://gmpkit.com) - gmpkit.com


---

## 🔧 Contributing

Want to contribute additional CRLs, formats (e.g., Form 483s), or improvements to the parser?

- Submit a Pull Request
- Open an Issue
- Contact [support@gmpkit.com] if you'd like to collaborate on a larger-scale ingestion project

---

## 🧠 Credits & Inspiration

This project was inspired by the FDA's initiative for [transparency](https://www.fda.gov/news-events/press-announcements/fda-embraces-radical-transparency-publishing-complete-response-letters):

"The CRLs were issued in response to applications submitted to the FDA for approval of drugs or biological products between 2020 and 2024, marking a significant step in the Agency’s broader initiatives to modernize and increase transparency."

This project was built on the dataset released on 10 July 2025, along with the need for more usable, machine-readable regulatory content in drug development, quality systems, and compliance work.

Built using:
- Documents in the public domain at [Open FDA](https://open.fda.gov/apis/other/approved_CRLs/)
- [`n8n`](https://n8n.io/) for workflow automation
- `OpenAI GPT` for formatting and metadata extraction
---

## 📮 Contact

Maintained by GMPKit, LLC
Project Website: [https://gmpkit.com](https://gmpkit.com)  
Blog: [https://gmpkit.com/blog](https://gmpkit.com/blog)

---

