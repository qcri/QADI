# QADI
QCRI Arabic Dialect Identification (QADI)

Country level Arabic dialect identification (DI) dataset.
The dataset provide a dataset for benchmarking DI task.

## QADI Dataset
The dataset contains 540590 tweets from 18 country, representing most contries from Arab world.
The data is distributed accordingly:


| Country*  | Train | Test|
|:-------|:-----:|:-----:|
| AE | 27819 | 192 |
| BH | 28295 | 184 |
| DZ | 17603 | 170 |
| EG | 67783 | 200 |
| IQ | 18367 | 178 |
| JO | 34109 | 180 |
| KW | 49963 | 190 |
| LB | 38386 | 194 |
| LY | 40883 | 169 |
| MA | 12813 | 178 |
| OM | 24786 | 169 |
| PL | 48641 | 173 |
| QA | 36675 | 198 |
| SA | 35396 | 199 |
| SD | 16251 | 188 |
| SY | 18317 | 194 |
| TN | 12940 | 154 |
| YE | 11563 | 193 |

\* Country names are provided using [ISO-3166-1](https://en.wikipedia.org/wiki/ISO_3166-1_alpha-2) codes.

## Download the dataset
To download the data, you may used `twarc` to hydrate the tweets. 

```twarc dataset/tweetsCountryID.txt```

The tweets are arranged per country. Each file is a list of ids for the tweets from the designated country.
 

## Contact

* Hamdy Mubarak (hmubarak at hbku dot edu dot qa)
* Ahmed Abdelali (aabdelali at hbku dot edu dot qa)
* Kareem Darwish (hmubarak at hbku dot edu dot qa)
* Younes Samih (ysamih at hbku dot edu dot qa)
* Sabit Hassan (sahassan2 at hbku dot edu dot qa)

## Reference

