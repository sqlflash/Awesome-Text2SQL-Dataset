# Awesome-Text2SQL-Dataset
Awesome-Text2SQL-Dataset is a curated collection of datasets specifically designed for the Text-to-SQL task — the challenge of converting natural language questions into SQL queries. As a critical component of natural language interfaces to databases (NLIDB), Text2SQL plays a vital role in enabling users to interact with data using everyday language.

This repository aims to provide researchers, developers, and practitioners with a comprehensive list of datasets that support the development and evaluation of Text2SQL models. Whether you’re exploring schema linking, complex SQL generation, cross-domain generalization, or conversational query generation, you’ll find relevant datasets here to accelerate your work.

We welcome contributions to keep this list up-to-date and useful for the community.

## 🧪 Evaluation Benchmarks

| Dataset   | Link                                                | Desc                                     |
|-----------|-----------------------------------------------------------|-------------------------------------------------------------|
| WikiSQL   | [[paper](https://arxiv.org/pdf/1709.00103)][[dataset](https://github.com/salesforce/WikiSQL)]      | Single-table, single-turn, simple SQL queries         |
| Spider    | [[paper](https://arxiv.org/pdf/1809.08887)]                                                                                  | Complex SQL, cross-domain, multi-table queries |
| SParC     | [[paper](https://ar5iv.labs.arxiv.org/html/1906.02285)]                         | Cross-domain, multi-turn, based on Spider schema |
| CoSQL     | [[paper](https://ar5iv.labs.arxiv.org/html/1909.05378)]               | Cross-domain, multi-turn, with natural dialogs and user feedback |
| BIRD      | [[paper](https://arxiv.org/pdf/2305.03111)]                                                                                  | Large-scale, cross-domain, realistic business questions with complex SQL |


## 🆕 Latest Datasets (2025)

Recent datasets that introduce new challenges such as data synthesis, error correction, and ambiguous query resolution. These datasets reflect the newest trends and tasks in Text2SQL research.

| Dataset                  | Link                                                                                                          | Desc |
|--------------------------|---------------------------------------------------------------------------------------------------------------|------|
| synthetic_text_to_sql | [dataset](https://huggingface.co/datasets/gretelai/synthetic_text_to_sql)                             | Large-scale synthetic Text2SQL dataset |
| TINYSQL             | [paper](https://arxiv.org/html/2503.12730) [[HF](https://huggingface.co/collections/withmartian/tinysql-6760e92748b63fa56a6ffc9f)] | Small, diverse benchmark for lightweight evaluation |
| NL2SQL-Bugs         | [paper](https://arxiv.org/pdf/2503.11984)                                                                    | Dataset with extensive SQL syntax errors for robustness testing |
| OmniSQL            | [paper](https://arxiv.org/html/2503.02240)                                                                    | Massively synthetic SQL corpus built via templated generation |
| PRACTIQ              | [paper](https://arxiv.org/html/2410.11076)                                                                    | Focused on resolving vague and ambiguous natural language queries |

## 🗂️ Datasets

These datasets focus on specific domains such as healthcare, finance, programming, and linguistics. They help evaluate how well Text2SQL systems generalize to specialized fields or languages.

| Dataset        | Link                                                                                      | Desc |
|----------------|-------------------------------------------------------------------------------------------|------|
| EHRSQL     | [paper](https://arxiv.org/html/2301.07695)                                                | Healthcare domain, built from extensive user surveys |
| BEAVER     | [paper](https://arxiv.org/html/2409.02038)                                                | Business and accounting domain |
| SEDE      | [paper](https://ar5iv.labs.arxiv.org/html/2106.05006)                                     | Software engineering domain, Stack Exchange schemas |
| Spider-DK  | [paper](https://ar5iv.labs.arxiv.org/html/2109.05157)                                     | Domain knowledge-enhanced Spider variant |
| Spider-Syn| [paper](https://ar5iv.labs.arxiv.org/html/2106.01065)                                     | Synonym-augmented Spider version |
| TURSpider  | [paper](https://ieeexplore.ieee.org/document/10753591)                                    | Turkish language version of Spider |
| BookSQL    | [paper](https://arxiv.org/html/2406.07860)                                                | Finance and accounting QA over book data |
| Archer     | [paper](https://arxiv.org/html/2402.12554)                                                | Mathematics and set theory domain |
| UNITE      | [paper](https://ar5iv.labs.arxiv.org/html/2305.16265)                                     | Unified benchmark combining Spider, SParC, CoSQL, etc. |
