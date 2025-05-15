# Awesome-Text2SQL-Dataset
Awesome-Text2SQL-Dataset is a curated collection of datasets specifically designed for the Text-to-SQL task — the challenge of converting natural language questions into SQL queries. As a critical component of natural language interfaces to databases (NLIDB), Text2SQL plays a vital role in enabling users to interact with data using everyday language.

This repository aims to provide researchers, developers, and practitioners with a comprehensive list of datasets that support the development and evaluation of Text2SQL models. Whether you’re exploring schema linking, complex SQL generation, cross-domain generalization, or conversational query generation, you’ll find relevant datasets here to accelerate your work.

We welcome contributions to keep this list up-to-date and useful for the community.

## 🆕 Latest Datasets (2025)

Recent datasets that introduce new challenges such as data synthesis, error correction, and ambiguous query resolution. These datasets reflect the newest trends and tasks in Text2SQL research.

| Dataset                  | Link                                                                                                          | Desc |
|--------------------------|---------------------------------------------------------------------------------------------------------------|------|
| TINYSQL             | [[Paper](https://arxiv.org/html/2503.12730)][[Dateset](https://huggingface.co/collections/withmartian/tinysql-6760e92748b63fa56a6ffc9f)] | Small, diverse benchmark for lightweight evaluation |
| NL2SQL-Bugs         | [[Paper](https://arxiv.org/pdf/2503.11984)][[Dateset](https://github.com/HKUSTDial/NL2SQL-Bugs-Benchmark)]                                                                  | Dataset with extensive SQL syntax errors for robustness testing |
| OmniSQL            | [[Paper](https://arxiv.org/html/2503.02240)][[Dateset](https://huggingface.co/datasets/seeklhy/SynSQL-2.5M)]                                                                 | Massively synthetic SQL corpus built via templated generation |
| synthetic_text_to_sql | [[Dataset](https://huggingface.co/datasets/gretelai/synthetic_text_to_sql)]                             | Large-scale synthetic Text2SQL dataset |

## 🗂️ Datasets

These datasets focus on specific domains such as healthcare, finance, programming, and linguistics. They help evaluate how well Text2SQL systems generalize to specialized fields or languages.

| Dataset        | Link                                                                                                                   | Desc                         |
|------------|----------------------------------------------------------------------------------------------------------------------------|------------------------------|
| WikiSQL    | [[paper](https://arxiv.org/pdf/1709.00103.pdf)][[dataset](https://github.com/salesforce/WikiSQL)]                          |2017/09, Single-table, single-turn, simple SQL queries         |
| Spider 1.0 |[[paper](https://arxiv.org/pdf/1809.08887.pdf)][[Leaderboard](https://yale-lily.github.io/spider)]                          | 2018/09, Complex SQL, cross-domain, multi-table queries |
| SParC      |[[paper](https://arxiv.org/pdf/1906.02285.pdf)][[Leaderboard](https://yale-lily.github.io/sparc)]                           |2019/06, Cross-domain, multi-turn, based on Spider schema |
|CSpider     |[[paper](https://arxiv.org/pdf/1906.02285.pdf)][[Leaderboard](https://taolusi.github.io/CSpider-explorer/)]                 |2019/09,  |
| CoSQL      | [[Paper](https://ar5iv.labs.arxiv.org/html/1909.05378)][[Leaderboard](https://yale-lily.github.io/cosql)]                  |2019/09,  Cross-domain, multi-turn, with natural dialogs and user feedback |
|KaggleDBQA  |[[paper](https://arxiv.org/abs/2106.11455)][[dataset](https://github.com/Chia-Hsuan-Lee/KaggleDBQA/)]                       |2021/06,|
| Spider-Syn | [[Paper](https://ar5iv.labs.arxiv.org/html/2106.01065)][[dataset](https://github.com/ygan/Spider-Syn)]                     | 2021/06, Synonym-augmented Spider version |
| SEDE       |[[Paper](https://ar5iv.labs.arxiv.org/html/2106.05006)][[dataset](https://github.com/hirupert/sede)]                        | 2021/06, Software engineering domain, Stack Exchange schemas |
|CHASE       |[[paper](https://aclanthology.org/2021.acl-long.180.pdf)][[dataset](https://github.com/xjtu-intsoft/chase)]                 |2021/08,|
| Spider-DK  | [[Paper](https://ar5iv.labs.arxiv.org/html/2109.05157)]                                                                    | 2021/09, Domain knowledge-enhanced Spider variant |
| EHRSQL     |[[Paper](https://arxiv.org/html/2301.07695)][[dataset](https://github.com/glee4810/EHRSQL)]                                 | 2023/01, built from extensive user surveys |
|BIRD-SQL    |[[paper](https://arxiv.org/pdf/2305.03111.pdf)][[Leaderboard](https://bird-bench.github.io/)]                               |2023/05,|
| UNITE      | [[Paper](https://ar5iv.labs.arxiv.org/html/2305.16265)][[dataset](https://github.com/awslabs/unified-text2sql-benchmark)]] |2023/05, Unified benchmark combining Spider, SParC, CoSQL, etc. |
| Archer     | [[Paper](https://arxiv.org/html/2402.12554)]  [[Leaderboard](https://sig4kg.github.io/archer-bench/)]                      | 2024/02, Mathematics and set theory domain | 
| BookSQL    | [[Paper](https://arxiv.org/html/2406.07860)][[dataset](https://github.com/Exploration-Lab/BookSQL)]]                       | 2024/06, Finance and accounting QA over book data |
|Spider 2.0  |[[paper](https://spider2-sql.github.io/)] [[Leaderboard](https://spider2-sql.github.io/)]                                   |2024/08|
| BEAVER     |[[Paper](https://arxiv.org/html/2409.02038)[[dataset](https://github.com/peterbaile/beaver)]]                               | 2024/09,  |
| PRACTIQ    | [[Paper](https://arxiv.org/html/2410.11076)]                                                                               |2024/10, Focused on resolving vague and ambiguous natural language queries |
| TURSpider  | [[Paper](https://ieeexplore.ieee.org/document/10753591)][[dataset](https://github.com/alibugra/TURSpider)]                 | 2024/11，Turkish language version of Spider |
