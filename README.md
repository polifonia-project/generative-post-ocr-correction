# generative-post-ocr-correction
A repository for generative post-ocr correction datasets and models

# Datasets

## Benchmarks aligned and segmented
To evaluate the performance our generative models, we used 8 datasets that are part of 2 standard post-OCR benchmarks (*[ICDAR2019](https://sites.google.com/view/icdar2019-postcorrectionocr)* and *[ICDAR2017](https://sites.google.com/view/icdar2017-postcorrectionocr?authuser=0)*) and a recently released one (*[Gutenberg-HathiTrust Parallel Corpus](https://databank.illinois.edu/datasets/IDB-1685085)*, GHT).
The selected datasets cover three languages i.e. English, French and German; have texts from different sources, including monographs and periodicals; and contain different levels of errors, ranging from $0.24$ to $0.02$ CER.
The corresponding files are available in the ./data folder.

| dataset                       | lang | split | \#items | \#words | $\mu$ CER | $\sigma$ CER | $\mu$ WER | $\sigma$ WER |
|-------------------------------|------|-------|---------|---------|-----------|--------------|-----------|--------------|
| GHT-high        | EN   | train | 73654   | 4120950 | 0.07      | 0.07         | 0.15      | 0.11         |
| GHT-high       | EN   | dev   | 9189    | 512985  | 0.07      | 0.07         | 0.15      | 0.11         |
| GHT-high       | EN   | test  | 9255    | 514495  | 0.07      | 0.07         | 0.15      | 0.11         |
| GHT-low        | EN   | train | 39782   | 2234299 | 0.06      | 0.06         | 0.13      | 0.1          |
| GHT-low        | EN   | dev   | 4922    | 274304  | 0.06      | 0.06         | 0.13      | 0.1          |
| GHT-low        | EN   | test  | 4917    | 274556  | 0.06      | 0.06         | 0.13      | 0.1          |
| ICDAR2019                     | DE   | dev   | 7148    | 377689  | 0.23      | 0.09         | 0.77      | 0.17         |
| ICDAR2019                     | DE   | test  | 15258   | 923494  | 0.24      | 0.09         | 0.76      | 0.22         |
| ICDAR2019                     | DE   | train | 40510   | 2441899 | 0.24      | 0.1          | 0.74      | 0.2          |
| ICDAR2019                     | FR   | dev   | 2509    | 70752   | 0.07      | 0.12         | 0.19      | 0.21         |
| ICDAR2019                     | FR   | test  | 4296    | 290160  | 0.08      | 0.14         | 0.22      | 0.22         |
| ICDAR2019                     | FR   | train | 14218   | 1084265 | 0.07      | 0.11         | 0.22      | 0.22         |
| ICDAR2017-mono | EN   | dev   | 2762    | 149670  | 0.08      | 0.08         | 0.24      | 0.16         |
| ICDAR2017-mono | EN   | test  | 3316    | 275874  | 0.04      | 0.06         | 0.15      | 0.19         |
| ICDAR2017-mono | EN   | train | 15657   | 1100996 | 0.05      | 0.09         | 0.13      | 0.16         |
| ICDAR2017-per  | EN   | dev   | 1297    | 71933   | 0.09      | 0.11         | 0.22      | 0.18         |
| ICDAR2017-per  | EN   | test  | 2481    | 122002  | 0.1       | 0.13         | 0.23      | 0.22         |
| ICDAR2017-per  | EN   | train | 7354    | 441563  | 0.09      | 0.12         | 0.21      | 0.2          |
| ICDAR2017-mono | FR   | dev   | 3334    | 166686  | 0.02      | 0.04         | 0.09      | 0.12         |
| ICDAR2017-mono | FR   | test  | 2547    | 124782  | 0.02      | 0.04         | 0.09      | 0.12         |
| ICDAR2017-mono | FR   | train | 18893   | 1031749 | 0.02      | 0.04         | 0.1       | 0.14         |
| ICDAR2017-per  | FR   | dev   | 1874    | 80326   | 0.06      | 0.12         | 0.12      | 0.16         |
| ICDAR2017-per  | FR   | test  | 4272    | 205639  | 0.04      | 0.08         | 0.14      | 0.18         |
| ICDAR2017-per  | FR   | train | 10622   | 424017  | 0.07      | 0.11         | 0.2       | 0.21         |



## Silver datasets

### English

### French

### German


# Models

## Enlgish monolongual

## Multilingual
