## Ka-Kyung Kim, Ph.D.

**From specimen to clinical decision.** I design and operate genomics analysis that ends up in reports and services a hospital actually uses, and I measure how far those results can be trusted.

Chief Researcher, Diagnosis Division, **Cytogen** — CTC-based liquid biopsy, Seoul, Korea.

`20+ years` omics and clinical data &nbsp;·&nbsp; `20+` peer-reviewed papers &nbsp;·&nbsp; `7` institutions and companies &nbsp;·&nbsp; `4` degrees across computer science, life science, and molecular medicine

[Portfolio](https://kakyungkim.github.io) · [Blog](https://kakyungkim.github.io/en/) · [CV](https://kakyungkim.github.io/assets/home/KaKyung-Kim-CV.pdf) · [Google Scholar](https://scholar.google.com/citations?user=jSjoINAAAAAJ) · [ORCID](https://orcid.org/0009-0001-9380-597X) · [LinkedIn](https://www.linkedin.com/in/kakyungkim/) · <kakyung.kim@gmail.com>

---

### Recent highlights

- **2026.11** — Oral presentation accepted at **BIOINFO 2026 / GIW XXXV / ISCB-Asia** (22 of 287 submissions): a reliability map for per-gene multiome RNA velocity parameters. A second abstract from the same harness was accepted as a poster.
- **2026** — Shipped a **cell image review assistant** in-house, trained on 1,531 cells drawn from reader decisions. Slide-level cross-validation had inflated agreement to kappa 0.910; re-splitting at the specimen level to block leakage brought it to 0.704, and the corrected figure is the one that shipped. Confidence-based triage cut the cells needing priority human confirmation by 70%.
- **2026** — Published an **ADMET split audit** on public data. Across 12 Therapeutics Data Commons tasks, a structure-disjoint split degraded all 12 (median drop 0.098); on screening metrics, top-10% hit rate fell on all 8 tasks tested and VDss went from 0.358 to 0.176 (p<0.001). Raising seeds from 5 to 15 narrowed the gaps enough to **retract three of my own initial conclusions**, and I published the correction. [Write-up (Korean)](https://kakyungkim.github.io/kr/2026/09/08/admet-split-audit/)
- **2026** — Fifth trend report in **BRIC View** (2026-T24, generative AI in biotech and drug discovery).
- **Since 2026.06** — Two agent harnesses running in the open: [econ-radar](https://kakyungkim.github.io/econ-radar) daily, [paper-radar](https://kakyungkim.github.io/paper-radar) weekly.

### Selected publications

| Year | Work | Venue | Role |
|---|---|---|---|
| 2019 | [Whole-exome and whole-transcriptome sequencing of canine mammary gland tumors](https://doi.org/10.1038/s41597-019-0149-8) | *Scientific Data* 6(1):147 | First author |
| 2013 | [miRTCat: a comprehensive map of human and mouse microRNA target sites](https://doi.org/10.1093/bioinformatics/btt296) | *Bioinformatics* 29(15):1898 | First author |
| 2018 | [Palmitate and mmLDL cooperatively promote inflammatory responses in macrophages](https://doi.org/10.1371/journal.pone.0193649) | *PLoS One* 13:e0193649 | Co-first author |
| 2020 | [Cross-species oncogenic signatures of breast cancer in canine mammary tumors](https://doi.org/10.1038/s41467-020-17458-0) | *Nature Communications* 11:3616 | Co-author |
| 2022 | [GWAS identifies TNFSF15 associated with childhood asthma](https://doi.org/10.1111/all.14952) | *Allergy* 77(1):218 | Co-author |
| 2021 | [Genetic features of gastric mixed adenoneuroendocrine carcinomas](https://doi.org/10.1002/path.5556) | *Journal of Pathology* 253(1):94 | Co-author |

Full list on [Google Scholar](https://scholar.google.com/citations?user=jSjoINAAAAAJ), [ORCID](https://orcid.org/0009-0001-9380-597X), and the [portfolio](https://kakyungkim.github.io/#publications). Three manuscripts in preparation.

### What I build

Automate the interpretation, but leave the evidence so a person can check it.

| Repository | What it does |
|---|---|
| [econ-radar](https://github.com/kakyungkim/econ-radar) | Agent harness publishing a daily economic digest weighted toward pharma, bio, and AI. Collection, selection, summarization, and publishing split across agents. Daily brief plus weekly roundup, running since June 2026. |
| [paper-radar](https://github.com/kakyungkim/paper-radar) | Weekly digest of bioinformatics, clinical ML, and drug-discovery AI papers, sorted into three readings: method, clinic, and industry. |
| [paper-production-harness](https://github.com/kakyungkim/paper-production-harness) | Topic-agnostic multi-agent harness that runs a paper from analysis through to the talk. CC BY 4.0. |
| [korea-agentic-hackathon-2026](https://github.com/kakyungkim/korea-agentic-hackathon-2026) | Drug candidate validation agent that catches claims a docking score cannot support. NVIDIA × FastCampus Korea Agentic AI Hackathon 2026. |
| [pharmasignal-v0](https://github.com/kakyungkim/pharmasignal-v0) | Drug safety signal agent over regulatory filings and trial registries. Inference is routed by data sensitivity, so restricted material never reaches a commercial API. Agent Forge AI Hackathon Seoul 2026. |
| [chillmcp](https://github.com/kakyungkim/chillmcp) | MCP server built with FastMCP: 12 model-callable tools and 5 interactive prompts, MIT licensed. SKT AI Summit Hackathon 2025. |

Closed-source work includes **VeriVar**, a dual-mode somatic variant interpretation pipeline where an LLM mode and a rule-based mode run side by side and their disagreements serve as a verification signal, and **AutoBioX**, the multi-agent research harness behind the GIW 2026 abstracts.

### Talks and writing

- **BIOINFO 2026 / GIW XXXV / ISCB-Asia** — oral presentation, accepted 22 of 287 (Nov 2026, upcoming)
- **PseudoCon 2026** — the AutoBioX multi-agent pipeline
- **ABDD Summit 2026, Stanford** — automated clinical reporting for oncology NGS: a dual-mode LLM pipeline (i-Talk and poster)
- **Future of Medicine Symposium 2025** — single-cell QC standardization and an scRNA-seq × immunofluorescence pipeline (lightning talk)
- **BRIC View** — five invited trend reports (2017, 2018, 2025, 2026 ×2) on cloud genomics, allergy therapeutics, single-cell in drug discovery, bio big data, and generative AI

I write up what I built and where I went wrong, in Korean and English: [kakyungkim.github.io](https://kakyungkim.github.io/en/).

### Awards

Korea Clinical Datathon, **Grand Prize** (2019, sepsis prediction, KoNECT) · Cheiron ResearchThon, Creative Academic Impact Award (2025) · ABDD Summit, Best Poster (2024) · KSMCB Annual Meeting, Outstanding Poster (2011)

### Stack

- **Omics** — multi-platform NGS (WES, WGS, RNA-seq, scRNA-seq, multiome, liquid biopsy), Nextflow, Seurat/Scanpy, AWS
- **AI** — PyTorch, pathology foundation model embeddings, LLM agent harnesses, RAG with citation grounding, MCP
- **Clinical** — Ph1–3 trial analysis, clinical report automation, GCLP/CAP/ISO quality systems
- **Languages** — Python, R, Bash, SQL

### Education

Ph.D. Molecular Medicine, Sungkyunkwan University (2011) &nbsp;·&nbsp; M.S. Life Science, Korea University (2004) &nbsp;·&nbsp; B.S. Computer Science, Dongguk University (2000) &nbsp;·&nbsp; B.S. Health & Environment and Business, Korea National Open University (2023)
