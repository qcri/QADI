# QADI
QCRI Arabic Dialect Identification (QADI)

Country level Arabic dialect identification (DI) dataset.
It provides a collection for benchmarking DI task.

## QADI Dataset
The dataset contains 540,590 tweets from 18 Arab countries. The data is distributed according to the following table§:


| Country*  | Train | Test|
|:-------|:-----:|:-----:|
| AE | 27,819 | 192 |
| BH | 28,295 | 184 |
| DZ | 17,603 | 170 |
| EG | 67,783 | 200 |
| IQ | 18,367 | 178 |
| JO | 34,109 | 180 |
| KW | 49,963 | 190 |
| LB | 38,386 | 194 |
| LY | 40,883 | 169 |
| MA | 12,813 | 178 |
| OM | 24,786 | 169 |
| PL | 48,641 | 173 |
| QA | 36,675 | 198 |
| SA | 35,396 | 199 |
| SD | 16,251 | 188 |
| SY | 18,317 | 194 |
| TN | 12,940 | 154 |
| YE | 11,563 | 193 |

\* Country names are provided using [ISO-3166-1](https://en.wikipedia.org/wiki/ISO_3166-1_alpha-2) codes.

## Download the dataset
To download the data, after cloning the repository or downloading its content. The dataset files contains ids for the all the tweets identified as from the designated country. you may used `twarc` or other Twitter Scraping tools to hydrate the tweets. 

```twarc dataset/tweetsCountryID.txt```

The tweets are arranged per country. Each file is a list of ids for the tweets from the designated country.
 

## Contact

* Hamdy Mubarak (hmubarak at hbku dot edu dot qa)
* Ahmed Abdelali (aabdelali at hbku dot edu dot qa)
* Kareem Darwish (hmubarak at hbku dot edu dot qa)
* Younes Samih (ysamih at hbku dot edu dot qa)
* Sabit Hassan (sahassan2 at hbku dot edu dot qa)

## Reference

