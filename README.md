# russian-slovak-homonymy-dataset
This repository contains a curated dataset of Russian–Slovak lexical equivalents and interlingual homonyms for linguistic research and embedding-based predictive didactics. The dataset comprises 300 Russian–Slovak lexical pairs, evenly divided into 150 translation equivalents and 150 interlingual homonyms. The lexical data are provided in CSV format and organized into two files (equivalents_ru_sk.csv; homonyms_ru_sk.csv).

The repository also includes item-level risk metadata derived from an embedding-based typology. This information is provided in item_risk_classification.csv, which assigns selected test items to low-risk and high-risk categories and serves as the basis for learner-based validation.

In addition, anonymized learner response data from an experimental study based on the lexical dataset are included. These responses are provided as a binary-coded CSV file (student_response_data_binary.csv), representing learner performance on selected lexical items.

Repository structure
├── equivalents_ru_sk.csv          # Russian–Slovak translation equivalents (low-risk baseline)
├── homonyms_ru_sk.csv             # Russian–Slovak interlingual homonyms
├── item_risk_classification.csv   # Item-level low-risk / high-risk classification
├── student_response_data_binary.csv  # Anonymized learner responses (binary-coded)
├── README.md
├── LICENSE
└── .gitignore
