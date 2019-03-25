## Determine the population genetic structure of s.aurita and s. maderensis using Radseq
### Dataset needed to perform the analysis
#### 1. Radseq Data Sets sequenced on an Illumina HiSeq 2000 PE150 from six populations obtained from West Africa
 ||        |            |                   |           |          |                 |              |             |       |        |              |   |   |   |
|--------|------------|-------------------|-----------|----------|-----------------|--------------|-------------|-------|--------|--------------|---|---|---|
| Sample | country    | Geographical site | Longitude | Latitude | Collection date | Species      | Fork length | Girth | Weight | Total Length |   |   |   |
| GH1    | Ghana      | Sekondi-Takoradi  | 0.994     | 5.898    | 2016            | S.aurita     | 15          | 9     | 43.2   | 20           |   |   |   |
| GH4    | Ghana      | Sekondi-Takoradi  | 0.994     | 5.898    | 2016            | S.aurita     | 16.5        | 9     | 53.6   | 17           |   |   |   |
| GH2    | Ghana      | Sekondi-Takoradi  | 0.994     | 5.898    | 2016            | S.aurita     | 15          | 8.5   | 45.9   | 18           |   |   |   |
| GH5    | Ghana      | Sekondi-Takoradi  | 0.994     | 5.898    | 2016            | S.aurita     | 15          | 8.5   | 44.3   | 19           |   |   |   |
| GH6    | Ghana      | Sekondi-Takoradi  | 0.994     | 5.898    | 2016            | S.aurita     | 14.5        | 8     | 44.2   | 17           |   |   |   |
| GH7    | Ghana      | Sekondi-Takoradi  | 0.994     | 5.898    | 2016            | S.aurita     | 17.5        | 9     | 59.4   | 17           |   |   |   |
| GH8    | Ghana      | Sekondi-Takoradi  | 0.994     | 5.898    | 2016            | S.aurita     | 15          | 8.5   | 46.4   | 19.6         |   |   |   |
| GH9    | Ghana      | Sekondi-Takoradi  | 0.994     | 5.898    | 2016            | S.aurita     | 16          | 8.5   | 41.2   | 17.4         |   |   |   |
| GH10   | Ghana      | Sekondi-Takoradi  | 0.994     | 5.898    | 2016            | S.aurita     | 16.5        | 9.5   | 55.8   | 18           |   |   |   |
| GH5    | Ghana      | Sekondi-Takoradi  | 0.994     | 5.898    | 2016            | S.aurita     | 12          | 10    | 44.3   | 19           |   |   |   |
| GH11   | Ghana      | Sekondi-Takoradi  | 0.994     | 5.898    | 2016            | S.aurita     | 11.5        | 6     | 17.6   | 13           |   |   |   |
| GH12   | Ghana      | Sekondi-Takoradi  | 0.994     | 5.898    | 2016            | S.aurita     | 11.5        | 6     | 17.6   | 13           |   |   |   |
| GH13   | Ghana      | Sekondi-Takoradi  | 0.994     | 5.898    | 2016            | S.aurita     | 11          | 6     | 15.7   | 12.6         |   |   |   |
| GH14   | Ghana      | Sekondi-Takoradi  | 0.994     | 5.898    | 2016            | S.aurita     | 11.5        | 6     | 16.1   | 13           |   |   |   |
| GH15   | Ghana      | Sekondi-Takoradi  | 0.994     | 5.898    | 2016            | S.aurita     | 12          | 6     | 15.3   | 12.5         |   |   |   |
| GH43   | Ghana      | Sekondi-Takoradi  | 0.994     | 5.898    | 2016            | S.aurita     | 18          | 10    | 23.6   | 20.5         |   |   |   |
| GH44   | Ghana      | Sekondi-Takoradi  | 0.994     | 5.898    | 2016            | S.aurita     | 17          | 10    | 71.9   | 19.6         |   |   |   |
| GH45   | Ghana      | Sekondi-Takoradi  | 0.994     | 5.898    | 2016            | S.aurita     | 17          | 9.5   | 68.3   | 20.5         |   |   |   |
| GH46   | Ghana      | Sekondi-Takoradi  | 0.994     | 5.898    | 2016            | S.aurita     | 17          | 10    | 66.7   | 20           |   |   |   |
| GH47   | Ghana      | Sekondi-Takoradi  | 0.994     | 5.898    | 2016            | S.aurita     | 17          | 10    | 60.3   | 19           |   |   |   |
| T2     | Togo       | Harbour           | 1.301     | 6.151    | 2016            | S.aurita     | 15          | 8.5   | 45     | 17.5         |   |   |   |
| T3     | Togo       | Harbour           | 1.301     | 6.151    | 2016            | S.aurita     | 17          | 9.5   | 68     | 17           |   |   |   |
| T4     | Togo       | Harbour           | 1.301     | 6.151    | 2016            | S.aurita     | 16          | 9.5   | 62     | 19           |   |   |   |
| T5     | Togo       | Harbour           | 1.301     | 6.151    | 2016            | S.aurita     | 15.5        | 9     | 53     | 19           |   |   |   |
| T6     | Togo       | Harbour           | 1.301     | 6.151    | 2016            | S.aurita     | 15          | 8     | 41     | 18           |   |   |   |
| T7     | Togo       | Harbour           | 1.301     | 6.151    | 2016            | S.aurita     | 15.5        | 8     | 50     | 17           |   |   |   |
| T8     | Togo       | Harbour           | 1.301     | 6.151    | 2016            | S.aurita     | 15          | 9     | 48     | 17.5         |   |   |   |
| T9     | Togo       | Harbour           | 1.301     | 6.151    | 2016            | S.aurita     | 16          | 10    | 61     | 17.5         |   |   |   |
| T10    | Togo       | Harbour           | 1.301     | 6.151    | 2016            | S.aurita     | 15          | 9     | 40     | 19           |   |   |   |
| T41    | Togo       | Harbour           | 1.301     | 6.151    | 2016            | S.aurita     | 18          | 10    | 82     | 17           |   |   |   |
| T44    | Togo       | Harbour           | 1.301     | 6.151    | 2016            | S.aurita     | 16          | 9     | 60     | 20.5         |   |   |   |
| T45    | Togo       | Harbour           | 1.301     | 6.151    | 2016            | S.aurita     | 16.5        | 8     | 60     | 18.5         |   |   |   |
| T47    | Togo       | Harbour           | 1.301     | 6.151    | 2016            | S.aurita     | 14.5        | 9     | 40     | 16.5         |   |   |   |
| T21    | Togo       | Harbour           | 1.301     | 6.151    | 2016            | S.aurita     | 17.5        | 10.5  | 70     | 17.5         |   |   |   |
| T22    | Togo       | Harbour           | 1.301     | 6.151    | 2016            | S.aurita     | 16.5        | 9     | 61     | 20           |   |   |   |
| T23    | Togo       | Harbour           | 1.301     | 6.151    | 2016            | S.aurita     | 16.5        | 8     | 38     | 19           |   |   |   |
| T24    | Togo       | Harbour           | 1.301     | 6.151    | 2016            | S.aurita     | 16          | 9     | 59     | 16.5         |   |   |   |
| T25    | Togo       | Harbour           | 1.301     | 6.151    | 2016            | S.aurita     | 16          | 8.5   | 52     | 19           |   |   |   |
| T26    | Togo       | Harbour           | 1.301     | 6.151    | 2016            | S.aurita     | 17.5        | 8     | 47     | 18.5         |   |   |   |
| M70    | Mauritania | Nouakchott        | -15.978   | 18.0841  | 2016            | S.aurita     | 26.4        | 8.3   | 306    | 0            |   |   |   |
| M74    | Mauritania | Nouakchott        | -15.978   | 18.0841  | 2016            | S.aurita     | 26.1        | 8.1   | 304    | 0            |   |   |   |
| M66    | Mauritania | Nouakchott        | -15.978   | 18.0841  | 2016            | S.aurita     | 28.5        | 8.2   | 360    | 0            |   |   |   |
| M60    | Mauritania | Nouakchott        | -15.978   | 18.0841  | 2016            | S.aurita     | 27.3        | 8.2   | 330    | 0            |   |   |   |
| M58    | Mauritania | Nouakchott        | -15.978   | 18.0841  | 2016            | S.aurita     | 27.5        | 8     | 330    | 0            |   |   |   |
| M41    | Mauritania | Nouakchott        | -15.978   | 18.0841  | 2016            | S.aurita     | 32.5        | 9.5   | 527    | 0            |   |   |   |
| M1     | Mauritania | Nouakchott        | -15.978   | 18.0841  | 2016            | S.aurita     | 24          | 8.4   | 231    | 0            |   |   |   |
| M2     | Mauritania | Nouakchott        | -15.978   | 18.0841  | 2016            | S.aurita     | 24.7        | 8.3   | 259    | 0            |   |   |   |
| M3     | Mauritania | Nouakchott        | -15.978   | 18.0841  | 2016            | S.aurita     | 23.9        | 6.5   | 235    | 0            |   |   |   |
| M4     | Mauritania | Nouakchott        | -15.978   | 18.0841  | 2016            | S.aurita     | 24.5        | 8     | 258    | 0            |   |   |   |
| M5     | Mauritania | Nouakchott        | -15.978   | 18.0841  | 2016            | S.aurita     | 25.2        | 8.5   | 252    | 0            |   |   |   |
| M6     | Mauritania | Nouakchott        | -15.978   | 18.0841  | 2016            | S.aurita     | 22.5        | 7.5   | 202    | 0            |   |   |   |
| M8     | Mauritania | Nouakchott        | -15.978   | 18.0841  | 2016            | S.aurita     | 25.2        | 8.5   | 269    | 0            |   |   |   |
| M10    | Mauritania | Nouakchott        | -15.978   | 18.0841  | 2016            | S.aurita     | 26.6        | 9     | 311    | 0            |   |   |   |
| M50    | Mauritania | Nouakchott        | -15.978   | 18.0841  | 2016            | S.aurita     | 33          | 8.5   | 510    | 0            |   |   |   |
| M58    | Mauritania | Nouakchott        | -15.978   | 18.0841  | 2016            | S.aurita     | 27.5        | 8     | 330    | 0            |   |   |   |
| M59    | Mauritania | Nouakchott        | -15.978   | 18.0841  | 2016            | S.aurita     | 26.8        | 8.5   | 320    | 0            |   |   |   |
| M60    | Mauritania | Nouakchott        | -15.978   | 18.0841  | 2016            | S.aurita     | 27.3        | 8.2   | 330    | 0            |   |   |   |
| M66    | Mauritania | Nouakchott        | -15.978   | 18.0841  | 2016            | S.aurita     | 28.5        | 8.2   | 360    | 0            |   |   |   |
| S1     | Senegal    | Fass Boue         | -16.85    | 14.179   | 2016            | S.aurita     | 25.5        | 6.2   | 260.7  | 30.8         |   |   |   |
| S2     | Senegal    | Fass Boue         | -16.85    | 14.179   | 2016            | S.aurita     | 27.5        | 6     | 296.7  | 32.8         |   |   |   |
| S3     | Senegal    | Fass Boue         | -16.85    | 14.179   | 2016            | S.aurita     | 26.5        | 6.2   | 245.5  | 31.5         |   |   |   |
| S4     | Senegal    | Fass Boue         | -16.85    | 14.179   | 2016            | S.aurita     | 25.1        | 6.5   | 243.3  | 30.7         |   |   |   |
| S5     | Senegal    | Fass Boue         | -16.85    | 14.179   | 2016            | S.aurita     | 25.7        | 6     | 246.2  | 31.1         |   |   |   |
| S6     | Senegal    | Fass Boue         | -16.85    | 14.179   | 2016            | S.aurita     | 26.5        | 6.5   | 281.3  | 31.8         |   |   |   |
| S7     | Senegal    | Fass Boue         | -16.85    | 14.179   | 2016            | S.aurita     | 26.7        | 6     | 252.7  | 32           |   |   |   |
| S8     | Senegal    | Fass Boue         | -16.85    | 14.179   | 2016            | S.aurita     | 26.8        | 6.5   | 231.9  | 31.5         |   |   |   |
| S9     | Senegal    | Fass Boue         | -16.85    | 14.179   | 2016            | S.aurita     | 27.4        | 6.5   | 278.8  | 32.5         |   |   |   |
| S10    | Senegal    | Fass Boue         | -16.85    | 14.179   | 2016            | S.aurita     | 26.7        | 6.1   | 291.6  | 32.3         |   |   |   |
| S21    | Senegal    | Fass Boue         | -16.85    | 14.179   | 2016            | S.aurita     | 25          | 6.3   | 302.1  | 32.1         |   |   |   |
| S22    | Senegal    | Fass Boue         | -16.85    | 14.179   | 2016            | S.aurita     | 25.5        | 6.5   | 251.4  | 31           |   |   |   |
| S23    | Senegal    | Fass Boue         | -16.85    | 14.179   | 2016            | S.aurita     | 27.2        | 6.3   | 285.2  | 32.4         |   |   |   |
| S25    | Senegal    | Fass Boue         | -16.85    | 14.179   | 2016            | S.aurita     | 27          | 5.7   | 281.4  | 32.5         |   |   |   |
| S27    | Senegal    | Fass Boue         | -16.85    | 14.179   | 2016            | S.aurita     | 25.7        | 6     | 210.8  | 30.2         |   |   |   |
| S28    | Senegal    | Fass Boue         | -16.85    | 14.179   | 2016            | S.aurita     | 25          | 6.5   | 231.2  | 30           |   |   |   |
| S38    | Senegal    | Fass Boue         | -16.85    | 14.179   | 2016            | S.aurita     | 25.3        | 5.7   | 216.6  | 28.1         |   |   |   |
| S24    | Senegal    | Fass Boue         | -16.85    | 14.179   | 2016            | S.aurita     | 26.2        | 6.4   | 259    | 31.8         |   |   |   |
| G1     | Guinea     | BOULBINET         | -11.352   | 9.932    | 2017            | S.aurita     | 17          | 4     | 61.1   | 20           |   |   |   |
| G11    | Guinea     | BOULBINET         | -11.352   | 9.932    | 2017            | S.aurita     | 15          | 4.5   | 47.1   | 17.5         |   |   |   |
| G13    | Guinea     | BOULBINET         | -11.352   | 9.932    | 2017            | S.aurita     | 15.5        | 4.5   | 53.5   | 18.5         |   |   |   |
| G14    | Guinea     | BOULBINET         | -11.352   | 9.932    | 2017            | S.aurita     | 18          | 4     | 83     | 20           |   |   |   |
| G15    | Guinea     | BOULBINET         | -11.352   | 9.932    | 2017            | S.aurita     | 16.5        | 4     | 52.3   | 19           |   |   |   |
| G16    | Guinea     | BOULBINET         | -11.352   | 9.932    | 2017            | S.aurita     | 17          | 4.5   | 59.5   | 19.5         |   |   |   |
| G19    | Guinea     | BOULBINET         | -11.352   | 9.932    | 2017            | S.aurita     | 16          | 5     | 51.1   | 19           |   |   |   |
| G2     | Guinea     | BOULBINET         | -11.352   | 9.932    | 2017            | S.aurita     | 16.5        | 2.8   | 57.4   | 20           |   |   |   |
| G21    | Guinea     | BOULBINET         | -11.352   | 9.932    | 2017            | S.aurita     | 17          | 4     | 65.5   | 21           |   |   |   |
| G22    | Guinea     | BOULBINET         | -11.352   | 9.932    | 2017            | S.aurita     | 19          | 5     | 78.1   | 22.5         |   |   |   |
| G23    | Guinea     | BOULBINET         | -11.352   | 9.932    | 2017            | S.aurita     | 16          | 5     | 56.3   | 18           |   |   |   |
| G25    | Guinea     | BOULBINET         | -11.352   | 9.932    | 2017            | S.aurita     | 18          | 5     | 69.9   | 18.5         |   |   |   |
| G31    | Guinea     | BOULBINET         | -11.352   | 9.932    | 2017            | S.aurita     | 18          | 5     | 59     | 19           |   |   |   |
| G37    | Guinea     | BOULBINET         | -11.352   | 9.932    | 2017            | S.aurita     | 16          | 4     | 59     | 21.5         |   |   |   |
| G43    | Guinea     | BOULBINET         | -11.352   | 9.932    | 2017            | S.aurita     | 16          | 4.5   | 56.2   | 19.5         |   |   |   |
| G1     | Guinea     | BOULBINET         | -11.352   | 9.932    | 2017            | S.aurita     | 17          | 4     | 61.1   | 20           |   |   |   |
| G2     | Guinea     | BOULBINET         | -11.352   | 9.932    | 2017            | S.aurita     | 16.5        | 2.8   | 57.4   | 20           |   |   |   |
| G3     | Guinea     | BOULBINET         | -11.352   | 9.932    | 2017            | S.aurita     | 16          | 4     | 56.4   | 19.5         |   |   |   |
| G4     | Guinea     | BOULBINET         | -11.352   | 9.932    | 2017            | S.aurita     | 16.5        | 5     | 63.5   | 20           |   |   |   |
| G5     | Guinea     | BOULBINET         | -11.352   | 9.932    | 2017            | S.aurita     | 16          | 4.5   | 57.2   | 20           |   |   |   |
| ID     | Country    | Geographical site | Longitude | Latitude | Collection date | Species      | Fork length | Girth | Weight | Total Length |   |   |   |
| M7     | Mauritania | Nouakchott        | -15.978   | 18.0841  | 2016            | S.maderensis | 25.5        | 8.7   | 280    | 0            |   |   |   |
| M9     | Mauritania | Nouakchott        | -15.978   | 18.0841  | 2016            | S.maderensis | 26.9        | 8.6   | 321    | 0            |   |   |   |
| M75    | Mauritania | Nouakchott        | -15.978   | 18.0841  | 2016            | S.maderensis | 27.8        | 8.4   | 352    | 0            |   |   |   |
| M50    | Mauritania | Nouakchott        | -15.978   | 18.0841  | 2016            | S.maderensis | 33          | 8.5   | 510    | 0            |   |   |   |
| M42    | Mauritania | Nouakchott        | -15.978   | 18.0841  | 2016            | S.maderensis | 32.5        | 9.5   | 515    | 0            |   |   |   |
| M79    | Mauritania | Nouakchott        | -15.978   | 18.0841  | 2016            | S.maderensis | 25.7        | 8.3   | 286    | 0            |   |   |   |
| M80    | Mauritania | Nouakchott        | -15.978   | 18.0841  | 2016            | S.maderensis | 22.6        | 7.2   | 201    | 0            |   |   |   |
| M88    | Mauritania | Nouakchott        | -15.978   | 18.0841  | 2016            | S.maderensis | 22.5        | 7.1   | 185    | 0            |   |   |   |
| M89    | Mauritania | Nouakchott        | -15.978   | 18.0841  | 2016            | S.maderensis | 24.6        | 8.5   | 235    | 0            |   |   |   |
| M9     | Mauritania | Nouakchott        | -15.978   | 18.0841  | 2016            | S.maderensis | 26.9        | 8.6   | 321    | 0            |   |   |   |
| M25    | Mauritania | Nouakchott        | -15.978   | 18.0841  | 2016            | S.maderensis | 24.8        | 8.4   | 251    | 0            |   |   |   |
| M90    | Mauritania | Nouakchott        | -15.978   | 18.0841  | 2016            | S.maderensis | 25.4        | 8.3   | 275    | 0            |   |   |   |
| M98    | Mauritania | Nouakchott        | -15.978   | 18.0841  | 2016            | S.maderensis | 23.3        | 7.7   | 214    | 0            |   |   |   |
| M16    | Mauritania | Nouakchott        | -15.978   | 18.0841  | 2016            | S.maderensis | 24.5        | 8.6   | 244    | 0            |   |   |   |
| M99    | Mauritania | Nouakchott        | -15.978   | 18.0841  | 2016            | S.maderensis | 26.7        | 8.7   | 304    | 0            |   |   |   |
| M17    | Mauritania | Nouakchott        | -15.978   | 18.0841  | 2016            | S.maderensis | 25.3        | 7.6   | 265    | 0            |   |   |   |
| M14    | Mauritania | Nouakchott        | -15.978   | 18.0841  | 2016            | S.maderensis | 25.9        | 7.5   | 281    | 0            |   |   |   |
| M12    | Mauritania | Nouakchott        | -15.978   | 18.0841  | 2016            | S.maderensis | 26.5        | 8.6   | 298    | 0            |   |   |   |
| M85    | Mauritania | Nouakchott        | -15.978   | 18.0841  | 2016            | S.maderensis | 22.3        | 7.1   | 203    | 0            |   |   |   |
| S1     | Senegal    | Fass Boue         | -16.85    | 14.179   | 2016            | S.maderensis | 24          | 6.6   | 239.4  | 29.5         |   |   |   |
| S2     | Senegal    | Fass Boue         | -16.85    | 14.179   | 2016            | S.maderensis | 25          | 6.5   | 240.5  | 30           |   |   |   |
| S3     | Senegal    | Fass Boue         | -16.85    | 14.179   | 2016            | S.maderensis | 24.7        | 6.7   | 237.7  | 29.5         |   |   |   |
| S4     | Senegal    | Fass Boue         | -16.85    | 14.179   | 2016            | S.maderensis | 23.2        | 6     | 200.3  | 30.5         |   |   |   |
| S5     | Senegal    | Fass Boue         | -16.85    | 14.179   | 2016            | S.maderensis | 35.5        | 6.5   | 215.1  | 28.7         |   |   |   |
| S6     | Senegal    | Fass Boue         | -16.85    | 14.179   | 2016            | S.maderensis | 27.5        | 7.7   | 329.2  | 33.9         |   |   |   |
| S7     | Senegal    | Fass Boue         | -16.85    | 14.179   | 2016            | S.maderensis | 25.6        | 6.7   | 251.1  | 30.4         |   |   |   |
| S8     | Senegal    | Fass Boue         | -16.85    | 14.179   | 2016            | S.maderensis | 25.2        | 6.6   | 233.2  | 30.1         |   |   |   |
| S9     | Senegal    | Fass Boue         | -16.85    | 14.179   | 2016            | S.maderensis | 24.3        | 6.8   | 263.3  | 29.2         |   |   |   |
| S10    | Senegal    | Fass Boue         | -16.85    | 14.179   | 2016            | S.maderensis | 24.5        | 6.7   | 238.4  | 29.5         |   |   |   |
| S31    | Senegal    | Fass Boue         | -16.85    | 14.179   | 2016            | S.maderensis | 21.6        | 5.6   | 144.1  | 26.2         |   |   |   |
| S11    | Senegal    | Fass Boue         | -16.85    | 14.179   | 2016            | S.maderensis | 24          | 6.7   | 217.2  | 29           |   |   |   |
| S21    | Senegal    | Fass Boue         | -16.85    | 14.179   | 2016            | S.maderensis | 24.4        | 6.8   | 259.5  | 29.7         |   |   |   |
| S22    | Senegal    | Fass Boue         | -16.85    | 14.179   | 2016            | S.maderensis | 25.2        | 7     | 287.3  | 30.6         |   |   |   |
| S48    | Senegal    | Fass Boue         | -16.85    | 14.179   | 2016            | S.maderensis | 22.5        | 6     | 197.7  | 27.1         |   |   |   |
| S49    | Senegal    | Fass Boue         | -16.85    | 14.179   | 2016            | S.maderensis | 22.5        | 6     | 165.7  | 17           |   |   |   |
| S50    | Senegal    | Fass Boue         | -16.85    | 14.179   | 2016            | S.maderensis | 22.2        | 5.8   | 152.5  | 26.1         |   |   |   |
| S41    | Senegal    | Fass Boue         | -16.85    | 14.179   | 2016            | S.maderensis | 23.1        | 6     | 175    | 27.4         |   |   |   |
| S42    | Senegal    | Fass Boue         | -16.85    | 14.179   | 2016            | S.maderensis | 21.3        | 6     | 175.3  | 27.7         |   |   |   |
| S43    | Senegal    | Fass Boue         | -16.85    | 14.179   | 2016            | S.maderensis | 23          | 6.3   | 186.6  | 28.2         |   |   |   |
| G6     | Guinea     | BOULBINET         | -11.352   | 9.932    | 2017            | S.maderensis | 15          | 5     | 48.8   | 18           |   |   |   |
| G7     | Guinea     | BOULBINET         | -11.352   | 9.932    | 2017            | S.maderensis | 14.5        | 5     | 50.6   | 18           |   |   |   |
| G8     | Guinea     | BOULBINET         | -11.352   | 9.932    | 2017            | S.maderensis | 14          | 5     | 38.9   | 17           |   |   |   |
| G9     | Guinea     | BOULBINET         | -11.352   | 9.932    | 2017            | S.maderensis | 15          | 4.5   | 62.5   | 20           |   |   |   |
| G10    | Guinea     | BOULBINET         | -11.352   | 9.932    | 2017            | S.maderensis | 15          | 6     | 46.4   | 17           |   |   |   |
| G23    | Guinea     | BOULBINET         | -11.352   | 9.932    | 2017            | S.maderensis | 14          | 4.5   | 36     | 19.5         |   |   |   |
| G25    | Guinea     | BOULBINET         | -11.352   | 9.932    | 2017            | S.maderensis | 14.5        | 5     | 55.4   | 17           |   |   |   |
| G26    | Guinea     | BOULBINET         | -11.352   | 9.932    | 2017            | S.maderensis | 15.5        | 5     | 45.6   | 19           |   |   |   |
| G27    | Guinea     | BOULBINET         | -11.352   | 9.932    | 2017            | S.maderensis | 14.5        | 5.5   | 58.1   | 17           |   |   |   |
| G28    | Guinea     | BOULBINET         | -11.352   | 9.932    | 2017            | S.maderensis | 14.5        | 5     | 45.6   | 20           |   |   |   |
| G29    | Guinea     | BOULBINET         | -11.352   | 9.932    | 2017            | S.maderensis | 14.5        | 5     | 58.9   | 18.5         |   |   |   |
| G30    | Guinea     | BOULBINET         | -11.352   | 9.932    | 2017            | S.maderensis | 15          | 5     | 55.4   | 18           |   |   |   |
| G33    | Guinea     | BOULBINET         | -11.352   | 9.932    | 2017            | S.maderensis | 15          | 5.5   | 56.6   | 18           |   |   |   |
| G34    | Guinea     | BOULBINET         | -11.352   | 9.932    | 2017            | S.maderensis | 14.5        | 5     | 54.7   | 17           |   |   |   |
| G35    | Guinea     | BOULBINET         | -11.352   | 9.932    | 2017            | S.maderensis | 14          | 4.5   | 40.5   | 17           |   |   |   |
| G37    | Guinea     | BOULBINET         | -11.352   | 9.932    | 2017            | S.maderensis | 13.5        | 5     | 53     | 19           |   |   |   |
| G38    | Guinea     | BOULBINET         | -11.352   | 9.932    | 2017            | S.maderensis | 13.5        | 5     | 50.4   | 18           |   |   |   |
| G39    | Guinea     | BOULBINET         | -11.352   | 9.932    | 2017            | S.maderensis | 15          | 5     | 39.6   | 6.5          |   |   |   |
| G40    | Guinea     | BOULBINET         | -11.352   | 9.932    | 2017            | S.maderensis | 13          | 4.5   | 45     | 17           |   |   |   |
| N1     | Nigeria    |                   | 3.406     | 6.465    | 2016            | S.maderensis | 12.2        | 10    | 30     | 14.5         |   |   |   |
| N2     | Nigeria    |                   | 3.406     | 6.465    | 2016            | S.maderensis | 13.8        | 10.6  | 28     | 16.2         |   |   |   |
| N3     | Nigeria    |                   | 3.406     | 6.465    | 2016            | S.maderensis | 13.1        | 10.2  | 25     | 15.3         |   |   |   |
| N4     | Nigeria    |                   | 3.406     | 6.465    | 2016            | S.maderensis | 20.5        | 14    | 40     | 24.7         |   |   |   |
| N5     | Nigeria    |                   | 3.406     | 6.465    | 2016            | S.maderensis | 13.6        | 9     | 38     | 16.1         |   |   |   |
| N6     | Nigeria    |                   | 3.406     | 6.465    | 2016            | S.maderensis | 13.2        | 8.7   | 35     | 15.4         |   |   |   |
| N7     | Nigeria    |                   | 3.406     | 6.465    | 2016            | S.maderensis | 13.3        | 8.8   | 35     | 16.6         |   |   |   |
| N8     | Nigeria    |                   | 3.406     | 6.465    | 2016            | S.maderensis | 20.3        | 14.1  | 40     | 24.3         |   |   |   |
| N9     | Nigeria    |                   | 3.406     | 6.465    | 2016            | S.maderensis | 13.3        | 8.8   | 35     | 15.8         |   |   |   |
| N10    | Nigeria    |                   | 3.406     | 6.465    | 2016            | S.maderensis | 12.7        | 8.3   | 30     | 14.8         |   |   |   |
| N11    | Nigeria    |                   | 3.406     | 6.465    | 2016            | S.maderensis | 13.3        | 8.6   | 35     | 15.5         |   |   |   |
| N12    | Nigeria    |                   | 3.406     | 6.465    | 2016            | S.maderensis | 13.6        | 9.1   | 45     | 16.3         |   |   |   |
| N13    | Nigeria    |                   | 3.406     | 6.465    | 2016            | S.maderensis | 14.3        | 9.3   | 25     | 17           |   |   |   |
| N14    | Nigeria    |                   | 3.406     | 6.465    | 2016            | S.maderensis | 12.2        | 8     | 25     | 14           |   |   |   |
| N15    | Nigeria    |                   | 3.406     | 6.465    | 2016            | S.maderensis | 14.2        | 12.2  | 35     | 16.8         |   |   |   |
| N16    | Nigeria    |                   | 3.406     | 6.465    | 2016            | S.maderensis | 13.9        | 9.2   | 80     | 16.3         |   |   |   |
| N17    | Nigeria    |                   | 3.406     | 6.465    | 2016            | S.maderensis | 16.9        | 8.5   | 55     | 20.3         |   |   |   |
| N18    | Nigeria    |                   | 3.406     | 6.465    | 2016            | S.maderensis | 13.9        | 9     | 30     | 16.3         |   |   |   |
| N19    | Nigeria    |                   | 3.406     | 6.465    | 2016            | S.maderensis | 12.7        | 9     | 35     | 15           |   |   |   |
| N20    | Nigeria    |                   | 3.406     | 6.465    | 2016            | S.maderensis | 13.1        | 9.9   | 40     | 15.5         |   |   |   |
| T1     | Togo       | Harbour           | 1.301     | 6.151    | 2016            | S.maderensis | 21.5        | 13.5  | 142    | 26           |   |   |   |
| T2     | Togo       | Harbour           | 1.301     | 6.151    | 2016            | S.maderensis | 20          | 11    | 129    | 24.5         |   |   |   |
| T3     | Togo       | Harbour           | 1.301     | 6.151    | 2016            | S.maderensis | 17.5        | 13.5  | 73     | 20           |   |   |   |
| T4     | Togo       | Harbour           | 1.301     | 6.151    | 2016            | S.maderensis | 20          | 12.5  | 123    | 24.5         |   |   |   |
| T5     | Togo       | Harbour           | 1.301     | 6.151    | 2016            | S.maderensis | 19          | 13.5  | 104    | 22.5         |   |   |   |
| T6     | Togo       | Harbour           | 1.301     | 6.151    | 2016            | S.maderensis | 21          | 13    | 141    | 25.5         |   |   |   |
| T7     | Togo       | Harbour           | 1.301     | 6.151    | 2016            | S.maderensis | 20          | 12.5  | 117    | 24           |   |   |   |
| T8     | Togo       | Harbour           | 1.301     | 6.151    | 2016            | S.maderensis | 20.5        | 13.5  | 137    | 25           |   |   |   |
| T9     | Togo       | Harbour           | 1.301     | 6.151    | 2016            | S.maderensis | 21          | 13    | 147    | 25.5         |   |   |   |
| T10    | Togo       | Harbour           | 1.301     | 6.151    | 2016            | S.maderensis | 22          | 14    | 171    | 26.5         |   |   |   |
| T11    | Togo       | Harbour           | 1.301     | 6.151    | 2016            | S.maderensis | 22          | 14    | 153    | 21.5         |   |   |   |
| T12    | Togo       | Harbour           | 1.301     | 6.151    | 2016            | S.maderensis | 18          | 11.5  | 91     | 26           |   |   |   |
| T13    | Togo       | Harbour           | 1.301     | 6.151    | 2016            | S.maderensis | 21          | 13.5  | 143    | 25           |   |   |   |
| T14    | Togo       | Harbour           | 1.301     | 6.151    | 2016            | S.maderensis | 21          | 13.5  | 129    | 24           |   |   |   |
| T15    | Togo       | Harbour           | 1.301     | 6.151    | 2016            | S.maderensis | 21          | 13.5  | 69     | 20           |   |   |   |
| T26    | Togo       | Harbour           | 1.301     | 6.151    | 2016            | S.maderensis | 21.5        | 14.5  | 137    | 26           |   |   |   |
| T37    | Togo       | Harbour           | 1.301     | 6.151    | 2016            | S.maderensis | 20          | 11.5  | 71     | 20.5         |   |   |   |
| T38    | Togo       | Harbour           | 1.301     | 6.151    | 2016            | S.maderensis | 17          | 12.5  | 95     | 22.5         |   |   |   |
| T39    | Togo       | Harbour           | 1.301     | 6.151    | 2016            | S.maderensis | 19          | 13.5  | 118    | 23.5         |   |   |   |
| T45    | Togo       | Harbour           | 1.301     | 6.151    | 2016            | S.maderensis | 20          | 13    | 97     | 22.5         |   |   |   |
|        |            |                   |           |          |                 |              |             |       |        |              |   |   |   |
#### 2. HiSeq Read Set Sequencing Metadata
| Name                 | Plate name   | country    | species      | Run Type   | Library Source | Library Type | Read #  | Average Quality |   |
|----------------------|--------------|------------|--------------|------------|----------------|--------------|---------|-----------------|---|
| M80                  | D1           | Mauritania | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 3972953 | 40              |   |
| M70                  | D2           | Mauritania | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 2863133 | 40              |   |
| M74                  | D3           | Mauritania | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 3836010 | 40              |   |
| M60                  | D7           | Mauritania | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 2997783 | 40              |   |
| M58                  | D8           | Mauritania | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 3762103 | 40              |   |
| M41                  | D9           | Mauritania | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 3029751 | 40              |   |
| M1                   | G1           | Mauritania | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 3114856 | 40              |   |
| M2                   | G2           | Mauritania | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 3448832 | 40              |   |
| M3                   | G3           | Mauritania | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 2990393 | 40              |   |
| M4                   | G4           | Mauritania | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 3363135 | 40              |   |
| M5                   | G5           | Mauritania | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 2326233 | 40              |   |
| M6                   | G6           | Mauritania | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 2888975 | 40              |   |
| M8                   | G8           | Mauritania | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 4453339 | 40              |   |
| M10                  | G10          | Mauritania | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 3317070 | 40              |   |
| M50                  | 1A           | Mauritania | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 2388069 | 40              |   |
| M58                  | 2A           | Mauritania | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 498866  | 40              |   |
| M59                  | 7A           | Mauritania | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 440287  | 40              |   |
| M60                  | 8A           | Mauritania | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 426360  | 40              |   |
| M66                  | 9A           | Mauritania | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 1423744 | 40              |   |
| S1                   | C1           | Senegal    | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 2909942 | 40              |   |
| S2                   | C2           | Senegal    | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 2322853 | 40              |   |
| S3                   | C3           | Senegal    | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 3231356 | 40              |   |
| S4                   | C4           | Senegal    | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 3268838 | 40              |   |
| S5                   | C5           | Senegal    | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 2507019 | 40              |   |
| S6                   | C6           | Senegal    | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 6007766 | 40              |   |
| S7                   | C7           | Senegal    | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 2334828 | 40              |   |
| S8                   | C8           | Senegal    | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 2426209 | 36              |   |
| S9                   | C9           | Senegal    | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 2855746 | 40              |   |
| S10                  | C10          | Senegal    | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 3235321 | 40              |   |
| S21                  | IC           | Senegal    | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 1829026 | 40              |   |
| S22                  | 2C           | Senegal    | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 2884170 | 40              |   |
| S23                  | 3C           | Senegal    | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 2374320 | 40              |   |
| S25                  | 5C           | Senegal    | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 67387   | 40              |   |
| S27                  | 7C           | Senegal    | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 1490195 | 40              |   |
| S28                  | 8C           | Senegal    | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 3220885 | 40              |   |
| S38                  | S38          | Senegal    | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 1807230 | 40              |   |
| S24                  | 4C           | Senegal    | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 3490025 | 40              |   |
| G11                  | Guinea1_New  | Guinea     | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 1671444 | 40              |   |
| G13                  | Guinea11_New | Guinea     | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 2736320 | 40              |   |
| G14                  | Guinea13_New | Guinea     | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 3281360 | 40              |   |
| G15                  | Guinea14_New | Guinea     | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 3738207 | 40              |   |
| G16                  | Guinea15_New | Guinea     | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 2614403 | 40              |   |
| G19                  | Guinea16_New | Guinea     | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 2539545 | 40              |   |
| G2                   | Guinea19_New | Guinea     | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 2416160 | 40              |   |
| G21                  | Guinea2_New  | Guinea     | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 1950201 | 40              |   |
| G22                  | Guinea21_New | Guinea     | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 2096833 | 40              |   |
| G23                  | Guinea22_New | Guinea     | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 3559740 | 40              |   |
| G25                  | Guinea23_New | Guinea     | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 2235137 | 40              |   |
| G31                  | Guinea25_New | Guinea     | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 2786868 | 40              |   |
| G37                  | Guinea31_New | Guinea     | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 4059001 | 40              |   |
| G43                  | Guinea37_New | Guinea     | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 3573740 | 40              |   |
| G1                   | Guinea43_New | Guinea     | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 3453429 | 40              |   |
| G2                   | Guinea_11G   | Guinea     | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 778994  | 40              |   |
| G3                   | Guinea_1G    | Guinea     | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 1068216 | 40              |   |
| G4                   | Guinea_1H    | Guinea     | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 1644856 | 40              |   |
| G5                   | Guinea_4G    | Guinea     | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 654806  | 40              |   |
|                      | Guinea_5H    | Guinea     | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 1233015 | 40              |   |
| GH1                  | A1           | Ghana      | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 4682704 | 40              |   |
| GH4                  | A4           | Ghana      | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 3296860 | 40              |   |
| GH2                  | A2           | Ghana      | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 3274985 | 40              |   |
|                      | A3           | Ghana      | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 176859  | 40              |   |
| GH5                  | A5           | Ghana      | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 2975779 | 40              |   |
| GH6                  | A6           | Ghana      | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 5448638 | 40              |   |
| GH7                  | A7           | Ghana      | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 3521271 | 40              |   |
| GH8                  | A8           | Ghana      | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 2593197 | 40              |   |
| GH9                  | A9           | Ghana      | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 2336965 | 40              |   |
| GH10                 | A10          | Ghana      | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 3822138 | 40              |   |
| GH11                 | F6           | Ghana      | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 1753505 | 40              |   |
| GH12                 | F7           | Ghana      | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 7250197 | 40              |   |
| GH13                 | F8           | Ghana      | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 1904330 | 40              |   |
| GH14                 | F9           | Ghana      | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 2578087 | 40              |   |
| GH15                 | F10          | Ghana      | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 1791180 | 40              |   |
| GH43                 | B1           | Ghana      | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 777363  | 40              |   |
| GH44                 | B2           | Ghana      | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 1051070 | 40              |   |
| GH45                 | B3           | Ghana      | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 760786  | 40              |   |
| GH46                 | B4           | Ghana      | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 1085310 | 40              |   |
| GH47                 | B5           | Ghana      | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 1559745 | 40              |   |
|                      | 1E           | Togo       | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 1903707 | 40              |   |
| T2                   | 2E           | Togo       | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 2920657 | 40              |   |
| T3                   | 3E           | Togo       | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 6364394 | 40              |   |
| T4                   | 4E           | Togo       | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 2399133 | 40              |   |
| T5                   | 5E           | Togo       | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 2825722 | 40              |   |
| T6                   | 6E           | Togo       | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 2330258 | 40              |   |
| T7                   | 7E           | Togo       | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 2163294 | 40              |   |
| T8                   | 8E           | Togo       | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 4392504 | 40              |   |
| T9                   | 9E           | Togo       | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 3699474 | 40              |   |
| T10                  | 10E          | Togo       | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 1982836 | 40              |   |
| T41                  | T41          | Togo       | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 3335789 | 40              |   |
| T44                  | T44          | Togo       | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 3130346 | 40              |   |
| T45                  | T45          | Togo       | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 3762442 | 40              |   |
| T47                  | T47          | Togo       | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 3393171 | 40              |   |
| T21                  | 1D           | Togo       | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 669464  | 40              |   |
| T22                  | 2D           | Togo       | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 2721236 | 40              |   |
| T23                  | 3D           | Togo       | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 652961  | 40              |   |
| T24                  | 4D           | Togo       | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 2033845 | 40              |   |
| T25                  | 5D           | Togo       | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 1966840 | 40              |   |
| T26                  | 6D           | Togo       | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 3079161 | 40              |   |
| Benin_1E_resequence  |              | Benin      | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 648405  | 40              |   |
| Benin_2E             |              | Benin      | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 3250561 | 40              |   |
| Benin_3E             |              | Benin      | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 1175269 | 40              |   |
| Benin_4E_resequence  |              | Benin      | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 1138702 | 40              |   |
| Benin_5E             |              | Benin      | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 426831  | 36              |   |
| Benin_5E_resequence  |              | Benin      | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 1160370 | 40              |   |
| Benin_6E_resequence  |              | Benin      | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 1864077 | 40              |   |
| Benin_7E             |              | Benin      | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 421762  | 37              |   |
| Benin_B1             |              | Benin      | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 3516024 | 40              |   |
| Benin_B10            |              | Benin      | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 3049783 | 40              |   |
| Benin_B2             |              | Benin      | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 2699346 | 40              |   |
| Benin_B3             |              | Benin      | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 2277126 | 40              |   |
| Benin_B4             |              | Benin      | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 2994343 | 36              |   |
| Benin_B5             |              | Benin      | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 2529279 | 40              |   |
| Benin_B6             |              | Benin      | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 3737002 | 40              |   |
| Benin_B7             |              | Benin      | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 6323212 | 40              |   |
| Benin_B8             |              | Benin      | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 6343378 | 40              |   |
| Benin_B9             |              | Benin      | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 3290984 | 40              |   |
| M7                   | G7           | Mauritania | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 2429179 | 40              |   |
| M9                   | G9           | Mauritania | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 604046  | 40              |   |
| M66                  | D5           | Mauritania | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 2221548 | 40              |   |
| M50                  | D6           | Mauritania | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 2773836 | 40              |   |
| M42                  | D10          | Mauritania | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 1002115 | 36              |   |
| M79                  | 1A           | Mauritania | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 707037  | 36              |   |
| M80                  | 2A           | Mauritania | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 1770842 | 36              |   |
| M88                  | 4A           | Mauritania | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 1225941 | 36              |   |
| M89                  | 5A           | Mauritania | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 1988491 | 36              |   |
| M9                   | 6A           | Mauritania | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 1001721 | 36              |   |
| M25                  | 7A           | Mauritania | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 1020230 | 36              |   |
| M90                  | 7B           | Mauritania | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 964148  | 36              |   |
| M98                  | 8A           | Mauritania | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 1096085 | 36              |   |
| M16                  | 9A           | Mauritania | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 3315913 | 36              |   |
| M99                  | 9B           | Mauritania | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 1383283 | 36              |   |
| M17                  | 10A          | Mauritania | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 3834032 | 36              |   |
| M14                  | 11A          | Mauritania | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 2553159 | 40              |   |
| M12                  | 11B          | Mauritania | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 2221548 | 40              |   |
| M85                  | 12A          | Mauritania | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 3620659 | 40              |   |
| S1                   | H1           | Senegal    | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 2084735 | 40              |   |
| S2                   | H2           | Senegal    | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 1317125 | 40              |   |
| S3                   | H3           | Senegal    | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 468068  | 40              |   |
| S4                   | H4           | Senegal    | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 2394435 | 40              |   |
| S5                   | H5           | Senegal    | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 1340907 | 40              |   |
| S6                   | H6           | Senegal    | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 1246669 | 40              |   |
| S7                   | H7           | Senegal    | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 2197183 | 40              |   |
| S8                   | H8           | Senegal    | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 639825  | 40              |   |
| S9                   | H9           | Senegal    | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 3494326 | 40              |   |
| S10                  | H10          | Senegal    | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 2025534 | 40              |   |
| S31                  | 1B           | Senegal    | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 1209463 | 36              |   |
| S11                  | 1C           | Senegal    | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 2934705 | 36              |   |
| S21                  | 2B           | Senegal    | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 2786505 | 36              |   |
| S22                  | 2C           | Senegal    | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 3530385 | 40              |   |
| S48                  | 3B           | Senegal    | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 4799496 | 40              |   |
| S49                  | 3C           | Senegal    | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 3258402 | 40              |   |
| S50                  | 4C           | Senegal    | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 3135016 | 40              |   |
| S41                  | 4C-res       | Senegal    | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 3045871 | 40              |   |
| S42                  | 5C           | Senegal    | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 3357428 | 40              |   |
| S43                  | 9C           | Senegal    | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 2814198 | 40              |   |
| G6                   | 10E          | Guinea     | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 2162394 | 40              |   |
| G7                   | 6E           | Guinea     | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 2579701 | 40              |   |
| G8                   | 6F           | Guinea     | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 2538471 | 40              |   |
| G9                   | 7E           | Guinea     | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 5642128 | 40              |   |
| G10                  | 8E           | Guinea     | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 5698079 | 36              |   |
| G23                  | G23          | Guinea     | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 3328832 | 36              |   |
| G25                  | G25          | Guinea     | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 3586765 | 36              |   |
| G26                  | G26          | Guinea     | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 4175486 | 36              |   |
| G27                  | G27          | Guinea     | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 3136132 | 36              |   |
| G28                  | G28          | Guinea     | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 3974891 | 40              |   |
| G29                  | G29          | Guinea     | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 3757137 | 40              |   |
| G30                  | G30          | Guinea     | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 3116255 | 40              |   |
| G33                  | G33          | Guinea     | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 4791637 | 40              |   |
| G34                  | G34          | Guinea     | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 2728215 | 40              |   |
| G35                  | G35          | Guinea     | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 3664194 | 40              |   |
| G37                  | G37          | Guinea     | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 4389357 | 40              |   |
| G38                  | G38          | Guinea     | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 3930490 | 36              |   |
| G39                  | G39          | Guinea     | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 3393483 | 36              |   |
| G40                  | G40          | Guinea     | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 3026438 | 40              |   |
| N1                   | 3G           | Nigeria    | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 3798103 | 36              |   |
| N2                   | 3H           | Nigeria    | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 2818093 | 36              |   |
| N3                   | 8F           | Nigeria    | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 1847396 | 40              |   |
| N4                   | 1H           | Nigeria    | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 1882335 | 40              |   |
| N5                   | 10F          | Nigeria    | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 1458661 | 36              |   |
| N6                   | 10G          | Nigeria    | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 2077416 | 40              |   |
| N7                   | 10G.res      | Nigeria    | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 4632541 | 40              |   |
| N8                   | 11F          | Nigeria    | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 3651073 | 40              |   |
| N9                   | 11G          | Nigeria    | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 1764589 | 40              |   |
| N10                  | 12F          | Nigeria    | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 863906  | 40              |   |
| N11                  | 12G          | Nigeria    | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 532017  | 40              |   |
| N12                  | 1G           | Nigeria    | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 2093608 | 36              |   |
| N13                  | 2G           | Nigeria    | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 4897107 | 36              |   |
| N14                  | 2H           | Nigeria    | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 2095123 | 36              |   |
| N15                  | 4G           | Nigeria    | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 432852  | 40              |   |
| N16                  | 5G           | Nigeria    | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 2996849 | 36              |   |
| N17                  | 7G           | Nigeria    | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 1436918 | 36              |   |
| N18                  | 8G           | Nigeria    | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 562976  | 40              |   |
| N19                  | 9F           | Nigeria    | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 1859757 | 36              |   |
| N20                  | 9G           | Nigeria    | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 4351480 | 40              |   |
| T1                   | 10A          | Togo       | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 1490224 | 40              |   |
| T2                   | 10B          | Togo       | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 2093608 | 40              |   |
| T3                   | 11A          | Togo       | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 1318183 | 40              |   |
| T4                   | 11B          | Togo       | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 3250561 | 40              |   |
| T5                   | 12A          | Togo       | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 1546825 | 40              |   |
| T6                   | 12B          | Togo       | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 745465  | 40              |   |
| T7                   | 3A           | Togo       | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 498351  | 40              |   |
| T8                   | 4B           | Togo       | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 2610747 | 40              |   |
| T9                   | 5A           | Togo       | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 1490224 | 40              |   |
| T10                  | 5B           | Togo       | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 3150474 | 40              |   |
| T11                  | 6A           | Togo       | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 6004595 | 40              |   |
| T12                  | 6B           | Togo       | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 485764  | 40              |   |
| T13                  | 8A           | Togo       | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 1165329 | 40              |   |
| T14                  | 8B           | Togo       | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 2399695 | 40              |   |
| T15                  | 8Bres        | Togo       | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 769184  | 36              |   |
| T26                  | T26          | Togo       | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 4202676 | 36              |   |
| T37                  | T37          | Togo       | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 3721938 | 40              |   |
| T38                  | T38          | Togo       | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 3230095 | 36              |   |
| T39                  | T39          | Togo       | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 4299789 | 40              |   |
| T45                  | T45          | Togo       | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 3032301 | 40              |   |
| Benin_10E            |              | Benin      | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 801564  | 36              |   |
| Benin_10E_resequence |              | Benin      | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 3345083 | 40              |   |
| Benin_11E            |              | Benin      | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 2280475 | 40              |   |
| Benin_12E_resequence |              | Benin      | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 1977142 | 36              |   |
| Benin_1F             |              | Benin      | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 3459880 | 36              |   |
| Benin_2F_resequence  |              | Benin      | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 2637252 | 36              |   |
| Benin_3F_resequence  |              | Benin      | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 1915437 | 36              |   |
| Benin_4F_resequence  |              | Benin      | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 1858038 | 36              |   |
| Benin_5F_resequence  |              | Benin      | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 5330703 | 36              |   |
| Benin_6F_resequence  |              | Benin      | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 1415566 | 40              |   |
| Benin_7F             |              | Benin      | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 1508411 | 40              |   |
| Benin_A11            |              | Benin      | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 5986337 | 40              |   |
| Benin_A12            |              | Benin      | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 3322288 | 36              |   |
| Benin_B11            |              | Benin      | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 5785770 | 36              |   |
| Benin_B12            |              | Benin      | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 3084180 | 36              |   |
| Benin_C11            |              | Benin      | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 2360582 | 36              |   |
| Benin_D11            |              | Benin      | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 3289491 | 36              |   |
| Benin_E11            |              | Benin      | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 2817261 | 36              |   |
| Benin_F11            |              | Benin      | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 3926321 | 36              |   |
| Benin_G11            |              | Benin      | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 3143584 | 36              |   |
| Benin_H11            |              | Benin      | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 3475239 | 36              |   |
### **Step 1: Download and acquire the Data**
#### All sequence data was  downloaded onto bluewaves cluster using the wget command with a link to the data from the sequencing center
```
wget -r -np -l 1 --no-check-certificate http://genomics/?A=G;O=1
```
### **Step 2: Check Sum was performed on data using checksum files obtained from the sequencing center**
```
md5sum *fastq.gz
```
##### Checksum for data downloaded matches what is obtained from the sequencing center for all samples.

### **Step 3: Demultiplex data**
##### demultiplexing was carried out with barcodes supplied by sequencing center using Process_radtags from stacks package (http://creskolab.uoregon.edu/stacks/)

```
(ddocent_env) [evelyn-takyi@n018 20180312-Takyi-nondemultiplexed]$ process_radtags -1 2018June_Takyi-Sardinella_P2P1_S27_L003_R1_001.fq.gz -2 2018June_Takyi-Sardinella_P2P1_S27_L003_R2_001.fq.gz -i gzfastq -b barcode27 -r -e ecoRI -o /data3/marine_diseases_lab/evelyn/eveproject/evelyn/Sardinella/gridftp.tamucc.edu/genomics/20180312-Takyi-Sardinella/batch2/gridftp.tamucc.edu/genomics/20180622-Takyi-Sardinella/rawdata/ -D
```
##### After demultiplexing, the output file also contain files coded .rem.fq.gz. These files failed the demultiplex process and has to be removed.
```
rm *rem*
```
##### samples were renamed using a script (https://github.com/jpuritz/dDocent/raw/master/Rename_for_dDocent.sh) from dDocent pipeline/John Puritz.
##### first download the script, change mode to make it executable and run script
```
curl -L -O https://github.com/jpuritz/dDocent/raw/master/Rename_for_dDocent.sh
chmod a +x
bash Rename_for_dDocent.sh SimRAD.barcodes
ls *.fq.gz.(This checks to see if all our files are renamed)
```

### **Step 4: Initial Raw Data Assessment and Characterization**
##### FASTQC program on the command line was use to create FASTQC report with: a. Basic statistics b. Per base sequence quality scores c. Per sequence quality scores d. Per base GC content e. Per sequence GC content f. Per sequence GC content.
```
1. First load the Fastqc module on the cluster
module load FastQC/0.11.5-Java-1.8.0_92
2. Run the FastQC on all the samples
fastqc *fq.gz
```
##### Next i used a MultiQC program to put together all fastqc results files
```
1. make new folder with all Fastqc files and copy all files ending in .zip into the folder
mkdir Results
mv *.zip ./Results
cd Results
2. Use Bioconda to install the multiqc program and run the program
conda install -c bioconda multiqc
multiqc .
```
#### Export file to local folder so you can open it up with .html
```
FINALANALYSIS evelyntakyi$ scp -r AAAAAA@bluewaves:/data3/marine_diseases_lab/evelyn/eveproject/evelyn/gridftp.tamucc.edu/genomics/20180312-Takyi-Sardinella/maderensis_Final2/FastQC/Results .
```
#### 1. Read counts and Quality
Read counts and quality are provided in the metadata file for each sample.
#### 2. Multiqc report
##### a. GC content: The GC content ranges between 42% to 47% across all reads.
##### b. % Duplicates: The percent duplication was high across all the samples and ranging from 23% to 86%.
##### c. Mean Quality Score: 236/236 Samples Passed. None failed
##### d.  Per base sequence content:  All 236 samples failed
##### This graph depicts the mean quality score at each position across a read.236/236 Passed
![plot1](https://github.com/evelyn-takyi/Sardinella-project/blob/master/All%20plot/mean%20quality.png)
##### e. Per Sequence Quality Score: 236/236 Samples Passed
This graph depicts the number of reads with average quality scores.
![plot1](https://github.com/evelyn-takyi/Sardinella-project/blob/master/All%20plot/sequence%20qaulity%20scores.png)
##### f. Per Sequence GC Content
This graph depicts the average GC contents of reads and is roughly normally distributed.
![plot1](https://github.com/evelyn-takyi/Sardinella-project/blob/master/All%20plot/GC%20content.png)
### **Step 5: Bioinformatic Processing of the ddRadseq Data**
#### Two different species are going to be analysed in this work.
#### I will start with **s.aurita species**
#### The ddocent pipeline (http://www.ddocent.com)was used for processing of the data. Software is downloaded unto the bluewaves cluster.
##### The pipeline uses an interactive approach to to perform the following steps; quality trim reads, perform an assembly, map reads to a reference and call Variants.
##### First, you must load the software and activate the ddocent environment
```
#Load software
module load ddocent/2.5.2
# Activate the environment
source activate ddocent_env
# Type dDocent
```
##### Before we can run dDocent to call variants, we first need to assemble our reference denovo because this species doesnt have a reference sequence.
######
For generating a denovo Assembly
```
mkdir assembly
cd Assembly
#Five samples that have been quality filtered and trimmed with high quality from each of the populations for both s.aurita and s.maderensis were selected were copied into the directory Assembly
```
##### The ddocent pipeline uses two programs CD-HIT and Rainbow to assemble Radseq data. These programs are based on an alignment read based clustering which uses a similarity threshold to cluster the reads. To start the assembly, ddocent takes into account the 3 factors below;
###### 1.sequencing errors can be introduced in Radseq data where some sequences will have very low coverage, this must be removed from the assembly and  unique sequences with a cut off value of considerable coverage in the data set are identified and selected. hereafter noted as K1.
###### 2. We are also assemblying reference sequence considering different individuals, it is appropriate to consider unique sequences to be present in atleast most of the individuals.Therefore a cut off value of how many individuals should a unique sequence appear in should also be considered. hereafter noted as K2.
###### 3. The similarity threshold noted as c necessary to cluster the reads into various loci must be determined. To do this, i used a script by Jon Puritz/ReferenceOpt.sh(https://github.com/jpuritz/dDocent/blob/master/scripts/ReferenceOpt.sh).This script basically chooses an interval of cutoff values for K1, K2 and a similarity threshold to cluster reads.
```{r}
The interval values below are;
K1 value is 4 to 2 coverage for each unique sequence.
K2 value is 4 to 2 individuals a unique sequence appears in
c values from 0.8-0.98 similarity threshold.
```
##### Using the information above, lets start denovo assembly for s. aurita
```
bash ReferenceOpt.sh 4 4 2 2 PE 20
# PE represents Paired end
# the value 20 represent the number of threads to run the scripts
```
###### After running the script, it output a data known kopt.data which when visualised contains k1,k2 value combination across similarity thresholds and the number of contig obtained.  To visualise the information in the kopt.data, use the code
```
cat kopt.data
```
kopt.data
  | K1| K2| C    | Contig|
|---|---|------|-------|
| 4 |2  |  0.08| 20285 |
| 4 | 2 | 0.82 | 20323 |
| 4 | 2 | 0.84 | 20364 |
| 4 | 2 | 0.86 | 20383 |
| 4 | 2 | 0.88 | 20400 |
| 4 | 2 | 0.90 | 20422 |
| 4 | 2 | 0.92 | 20520 |
| 4 | 2 | 0.94 | 20623 |
| 4 | 2 | 0.96 | 20721 |
| 4 | 2 | 0.98 | 20845 |
###### Next is to pick a similarity threshold to cluster reads, to do so first, we plot the above data using ggplot2 in R package using the code below adapted from Jon/Puritz (http://www.ddocent.com/quick/). The similarity cut off is the point of inflection on the graph.
```
library(ggplot2)

data.table <- read.table("kopt.data", header = FALSE, col.names= c("k1","k2","Similarity", "Contigs"))

data.table$K1K2 <- paste(data.table$k1, data.table$k2, sep=",")

df=data.frame(data.table)
df$K1K2 <- as.factor(df$K1K2)

p <- ggplot(df, aes(x=Similarity, y=Contigs, group=K1K2)) + scale_x_continuous(breaks=seq(0.8,0.98,0.01)) + geom_line(aes(colour = K1K2))
p
```
The output is below
![plot2](https://github.com/evelyn-takyi/Sardinella-project/blob/master/RefoptA.png)
The similarity threshold is the value at the point of inflection on the curve. herein in 0.9 selected as our appropriate cut off.

##### selecting cut off values of k1 and k2 in clustering sequences into a single locus is one critical step. We also need to evaluate mappings to our reference that will be assembled with few reads before choosing a final number of contig to represent our reference.  To peform this evaluation, i used the script RefMapOpt.sh (https://github.com/jpuritz/dDocent/blob/master/scripts/RefMapOpt.sh)
###### The script basically assembles reference with intervals of K1, K2 values and a similarity threshold of 0.9 after which it maps 20 randomly samples(default in the script) to  the reference contigs assembled across all the cut off values used.
```
bash RefMapOpt.sh 2 5 2 5 0.9 20 PE
# K1 value is 2 to 5
# K2 value is 2 to 5
# C value is 0.9
# Number of threads used is 20
# PE represent paired end
```
Results are outputted in a tablular form
| Cov     | Non0Cov | Contigs | MeanContigsMapped | K1 | K2 | SUM Mapped | SUM Properly | Mean Mapped | Mean Properly | MisMatched |
|---------|---------|---------|-------------------|----|----|------------|--------------|-------------|---------------|------------|
| 5.1378  | 7.52733 | 258610  | 172140            | 2  | 2  | 18601681   | 13233039     | 1.33E+06    | 945217        | 91745.6    |
| 7.22865 | 9.45369 | 130928  | 95859.9           | 2  | 3  | 13250174   | 8658665      | 946441      | 618476        | 66231.3    |
| 10.0434 | 12.6844 | 74720   | 56594.2           | 2  | 4  | 10506338   | 6621964      | 750453      | 472997        | 55011      |
| 14.6825 | 18.116  | 42702   | 33203.8           | 2  | 5  | 8777794    | 5211280      | 626985      | 372234        | 41542.9    |
| 9.67957 | 12.8533 | 82324   | 60523.7           | 3  | 2  | 11156193   | 7219651      | 796871      | 515689        | 60601.2    |
| 18.1624 | 22.0825 | 30121   | 23726.6           | 3  | 3  | 7659226    | 4561326      | 547088      | 325809        | 38603.5    |
| 36.3081 | 42.6345 | 13061   | 10699.9           | 3  | 4  | 6639589    | 3534219      | 474256      | 252444        | 33968.8    |
| 64.7652 | 73.2299 | 6317    | 5359.21           | 3  | 5  | 5728612    | 3008507      | 409187      | 214893        | 26955.6    |
| 23.3165 | 28.935  | 22878   | 17971.8           | 4  | 2  | 7468413    | 4711947      | 533458      | 336568        | 40834.8    |
| 61.7502 | 69.8452 | 6976    | 5897.79           | 4  | 3  | 6031633    | 3205327      | 430831      | 228952        | 26372.8    |
| 116.116 | 127.164 | 3394    | 2974.07           | 4  | 4  | 5518973    | 2795911      | 394212      | 199708        | 24969.1    |
| 154.138 | 165.389 | 2188    | 1946.71           | 4  | 5  | 4723704    | 2600495      | 337407      | 185750        | 16348.9    |
| 59.8067 | 70.5072 | 7680    | 6360.57           | 5  | 2  | 6431255    | 3533321      | 459375      | 252380        | 38750.4    |
| 120.921 | 129.114 | 2838    | 2506.57           | 5  | 3  | 4806145    | 2791040      | 343296      | 199360        | 16342.9    |
| 173.338 | 182.504 | 1806    | 1615.43           | 5  | 4  | 4385096    | 2525316      | 313221      | 180380        | 17047.4    |
| 217.311 | 227.027 | 1346    | 1214.14           | 5  | 5  | 4098051    | 2336437      | 292718      | 166888        | 15973.4    |

###### In order to have confidence in selecting the number of contigs to represent our reference and proceed, we look at the result in the table and consider these; properly mapped reads with good coverage and minimizing mismatched reads because we want a high percentage of our reads to map to the reference.
using this criteria the cut off value of K1=3, K2=2 and 82324 Contigs are selected.
###### Now having chosen the appropriate cut off values  and a c(similarity threshold) value of 0.9, we remake  our reference using a script remake_reference.sh made by Jon Puritz to obtain our reference assembly that we are confident in.
```
bash remake_reference.sh 3 2 0.90 PE 20
# Use the mawk function to visualise the number of the reference contigs
mawk '/>/' reference.fasta | wc -l
```
82324 Contigs in a fasta file were assembled for S.aurita!!!

#### To have more confidence in the reference assembly, various sequences of s.aurita published online from ncbi were downloaded and blasted against our denovo reference assembly.
Significant hit was observed
```
Database: Aurita
           82,324 sequences; 23,834,470 total letters
```

| Query                                                                                                                          | Length of query | Sequences producing significant alignments: | Bits Score | E-value   |
|--------------------------------------------------------------------------------------------------------------------------------|-----------------|---------------------------------------------|------------|-----------|
|                                                                                                                                |                 |                                             |            |           |
|                                                                                                                                |                 |                                             |            |           |
| DQ197990.1 Sardinella aurita cytochrome b (cytb) gene, complete cds;mitochondrial                                              | 1141            | dDocent_Contig_411                          | 483        | 9.00E-136 |
|                                                                                                                                |                 | dDocent_Contig_1873                         | 425        | 2.00E-118 |
|                                                                                                                                |                 | dDocent_Contig_2480                         | 418        | 3.00E-116 |
|                                                                                                                                |                 | dDocent_Contig_1242                         | 368        | 3.00E-101 |
|                                                                                                                                |                 | dDocent_Contig_16133                        | 268        | 3.00E-71  |
|                                                                                                                                |                 | dDocent_Contig_77003                        | 263        | 1.00E-69  |
| KJ655528.1 Sardinella aurita clone Sara8 microsatellite sequence                                                               | 595             | dDocent_Contig_54832                        | 204        | 4.00E-52  |
|                                                                                                                                |                 | dDocent_Contig_21255                        | 126        | 9.00E-29  |
|                                                                                                                                |                 |                                             |            |           |
| Sardinella aurita voucher JFBM 48669-JE1131 recombination activating protein 1 gene, partial cds                               | 1471            | dDocent_Contig_72123                        | 268        | 4.00E-71  |
|                                                                                                                                |                 |                                             |            |           |
|                                                                                                                                |                 |                                             |            |           |
| MG958416.1 Sardinella aurita voucher MNHN-IC 2017-0508-BPS-1383 recombination activating protein 1 gene, partial cds           | 1510            | dDocent_Contig_72123                        | 274        | 8.00E-73  |
|                                                                                                                                |                 |                                             |            |           |
| MG958277.1 Sardinella aurita voucher JFBM 48669-JE1131 recombination activating protein 2 gene, partial cds                    | 1122            | dDocent_Contig_2087                         | 342        | 2.00E-93  |
|                                                                                                                                |                 |                                             |            |           |
| Sardinella aurita voucher JFBM 48669-JE1131 cytochrome b gene, partial cds; mitochondrial                                      | 1142            | dDocent_Contig_411                          | 484        | 3.00E-136 |
|                                                                                                                                |                 | dDocent_Contig_1873                         | 456        | 7.00E-122 |
|                                                                                                                                |                 | dDocent_Contig_2480                         | 401        | 3.00E-111 |
|                                                                                                                                |                 | dDocent_Contig_1242                         | 372        | 2.00E-102 |
|                                                                                                                                |                 | dDocent_Contig_16133                        | 263        | 1.00E-69  |
|                                                                                                                                |                 | dDocent_Contig_77003                        | 257        | 6.00E-68  |
|                                                                                                                                |                 | dDocent_Contig_43148                        | 52.8       | 3.00E-06  |
| MG958159.1 Sardinella aurita voucher MNHN-IC 2017-0508-BPS-1383 zic family member 1 gene, partial cds                          | 812             | dDocent_Contig_44444                        | 357        | 4.00E-98  |
|                                                                                                                                |                 |                                             |            |           |
| Sardinella aurita isolate SAUR5 tRNA-Glu (trnE) gene,partial sequence; and cytochrome b (cytb) gene, partial cds;mitochondrial | 414             | dDocent_Contig_411                          | 466        | 3.00E-131 |
|                                                                                                                                |                 | dDocent_Contig_1242                         | 351        | 9.00E-97  |
|                              

#### Next is after assemblying our reference sequence, we proceed with the pipeline to map our reads to the reference and call variants.
##### Now we are ready to run ddocent with the configuration file.
```
#Load software
module load ddocent/2.5.2
# Activate the environment
source activate ddocent_env
```
###### change into the appropriate directory containing all the sequences and reference file
###### Type dDocent
```(ddocent_env) [AAAA@n062 20180312-Takyi-Sardinella]$ cd Aurita_Final2/
(ddocent_env) [AAAAA@n062 Aurita_Final2]$ dDocent
```
dDocent 2.5.3
Contact jpuritz@uri.edu with any problems
Checking for required software
All required software is installed!
dDocent run started Sat Mar 23 14:48:01 EDT 2019
**114 individuals are detected. Is this correct? Enter yes or no and press [ENTER]**
```
yes
```
Proceeding with 114 individuals
**dDocent detects 20 processors available on this system.
Please enter the maximum number of processors to use for this analysis.**
```
20
```
**dDocent detects 125 gigabytes of maximum memory available on this system.
Please enter the maximum memory to use for this analysis in gigabytes
For example, to limit dDocent to ten gigabytes, enter 10
This option does not work with all distributions of Linux.  If runs are hanging at variant calling, enter 0
Then press [ENTER]**
```
120
```
**Do you want to quality trim your reads?
Type yes or no and press [ENTER]?**
```
yes
# the default parameters in the pipeline were used for quality trimming. Reads were quality trim a phred score below 20 for base calls and an average quality score of 10 for each read. Adapters were also detected and trim
```

**Do you want to perform an assembly?
Type yes or no and press [ENTER].**
```
no
```
Reference contigs need to be in a file named reference.fasta

**Do you want to map reads?  Type yes or no and press [ENTER]**
```
yes
```
###### BWA will be used to map reads.  You may need to adjust -A -B and -O parameters for your taxa. Would you like to enter a new parameters now? Type yes or no and press [ENTER]
```
no
```
Proceeding with default values for BWA read mapping.
**Do you want to use FreeBayes to call SNPs?  Please type yes or no and press [ENTER]**
```
yes
```
Please enter your email address.  dDocent will email you when it is finished running.
Don't worry; dDocent has no financial need to sell your email address to spammers.
```
evelyn-takyi@my.uri.edu
```
###### At this point, all configuration information has been entered and dDocent may take several hours to run.
###### It is recommended that you move this script to a background operation and disable terminal input and output.
###### All data and logfiles will still be recorded.
###### To do this:
######- ress control and Z simultaneously
##### Type 'bg' without the quotes and press enter
##### Type 'disown -h' again without the quotes and press enter
##### Now sit back, relax, and wait for your analysis to finish

#### After ddocent is finished calling SNPs, it is stored in vcf file as
**TotalRawSNPs.vcf**

### Next is to filter SNPs using VCFTools and bash script
#### The following steps were adapted from an excellent protocol developed by Jon Puritz. For more detailed information please see http://ddocent.com/filtering/

#### 1. First we will use VCFTools to filter out any variants that have not been successfully genotyped in 50% of individuals ( --max-missing 0.5), those with a minor allele count of 3 (--mac 3)), and those with a quality score below 20 (--minQ 20)
```
 vcftools --vcf TotalRawSNPs.vcf --max-missing 0.5 --mac 3 --minQ 20 --recode --recode-INFO-all --out raw.g5mac3
After filtering, kept 115 individuals and  kept 341983 out of a possible 1256073 Sites
```
#### 2.Next step is to get rid of individuals that did not sequence well or are missing a lot of loci. We use the script ./filter_missing_ind.sh. this prints out a histogram showing the percentage of missing data in the individuals and ask you to select a cut off value to remove individuals with missing data or loci.
```
./filter_missing_ind.sh raw.g5mac3.recode.vcf DP3g95maf05

        Histogram of % missing data per individual                                       

  7 +-+---**---+----------+-----------+----------+----------+----------+----------+-----------+----------+--------+-+   
    +     **   +          +           +          +          +          +          +           +          +          +   
    |     **                                                  'totalmissing' using (bin($1,binwidth)):(1.0) ******* |   
    |     **                                                                                                        |   
  6 +-+   ***                                                                                                     +-+   
    |     ***                                                                                                       |   
    |     ***                                                                                                       |   
    |     ***                                                                                                       |   
  5 +-+   ***                                                                                                     +-+   
    |     ***                                                                                                       |   
    |     ***                                                                                                       |   
  4 +**** ******* ***                                                                                             +-+   
    |**** ******* * *                                                                                               |   
    |**** ******* * *                                                                                               |   
    |**** ******* * *                                                                                               |   
  3 +**** ******* * *               ***                                                                           +-+   
    |**** ******* * *               * *                                                                             |   
    |**** ******* * *               * *                                                                             |   
    |**** ******* * *               * *                                                                             |   
  2 +************** ****    ****  *** *  *****    *** ****      ***               ****** ** ***             ***   +-+   
    |**** ******* * ** *    *  *  * * *  * ***    * * *  *      * *               * **** ** * *             * *     |   
    |**** ******* * ** *    *  *  * * *  * ***    * * *  *      * *               * **** ** * *             * *     |   
    +**** ******* * ** *  + *  *  * * *  * ***   +* * *  *  +   * *    +          * **** ** * *          +  * *     +   
  1 +*******************--+-****--*****--*****---+***-****--+---***----+----------******-**-***----------+--***---+-
  0         0.1        0.2         0.3        0.4        0.5        0.6        0.7         0.8     0.9         1   
                                              % of missing data*  
0.9% cut off was selected                                                 

After filtering, kept 100 out of 115 Individuals and  341983 out of a possible 341983 Sites

```
##### 3. next command, which applies a minimum mean depth for a genotype call. Genotypes will be called if they have atleast Five reads.
```
vcftools --vcf DP3g95maf05.recode.vcf --minDP 5 --maf 0.01 --recode --recode-INFO-all --out raw.g5mac3dp3
```
After filtering, kept 276130 out of a possible 341983 Sites

##### Next, we need to filter loci by applying genotype call rate of 0.9 across individuals in each population. To do this we use another script pop_missing_filter.sh by jon Puritz.
```
./pop_missing_filter.sh raw.g5mac3dp3.recode.vcf popmap 0.9 1 TRSdp5MIp25
```
After filtering, kept 58019 out of a possible 276130 Sites
##### Next filter is based on script will automatically filter a FreeBayes generated VCF file using criteria related to site depth,quality versus depth, strand representation, allelic balance at heterzygous individuals, and paired read representation. We use the script dDocent_filters

```
./dDocent_filters TRSdp5MIp25.recode.vcf  TRSdp5MIp25g9dd

Number of sites filtered based on allele balance at heterozygous loci, locus quality, and mapping quality / Depth
37787 of 58019

Are reads expected to overlap?  In other words, is fragment size less than 2X the read length?  Enter yes or no.
no
Number of additional sites filtered based on overlapping forward and reverse reads
11084 of 20232

Is this from a mixture of SE and PE libraries? Enter yes or no.
no
Number of additional sites filtered based on properly paired status
324 of 9148

Number of sites filtered based on high depth and lower than 2*DEPTH quality score
4206 of 8824



                                             Histogram of mean depth per site                                           

  400 +-+--+----+-----+----+----+----+-----+----+----+----+-----+----+----+----+-----+----+----+----+-----+----+--+-+   
      +    +    +     +    +    +    +     +    +    +    +     +    +    +    +     +    +    +    +     +    +    +   
      ****                                                'meandepthpersite' using (bin($1,binwidth)):(1.0) ******* |   
  350 *-+*                                                                                                        +-+   
      *  *                                                                                                          |   
      *  *                                                                                                          |   
  300 *-+*                                                                                                        +-+   
      *  *                                                                                                          |   
      *  ***                                                                                                        |   
  250 *-+* *                                                                                                      +-+   
      *  * *                                                                                                        |   
  200 *-+* *                                                                                                      +-+   
      *  * ****                                                                                                     |   
      *  * *  *                                                                                                     |   
  150 *-+* *  *                                                                                                   +-+   
      *  * *  ******    ****                                                                                        |   
      *  * *  * *  ******  *                                                                                        |   
  100 *-+* *  * *  *  * *  ******                                                                                 +-+   
      *  * *  * *  *  * *  *  * *                                                                                   |   
      *  * *  * *  *  * *  *  * **************                                                                      |   
   50 *-+* *  * *  *  * *  *  * *  * *  *  * *******    *********                                                 +-+   
      *  * *  * *  *  * *  *  * *  * *  *  * *  *  ****** *  *  *      ****       ****                              |   
      *  * *  * *  *  * *  *  * *  * *  *  * *  *  * *  * *  *  ********  *********  ********************************   
    0 ***************************************************************************************************************   
      10   12   14    16   18   20   22    24   26   28   30    32   34   36   38    40   42   44   46    48   50   52  
                                                        Mean Depth                                                      

If distrubtion looks normal, a 1.645 sigma cutoff (~90% of the data) would be 4927.04015
The 95% cutoff would be 48
Would you like to use a different maximum mean depth cutoff than 48, yes or no
no
Number of sites filtered based on maximum mean depth
564 of 8824

Number of sites filtered based on within locus depth mismatch
96 of 8260

Total number of sites filtered
49855 of 58019

Remaining sites
8164
```
##### Next is to filter our variants by a minor allele frequency
```
vcftools --vcf TRSdp5MIp25g9dd.FIL.recode.vcf --maf 0.05 --recode --recode-INFO-all --out DP3g95maf05d
```
After filtering, kept 6400 out of a possible 8164 Sites
##### Apply a filter for HWE
###### Hardy Weinberg equilibrium is also another excellent filter to remove erroneous variant calls. To do this I will implement a script filter_hwe_by_pop.pl written by Chris Hollenbeck.
```
filter_hwe_by_pop.pl -v DP3g95maf05d.recode.vcf -p popmap -c 0.5 -o SNP.DP3gdp5MIp25g9HWE
Processing population: BA (17 inds)
Processing population: GA (20 inds)
Processing population: GUI (20 inds)
Processing population: MA (19 inds)
Processing population: SA (18 inds)
Processing population: TA (20 inds)
Outputting results of HWE test for filtered loci to 'filtered.hwe'
Kept 6116 of a possible 6400 loci (filtered 284 loci)
```
###### The script rad_haplotyper.pl by was used to filter any paralogs and loci with missing data
```
rad_haplotyper.pl -v SNP.DP3gdp5MIp25g9HWE.recode.vcf  -x 10 -mp 2 -r reference.fasta
```
###### stats.out contain information on loci with possible paralogs and loci with missing data

```(rad_haplotyper_env) [evelyn-takyi@n038 Aurita_Final2]$ cp stats.out stats.out.HF
(rad_haplotyper_env) [evelyn-takyi@n038 Aurita_Final2]$ mawk '/Missi/' stats.out.HF | mawk '$9 > 30' > HF.missing
(rad_haplotyper_env) [evelyn-takyi@n038 Aurita_Final2]$ mawk '/para/' stats.out.HF > HF.para
(rad_haplotyper_env) [evelyn-takyi@n038 Aurita_Final2]$ ./remove.bad.hap.loci.sh HF.loci.tofilter  SNP.DP3gdp5MIp25g9HWE.recode.vcf  
(rad_haplotyper_env) [evelyn-takyi@n038 Aurita_Final2]$ mawk '!/#/' SNP.DP3gdp5MIp25g9HWE.filtered.vcf | wc -l
3202 SNP loci
```
##### Next we need to remove indels in our data since our focus is on SNPs. To do this we  converted our variant calls to SNPS and indels using vcflib and use VCFtools to remove indels.

```vcfallelicprimitives -k -g SNP.DP3gdp5MIp25g9HWE.filtered.vcf| sed 's:\.|\.:\.\/\.:g' > TRSdp5MIp25g9.prim
(rad_haplotyper_env) [evelyn-takyi@n038 Aurita_Final2]$ vcftools --vcf TRSdp5MIp25g9.prim --recode-INFO-all --recode --out SNP.DP3g95maf05d --remove-indels
```
After filtering, kept 2847 out of a possible 3202 Sites

###### We then restrict loci to a maximum of 2 alleles.
```
vcftools --vcf SNP.DP3g95maf05d.recode.vcf  --recode-INFO-all --max-alleles 2 --out SNP.2a --recode
```
After filtering, kept 2776 out of a possible 2847 Sites

##### Finally filter loci not genotyped in about 50% of the individuals.
```
vcftools --vcf SNP.2a.recode.vcf --recode-INFO-all --max-missing 0.5 --out SNP.dp5a --recode
```
After filtering, kept 1393 out of a possible 2776 Sites
#####  To investigate how many loci are remaining in our file
```
mawk '!/#/' SNP.dp5a.recode.vcf | wc -l
```
1393 SNPs loci

##### PGDSpider was used to convert SNPs to BayeScan input file.
```
BayeScan2.1_linux64bits SNP1.BS -thin 100 -nbp 30
```
##### A VCF file of SNPs of outliers loci and neutral loci was generated with a false discovery rate of 10% using VCFtoOutlierOnly.sh

```
./VCFtoOutlierOnly.sh SNP.dp5a.recode.vcf  SNPDP5_fst.txt  0.1 SNPAUdp  

	--out SNPAUdp.outlieronly
After filtering, kept 11 outliers out of a possible 1393 Sites

	--out SNPAUdp.neutralonly

After filtering, kept 100 out of 100 Individuals
After filtering, kept 1382 neutral loci out of a possible 1393 Sites
```

### Analysis of our final filtered neutral SNPs
##### 1. Calculate basic population genetic statistics to determine genetic diversity in the population.
###### populations program in STACKS package was used in outputing the statistics
```
code:
populations -V SNP.dp5a.recode.vcf  -O /data3/marine_diseases_lab/evelyn/eveproject/evelyn/gridftp.tamucc.edu/genomics/20180312-Takyi-Sardinella/Aurita_Final2/ -M popmap --fstats --fst_correction p_value  --bootstrap  --kernel_smooth --genepop --structure
```


 | Population | No.of individuals| Sites | Polymorphic Sites | % Polymorphic Loci | Obs Het | Exp Het | Fis    |
|------------|-----------------|-------|-------------------|--------------------|---------|---------|----------
| Benin      | 15              | 1383  | 1330              | 96.1678            | 0.6296  | 0.3823  | -0.4602 |
| Ghana      | 19              | 1383  | 1333              | 96.3847            | 0.6104  | 0.3744  | -0.4462 |
| Guinea     | 7               | 1383  | 967               | 69.9205            | 0.5388  | 0.308   | -0.173  |
| Mauritania | 19              | 1383  | 1308              | 94.577             | 0.6269  | 0.3759  | -0.4808 |
| Senegal    | 17              | 1383  | 1355              | 97.9754            | 0.6317  | 0.3895  | -0.467  |
| Togo       | 20              | 1383  | 1359              | 98.2646            | 0.6246  | 0.3876  | -0.4631 |


#### 2. Determine genetic differentiation in the population
#### The overall FST and FIS values were calculated using the diffcalc function in the genepop package in R. This will output FST and FIS values for each population together with thier confidence interval(CI)
```test_result <- diffCalc(infile = "SNPAUdp.neutralonly.recode.gen", outfile = "myresults",fst = TRUE, pairwise = TRUE, bs_locus = TRUE, bs_pairwise = TRUE, boots = 1000, para = TRUE)
```
overall FST  = 0.0080	 CI (0.0019-0.0157)

overall FIS  = -0.6061 CI	(-0.6557 - -0.5746)

#### Pairwise FST values was calculated using the program Genodive
 Values of Fst for all pairs of populations is significant at (p<0.05)

  |            | Benin  | Ghana | Guinea | Mauritania | Senegal |
 |------------|--------|-------|--------|------------|---------|
 | Benin      |        |       |        |            |         |
 | Ghana      | -0.002 |       |        |            |         |
 | Guinea     | 0.05   | 0.063 |        |            |         |
 | Mauritania | 0      | 0.001 | 0.072 |            |         |
 | Senegal    | 0.004  | 0.007 | 0.029  | 0.009      |         |
 | Togo       | 0.003  | 0.007 | 0.029  | 0.009      | -0.002  |

##### p-values for all pairs of populations
 |            | Benin  | Ghana | Guinea | Mauritania | Senegal |
|------------|--------|-------|--------|------------|---------|
| Benin      |        |       |        |            |         |
| Ghana      | 0.823  |       |        |            |         |
| Guinea     | 0.00   | 0.00  |        |            |         |
| Mauritania | 0.53   | 0.13  | 0.00   |            |         |
| Senegal    | 0.07   | 0.022 | 0.005  | 0.007      |         |
| Togo       | 0.095  | 0.01  | 0.002  | 0.002      | 0.814   |


#### 3. To determine if any population structure exist in the populations.
#### A dendrogram  was generated using the function aboot in the poppr package in R
```{r}
bov_pop <- genind2genpop(genindB)
set.seed(20150428)
pop_tree <- aboot(bov_pop, sample = 1000, cutoff = 50)
```
![Plot](https://github.com/evelyn-takyi/Sardinella-project/blob/master/All%20plot/jessy3.png)


#### PCA plot was generated using the package  genlight in R
```{r}
rubi.pca <- glPca(aa.genlight, nf = 3)
barplot(rubi.pca$eig/sum(rubi.pca$eig), col = heat.colors(50), main="PCA Eigenvalues")
title(ylab="Percent of variance\nexplained", line = 2)
title(xlab="Eigenvalues", line = 1)

rubi.pca.scores <- as.data.frame(rubi.pca$scores)
rubi.pca.scores$pop <- pop(aa.genlightA)

library(ggplot2)
set.seed(9)
p <- ggplot(rubi.pca.scores, aes(x=PC1, y=PC2, colour=pop))
p <- p + geom_point(size=2)
p <- p + stat_ellipse(level = 0.95, size = 1)
p <- p + geom_hline(yintercept = 0)
p <- p + geom_vline(xintercept = 0)
p <- p + theme_bw()
p

```
![plot2](https://github.com/evelyn-takyi/Sardinella-project/blob/master/All%20plot/jessy4.png)  

##### Get percent contribution of each PC for representing variation.
```
eig.perc <- 100*rubi.pca$eig/sum(pca$eig)
head(eig.perc)
```
```{r}
0.13773474
0.04274037
0.02950127
0.02727903
0.02644892
0.02551657
```
#### Discriminant analysis of principal components (DAPC) was conducted in R using  the package Adegenet 1.3.0 to generate the number of clusters or groups present in our population

```
set.seed(20160308) # Setting a seed for a consistent result
grp <- find.clusters(genindB, max.n.clust = 10, n.pca = 45, choose.n.clust = TRUE)
names(grp)
grp$grp
dapc1 <- dapc(genindB, grp$grp, n.pca = 10, n.da = 2)
scatter(dapc1) # plot of the group
```
###### This outputs the DAPC plot and the BIC plot showing the number of groups.
![Dapc_BIC](https://github.com/evelyn-takyi/Sardinella-project/blob/master/dapc_BIC.png)
![Dapc_plo](https://github.com/evelyn-takyi/Sardinella-project/blob/master/All%20plot/jessy%20DAPC.png)

#### structure-like plot
##### DAPC function generates the posterior probability of each sample to a group and using that information to generate a structure plot
```{r}
dapcB.results <- as.data.frame(dapc1$posterior)
dapcB.results$pop <- pop(genindB)
dapcB.results$indNames <- rownames(dapcB.results)
library(reshape2)
dapcB.results <- melt(dapcB.results)
colnames(dapcB.results) <- c("Original_Pop","Sample","Assigned_Pop","Posterior_membership_probability")

p <- ggplot(dapcB.results, aes(x=Sample,y=Posterior_membership_probability, fill=Assigned_Pop))
p <- p + geom_bar(stat='identity')
p <- p + facet_grid(~Original_Pop, scales = "free")
p <- p + theme(axis.text.x = element_text(angle = 90, hjust = 1, size = 5))
```
##### To represent the plot in a piechart format,
###### i first of all calculated the  mean Posterior_membership_probability per population
grouped_data <- group_by(dapcB.results, Original_Pop, Assigned_Pop)
data_means <- summarise(grouped_data, mean=mean(Posterior_membership_probability))
######  plot means for each original pop colored by assigned pop
pieB <- ggplot(data_means, aes(x=Original_Pop,y=mean, fill=Assigned_Pop))
pieB <- pieB + geom_bar(stat='identity') + cp
pieB <- pieB + facet_grid(~Original_Pop, scales = "free") + theme(axis.text=element_blank(), axis.ticks=element_blank(), panel.grid = element_blank(), strip.background = element_blank())
pieB

![Plot3](https://github.com/evelyn-takyi/Sardinella-project/blob/master/All%20plot/jessy5.png)

##### Isolation by distance plot
```{r}
xy <- read.table("~/Desktop/AMresults/S_auritadismatrix.txt")
genindB@other$xy <- xy
genindB

titi <- genind2genpop(genindB)
genetic_distance <- dist.genpop(titi, method=2)
geographic_distance <- dist(titi$other$xy)
plot(geographic_distance, genetic_distance)
abline(lm(genetic_distance~geographic_distance), col="red",lty=2)
ibd <- mantel.randtest(genetic_distance,geographic_distance)
plot(ibd)
```
![plot4](https://github.com/evelyn-takyi/Sardinella-project/blob/master/All%20plot/jessy6.png)



## S. maderensis
### Denovo Assembly of references

a. I run the script ReferenceOpt.sh  to pick the cut off values of K1 and K2 and a similarity threshold.
```
bash ReferenceOpt.sh 4 4 2 2 PE 20
```
###### cat kopt.data 
 kopt.data

| 4 | 2 | 0.80 | 20285 |
|---|---|------|-------|
| 4 | 2 | 0.82 | 20323 |
| 4 | 2 | 0.84 | 20364 |
| 4 | 2 | 0.86 | 20383 |
| 4 | 2 | 0.88 | 20400 |
| 4 | 2 | 0.90 | 20422 |
| 4 | 2 | 0.92 | 20520 |
| 4 | 2 | 0.94 | 20623 |
| 4 | 2 | 0.96 | 20721 |
| 4 | 2 | 0.98 | 20845 |

![plot2](https://github.com/evelyn-takyi/Sardinella-project/blob/master/RefoptA.png)

The similarity threshold of 90% is observed to be the appropriate cut off value.

b. The script RefMapOpt.sh was run to pick K1, K2 values which were properly paired and good coverage, minimizing mismatched reads.

```
bash RefMapOpt.sh 2 5 2 5 0.9 20 PE
```
Kopt data

| 2 | 2 | 0.80 | 181457 |
|---|---|------|--------|
| 2 | 2 | 0.82 | 182072 |
| 2 | 2 | 0.84 | 182606 |
| 2 | 2 | 0.86 | 183057 |
| 2 | 2 | 0.88 | 183387 |
| 2 | 2 | 0.90 | 183620 |
| 2 | 2 | 0.92 | 185130 |
| 2 | 2 | 0.94 | 186665 |
| 2 | 2 | 0.96 | 188208 |
| 2 | 2 | 0.98 | 189824 |
| 2 | 3 | 0.80 | 60780  |
| 2 | 3 | 0.82 | 60919  |
| 2 | 3 | 0.84 | 61047  |
| 2 | 3 | 0.86 | 61153  |
| 2 | 3 | 0.88 | 61214  |
| 2 | 3 | 0.90 | 61264  |
| 2 | 3 | 0.92 | 61558  |
| 2 | 3 | 0.94 | 61894  |
| 2 | 3 | 0.96 | 62214  |
| 2 | 3 | 0.98 | 62552  |
| 2 | 4 | 0.80 | 25658  |
| 2 | 4 | 0.82 | 25698  |
| 2 | 4 | 0.84 | 25745  |
| 2 | 4 | 0.86 | 25777  |
| 2 | 4 | 0.88 | 25797  |
| 2 | 4 | 0.90 | 25816  |
| 2 | 4 | 0.92 | 25900  |
| 2 | 4 | 0.94 | 26015  |
| 2 | 4 | 0.96 | 26117  |
| 2 | 4 | 0.98 | 26221  |
| 2 | 5 | 0.80 | 11647  |
| 2 | 5 | 0.82 | 11666  |
| 2 | 5 | 0.84 | 11678  |
| 2 | 5 | 0.86 | 11690  |
| 2 | 5 | 0.88 | 11697  |
| 2 | 5 | 0.90 | 11704  |
| 2 | 5 | 0.92 | 11741  |
| 2 | 5 | 0.94 | 11783  |
| 2 | 5 | 0.96 | 11828  |
| 2 | 5 | 0.98 | 11868  |
Mapping results

|         |         |         |                   |    |    |            |              |             |
|---------|---------|---------|-------------------|----|----|------------|--------------|-------------|
| Cov     | Non0Cov | Contigs | MeanContigsMapped | K1 | K2 | SUM Mapped | SUM Properly | Mean Mapped |
| 7.53407 | 12.65   | 183620  | 114239            | 2  | 2  | 16600951   | 11344500     | 1.38E+06    |
| 14.1841 | 21.3783 | 61264   | 43034.2           | 2  | 3  | 10427872   | 6597936      | 868989      |
| 24.4562 | 35.1343 | 25816   | 19187.4           | 2  | 4  | 7576629    | 4590766      | 631386      |
| 16.8484 | 25.7664 | 50495   | 34515.1           | 3  | 2  | 10209312   | 6458448      | 850776      |
| 42.9016 | 60.4159 | 13624   | 10106.7           | 3  | 3  | 7014410    | 3968219      | 584534      |
| 85.9141 | 114.759 | 5118    | 3957.25           | 3  | 4  | 5277534    | 2940855      | 439794      |
| 39.1148 | 56.5291 | 16092   | 11408.6           | 4  | 2  | 7553693    | 4321675      | 629474      |
| 102.171 | 139.566 | 4451    | 3323.25           | 4  | 3  | 5458361    | 2912050      | 454863      |
| 179.742 | 236.671 | 1955    | 1527.83           | 4  | 4  | 4218912    | 2390190      | 351576   


c. The script  remake_reference.sh was used to remake the reference with the cut off value of K1=2, K2=3, and a c value of 0.9

```
bash remake_reference.sh 2 3 0.90 PE 20
mawk '/>/' reference.fasta | wc -l
```
**61264** Contigs were assembled for *S.maderensis*

## Blast sequences from ncbi to my denovo reference assembly on the commandline
#### build a database of the reference assembly
```
makeblastdb -in reference.fasta -parse_seqids  -title "mad" -dbtype nucl
```
```
Building a new DB, current time: 02/13/2019 22:23:18
New DB name:   /net/fs03.cluster.com/data3/marine_diseases_lab/evelyn/eveproject/evelyn/gridftp.tamucc.edu/genomics/20180312-Takyi-Sardinella/maderensis_Final2/No_NM/reference/reference.fasta
New DB title:  mad
Sequence type: Nucleotide
Keep Linkouts: T
Keep MBits: T
Maximum file size: 1000000000B
Adding sequences from FASTA; added 61264 sequences in 2.07483 seconds.
```
#### perform a nucleotide blast on references
```
blastn -query sequence.fasta  -db reference.fasta.3 -out results.txt2
```
```
Database: maderensis
           61,264 sequences; 17,686,769 total letters
Query= DQ197991.1 Sardinella maderensis cytochrome b (cytb) gene, complete
cds; mitochondrial
Length=1141
                                                                      Score     E
Sequences producing significant alignments:                          (Bits)  Value
dDocent_Contig_21512                                                  436     5e-122
dDocent_Contig_3189                                                   366     7e-101
dDocent_Contig_18897                                                  351     2e-96
dDocent_Contig_19547                                                  316     7e-86
dDocent_Contig_688                                                    233     8e-61

Query= MG958221.1 Sardinella maderensis voucher MNHN-IC 2013-0981-BPS-2657
cytochrome b gene, partial cds; mitochondrial
Length=1143
                                                                      Score     E
Sequences producing significant alignments:                          (Bits)  Value

dDocent_Contig_21512                                                  436     5e-122
dDocent_Contig_3189                                                   372     2e-102
dDocent_Contig_18897                                                  357     4e-98
dDocent_Contig_19547                                                  300     7e-81
dDocent_Contig_688                                                    259     1e-68

Query= KY176607.1 Sardinella maderensis voucher 981 cytochrome c oxidase
subunit I (COI) gene, partial cds; mitochondrial
Length=642
                                                                      Score     E
Sequences producing significant alignments:                          (Bits)  Value

dDocent_Contig_839                                                    527     2e-149
dDocent_Contig_262                                                    305     9e-83
dDocent_Contig_957                                                    265     1e-70
dDocent_Contig_10743                                                  233     4e-61

Query= KX062183.1 Sardinella maderensis isolate SMAD4 tRNA-Glu (trnE) gene,
partial sequence; and cytochrome b (cytb) gene, partial cds;
mitochondrial
Length=414
                                                                      Score     E
Sequences producing significant alignments:                          (Bits)  Value
dDocent_Contig_3189                                                   361     1e-99
dDocent_Contig_19547                                                  335     7e-92
dDocent_Contig_18897                                                  289     6e-78

Query= KP307745.1 Sardinella maderensis voucher TAU<ISR_:P.15439 16S
ribosomal RNA gene, partial sequence; mitochondrial
Length=586
                                                                      Score     E
Sequences producing significant alignments:                          (Bits)  Value
dDocent_Contig_8343                                                   327     2e-89
dDocent_Contig_1361                                                   148     1e-35

Query= NC_009587.1 Sardinella maderensis mitochondrion, complete genome
Length=16651
                                                                      Score     E
Sequences producing significant alignments:                          (Bits)  Value
dDocent_Contig_23265                                                  534     3e-150
dDocent_Contig_839                                                    532     1e-149
dDocent_Contig_2057                                                   520     8e-146
dDocent_Contig_985                                                    503     8e-141
dDocent_Contig_6519                                                   497     4e-139
dDocent_Contig_22457                                                  496     1e-138
dDocent_Contig_40235                                                  494     5e-138
dDocent_Contig_688                                                    468     3e-130
dDocent_Contig_1720                                                   464     4e-129
dDocent_Contig_19547                                                  460     5e-128
dDocent_Contig_2959                                                   459     2e-127
dDocent_Contig_3936                                                   457     6e-127
dDocent_Contig_8343                                                   453     8e-126
dDocent_Contig_21512                                                  448     4e-124
dDocent_Contig_1361                                                   409     2e-112
dDocent_Contig_262                                                    407     6e-112
dDocent_Contig_10236                                                  398     4e-109
dDocent_Contig_8419                                                   383     1e-104
dDocent_Contig_965                                                    381     4e-104
dDocent_Contig_3189                                                   377     5e-103
dDocent_Contig_1696                                                   377     5e-103
dDocent_Contig_18897                                                  357     6e-97
dDocent_Contig_15907                                                  357     6e-97
dDocent_Contig_434                                                    320     8e-86
dDocent_Contig_8029                                                   316     1e-84
dDocent_Contig_5320                                                   316     1e-84
dDocent_Contig_312                                                    315     4e-84
dDocent_Contig_52690                                                  292     2e-77
dDocent_Contig_46683                                                  285     3e-75
dDocent_Contig_54810                                                  279     1e-73
dDocent_Contig_15265                                                  279     1e-73
dDocent_Contig_3660                                                   279     1e-73
dDocent_Contig_957                                                    279     1e-73
dDocent_Contig_4870                                                   278     5e-73
dDocent_Contig_46861                                                  274     7e-72
dDocent_Contig_24625                                                  272     2e-71
dDocent_Contig_58                                                     272     2e-71
dDocent_Contig_2463                                                   268     3e-70
dDocent_Contig_10743                                                  233     1e-59
dDocent_Contig_901                                                    224     7e-57
dDocent_Contig_14455                                                  196     1e-48
dDocent_Contig_444                                                    193     2e-47

Query= AM911205.1 Sardinella maderensis mitochondrial partial 16S rRNA gene
Length=568
                                                                      Score     E
Sequences producing significant alignments:                          (Bits)  Value
dDocent_Contig_8343                                                   329     5e-90
dDocent_Contig_1361                                                   141     2e-33

Query= AM911175.1 Sardinella maderensis mitochondrial partial coi gene for cytochrome oxidase subunit I
Length=594
                                                                     E
Sequences producing significant alignments:                          (Bits)  Value
dDocent_Contig_839                                                    532     3e-151
dDocent_Contig_262                                                    289     8e-78
dDocent_Contig_957                                                    265     1e-70
dDocent_Contig_10743                                                  233     4e-61
```


### The dDocent pipeline was used to map all the reads to the reference assembly and variant  calling

#### Filtering of raw SNP calls using vcftools and bash scripts
```
vcftools --vcf TotalRawSNPs.vcf --max-missing 0.5 --mac 3 --minQ 20 --recode --recode-INFO-all --out raw.g5mac3
```
After filtering, kept 142840 out of a possible 985007 Sites

```
/filter_missing_ind.sh raw.g5mac3.recode.vcf DP3g95maf05
```
After filtering, kept 142840 out of a possible 142840 Sites


```

                                       Histogram of % missing data per individual                                       

  6 +-+-----**-+----------+-----------+----------+----------+----------+----------+-----------+----------+--------+-+   
    +       ** +          +           +          +          +          +          +           +          +          +   
    |       **                                                'totalmissing' using (bin($1,binwidth)):(1.0) ******* |   
    |       **                                                                                                      |   
    |       **                                                                                                      |   
  5 +-+   ****                                                                       **                           +-+   
    |     ****                                                                       **                             |   
    |     ****                                                                       **                             |   
    |     ****                                                                       **                             |   
  4 +-+   *****      **                     ***                                      **                           +-+   
    |     *****      **                     * *                                      **                             |   
    |     *****      **                     * *                                      **                             |   
    |     *****      **                     * *                                      **                             |   
    |     *****      **                     * *                                      **                             |   
  3 +**** ***** **** ** **  **  **          * *                                  **  **              ***          +-+   
    |**** ***** ** * ** **  **  **          * *                                  **  **              * *            |   
    |**** ***** ** * ** **  **  **          * *                                  **  **              * *            |   
    |**** ***** ** * ** **  **  **          * *                                  **  **              * *            |   
  2 +**** ******** *******  ******    **    * *   **                   *****     ******   ******     * **         +-+   
    |**** ******** *******  ******    **    * *   **                   * * *     ** ***   * *  *     * **           |   
    |**** ******** *******  ******    **    * *   **                   * * *     ** ***   * *  *     * **           |   
    |**** ******** *******  ******    **    * *   **                   * * *     ** ***   * *  *     * **           |   
    +**** ******** *******+ ******    **    * *  +**        +          * * *     ** ***   * * +*     * **+          +   
  1 +****-****************+-******----**----***--+**--------+----------*****-----******---******-----****+--------+-+   
    0         0.1        0.2         0.3        0.4        0.5        0.6        0.7         0.8        0.9         1   
                                                    % of missing data                                                   

The 85% cutoff would be 0.775686
Would you like to set a different cutoff, yes or no
no

Excluding individuals in 'exclude' list
After filtering, kept 106 out of 122 Individuals
Outputting VCF file...
After filtering, kept 142840 out of a possible 142840 Sites
```

```
vcftools --vcf DP3g95maf05.recode.vcf --minDP 5 --maf 0.01 --recode --recode-INFO-all --out raw.g5mac3dp3
```
After filtering, kept 107565 out of a possible 142840 Sites

```
./pop_missing_filter.sh raw.g5mac3dp3.recode.vcf popmap 0.9 1 TRSdp5MIp25
```
After filtering, kept 21044 out of a possible 107565 Sites

```
./dDocent_filters TRSdp5MIp25.recode.vcf  TRSdp5MIp25g9dd

Number of sites filtered based on allele balance at heterozygous loci, locus quality, and mapping quality / Depth
 12811 of 21044

Are reads expected to overlap?  In other words, is fragment size less than 2X the read length?  Enter yes or no.
Number of additional sites filtered based on overlapping forward and reverse reads
2415 of 8233

Is this from a mixture of SE and PE libraries? Enter yes or no.
no

Number of additional sites filtered based on properly paired status
51 of 5818

Number of sites filtered based on high depth and lower than 2*DEPTH quality score
1893 of 5767



                                        Histogram of mean depth per site                                           
                                                                                                                    180+-+-+---+----+---+---+---+----+---+---+---+----+---+---+---+---+----+---+---+---+----+---+---+---+----+---+-+-*****   +    +   +   +   +    +   +   +   +    +   +   +   +   +    +   +   +   +    +   +   +   +    +   +   +   
  *   *                                               'meandepthpersite' using (bin($1,binwidth)):(1.0) ******|   
160 *-+ * +-+ *                                                                                               |   
140 *-+ *                                                                                          +-+ *                                                                                             |   
  *   *****                                                                                                     |   
120 *-+ *   *                                                                                                   +-+   
  *   *   *                                                                                                     |   
100 *-+ *   *                                                                                                   +-+   
  *   *   ******                                                                                                |   
  *   *   *    *****                                                                                            |   
80 *-+ *   *    *   *                                                                                          +-+   
  *   *   *    *   *                                                                                            |   
60 *-+ *   *    *   *********                                                                                  +-+   
  *   *   *    *   *   *   *                                                                                    |   
  *   *   *    *   *   *   *                                                                                    |   
40 *-+ *   *    *   *   *   *                                     ******                                       +-+   
  *   *   *    *   *   *  ***************************           *    *                                         |   
20 *-+ *   *    *   *   *   *    *   *   *   *    *   *************    *****       **********                  +-+   
  *   *   *    *   *   *   *    *   *   *   *    *   *   *   *   *    *   *****   *    *   *********        *****   
  *   *   *    *   *   *   *    *   *   *   *    *   *   *   *   *    *   *   *****    *   *   *   **********   *   
0 ***************************************************************************************************************   
  10  11  12   13  14  15  16   17  18  19  20   21  22  23  24  25   26  27  28  29   30  31  32  33   34  35  36  
                                                  Mean Depth                                                      

If distrubtion looks normal, a 1.645 sigma cutoff (~90% of the data) would be 4136.80545
The 95% cutoff would be 33
Would you like to use a different maximum mean depth cutoff than 33, yes or no
no
Number of sites filtered based on maximum mean depth
362 of 5767

Number of sites filtered based on within locus depth mismatch
18 of 5405

Total number of sites filtered
15657 of 21044

Remaining sites
5387

```

```
vcftools --vcf TRSdp5MIp25g9dd.FIL.recode.vcf --maf 0.05 --recode --recode-INFO-all --out DP3g95maf05d
```
After filtering, kept 3420 out of a possible 5387 Sites

```
rad_haplotyper.pl -v SNP.DP3gdp5MIp25g9HWE.recode.vcf  -x 10 -mp 2 -r reference.fasta
[evelyn-takyi@n038 Aurita_Final2]$ cp stats.out stats.out.HF
(rad_haplotyper_env) [evelyn-takyi@n038 Aurita_Final2]$ mawk ...'/Missi/' stats.out.HF | mawk '$9 > 30' > HF.missing
(rad_haplotyper_env) [evelyn-takyi@n038 Aurita_Final2]$ mawk ...'/para/' stats.out.HF > HF.para
(rad_haplotyper_env) [evelyn-takyi@n038 Aurita_Final2]$ ./remove.bad.hap.loci.sh HF.loci.tofilter SNP.DP3gdp5MIp25g9HWE.recode.vcf  
(rad_haplotyper_env) [evelyn-takyi@n038 Aurita_Final2]$ mawk '!/#/' SNP.DP3gdp5MIp25g9HWE.filtered.vcf | wc -l
1479
```
```
vcfallelicprimitives -k -g SNP.DP3gdp5MIp25g9HWE.filtered.vcf| sed 's:\.|\.:\.\/\.:g' > TRSdp5MIp25g9.prim
vcftools --vcf TRSdp5MIp25g9.prim --recode-INFO-all --recode --out SNP.DP3g95maf05d --remove-indels
```
After filtering, kept 1592 out of a possible 1718 Sites

```
vcftools --vcf SNP.DP3g95maf05d.recode.vcf  --recode-INFO-all --max-alleles 2 --out SNP.2a --recode
```
After filtering, kept 1562 out of a possible 1592 Sites

##### Use PGDSpider to convert SNPs to BayeScan input file.
##### BayeScan2.1_linux64bits SNP1.BS -thin 100 -nbp 30
##### Create a VCF file of SNPs of outliers with a false discovery rate of 10%

```
./VCFtoOutlierOnly.sh SNPM.2a.recode.vcf  SNPMA_fst.txt  0.1 SNPMAdp  

Parameters as interpreted:
	--vcf SNPM.2a.recode.vcf
	--recode-INFO-all
	--out SNPMAdp.outlieronly
	--positions Outlier.list
	--recode

After filtering, kept 106 out of 106 Individuals
After filtering, kept 3 out of a possible 1562 Sites


VCFtools - 0.1.14
(C) Adam Auton and Anthony Marcketta 2009

Parameters as interpreted:
	--vcf SNPM.2a.recode.vcf
	--exclude-positions Outlier.list
	--recode-INFO-all
	--out SNPMAdp.neutralonly
	--recode

After filtering, kept 106 out of 106 Individuals
After filtering, kept 1559 out of a possible 1562 Sites
```

### Analysis of the neutral population genetic structure
#### Basic statistics

| Population |No. of samples		|Private alleles   | Sites | Polymorphic Sites | % Polymorphic Loci | Obs Het | Exp Het |  Fis     |
|------------|--------------------|------------------|-------|-------------------|--------------------|---------|---------|----------|
| Benin      |  19                 |    9             | 1559  | 954               | 61.1931            | 0.266   | 0.1927  | -0.1339  |
| Guinea     | 12                  |    2             | 1559  | 713               | 45.7344            | 0.2464  | 0.173   | -0.0803  |
| Mauritania | 21                  |    5             | 1559  | 902               | 57.8576            | 0.2536  | 0.184   | -0.1189  |
| Nigeria    | 15                  |    447           | 1559  | 1013              | 64.9775            | 0.2212  | 0.2501  |  0.1936  |
| Senegal    | 18                  |    4             | 1559  | 867               | 55.6126            | 0.2564  | 0.1828  | -0.1227  |
| Togo       | 21                  |    2             | 1559  | 885               | 56.7672            | 0.2616  | 0.1883  | -0.1262  |


#### The overall FST and FIS values were calculated using the diffcalc function in the genepop package in R
```test_result <- diffCalc(infile = "SNPmadp.neutralonly.recode.gen", outfile = "madresults",fst = TRUE, pairwise = TRUE, bs_locus = TRUE, bs_pairwise = TRUE, boots = 1000, para = TRUE)
```
overall FST  =  0.1931	 CI (0.0858 - 0.3720)
overall FIS  = -0.1857	CI (-0.4258	- -0.0848)


#### Pairwise FST values calculated using the program Genodive
 Values of Fst for all pairs of populations is significant at (p<0.05)

 |            | Benin  | Guinea | Mauritania | Nigeria | Senegal |
 |------------|--------|--------|------------|---------|---------|
 | Benin      |        |        |            |         |         |
 | Guinea     | -0.003 |        |            |         |         |
 | Mauritania | 0      | 0      |            |         |         |
 | Nigeria    | 0.392  | 0.339  | 0.381      |         |         |
 | Senegal    | 0.002  | 0.006  | -0.002     | 0.368   |         |
 | Togo       | -0.005 | 0.016  | 0.007      | 0.374   | 0.009   |

p-values for all pairs of populations

  |            | Benin  | Guinea | Mauritania | Nigeria | Senegal |
  |------------|--------|--------|------------|---------|---------|
  | Benin      |        |        |            |         |         |
  | Guinea     | 0.562  |        |            |         |         |
  | Mauritania | 0.520  | 0.021  |            |         |         |
  | Nigeria    | 0.003  | 0.573  | 0.003      |         |         |
  | Senegal    | 0.354  | 0.240  | 0.652      | 0.003   |         |
  | Togo       | 0.818  | 0.037  | 0.092      | 0.003   | 0.061   |



### UPGMA tree
 ```{r}
 bov_pop <- genind2genpop(genindB)
 set.seed(20150428)
 pop_tree <- aboot(bov_pop, sample = 1000,
                            cutoff = 50)
```                            
![plot1](https://github.com/evelyn-takyi/Sardinella-project/blob/master/All%20plot/jessy7.png)


### DAPC

```set.seed(20160308) # Setting a seed for a consistent result
grp <- find.clusters(genindB, max.n.clust = 10, n.pca = 55, choose.n.clust = TRUE)
names(grp)
grp$grp
dapc1 <- dapc(genindB, grp$grp, n.pca = 10, n.da = 2)
scatter(dapc1) # plot of the group
```

![Dapc_BIC](https://github.com/evelyn-takyi/Sardinella-project/blob/master/BIC_MAD.png)

### structure-like plot using Posterior probability from dapc function
```
dapcB.results <- as.data.frame(dapc1$posterior)
dapcB.results$pop <- pop(genindB)
dapcB.results$indNames <- rownames(dapcB.results)
library(reshape2)
dapcB.results <- melt(dapcB.results)
colnames(dapcB.results) <- c("Original_Pop","Sample","Assigned_Pop","Posterior_membership_probability")

p <- ggplot(dapcB.results, aes(x=Sample,y=Posterior_membership_probability, fill=Assigned_Pop))
p <- p + geom_bar(stat='identity')
p <- p + facet_grid(~Original_Pop, scales = "free")
p <- p + theme(axis.text.x = element_text(angle = 90, hjust = 1, size = 5))
p

calculate mean per population
grouped_data <- group_by(dapcB.results, Original_Pop, Assigned_Pop)
data_means <- summarise(grouped_data, mean=mean(Posterior_membership_probability))
# plot means for each original pop colored by assigned pop
pieB <- ggplot(data_means, aes(x=Original_Pop,y=mean, fill=Assigned_Pop))
pieB <- pieB + geom_bar(stat='identity') + cp
pieB <- pieB + facet_grid(~Original_Pop, scales = "free") + theme(axis.text=element_blank(), axis.ticks=element_blank(), panel.grid = element_blank(), strip.background = element_blank())
pieB

cp <- coord_polar(theta = "y")
cp$is_free <- function() TRUE
```
![Plot3](https://github.com/evelyn-takyi/Sardinella-project/blob/master/All%20plot/jessy8.png)


### Analysis without Nigerian populatiion
#### Basic Statistic

| Population | Private Alleles | Sites | Polymorphic Sites | % Polymorphic Loci | Obs Het | Exp Het | nucleotide diversity | Fis     |
|------------|-----------------|-------|-------------------|--------------------|---------|---------|----------------------|---------|
| Benin      | 22              | 1112  | 954               | 85.7               | 0.372   | 0.270   | 0.284               | -0.187   |
| Guinea     | 2               | 1112  | 713               | 64.1               | 0.345   | 0.242   | 0.285               | -0.113   |
| Mauritania | 12              | 1112  | 902               | 81.1               | 0.355   | 0.258   | 0.276               | -0.167   |
| Senegal    | 24              | 1112  | 867               | 77.96              | 0.359   | 0.256   | 0.276               | -0.172   |
| Togo       | 17              | 1112  | 885               | 79.58              | 0.367   | 0.263   | 0.282               | -0.176   |


#### The overall FST and FIS values were calculated using the diffcalc function in the genepop package in R
```
wc(genindNM)
```
$FST
[1] 0.001773188

$FIS
[1] -0.3120278



#### Pairwise FST values calculated using the program Genodive
 Values of Fst for all pairs of populations is significant at (p<0.05)

 |            | Benin  | Guinea | Mauritania | Senegal |
 |------------|--------|--------|------------|---------|
 | Benin      |        |        |            |         |         
 | Guinea     | -0.003 |        |            |         |         
 | Mauritania | 0      | 0      |            |         |         
 | Senegal    | 0.002  | 0.006  | -0.002     |         |       
 | Togo       | -0.005 | 0.016  | 0.007      | 0.009   |

p-values for all pairs of populations

  |            | Benin  | Guinea | Mauritania | Senegal |
  |------------|--------|--------|------------|---------|
  | Benin      |        |        |            |         |        
  | Guinea     | 0.532  |        |            |         |        
  | Mauritania | 0.490  | 0.627  |            |         |        
  | Senegal    | 0.321  | 0.227  | 0.641      |         |
  | Togo       | 0.823  | 0.031  | 0.08       | 0.061   |

### Neighbor joining tree
   ```{r}
   bov_pop <- genind2genpop(genindB)
   set.seed(20150428)
   pop_tree <- aboot(bov_pop, sample = 1000,
                              cutoff = 50)
   ```
![Plot3](https://github.com/evelyn-takyi/Sardinella-project/blob/master/All%20plot/jessy10.png)

### structure-like plot using Posterior probability from dapc function

![Plot3](https://github.com/evelyn-takyi/Sardinella-project/blob/master/All%20plot/jessy11.png)


## This analysis was performed combining both reads of *s. aurita* and *S.maderensis*
### AIM: To show whether there is clear differentiation between *s.aurita* and *s.maderensis*

 **1203 neutral loci FINAL FILTERED SNPS**

## Analysis of the neutral SNPs to differentiate between *S.aurita* and *S.maderensis*

##### Packages loaded in R
```
library(vcfR)
library(readr)
library(ggplot2)
library(reshape2)
library(pegas)
library(adegenet)
library(diveRsity)
library(genetics)
library(poppr)
library(readr)
library(ggplot2)
library(ape)
library(ggmap)
library("devtools")
```
#### This code reads the SNP VCF file into R and converts it into a genlight  object.
```{r}
AU1 <- read.vcfR("~/Desktop/FINALANALYSIS/SNPAM.neutralonly.recode.vcf")
aa.genlight <- vcfR2genlight(AU1, n.cores=1)

locNames(aa.genlight) <- paste(AU1@fix[,1],AU1@fix[,2],sep="_")
pop(aa.genlight)<-substr(indNames(aa.genlight),1,3)
aa.genlight@position
as.matrix(aa.genlight)[1:16,1:10]

indNames(aa.genlight)
popNames(aa.genlight)
```
##### This code converts the file into a genind object
```
genindB <- vcfR2genind(AU1)
strata<- read.table("~/Desktop/FINALANALYSIS/popmap.txt", header=TRUE)
strata_df <- data.frame(strata)
strata(genindB) <- strata_df
setPop(genindB) <- ~Population
```
##### Determine the overall FST and FIS values
```
fstat(genindB)
wc(genindB)
```          
$FST
[1] 0.1279823

$FIS
[1] -0.2260168

##### construct a Neighbor joining tree
```
bov_pop <- genind2genpop(genindB)
set.seed(20150428)
pop_tree <- aboot(bov_pop, sample = 1000,
                           cutoff = 50)
```                           
![plot](https://github.com/evelyn-takyi/Sardinella-project/blob/master/All%20plot/jessy2.png)

##### PCA plot showing difference between s.aurita and s.maderensis
```
rubi.pca <- glPca(aa.genlight, nf = 3)
barplot(rubi.pca$eig/sum(rubi.pca$eig), col = heat.colors(50), main="PCA Eigenvalues")
title(ylab="Percent of variance\nexplained", line = 2)
title(xlab="Eigenvalues", line = 1)

rubi.pca.scores <- as.data.frame(rubi.pca$scores)
rubi.pca.scores$pop <- pop(aa.genlight)
```

![PCA plot](https://github.com/evelyn-takyi/Sardinella-project/blob/master/All%20plot/jessy1.png)
