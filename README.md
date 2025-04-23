# Protecting The Genome Datasets with Differential Privacy (DP)

This repository contains my seminar paper, written in Hebrew, for the Bioinformatics course at the Open University of Israel. The paper explores how **Differential Privacy** and other privacy-preserving techniques can be applied to **Genomic Data** — a field at the intersection of bioinformatics, ethics, and data security.

🗓️ Completed: July 2024

## 📄 About the Paper

As genomic sequencing becomes faster and cheaper, **scientists around the world are eager to share and combine genomic data** to accelerate the pace of discovery in medicine, population genetics, personalized treatment, and disease prevention. Access to large, diverse datasets is essential for breakthroughs in rare disease research, cancer genomics, and epidemiology.

However, genomic data is **deeply personal** and **inherently identifiable**. Even a small fragment of DNA can uniquely identify a person and reveal sensitive information such as ancestry, predisposition to disease, or biological relationships.

This creates a critical tension between:
- 🔬 The **scientific desire** to freely share and analyze data, and  
- 🔒 The **ethical and legal responsibility** to protect individual privacy

This seminar paper addresses that tension by exploring **privacy-preserving methods** that enable data sharing without compromising personal privacy.

This seminar paper provides a comprehensive overview of:
- The structure and significance of genomic data
- Risks and ethical implications of sharing genomic information
- Privacy-preserving techniques such as:
  - **Access control**
  - **Encryption**
  - **K-anonymity**
  - **Differential privacy** (central and local implementations)
- Challenges in applying differential privacy to real-world genomic datasets
- Proposed solutions and frameworks (e.g., GenShare, selective SNP hiding)

## 🌍 Language

The seminar paper is written in **Hebrew**.

## 📘 English Summary

In the era of personalized medicine and large-scale genomic studies, **sharing genomic data** has become a powerful driver of scientific progress. Researchers worldwide are eager to collaborate, pool datasets, and uncover new insights into human health, disease, and evolution. Whether it’s identifying rare genetic disorders or developing targeted treatments, access to vast, diverse genomic databases is essential.

But while the **scientific incentives to share genomic data are strong**, so are the **ethical concerns**.

Genomic data is unlike any other personal data — it is **unique**, **immutable**, and **inherently identifiable**. A single DNA sequence can reveal sensitive information about a person’s ancestry, health risks, and family relationships. Worse still, even “anonymized” data can often be reverse-engineered to re-identify individuals.

This seminar paper explores how the field of **bioinformatics** is responding to this privacy dilemma — with a particular focus on the powerful technique of **differential privacy**.

The paper begins by laying out the structure and sensitivity of genomic data. It then surveys several privacy-preserving techniques used in research and clinical settings, including:

- 🔒 **Access control mechanisms**
- 🔐 **Data encryption methods**
- 📊 **K-anonymity and other statistical obfuscation techniques**
- 🧪 And most importantly, **differential privacy**, a formal mathematical framework that limits the risk of re-identification by introducing carefully calibrated noise

The heart of the paper dives into **how differential privacy can be applied to genomic data**, highlighting:

- 🧭 The differences between **central** and **local** differential privacy models  
- 🧬 The challenges of using these techniques with **highly correlated genomic datasets** (e.g., SNPs)  
- ⚖️ The balance between **data utility** and **privacy guarantees**

It also reviews real-world systems and protocols designed to enable privacy-aware genome sharing — including:

- **GenShare**
- **Selective SNP hiding**

In conclusion, the paper emphasizes that solving this challenge is not only a matter of data science or security — but also of **trust**, **ethics**, and the future of **collaborative science**. The right privacy-preserving technologies can help strike a balance: enabling researchers to share and analyze genomic data at scale, while respecting the rights of individuals whose DNA powers that research.
