## Determine the population genetic structure of s.aurita and s. maderensis using ddRadseq
### Dataset needed to perform the analysis
#### 1. Radseq Data Sets sequenced on an Illumina HiSeq 2000 PE150 from six populations obtained from West Africa
| Sample   | country    | Geographical site | Longitude | Latitude | Collection date | Species      | Fork length | Girth | Weight | Total Length |
|----------|------------|-------------------|-----------|----------|-----------------|--------------|-------------|-------|--------|--------------|
| GA__A5   | Ghana      | Sekondi-Takoradi  | 0.994     | 5.898    | 2016            | S.aurita     | 15          | 9     | 43.2   | 20           |
| GA_A4    | Ghana      | Sekondi-Takoradi  | 0.994     | 5.898    | 2016            | S.aurita     | 16.5        | 9     | 53.6   | 17           |
| GA_A2    | Ghana      | Sekondi-Takoradi  | 0.994     | 5.898    | 2016            | S.aurita     | 15          | 8.5   | 45.9   | 18           |
| GA_A3    | Ghana      | Sekondi-Takoradi  | 0.994     | 5.898    | 2016            | S.aurita     | 15          | 8.5   | 44.3   | 19           |
| GA_A5    | Ghana      | Sekondi-Takoradi  | 0.994     | 5.898    | 2016            | S.aurita     | 14.5        | 8     | 44.2   | 17           |
| GA_A6    | Ghana      | Sekondi-Takoradi  | 0.994     | 5.898    | 2016            | S.aurita     | 17.5        | 9     | 59.4   | 17           |
| GA_A7    | Ghana      | Sekondi-Takoradi  | 0.994     | 5.898    | 2016            | S.aurita     | 15          | 8.5   | 46.4   | 19.6         |
| GA_A8    | Ghana      | Sekondi-Takoradi  | 0.994     | 5.898    | 2016            | S.aurita     | 16          | 8.5   | 41.2   | 17.4         |
| GA_A9    | Ghana      | Sekondi-Takoradi  | 0.994     | 5.898    | 2016            | S.aurita     | 16.5        | 9.5   | 55.8   | 18           |
| GA_A10   | Ghana      | Sekondi-Takoradi  | 0.994     | 5.898    | 2016            | S.aurita     | 12          | 10    | 44.3   | 19           |
| GA_F6    | Ghana      | Sekondi-Takoradi  | 0.994     | 5.898    | 2016            | S.aurita     | 11.5        | 6     | 17.6   | 13           |
| GA_F7    | Ghana      | Sekondi-Takoradi  | 0.994     | 5.898    | 2016            | S.aurita     | 11.5        | 6     | 17.6   | 13           |
| GA_F8    | Ghana      | Sekondi-Takoradi  | 0.994     | 5.898    | 2016            | S.aurita     | 11          | 6     | 15.7   | 12.6         |
| GA_F9    | Ghana      | Sekondi-Takoradi  | 0.994     | 5.898    | 2016            | S.aurita     | 11.5        | 6     | 16.1   | 13           |
| GA_F10   | Ghana      | Sekondi-Takoradi  | 0.994     | 5.898    | 2016            | S.aurita     | 12          | 6     | 15.3   | 12.5         |
| GA_1B    | Ghana      | Sekondi-Takoradi  | 0.994     | 5.898    | 2016            | S.aurita     | 18          | 10    | 23.6   | 20.5         |
| GA_2B    | Ghana      | Sekondi-Takoradi  | 0.994     | 5.898    | 2016            | S.aurita     | 17          | 10    | 71.9   | 19.6         |
| GA_3B    | Ghana      | Sekondi-Takoradi  | 0.994     | 5.898    | 2016            | S.aurita     | 17          | 9.5   | 68.3   | 20.5         |
| GA_5B    | Ghana      | Sekondi-Takoradi  | 0.994     | 5.898    | 2016            | S.aurita     | 17          | 10    | 66.7   | 20           |
| GA_gha3B | Ghana      | Sekondi-Takoradi  | 0.994     | 5.898    | 2016            | S.aurita     | 17          | 10    | 60.3   | 19           |
| TA_E1    | Togo       | Harbour           | 1.301     | 6.151    | 2016            | S.aurita     | 15          | 8.5   | 45     | 17.5         |
| TA_E2    | Togo       | Harbour           | 1.301     | 6.151    | 2016            | S.aurita     | 17          | 9.5   | 68     | 17           |
| TA_E3    | Togo       | Harbour           | 1.301     | 6.151    | 2016            | S.aurita     | 16          | 9.5   | 62     | 19           |
| TA_E4    | Togo       | Harbour           | 1.301     | 6.151    | 2016            | S.aurita     | 15.5        | 9     | 53     | 19           |
| TA_E5    | Togo       | Harbour           | 1.301     | 6.151    | 2016            | S.aurita     | 15          | 8     | 41     | 18           |
| TA_E6    | Togo       | Harbour           | 1.301     | 6.151    | 2016            | S.aurita     | 15.5        | 8     | 50     | 17           |
| TA_E7    | Togo       | Harbour           | 1.301     | 6.151    | 2016            | S.aurita     | 15          | 9     | 48     | 17.5         |
| TA_E8    | Togo       | Harbour           | 1.301     | 6.151    | 2016            | S.aurita     | 16          | 10    | 61     | 17.5         |
| TA_E9    | Togo       | Harbour           | 1.301     | 6.151    | 2016            | S.aurita     | 15          | 9     | 40     | 19           |
| TA_E10   | Togo       | Harbour           | 1.301     | 6.151    | 2016            | S.aurita     | 18          | 10    | 82     | 17           |
| TA_41    | Togo       | Harbour           | 1.301     | 6.151    | 2016            | S.aurita     | 16          | 9     | 60     | 20.5         |
| TA_44    | Togo       | Harbour           | 1.301     | 6.151    | 2016            | S.aurita     | 16.5        | 8     | 60     | 18.5         |
| TA_45    | Togo       | Harbour           | 1.301     | 6.151    | 2016            | S.aurita     | 14.5        | 9     | 40     | 16.5         |
| TA_47    | Togo       | Harbour           | 1.301     | 6.151    | 2016            | S.aurita     | 17.5        | 10.5  | 70     | 17.5         |
| TA_1Dres | Togo       | Harbour           | 1.301     | 6.151    | 2016            | S.aurita     | 16.5        | 9     | 61     | 20           |
| TA_2Dres | Togo       | Harbour           | 1.301     | 6.151    | 2016            | S.aurita     | 16.5        | 8     | 38     | 19           |
| TA_3Dres | Togo       | Harbour           | 1.301     | 6.151    | 2016            | S.aurita     | 16          | 9     | 59     | 16.5         |
| TA_4D    | Togo       | Harbour           | 1.301     | 6.151    | 2016            | S.aurita     | 16          | 8.5   | 52     | 19           |
| TA_5D    | Togo       | Harbour           | 1.301     | 6.151    | 2016            | S.aurita     | 17.5        | 8     | 47     | 18.5         |
| TA_6Dres | Mauritania | Nouakchott        | -15.978   | 18.0841  | 2016            | S.aurita     | 26.4        | 8.3   | 306    | 0            |
| MA_D2    | Mauritania | Nouakchott        | -15.978   | 18.0841  | 2016            | S.aurita     | 26.1        | 8.1   | 304    | 0            |
| MA_D3    | Mauritania | Nouakchott        | -15.978   | 18.0841  | 2016            | S.aurita     | 28.5        | 8.2   | 360    | 0            |
| MA_D7    | Mauritania | Nouakchott        | -15.978   | 18.0841  | 2016            | S.aurita     | 27.3        | 8.2   | 330    | 0            |
| MA_D8    | Mauritania | Nouakchott        | -15.978   | 18.0841  | 2016            | S.aurita     | 27.5        | 8     | 330    | 0            |
| MA_D9    | Mauritania | Nouakchott        | -15.978   | 18.0841  | 2016            | S.aurita     | 32.5        | 9.5   | 527    | 0            |
| MA_G1    | Mauritania | Nouakchott        | -15.978   | 18.0841  | 2016            | S.aurita     | 24          | 8.4   | 231    | 0            |
| MA_G2    | Mauritania | Nouakchott        | -15.978   | 18.0841  | 2016            | S.aurita     | 24.7        | 8.3   | 259    | 0            |
| MA_G3    | Mauritania | Nouakchott        | -15.978   | 18.0841  | 2016            | S.aurita     | 23.9        | 6.5   | 235    | 0            |
| MA_G4    | Mauritania | Nouakchott        | -15.978   | 18.0841  | 2016            | S.aurita     | 24.5        | 8     | 258    | 0            |
| MA_G5    | Mauritania | Nouakchott        | -15.978   | 18.0841  | 2016            | S.aurita     | 25.2        | 8.5   | 252    | 0            |
| MA_G6    | Mauritania | Nouakchott        | -15.978   | 18.0841  | 2016            | S.aurita     | 22.5        | 7.5   | 202    | 0            |
| MA_G8    | Mauritania | Nouakchott        | -15.978   | 18.0841  | 2016            | S.aurita     | 25.2        | 8.5   | 269    | 0            |
| MA_G10   | Mauritania | Nouakchott        | -15.978   | 18.0841  | 2016            | S.aurita     | 26.6        | 9     | 311    | 0            |
| MA_1A    | Mauritania | Nouakchott        | -15.978   | 18.0841  | 2016            | S.aurita     | 33          | 8.5   | 510    | 0            |
| MA_2A    | Mauritania | Nouakchott        | -15.978   | 18.0841  | 2016            | S.aurita     | 27.5        | 8     | 330    | 0            |
| MA_7A    | Mauritania | Nouakchott        | -15.978   | 18.0841  | 2016            | S.aurita     | 26.8        | 8.5   | 320    | 0            |
| MA_8A    | Mauritania | Nouakchott        | -15.978   | 18.0841  | 2016            | S.aurita     | 27.3        | 8.2   | 330    | 0            |
| MA_9A    | Mauritania | Nouakchott        | -15.978   | 18.0841  | 2016            | S.aurita     | 28.5        | 8.2   | 360    | 0            |
| SA_C1    | Senegal    | Fass Boue         | -16.85    | 14.179   | 2016            | S.aurita     | 25.5        | 6.2   | 260.7  | 30.8         |
| SA_C2    | Senegal    | Fass Boue         | -16.85    | 14.179   | 2016            | S.aurita     | 27.5        | 6     | 296.7  | 32.8         |
| SA_C3    | Senegal    | Fass Boue         | -16.85    | 14.179   | 2016            | S.aurita     | 26.5        | 6.2   | 245.5  | 31.5         |
| SA_C4    | Senegal    | Fass Boue         | -16.85    | 14.179   | 2016            | S.aurita     | 25.1        | 6.5   | 243.3  | 30.7         |
| SA_C5    | Senegal    | Fass Boue         | -16.85    | 14.179   | 2016            | S.aurita     | 25.7        | 6     | 246.2  | 31.1         |
| SA_C6    | Senegal    | Fass Boue         | -16.85    | 14.179   | 2016            | S.aurita     | 26.5        | 6.5   | 281.3  | 31.8         |
| SA_C7    | Senegal    | Fass Boue         | -16.85    | 14.179   | 2016            | S.aurita     | 26.7        | 6     | 252.7  | 32           |
| SA_C8    | Senegal    | Fass Boue         | -16.85    | 14.179   | 2016            | S.aurita     | 26.8        | 6.5   | 231.9  | 31.5         |
| SA_C9    | Senegal    | Fass Boue         | -16.85    | 14.179   | 2016            | S.aurita     | 27.4        | 6.5   | 278.8  | 32.5         |
| SA_C10   | Senegal    | Fass Boue         | -16.85    | 14.179   | 2016            | S.aurita     | 26.7        | 6.1   | 291.6  | 32.3         |
| SA_1C    | Senegal    | Fass Boue         | -16.85    | 14.179   | 2016            | S.aurita     | 25          | 6.3   | 302.1  | 32.1         |
| SA_2C    | Senegal    | Fass Boue         | -16.85    | 14.179   | 2016            | S.aurita     | 25.5        | 6.5   | 251.4  | 31           |
| SA_3C    | Senegal    | Fass Boue         | -16.85    | 14.179   | 2016            | S.aurita     | 27.2        | 6.3   | 285.2  | 32.4         |
| SA_5Cres | Senegal    | Fass Boue         | -16.85    | 14.179   | 2016            | S.aurita     | 27          | 5.7   | 281.4  | 32.5         |
| SA_7Cres | Senegal    | Fass Boue         | -16.85    | 14.179   | 2016            | S.aurita     | 25.7        | 6     | 210.8  | 30.2         |
| SA_8Cres | Senegal    | Fass Boue         | -16.85    | 14.179   | 2016            | S.aurita     | 25          | 6.5   | 231.2  | 30           |
| SA_38    | Senegal    | Fass Boue         | -16.85    | 14.179   | 2016            | S.aurita     | 25.3        | 5.7   | 216.6  | 28.1         |
| SA_4CN   | Senegal    | Fass Boue         | -16.85    | 14.179   | 2016            | S.aurita     | 26.2        | 6.4   | 259    | 31.8         |
| GUI_11   | Guinea     | BOULBINET         | -11.352   | 9.932    | 2017            | S.aurita     | 17          | 4     | 61.1   | 20           |
| GUI_13   | Guinea     | BOULBINET         | -11.352   | 9.932    | 2017            | S.aurita     | 15          | 4.5   | 47.1   | 17.5         |
| GUI_14   | Guinea     | BOULBINET         | -11.352   | 9.932    | 2017            | S.aurita     | 15.5        | 4.5   | 53.5   | 18.5         |
| GUI_15   | Guinea     | BOULBINET         | -11.352   | 9.932    | 2017            | S.aurita     | 18          | 4     | 83     | 20           |
| GUI_16   | Guinea     | BOULBINET         | -11.352   | 9.932    | 2017            | S.aurita     | 16.5        | 4     | 52.3   | 19           |
| GUI_19   | Guinea     | BOULBINET         | -11.352   | 9.932    | 2017            | S.aurita     | 17          | 4.5   | 59.5   | 19.5         |
| GUI_1G   | Guinea     | BOULBINET         | -11.352   | 9.932    | 2017            | S.aurita     | 16          | 5     | 51.1   | 19           |
| GUI_1H   | Guinea     | BOULBINET         | -11.352   | 9.932    | 2017            | S.aurita     | 16.5        | 2.8   | 57.4   | 20           |
| GUI_1    | Guinea     | BOULBINET         | -11.352   | 9.932    | 2017            | S.aurita     | 17          | 4     | 65.5   | 21           |
| GUI_21   | Guinea     | BOULBINET         | -11.352   | 9.932    | 2017            | S.aurita     | 19          | 5     | 78.1   | 22.5         |
| GUI_22   | Guinea     | BOULBINET         | -11.352   | 9.932    | 2017            | S.aurita     | 16          | 5     | 56.3   | 18           |
| GUI_23   | Guinea     | BOULBINET         | -11.352   | 9.932    | 2017            | S.aurita     | 18          | 5     | 69.9   | 18.5         |
| GUI_25   | Guinea     | BOULBINET         | -11.352   | 9.932    | 2017            | S.aurita     | 18          | 5     | 59     | 19           |
| GUI_2    | Guinea     | BOULBINET         | -11.352   | 9.932    | 2017            | S.aurita     | 16          | 4     | 59     | 21.5         |
| GUI_31   | Guinea     | BOULBINET         | -11.352   | 9.932    | 2017            | S.aurita     | 16          | 4.5   | 56.2   | 19.5         |
| GUI_37   | Guinea     | BOULBINET         | -11.352   | 9.932    | 2017            | S.aurita     | 17          | 4     | 61.1   | 20           |
| GUI_43   | Guinea     | BOULBINET         | -11.352   | 9.932    | 2017            | S.aurita     | 16.5        | 2.8   | 57.4   | 20           |
| GUI_11G  | Guinea     | BOULBINET         | -11.352   | 9.932    | 2017            | S.aurita     | 16          | 4     | 56.4   | 19.5         |
| GUI_4G   | Guinea     | BOULBINET         | -11.352   | 9.932    | 2017            | S.aurita     | 16.5        | 5     | 63.5   | 20           |
| GUI_5H   | Guinea     | BOULBINET         | -11.352   | 9.932    | 2017            | S.aurita     | 16          | 4.5   | 57.2   | 20           |
| MM_10A   | Mauritania | Nouakchott        | -15.978   | 18.0841  | 2016            | S.maderensis | 25.5        | 8.7   | 280    | 0            |
| MM_11A   | Mauritania | Nouakchott        | -15.978   | 18.0841  | 2016            | S.maderensis | 26.9        | 8.6   | 321    | 0            |
| MM_11B   | Mauritania | Nouakchott        | -15.978   | 18.0841  | 2016            | S.maderensis | 27.8        | 8.4   | 352    | 0            |
| MM_12A   | Mauritania | Nouakchott        | -15.978   | 18.0841  | 2016            | S.maderensis | 33          | 8.5   | 510    | 0            |
| MM_1A    | Mauritania | Nouakchott        | -15.978   | 18.0841  | 2016            | S.maderensis | 32.5        | 9.5   | 515    | 0            |
| MM_2A    | Mauritania | Nouakchott        | -15.978   | 18.0841  | 2016            | S.maderensis | 25.7        | 8.3   | 286    | 0            |
| MM_3A    | Mauritania | Nouakchott        | -15.978   | 18.0841  | 2016            | S.maderensis | 22.6        | 7.2   | 201    | 0            |
| MM_4A    | Mauritania | Nouakchott        | -15.978   | 18.0841  | 2016            | S.maderensis | 22.5        | 7.1   | 185    | 0            |
| MM_4B    | Mauritania | Nouakchott        | -15.978   | 18.0841  | 2016            | S.maderensis | 24.6        | 8.5   | 235    | 0            |
| MM_5A    | Mauritania | Nouakchott        | -15.978   | 18.0841  | 2016            | S.maderensis | 26.9        | 8.6   | 321    | 0            |
| MM_6A    | Mauritania | Nouakchott        | -15.978   | 18.0841  | 2016            | S.maderensis | 24.8        | 8.4   | 251    | 0            |
| MM_6B    | Mauritania | Nouakchott        | -15.978   | 18.0841  | 2016            | S.maderensis | 25.4        | 8.3   | 275    | 0            |
| MM_7A    | Mauritania | Nouakchott        | -15.978   | 18.0841  | 2016            | S.maderensis | 23.3        | 7.7   | 214    | 0            |
| MM_7B    | Mauritania | Nouakchott        | -15.978   | 18.0841  | 2016            | S.maderensis | 24.5        | 8.6   | 244    | 0            |
| MM_8A    | Mauritania | Nouakchott        | -15.978   | 18.0841  | 2016            | S.maderensis | 26.7        | 8.7   | 304    | 0            |
| MM_9A    | Mauritania | Nouakchott        | -15.978   | 18.0841  | 2016            | S.maderensis | 25.3        | 7.6   | 265    | 0            |
| MM_9B    | Mauritania | Nouakchott        | -15.978   | 18.0841  | 2016            | S.maderensis | 25.9        | 7.5   | 281    | 0            |
| MM_D10   | Mauritania | Nouakchott        | -15.978   | 18.0841  | 2016            | S.maderensis | 26.5        | 8.6   | 298    | 0            |
| MM_D4    | Mauritania | Nouakchott        | -15.978   | 18.0841  | 2016            | S.maderensis | 22.3        | 7.1   | 203    | 0            |
| SM__1B   | Senegal    | Fass Boue         | -16.85    | 14.179   | 2016            | S.maderensis | 24          | 6.6   | 239.4  | 29.5         |
| SM_1C    | Senegal    | Fass Boue         | -16.85    | 14.179   | 2016            | S.maderensis | 25          | 6.5   | 240.5  | 30           |
| SM__2B   | Senegal    | Fass Boue         | -16.85    | 14.179   | 2016            | S.maderensis | 24.7        | 6.7   | 237.7  | 29.5         |
| SM__2C   | Senegal    | Fass Boue         | -16.85    | 14.179   | 2016            | S.maderensis | 23.2        | 6     | 200.3  | 30.5         |
| SM__3B   | Senegal    | Fass Boue         | -16.85    | 14.179   | 2016            | S.maderensis | 35.5        | 6.5   | 215.1  | 28.7         |
| SM__3C   | Senegal    | Fass Boue         | -16.85    | 14.179   | 2016            | S.maderensis | 27.5        | 7.7   | 329.2  | 33.9         |
| SM_4C    | Senegal    | Fass Boue         | -16.85    | 14.179   | 2016            | S.maderensis | 25.6        | 6.7   | 251.1  | 30.4         |
| SM__4C   | Senegal    | Fass Boue         | -16.85    | 14.179   | 2016            | S.maderensis | 25.2        | 6.6   | 233.2  | 30.1         |
| SM__5C   | Senegal    | Fass Boue         | -16.85    | 14.179   | 2016            | S.maderensis | 24.3        | 6.8   | 263.3  | 29.2         |
| SM_H10   | Senegal    | Fass Boue         | -16.85    | 14.179   | 2016            | S.maderensis | 24.5        | 6.7   | 238.4  | 29.5         |
| SM_H1    | Senegal    | Fass Boue         | -16.85    | 14.179   | 2016            | S.maderensis | 21.6        | 5.6   | 144.1  | 26.2         |
| SM_H2    | Senegal    | Fass Boue         | -16.85    | 14.179   | 2016            | S.maderensis | 24          | 6.7   | 217.2  | 29           |
| SM_H3    | Senegal    | Fass Boue         | -16.85    | 14.179   | 2016            | S.maderensis | 24.4        | 6.8   | 259.5  | 29.7         |
| SM_H4    | Senegal    | Fass Boue         | -16.85    | 14.179   | 2016            | S.maderensis | 25.2        | 7     | 287.3  | 30.6         |
| SM_H5    | Senegal    | Fass Boue         | -16.85    | 14.179   | 2016            | S.maderensis | 22.5        | 6     | 197.7  | 27.1         |
| SM_H6    | Senegal    | Fass Boue         | -16.85    | 14.179   | 2016            | S.maderensis | 22.5        | 6     | 165.7  | 17           |
| SM_H7    | Senegal    | Fass Boue         | -16.85    | 14.179   | 2016            | S.maderensis | 22.2        | 5.8   | 152.5  | 26.1         |
| SM_H8    | Senegal    | Fass Boue         | -16.85    | 14.179   | 2016            | S.maderensis | 23.1        | 6     | 175    | 27.4         |
| SM_H9    | Senegal    | Fass Boue         | -16.85    | 14.179   | 2016            | S.maderensis | 21.3        | 6     | 175.3  | 27.7         |
| GM_10E   | Senegal    | Fass Boue         | -16.85    | 14.179   | 2016            | S.maderensis | 23          | 6.3   | 186.6  | 28.2         |
| GM_23    | Guinea     | BOULBINET         | -11.352   | 9.932    | 2017            | S.maderensis | 15          | 5     | 48.8   | 18           |
| GM_25    | Guinea     | BOULBINET         | -11.352   | 9.932    | 2017            | S.maderensis | 14.5        | 5     | 50.6   | 18           |
| GM_26    | Guinea     | BOULBINET         | -11.352   | 9.932    | 2017            | S.maderensis | 14          | 5     | 38.9   | 17           |
| GM_27    | Guinea     | BOULBINET         | -11.352   | 9.932    | 2017            | S.maderensis | 15          | 4.5   | 62.5   | 20           |
| GM_28    | Guinea     | BOULBINET         | -11.352   | 9.932    | 2017            | S.maderensis | 15          | 6     | 46.4   | 17           |
| GM_29    | Guinea     | BOULBINET         | -11.352   | 9.932    | 2017            | S.maderensis | 14          | 4.5   | 36     | 19.5         |
| GM_30    | Guinea     | BOULBINET         | -11.352   | 9.932    | 2017            | S.maderensis | 14.5        | 5     | 55.4   | 17           |
| GM_33    | Guinea     | BOULBINET         | -11.352   | 9.932    | 2017            | S.maderensis | 15.5        | 5     | 45.6   | 19           |
| GM_34    | Guinea     | BOULBINET         | -11.352   | 9.932    | 2017            | S.maderensis | 14.5        | 5.5   | 58.1   | 17           |
| GM_35    | Guinea     | BOULBINET         | -11.352   | 9.932    | 2017            | S.maderensis | 14.5        | 5     | 45.6   | 20           |
| GM_36    | Guinea     | BOULBINET         | -11.352   | 9.932    | 2017            | S.maderensis | 14.5        | 5     | 58.9   | 18.5         |
| GM_37    | Guinea     | BOULBINET         | -11.352   | 9.932    | 2017            | S.maderensis | 15          | 5     | 55.4   | 18           |
| GM_38    | Guinea     | BOULBINET         | -11.352   | 9.932    | 2017            | S.maderensis | 15          | 5.5   | 56.6   | 18           |
| GM_39    | Guinea     | BOULBINET         | -11.352   | 9.932    | 2017            | S.maderensis | 14.5        | 5     | 54.7   | 17           |
| GM_40    | Guinea     | BOULBINET         | -11.352   | 9.932    | 2017            | S.maderensis | 14          | 4.5   | 40.5   | 17           |
| GM_6E    | Guinea     | BOULBINET         | -11.352   | 9.932    | 2017            | S.maderensis | 13.5        | 5     | 53     | 19           |
| GM_6F    | Guinea     | BOULBINET         | -11.352   | 9.932    | 2017            | S.maderensis | 13.5        | 5     | 50.4   | 18           |
| GM_7E    | Guinea     | BOULBINET         | -11.352   | 9.932    | 2017            | S.maderensis | 15          | 5     | 39.6   | 6.5          |
| GM_8E    | Guinea     | BOULBINET         | -11.352   | 9.932    | 2017            | S.maderensis | 13          | 4.5   | 45     | 17           |
| N1       | Nigeria    |                   | 3.406     | 6.465    | 2016            | S.maderensis | 12.2        | 10    | 30     | 14.5         |
| N2       | Nigeria    |                   | 3.406     | 6.465    | 2016            | S.maderensis | 13.8        | 10.6  | 28     | 16.2         |
| N3       | Nigeria    |                   | 3.406     | 6.465    | 2016            | S.maderensis | 13.1        | 10.2  | 25     | 15.3         |
| N4       | Nigeria    |                   | 3.406     | 6.465    | 2016            | S.maderensis | 20.5        | 14    | 40     | 24.7         |
| N5       | Nigeria    |                   | 3.406     | 6.465    | 2016            | S.maderensis | 13.6        | 9     | 38     | 16.1         |
| N6       | Nigeria    |                   | 3.406     | 6.465    | 2016            | S.maderensis | 13.2        | 8.7   | 35     | 15.4         |
| N7       | Nigeria    |                   | 3.406     | 6.465    | 2016            | S.maderensis | 13.3        | 8.8   | 35     | 16.6         |
| N8       | Nigeria    |                   | 3.406     | 6.465    | 2016            | S.maderensis | 20.3        | 14.1  | 40     | 24.3         |
| N9       | Nigeria    |                   | 3.406     | 6.465    | 2016            | S.maderensis | 13.3        | 8.8   | 35     | 15.8         |
| N10      | Nigeria    |                   | 3.406     | 6.465    | 2016            | S.maderensis | 12.7        | 8.3   | 30     | 14.8         |
| N11      | Nigeria    |                   | 3.406     | 6.465    | 2016            | S.maderensis | 13.3        | 8.6   | 35     | 15.5         |
| N12      | Nigeria    |                   | 3.406     | 6.465    | 2016            | S.maderensis | 13.6        | 9.1   | 45     | 16.3         |
| N13      | Nigeria    |                   | 3.406     | 6.465    | 2016            | S.maderensis | 14.3        | 9.3   | 25     | 17           |
| N14      | Nigeria    |                   | 3.406     | 6.465    | 2016            | S.maderensis | 12.2        | 8     | 25     | 14           |
| N15      | Nigeria    |                   | 3.406     | 6.465    | 2016            | S.maderensis | 14.2        | 12.2  | 35     | 16.8         |
| N16      | Nigeria    |                   | 3.406     | 6.465    | 2016            | S.maderensis | 13.9        | 9.2   | 80     | 16.3         |
| N17      | Nigeria    |                   | 3.406     | 6.465    | 2016            | S.maderensis | 16.9        | 8.5   | 55     | 20.3         |
| N18      | Nigeria    |                   | 3.406     | 6.465    | 2016            | S.maderensis | 13.9        | 9     | 30     | 16.3         |
| N19      | Nigeria    |                   | 3.406     | 6.465    | 2016            | S.maderensis | 12.7        | 9     | 35     | 15           |
| N20      | Nigeria    |                   | 3.406     | 6.465    | 2016            | S.maderensis | 13.1        | 9.9   | 40     | 15.5         |
| TM_10B   | Togo       | Harbour           | 1.301     | 6.151    | 2016            | S.maderensis | 21.5        | 13.5  | 142    | 26           |
| TM_11A   | Togo       | Harbour           | 1.301     | 6.151    | 2016            | S.maderensis | 20          | 11    | 129    | 24.5         |
| TM_11B   | Togo       | Harbour           | 1.301     | 6.151    | 2016            | S.maderensis | 17.5        | 13.5  | 73     | 20           |
| TM_12A   | Togo       | Harbour           | 1.301     | 6.151    | 2016            | S.maderensis | 20          | 12.5  | 123    | 24.5         |
| TM_12B   | Togo       | Harbour           | 1.301     | 6.151    | 2016            | S.maderensis | 19          | 13.5  | 104    | 22.5         |
| TM_26    | Togo       | Harbour           | 1.301     | 6.151    | 2016            | S.maderensis | 21          | 13    | 141    | 25.5         |
| TM_37    | Togo       | Harbour           | 1.301     | 6.151    | 2016            | S.maderensis | 20          | 12.5  | 117    | 24           |
| TM_38    | Togo       | Harbour           | 1.301     | 6.151    | 2016            | S.maderensis | 20.5        | 13.5  | 137    | 25           |
| TM_39    | Togo       | Harbour           | 1.301     | 6.151    | 2016            | S.maderensis | 21          | 13    | 147    | 25.5         |
| TM_3A    | Togo       | Harbour           | 1.301     | 6.151    | 2016            | S.maderensis | 22          | 14    | 171    | 26.5         |
| TM_45    | Togo       | Harbour           | 1.301     | 6.151    | 2016            | S.maderensis | 22          | 14    | 153    | 21.5         |
| TM_4A    | Togo       | Harbour           | 1.301     | 6.151    | 2016            | S.maderensis | 18          | 11.5  | 91     | 26           |
| TM_4B    | Togo       | Harbour           | 1.301     | 6.151    | 2016            | S.maderensis | 21          | 13.5  | 143    | 25           |
| TM_5A    | Togo       | Harbour           | 1.301     | 6.151    | 2016            | S.maderensis | 21          | 13.5  | 129    | 24           |
| TM_5B    | Togo       | Harbour           | 1.301     | 6.151    | 2016            | S.maderensis | 21          | 13.5  | 69     | 20           |
| TM_6A    | Togo       | Harbour           | 1.301     | 6.151    | 2016            | S.maderensis | 21.5        | 14.5  | 137    | 26           |
| TM_6B    | Togo       | Harbour           | 1.301     | 6.151    | 2016            | S.maderensis | 20          | 11.5  | 71     | 20.5         |
| TM_8A    | Togo       | Harbour           | 1.301     | 6.151    | 2016            | S.maderensis | 17          | 12.5  | 95     | 22.5         |
| TM_8B    | Togo       | Harbour           | 1.301     | 6.151    | 2016            | S.maderensis | 19          | 13.5  | 118    | 23.5         |

#### 2. HiSeq Read Set Sequencing Metadata
| Sample    | country    | species      | Run Type   | Library Source | Library Type | Read #  | Average Quality |
|-----------|------------|--------------|------------|----------------|--------------|---------|-----------------|
| MA_D1     | Mauritania | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 3972953 | 40              |
| MA_D2     | Mauritania | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 2863133 | 40              |
| MA_D3     | Mauritania | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 3836010 | 40              |
| MA_D7     | Mauritania | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 2997783 | 40              |
| MA_D8     | Mauritania | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 3762103 | 40              |
| MA_D9     | Mauritania | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 3029751 | 40              |
| MA_G1     | Mauritania | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 3114856 | 40              |
| MA_G2     | Mauritania | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 3448832 | 40              |
| MA_G3     | Mauritania | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 2990393 | 40              |
| MA_G4     | Mauritania | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 3363135 | 40              |
| MA_G5     | Mauritania | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 2326233 | 40              |
| MA_G6     | Mauritania | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 2888975 | 40              |
| MA_G8     | Mauritania | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 4453339 | 40              |
| MA_G10    | Mauritania | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 3317070 | 40              |
| MA_1A     | Mauritania | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 2388069 | 40              |
| MA_2A     | Mauritania | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 498866  | 40              |
| MA_7A     | Mauritania | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 440287  | 40              |
| MA_8A     | Mauritania | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 426360  | 40              |
| MA_9A     | Mauritania | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 1423744 | 40              |
| SA_C1     | Senegal    | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 2909942 | 40              |
| SA_C2     | Senegal    | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 2322853 | 40              |
| SA_C3     | Senegal    | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 3231356 | 40              |
| SA_C4     | Senegal    | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 3268838 | 40              |
| SA_C5     | Senegal    | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 2507019 | 40              |
| SA_C6     | Senegal    | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 6007766 | 40              |
| SA_C7     | Senegal    | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 2334828 | 40              |
| SA_C8     | Senegal    | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 2426209 | 36              |
| SA_C9     | Senegal    | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 2855746 | 40              |
| SA_C10    | Senegal    | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 3235321 | 40              |
| SA_1C     | Senegal    | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 1829026 | 40              |
| SA_2C     | Senegal    | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 2884170 | 40              |
| SA_3C     | Senegal    | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 2374320 | 40              |
| SA_5Cres  | Senegal    | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 67387   | 40              |
| SA_7Cres  | Senegal    | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 1490195 | 40              |
| SA_8Cres  | Senegal    | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 3220885 | 40              |
| SA_38     | Senegal    | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 1807230 | 40              |
| SA_4CN    | Senegal    | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 3490025 | 40              |
| GUI_11    | Guinea     | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 1671444 | 40              |
| GUI_13    | Guinea     | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 2736320 | 40              |
| GUI_14    | Guinea     | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 3281360 | 40              |
| GUI_15    | Guinea     | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 3738207 | 40              |
| GUI_16    | Guinea     | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 2614403 | 40              |
| GUI_19    | Guinea     | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 2539545 | 40              |
| GUI_1G    | Guinea     | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 2416160 | 40              |
| GUI_1H    | Guinea     | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 1950201 | 40              |
| GUI_1     | Guinea     | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 2096833 | 40              |
| GUI_21    | Guinea     | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 3559740 | 40              |
| GUI_22    | Guinea     | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 2235137 | 40              |
| GUI_23    | Guinea     | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 2786868 | 40              |
| GUI_25    | Guinea     | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 4059001 | 40              |
| GUI_2     | Guinea     | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 3573740 | 40              |
| GUI_31    | Guinea     | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 3453429 | 40              |
| GUI_37    | Guinea     | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 778994  | 40              |
| GUI_43    | Guinea     | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 1068216 | 40              |
| GUI_11G   | Guinea     | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 1644856 | 40              |
| GUI_4G    | Guinea     | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 654806  | 40              |
| GUI_5H    | Guinea     | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 1233015 | 40              |
| GA_A1     | Ghana      | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 4682704 | 40              |
| GA_A4     | Ghana      | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 3296860 | 40              |
| GA_A2     | Ghana      | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 3274985 | 40              |
| GA_A3     | Ghana      | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 176859  | 40              |
| GA_A5     | Ghana      | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 2975779 | 40              |
| GA_A6     | Ghana      | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 5448638 | 40              |
| GA_A7     | Ghana      | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 3521271 | 40              |
| GA_A8     | Ghana      | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 2593197 | 40              |
| GA_A9     | Ghana      | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 2336965 | 40              |
| GA_A10    | Ghana      | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 3822138 | 40              |
| GA_F6     | Ghana      | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 1753505 | 40              |
| GA_F7     | Ghana      | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 7250197 | 40              |
| GA_F8     | Ghana      | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 1904330 | 40              |
| GA_F9     | Ghana      | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 2578087 | 40              |
| GA_F10    | Ghana      | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 1791180 | 40              |
| GA_1B     | Ghana      | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 777363  | 40              |
| GA_2B     | Ghana      | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 1051070 | 40              |
| GA_3B     | Ghana      | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 760786  | 40              |
| GA_5B     | Ghana      | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 1085310 | 40              |
| GA_gha3B  | Ghana      | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 1559745 | 40              |
| TA_E1     | Togo       | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 1903707 | 40              |
| TA_E2     | Togo       | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 2920657 | 40              |
| TA_E3     | Togo       | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 6364394 | 40              |
| TA_E4     | Togo       | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 2399133 | 40              |
| TA_E5     | Togo       | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 2825722 | 40              |
| TA_E6     | Togo       | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 2330258 | 40              |
| TA_E7     | Togo       | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 2163294 | 40              |
| TA_E8     | Togo       | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 4392504 | 40              |
| TA_E9     | Togo       | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 3699474 | 40              |
| TA_E10    | Togo       | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 1982836 | 40              |
| TA_41     | Togo       | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 3335789 | 40              |
| TA_44     | Togo       | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 3130346 | 40              |
| TA_45     | Togo       | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 3762442 | 40              |
| TA_47     | Togo       | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 3393171 | 40              |
| TA_1Dres  | Togo       | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 669464  | 40              |
| TA_2Dres  | Togo       | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 2721236 | 40              |
| TA_3Dres  | Togo       | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 652961  | 40              |
| TA_4D     | Togo       | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 2033845 | 40              |
| TA_5D     | Togo       | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 1966840 | 40              |
| TA_6Dres  | Togo       | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 3079161 | 40              |
| Benin_1E  | Benin      | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 648405  | 40              |
| Benin_2E  | Benin      | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 3250561 | 40              |
| Benin_3E  | Benin      | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 1175269 | 40              |
| Benin_4E  | Benin      | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 1138702 | 40              |
| Benin_5E  | Benin      | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 426831  | 36              |
| Benin_6E  | Benin      | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 1160370 | 40              |
| Benin_7E  | Benin      | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 1864077 | 40              |
| Benin_B1  | Benin      | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 421762  | 37              |
| Benin_B10 | Benin      | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 3516024 | 40              |
| Benin_B2  | Benin      | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 3049783 | 40              |
| Benin_B3  | Benin      | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 2699346 | 40              |
| Benin_B4  | Benin      | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 2277126 | 40              |
| Benin_B5  | Benin      | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 2994343 | 36              |
| Benin_B6  | Benin      | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 2529279 | 40              |
| Benin_B7  | Benin      | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 3737002 | 40              |
| Benin_B8  | Benin      | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 6323212 | 40              |
| Benin_B9  | Benin      | S. aurita    | PAIRED_END | gDNA           | ddRAD        | 6343378 | 40              |
| MM_10A    | Mauritania | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 2429179 | 40              |
| MM_11A    | Mauritania | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 604046  | 40              |
| MM_11B    | Mauritania | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 2221548 | 40              |
| MM_12A    | Mauritania | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 2773836 | 40              |
| MM_1A     | Mauritania | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 1002115 | 36              |
| MM_2A     | Mauritania | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 707037  | 36              |
| MM_3A     | Mauritania | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 1770842 | 36              |
| MM_4A     | Mauritania | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 1225941 | 36              |
| MM_4B     | Mauritania | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 1988491 | 36              |
| MM_5A     | Mauritania | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 1001721 | 36              |
| MM_6A     | Mauritania | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 1020230 | 36              |
| MM_6B     | Mauritania | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 964148  | 36              |
| MM_7A     | Mauritania | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 1096085 | 36              |
| MM_7B     | Mauritania | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 3315913 | 36              |
| MM_8A     | Mauritania | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 1383283 | 36              |
| MM_9A     | Mauritania | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 3834032 | 36              |
| MM_9B     | Mauritania | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 2553159 | 40              |
| MM_D10    | Mauritania | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 2221548 | 40              |
| MM_D4     | Mauritania | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 3620659 | 40              |
| SM__1B    | Senegal    | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 2084735 | 40              |
| SM_1C     | Senegal    | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 1317125 | 40              |
| SM__2B    | Senegal    | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 468068  | 40              |
| SM__2C    | Senegal    | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 2394435 | 40              |
| SM__3B    | Senegal    | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 1340907 | 40              |
| SM__3C    | Senegal    | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 1246669 | 40              |
| SM_4C     | Senegal    | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 2197183 | 40              |
| SM__4C    | Senegal    | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 639825  | 40              |
| SM__5C    | Senegal    | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 3494326 | 40              |
| SM_H10    | Senegal    | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 2025534 | 40              |
| SM_H1     | Senegal    | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 1209463 | 36              |
| SM_H2     | Senegal    | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 2934705 | 36              |
| SM_H3     | Senegal    | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 2786505 | 36              |
| SM_H4     | Senegal    | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 3530385 | 40              |
| SM_H5     | Senegal    | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 4799496 | 40              |
| SM_H6     | Senegal    | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 3258402 | 40              |
| SM_H7     | Senegal    | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 3135016 | 40              |
| SM_H8     | Senegal    | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 3045871 | 40              |
| SM_H9     | Senegal    | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 3357428 | 40              |
| GM_10E    | Senegal    | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 2814198 | 40              |
| GM_23     | Guinea     | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 2162394 | 40              |
| GM_25     | Guinea     | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 2579701 | 40              |
| GM_26     | Guinea     | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 2538471 | 40              |
| GM_27     | Guinea     | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 5642128 | 40              |
| GM_28     | Guinea     | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 5698079 | 36              |
| GM_29     | Guinea     | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 3328832 | 36              |
| GM_30     | Guinea     | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 3586765 | 36              |
| GM_33     | Guinea     | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 4175486 | 36              |
| GM_34     | Guinea     | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 3136132 | 36              |
| GM_35     | Guinea     | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 3974891 | 40              |
| GM_36     | Guinea     | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 3757137 | 40              |
| GM_37     | Guinea     | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 3116255 | 40              |
| GM_38     | Guinea     | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 4791637 | 40              |
| GM_39     | Guinea     | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 2728215 | 40              |
| GM_40     | Guinea     | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 3664194 | 40              |
| GM_6E     | Guinea     | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 4389357 | 40              |
| GM_6F     | Guinea     | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 3930490 | 36              |
| GM_7E     | Guinea     | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 3393483 | 36              |
| GM_8E     | Guinea     | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 3026438 | 40              |
| N1        | Nigeria    | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 3798103 | 36              |
| N2        | Nigeria    | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 2818093 | 36              |
| N3        | Nigeria    | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 1847396 | 40              |
| N4        | Nigeria    | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 1882335 | 40              |
| N5        | Nigeria    | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 1458661 | 36              |
| N6        | Nigeria    | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 2077416 | 40              |
| N7        | Nigeria    | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 4632541 | 40              |
| N8        | Nigeria    | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 3651073 | 40              |
| N9        | Nigeria    | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 1764589 | 40              |
| N10       | Nigeria    | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 863906  | 40              |
| N11       | Nigeria    | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 532017  | 40              |
| N12       | Nigeria    | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 2093608 | 36              |
| N13       | Nigeria    | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 4897107 | 36              |
| N14       | Nigeria    | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 2095123 | 36              |
| N15       | Nigeria    | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 432852  | 40              |
| N16       | Nigeria    | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 2996849 | 36              |
| N17       | Nigeria    | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 1436918 | 36              |
| N18       | Nigeria    | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 562976  | 40              |
| N19       | Nigeria    | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 1859757 | 36              |
| N20       | Nigeria    | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 4351480 | 40              |
| TM_10B    | Togo       | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 1490224 | 40              |
| TM_11A    | Togo       | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 2093608 | 40              |
| TM_11B    | Togo       | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 1318183 | 40              |
| TM_12A    | Togo       | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 3250561 | 40              |
| TM_12B    | Togo       | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 1546825 | 40              |
| TM_26     | Togo       | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 745465  | 40              |
| TM_37     | Togo       | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 498351  | 40              |
| TM_38     | Togo       | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 2610747 | 40              |
| TM_39     | Togo       | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 1490224 | 40              |
| TM_3A     | Togo       | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 3150474 | 40              |
| TM_45     | Togo       | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 6004595 | 40              |
| TM_4A     | Togo       | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 485764  | 40              |
| TM_4B     | Togo       | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 1165329 | 40              |
| TM_5A     | Togo       | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 2399695 | 40              |
| TM_5B     | Togo       | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 769184  | 36              |
| TM_6A     | Togo       | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 4202676 | 36              |
| TM_6B     | Togo       | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 3721938 | 40              |
| TM_8A     | Togo       | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 3230095 | 36              |
| TM_8B     | Togo       | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 4299789 | 40              |
| TM_8B     | Togo       | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 3032301 | 40              |
| BM_10E    | Benin      | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 3345083 | 40              |
| BM_11E    | Benin      | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 2280475 | 40              |
| BM_12E    | Benin      | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 1977142 | 36              |
| BM_1F     | Benin      | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 3459880 | 36              |
| BM_2F     | Benin      | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 2637252 | 36              |
| BM_3F     | Benin      | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 1915437 | 36              |
| BM_4F     | Benin      | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 1858038 | 36              |
| BM_5F     | Benin      | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 5330703 | 36              |
| BM_7F     | Benin      | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 1415566 | 40              |
| BM_A11    | Benin      | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 1508411 | 40              |
| BM_A12    | Benin      | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 5986337 | 40              |
| BM_B11    | Benin      | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 3322288 | 36              |
| BM_B12    | Benin      | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 5785770 | 36              |
| BM_C11    | Benin      | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 3084180 | 36              |
| BM_D11    | Benin      | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 2360582 | 36              |
| BM_E11    | Benin      | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 3289491 | 36              |
| BM_F11    | Benin      | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 2817261 | 36              |
| BM_G11    | Benin      | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 3926321 | 36              |
| BM_H11    | Benin      | s.maderensis | PAIRED_END | gDNA           | ddRAD        | 3143584 | 36              |
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
##### Next  MultiQC program was usesd to put together all fastqc results files to visualise the quality of all samples together
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
#### Two different species were analysed in this work.
#### i. **s.aurita species**
#### The ddocent pipeline (http://www.ddocent.com)was used for processing of the data. Software is downloaded unto the bluewaves cluster.
##### The pipeline was run using a configuration file from ddocent  in an interactive mode  to perform the following steps; quality trim reads, perform an assembly, map reads to a reference and call Variants.
##### First, ddocent was  loaded and the ddocent conda environment was  activated.
```
#Load software
module load ddocent/2.5.2
# Activate the environment
source activate ddocent_env
# Type dDocent
```
##### Before we can run dDocent to call variants, we first need to assemble our reference genome  denovo because the two  species lack  a reference sequence.
######
For generating a denovo Assembly
```
mkdir assembly
cd Assembly
#Five samples that have been quality filtered and trimmed with high quality from each of the populations for both s.aurita and s.maderensis were selected were copied into the directory Assembly
```
##### The ddocent pipeline uses two programs CD-HIT and Rainbow to assemble Radseq data. These programs are based on an alignment read based clustering which uses a similarity threshold to cluster the reads. To start the assembly, ddocent takes into account the 3 factors below;
###### 1.sequencing errors can be introduced in Radseq data where some sequences will have very low coverage, this must be removed from the assembly and  unique sequences with a cut off value of coverage in the data set are identified and selected. hereafter noted as K1.
###### 2. We are also assemblying reference sequence considering different individuals, it is appropriate to consider unique sequences to be present in atleast most of the individuals.Therefore a cut off value of how many individuals should a unique sequence selected previously  appear in should also be considered. hereafter noted as K2.
###### 3. The similarity threshold noted as c necessary to cluster the unique reads into various loci must be determined. To do this,  a script by Jon Puritz/ReferenceOpt.sh(https://github.com/jpuritz/dDocent/blob/master/scripts/ReferenceOpt.sh) was used.This script basically chooses an interval of cutoff values for K1, K2 and a similarity threshold to cluster unique reads.
```{r}
Range of values selected to run the Reference Opt.sh script
K1 value in the range of 2 to 4 coverage for each unique sequence.
K2 value in the range of 2 to 4 individuals a unique sequence appears in
c values from 0.8-0.98 similarity threshold.
```
###### Using the information above, lets run the script  for s. aurita
```
bash ReferenceOpt.sh 4 4 2 2 PE 20
# PE represents Paired end
# the value 20 represent the number of threads to run the scripts
```
###### After running the script, it output a data known as kopt.data which when visualised contains k1,k2 value combination across similarity thresholds and the number of contig obtained.  To visualise the information in the kopt.data, use the code
```
cat kopt.data
```
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

##### selecting cut off values of k1 and k2 in clustering sequences is one critical step. We also need to evaluate mapping of few reads  to the  reference contigs to  be assembled  before choosing a final number of contig to represent our reference.  To perform this evaluation, the script RefMapOpt.sh (https://github.com/jpuritz/dDocent/blob/master/scripts/RefMapOpt.sh) was used.
###### The script basically assembles reference with range of values  of K1, K2  and a similarity threshold of 0.9 after which it maps 20 randomly samples(default in the script) to  the reference contigs assembled across all the cut off values used.
```
bash RefMapOpt.sh 2 5 2 5 0.9 20 PE
# K1 value is 2 to 5
# K2 value is 2 to 5
# C value is 0.9
# Number of threads used is 20
# PE represent paired end
```
###### Results are outputted in a tablular form
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

#### To have more confidence in the reference assembly, various sequences of s.aurita published online from ncbi were downloaded and blasted against the  denovo reference assembly.
Significant hits were observed
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


#### Next is after assemblying our reference sequence, we proceed  to map our reads to the reference and call variants.
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
###### dDocent 2.5.3
###### Contact jpuritz@uri.edu with any problems
###### Checking for required software
###### All required software is installed!
###### dDocent run started Sat Mar 23 14:48:01 EDT 2019
###### 114 individuals are detected. Is this correct? Enter yes or no and press [ENTER]
```
yes
```
###### Proceeding with 114 individuals
###### dDocent detects 20 processors available on this system.
###### Please enter the maximum number of processors to use for this analysis.
```
20
```
###### dDocent detects 125 gigabytes of maximum memory available on this system.
###### Please enter the maximum memory to use for this analysis in gigabytes
###### For example, to limit dDocent to ten gigabytes, enter 10
###### This option does not work with all distributions of Linux.  If runs are hanging at variant calling, enter 0
###### Then press [ENTER]**
```
120
```
###### Do you want to quality trim your reads?
###### Type yes or no and press [ENTER]?
```
yes
 the default parameters in the pipeline were used for quality trimming. Reads were quality trim a phred score below 20 for base calls and an average quality score of 10 for each read. Adapters were also detected and trim
```

###### Do you want to perform an assembly?
###### Type yes or no and press [ENTER].
```
no
```
###### Reference contigs need to be in a file named reference.fasta

###### Do you want to map reads?  Type yes or no and press [ENTER]
```
yes
```
###### BWA will be used to map reads.  You may need to adjust -A -B and -O parameters for your taxa. Would you like to enter a new parameters now? Type yes or no and press [ENTER]
```
no
```
###### Proceeding with default values for BWA read mapping.
###### Do you want to use FreeBayes to call SNPs?  Please type yes or no and press [ENTER]**
```
yes
```
###### Please enter your email address.  dDocent will email you when it is finished running.
###### Don't worry; dDocent has no financial need to sell your email address to spammers.
```
evelyn-takyi@my.uri.edu
```
###### At this point, all configuration information has been entered and dDocent may take few  hours to run.
###### It is recommended that you move this script to a background operation and disable terminal input and output.m  All data and logfiles will still be recorded.
###### To do this:
###### press control and Z simultaneously
##### Type 'bg' without the quotes and press enter
##### Type 'disown -h' again without the quotes and press enter
##### Now sit back, relax, and wait for your analysis to finish

#### Results of the mapping. Table below shows the average coverage of reads per sample mapping to the reference and the number of contigs mapped.
**reference = 82,324 contigs**

| Sample    | Country    | Average Coverage | Contigs mapped |
|-----------|------------|------------------|----------------|
| MA_D1     | Mauritania | 8.3              | 55608.5        |
| MA_D2     | Mauritania | 6.9              | 51072          |
| MA_D3     | Mauritania | 8.5              | 57507.5        |
| MA_D7     | Mauritania | 6.9              | 48979.5        |
| MA_D8     | Mauritania | 7.9              | 52073.5        |
| MA_D9     | Mauritania | 6.7              | 48935.5        |
| MA_G1     | Mauritania | 7                | 50880          |
| MA_G2     | Mauritania | 8.5              | 54979.5        |
| MA_G3     | Mauritania | 6.9              | 48480          |
| MA_G4     | Mauritania | 7.5              | 51543          |
| MA_G5     | Mauritania | 6.6              | 43816.5        |
| MA_G6     | Mauritania | 7.4              | 46117          |
| MA_G8     | Mauritania | 9.3              | 54091          |
| MA_G10    | Mauritania | 7.9              | 50213.5        |
| MA_1A     | Mauritania | 5.2              | 34045          |
| MA_2A     | Mauritania | 3.1              | 11090          |
| MA_7A     | Mauritania | 3.7              | 10986.5        |
| MA_8A     | Mauritania | 2.9              | 11737.5        |
| MA_9A     | Mauritania | 4.1              | 27688          |
| SA_C1     | Senegal    | 6.5              | 432345         |
| SA_C2     | Senegal    | 5.6              | 45156.5        |
| SA_C3     | Senegal    | 6.8              | 54019.5        |
| SA_C4     | Senegal    | 7                | 53771          |
| SA_C5     | Senegal    | 6.1              | 49773.5        |
| SA_C6     | Senegal    | 11.9             | 57832.5        |
| SA_C7     | Senegal    | 5.4              | 45544.5        |
| SA_C8     | Senegal    | 5.5              | 46975.5        |
| SA_C9     | Senegal    | 6.1              | 49539          |
| SA_C10    | Senegal    | 6.6              | 52037          |
| SA_1C     | Senegal    | 4.6              | 26178.5        |
| SA_2C     | Senegal    | 10.5             | 25309          |
| SA_3C     | Senegal    | 7.4              | 23518          |
| SA_5Cres  | Senegal    | 6                | 18901          |
| SA_7Cres  | Senegal    | 7.3              | 27336.5        |
| SA_8Cres  | Senegal    | 4.4              | 30146          |
| SA_38     | Senegal    | 7.1              | 33413          |
| SA_4CN    | Senegal    | 1.9              | 2421           |
| GUI_11    | Guinea     | 5                | 7284           |
| GUI_13    | Guinea     | 6                | 15843          |
| GUI_14    | Guinea     | 4                | 18616          |
| GUI_15    | Guinea     | 4.9              | 30311          |
| GUI_16    | Guinea     | 4.6              | 16013          |
| GUI_19    | Guinea     | 4.4              | 14012          |
| GUI_1G    | Guinea     | 5.2              | 11913          |
| GUI_1H    | Guinea     | 6.7              | 3940           |
| GUI_1     | Guinea     | 4.4              | 8023           |
| GUI_21    | Guinea     | 4.9              | 11364          |
| GUI_22    | Guinea     | 3.8              | 23156          |
| GUI_23    | Guinea     | 4.1              | 25112          |
| GUI_25    | Guinea     | 4.3              | 8654           |
| GUI_2     | Guinea     | 5.9              | 4037           |
| GUI_31    | Guinea     | 4.8              | 4934           |
| GUI_37    | Guinea     | 4.6              | 36179          |
| GUI_43    | Guinea     | 3.9              | 34949          |
| GUI_11G   | Guinea     | 3.8              | 18838          |
| GUI_4G    | Guinea     | 3.5              | 6936           |
| GUI_5H    | Guinea     | 4.3              | 45560          |
| GA_A1     | Ghana      | 10.5             | 57734.5        |
| GA_A4     | Ghana      | 7.9              | 55086.5        |
| GA_A2     | Ghana      | 8.5              | 52848          |
| GA_A3     | Ghana      | 2.3              | 8959.5         |
| GA_A5     | Ghana      | 7.5              | 51013          |
| GA_A6     | Ghana      | 12.1             | 58853.5        |
| GA_A7     | Ghana      | 8.2              | 53869.5        |
| GA_A8     | Ghana      | 6.1              | 47616          |
| GA_A9     | Ghana      | 6.4              | 48023          |
| GA_A10    | Ghana      | 8.8              | 51362          |
| GA_F6     | Ghana      | 8.1              | 13199.5        |
| GA_F7     | Ghana      | 15.1             | 29771.5        |
| GA_F8     | Ghana      | 6.2              | 36685          |
| GA_F9     | Ghana      | 6.9              | 44022          |
| GA_F10    | Ghana      | 6.9              | 28933          |
| GA_1B     | Ghana      | 3.4              | 15434          |
| GA_2B     | Ghana      | 7.3              | 10118.5        |
| GA_3B     | Ghana      | 4.2              | 24030          |
| GA_5B     | Ghana      | 4                | 16912.5        |
| GA_gha3B  | Ghana      | 4.6              | 28278          |
| TA_E1     | Togo       | 5.2              | 42110          |
| TA_E2     | Togo       | 6.8              | 53372.5        |
| TA_E3     | Togo       | 12.3             | 60339.5        |
| TA_E4     | Togo       | 5.24             | 39419          |
| TA_E5     | Togo       | 6                | 47447          |
| TA_E6     | Togo       | 5.5              | 45358          |
| TA_E7     | Togo       | 5.2              | 44286          |
| TA_E8     | Togo       | 8.8              | 55819          |
| TA_E9     | Togo       | 7.2              | 50257          |
| TA_E10    | Togo       | 4.9              | 39321          |
| TA_41     | Togo       | 6.6              | 31270.5        |
| TA_44     | Togo       | 6.9              | 26523          |
| TA_45     | Togo       | 6                | 39254.5        |
| TA_47     | Togo       | 7.2              | 28548          |
| TA_1Dres  | Togo       | 4.7              | 10754.5        |
| TA_2Dres  | Togo       | 8.8              | 19911.5        |
| TA_3Dres  | Togo       | 3.9              | 16958          |
| TA_4D     | Togo       | 5                | 34739          |
| TA_5D     | Togo       | 4.9              | 34301.5        |
| TA_6Dres  | Togo       | 6.2              | 34843          |
| Benin_1E  | Benin      | 3.2              | 14730.5        |
| Benin_2E  | Benin      | 8.4              | 8470           |
| Benin_3E  | Benin      | 4.1              | 21296.5        |
| Benin_4E  | Benin      | 4.2              | 25338.5        |
| Benin_5E  | Benin      | 4.2              | 9157           |
| Benin_6E  | Benin      | 5.4              | 33011          |
| Benin_7E  | Benin      | 2.9              | 9821.5         |
| Benin_B1  | Benin      | 10.8             | 22564.5        |
| Benin_B10 | Benin      | 7.4              | 52074.5        |
| Benin_B2  | Benin      | 6.9              | 53281.5        |
| Benin_B3  | Benin      | 6.2              | 45691.5        |
| Benin_B4  | Benin      | 7.1              | 54414          |
| Benin_B5  | Benin      | 6.4              | 50234          |
| Benin_B6  | Benin      | 7.8              | 55798.5        |
| Benin_B7  | Benin      | 12.4             | 58491          |
| Benin_B8  | Benin      | 13.9             | 58584.5        |
| Benin_B9  | Benin      | 7                | 53080          |

#####  After ddocent is finished calling variants, it is stored in vcf file as
TotalRawSNPs.vcf

#### Next is to filter the variants using VCFTools and bash script
#### The following steps were adapted from a protocol developed by Jon Puritz. For more detailed information please see http://ddocent.com/filtering/

##### 1. First we will use VCFTools to filter out any variants that have not been successfully genotyped in 50% of individuals ( --max-missing 0.5), those with a minor allele count of 3 (--mac 3)), and those with a quality score below 20 (--minQ 20)
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
###### 15 individuals were removed  and they are as follows BA_2E, GA_2B.res, GA_A3, GUI_11, GUI_11G, GUI_15, GUI_16, GUI_19, GUI_1, GUI_1G,GUI_1H, GUI_23, GUI_25, GUI_2, GUI_4G, GUI_5H,
##### 3. Next command  applies a minimum mean depth --minDP for a genotype call and minor allele frequency --maf filter.   Genotypes will be called if they have atleast Five reads.
```
vcftools --vcf DP3g95maf05.recode.vcf --minDP 5 --maf 0.01 --recode --recode-INFO-all --out raw.g5mac3dp3
```
After filtering, kept 276130 out of a possible 341983 Sites

##### Next, we need to filter loci by applying genotype call rate of 0.9 across individuals in each population. To do this we use another script pop_missing_filter.sh by Jon Puritz.
```
./pop_missing_filter.sh raw.g5mac3dp3.recode.vcf popmap 0.9 1 TRSdp5MIp25
```
After filtering, kept 58019 out of a possible 276130 Sites
##### Next filter is based on script which will automatically filter a FreeBayes generated VCF file using criteria related to site depth, quality versus depth, strand representation, allelic balance at heterozygous individuals, and paired read representation. We use the script dDocent_filters

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
##### Next is to filter our variants by a minor allele frequency 0f 0.05
```
vcftools --vcf TRSdp5MIp25g9dd.FIL.recode.vcf --maf 0.05 --recode --recode-INFO-all --out DP3g95maf05d
```
After filtering, kept 6400 out of a possible 8164 Sites
##### Next, Apply a filter for HWE
###### Hardy Weinberg equilibrium is also another excellent filter to remove erroneous variant calls by removing loci that are out of HWE within each population. To do this I will implement a script filter_hwe_by_pop.pl written by Chris Hollenbeck.
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
###### Next, was to filter out potential paralogs and loci with missing data. To do this, the script rad_haplotyper.pl by
```
rad_haplotyper.pl -v SNP.DP3gdp5MIp25g9HWE.recode.vcf  -x 10 -mp 2 -r reference.fasta
```
###### This outputs a file stats.out which contain information on loci with possible paralogs and loci with missing data. This loci are then removed as follows;

```(rad_haplotyper_env) [evelyn-takyi@n038 Aurita_Final2]$ cp stats.out stats.out.HF
(rad_haplotyper_env) [evelyn-takyi@n038 Aurita_Final2]$ mawk '/Missi/' stats.out.HF | mawk '$9 > 30' > HF.missing
(rad_haplotyper_env) [evelyn-takyi@n038 Aurita_Final2]$ mawk '/para/' stats.out.HF > HF.para
(rad_haplotyper_env) [evelyn-takyi@n038 Aurita_Final2]$ ./remove.bad.hap.loci.sh HF.loci.tofilter  SNP.DP3gdp5MIp25g9HWE.recode.vcf  
(rad_haplotyper_env) [evelyn-takyi@n038 Aurita_Final2]$ mawk '!/#/' SNP.DP3gdp5MIp25g9HWE.filtered.vcf | wc -l
3202 SNP loci
```
##### Next, Indels need to be removed  in the data since our focus is on SNPs. To do this we  converted our variant calls to SNPS and indels using vcflib and use VCFtools to remove indels.

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
| Population | Average contig mapped | Average  coverage | No. of individuals | Sites | Polymorphic sites | % polymorphic loci | Obs Het | Exp Het | FIS   |
|------------|-----------------------|-------------------|--------------------|-------|-------------------|--------------------|---------|---------|-------|
| Mauritania | 42623                 | 6.5               | 19                 | 1383  | 1308              | 94.6               | 0.62    | 0.37    | -0.48 |
| Senegal    | 59678                 | 6.4               | 17                 | 1383  | 1355              | 97.9               | 0.63    | 0.38    | -0.46 |
| Guinea     | 17283                 | 4.6               | 7                  | 1383  | 967               | 69.9               | 0.53    | 0.31    | -0.17 |
| Ghana      | 36637                 | 7.2               | 19                 | 1383  | 1333              | 96.3               | 0.61    | 0.37    | -0.44 |
| Togo       | 37741                 | 6.3               | 20                 | 1383  | 1359              | 98.2               | 0.62    | 0.38    | -0.46 |
| Benin      | 36825                 | 6.9               | 15                 | 1383  | 1330              | 96.1               | 0.62    | 0.38    | -0.46 |

#### 2. Determine genetic differentiation in the population
#### The overall FST and FIS values were calculated using the diffcalc function in the genepop package in R. This will output FST and FIS values for each population together with thier confidence interval(CI)
```test_result <- diffCalc(infile = "SNPAUdp.neutralonly.recode.gen", outfile = "myresults",fst = TRUE, pairwise = TRUE, bs_locus = TRUE, bs_pairwise = TRUE, boots = 1000, para = TRUE)
```
overall FST  = 0.0080	 CI (0.0019-0.0157)

overall FIS  = -0.6061 CI	(-0.6557 - -0.5746)

#### Pairwise FST values calculated using the program Genodive

|            | Mauritania | Senegal | Guinea | Ghana  | Togo  |
|------------|------------|---------|--------|--------|-------|
| Mauritania |            |         |        |        |       |
| Senegal    | 0.009      |         |        |        |       |
| Guinea     | 0.07       | 0.029   |        |        |       |
| Ghana      | 0.001      | 0.007   | 0.063  |        |       |
| Togo       | 0.009      | -0.002  | 0.029  | 0.007  |       |
| Benin      | 0          | 0.004   | 0.05   | -0.002 | 0.003 |


#### 3. To determine if any population structure exist.
#### A dendrogram  was generated using the function aboot in the poppr package in R
```{r}
bov_pop <- genind2genpop(genindB)
set.seed(20150428)
pop_tree <- aboot(bov_pop, sample = 1000, cutoff = 50)
```
![Plot](https://github.com/evelyn-takyi/Sardinella-project/blob/master/All%20plot/Tree.png)


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
![plot2](https://github.com/evelyn-takyi/Sardinella-project/blob/master/All%20plot/AUTPCA.png)  

##### Get percent contribution of each PC for representing variation.
```
eig.perc <- 100*rubi.pca$eig/sum(pca$eig)
head(eig.perc)
PC1 0.049751543
PC2 0.015438367
PC3 0.010656234
PC4 0.009853533
PC5 0.009553687

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
![Plot3](https://github.com/evelyn-takyi/Sardinella-project/blob/master/All%20plot/AUTSTR.png)

### Analysis without Guinea populations
### SNP Filtering
```
vcftools --vcf TotalRawSNPs.vcf --max-missing 0.5 --mac 3 --minQ 20 --recode --recode-INFO-all --out raw.g5mac3
After filtering, kept 94 out of 94 Individuals, kept 322471 out of a possible

```
```
./filter_missing_ind.sh raw.g5mac3.recode.vcf DP3g95maf05
After filtering, kept 322471 out of a possible 322471 Sites
Run Time = 32.00 seconds


                                       Histogram of % missing data per individual                                       

  7 +-+----***-+----------+-----------+----------+----------+----------+----------+-----------+----------+--------+-+   
    +      * * +          +           +          +          +          +          +           +          +          +   
    |      * *                                                'totalmissing' using (bin($1,binwidth)):(1.0) ******* |   
    |      * *                                                                                                      |   
  6 +-+    * *                                                                                                    +-+   
    |      * *                                                                                                      |   
    |      * *                                                                                                      |   
    |      * *                                                                                                      |   
  5 +-+  *** *   ***                                                                                              +-+   
    |    * * *   * *                                                                                                |   
    |    * * *   * *                                                                                                |   
  4 +-+  * * *** * *                     ****                                                                     +-+   
    |    * * *** * *                     *  *                                                                       |   
    |    * * *** * *                     *  *                                                                       |   
    |    * * *** * *                     *  *                                                                       |   
  3 +-**** * ***** **  ******            *  *       ***                                                           +-+   
    | ** * * ***** **  * *  *            *  *       * *                                                             |   
    | ** * * ***** **  * *  *            *  *       * *                                                             |   
    | ** * * ***** **  * *  *            *  *       * *                                                             |   
  2 +-** * * ***** ***** *  *            *  *     *** *   **          ******         *** ***                      +-+   
    | ** * * ***** ***** *  *            *  *     * * *   **          *  * *         * * * *                        |   
    | ** * * ***** ***** *  *            *  *     * * *   **          *  * *         * * * *                        |   
    + ** * * ***** ***** *+ *         +  *  *    +* * *   **+         *+ * *      +  * * * *  +          +          +   
  1 +-***********************---------+--****----+*****---**+---------******------+--***-***--+----------+--------+-+   
    0         0.1        0.2         0.3        0.4        0.5        0.6        0.7         0.8        0.9         1   
                                                    % of missing data                                                   

The 85% cutoff would be 0.628435
Would you like to set a different cutoff, yes or no
yes
Please enter new cutoff
0.6
All individuals with more than 60.0% missing data will be removed.
After filtering, kept 77 out of 94 Individuals
After filtering, kept 322471 out of a possible 322471 Sites
```
###### Individuals removed;  TA_1Dres, TA_2Dres, TA_3Dres, SA_4CN, SA_5Cres, MA_2A, MA_7A, MA_8A, GA_F6, GA_A3, GA_1B.res, GA_2B.res, GA_3B.res, BA_7E, BA_5E.res, BA_1E.res,BA_2E

```
vcftools --vcf DP3g95maf05.recode.vcf --minDP 5 --maf 0.01 --recode --recode-INFO-all --out raw.g5mac3dp3
```
###### After filtering, kept 77 out of 77 Individuals
###### After filtering, kept 251879 out of a possible 322471 Sites

```
./pop_missing_filter.sh raw.g5mac3dp3.recode.vcf popmap 0.9 1 TRSdp5MIp25
```
###### After filtering, kept 77 out of 77 Individuals
###### After filtering, kept 156369 out of a possible 251879 Sites
```
./dDocent_filters TRSdp5MIp25.recode.vcf  TRSdp5MIp25g9dd
This script will automatically filter a FreeBayes generated VCF file using criteria related to site depth,
quality versus depth, strand representation, allelic balance at heterzygous individuals, and paired read representation.
The script assumes that loci and individuals with low call rates (or depth) have already been removed.

Contact Jon Puritz (jpuritz@gmail.com) for questions and see script comments for more details on particular filters

Number of sites filtered based on allele balance at heterozygous loci, locus quality, and mapping quality / Depth
 57202 of 156369

Are reads expected to overlap?  In other words, is fragment size less than 2X the read length?  Enter yes or no.
no
Number of additional sites filtered based on overlapping forward and reverse reads
 42523 of 99167

Is this from a mixture of SE and PE libraries? Enter yes or no.
no
Number of additional sites filtered based on properly paired status
 3161 of 56644

Number of sites filtered based on high depth and lower than 2*DEPTH quality score
 8184 of 53483



                                               Histogram of mean depth per site                                         
   Number of Occurrences                                                                                                
     1600 +-+------+--------+--------+-------+--------+--------+--------+--------+--------+-------+--------+------+-+   
          **********        +        +       +        +        +        +        +        +       +        +        +   
          *        *                                      'meandepthpersite' using (bin($1,binwidth)):(1.0) ******* |   
     1400 *-+      *                                                                                              +-+   
          *        *                                                                                                |   
          *        *                                                                                                |   
     1200 *-+      *                                                                                              +-+   
          *        **********                                                                                       |   
          *        *        *                                                                                       |   
     1000 *-+      *        *                                                                                     +-+   
          *        *        *                                                                                       |   
      800 *-+      *        **********                                                                            +-+   
          *        *        *        *                                                                              |   
          *        *        *        *                                                                              |   
      600 *-+      *        *        *                                                                            +-+   
          *        *        *        *********                                                                      |   
          *        *        *        *       *                                                                      |   
      400 *-+      *        *        *       **********                                                           +-+   
          *        *        *        *       *        **********                                                    |   
          *        *        *        *       *        *        *                                                    |   
      200 *-+      *        *        *       *        *        ******************************************************   
          *        *        *        *       *        *        *        *        *        *       *        *        *   
          *        *        *        *       *        *        *        *        *        *       *        *        *   
        0 ***********************************************************************************************************   
          10       11       12       13      14       15       16       17       18       19      20       21       22  
                                                          Mean Depth                                                    

If distrubtion looks normal, a 1.645 sigma cutoff (~90% of the data) would be 2272.999635
The 95% cutoff would be 20
Would you like to use a different maximum mean depth cutoff than 20, yes or no
no
Number of sites filtered based on maximum mean depth
 3003 of 53483

Number of sites filtered based on within locus depth mismatch
 233 of 50480

Total number of sites filtered
 106122 of 156369

Remaining sites
 50247
```
```
vcftools --vcf TRSdp5MIp25g9dd.FIL.recode.vcf --maf 0.05 --recode --recode-INFO-all --out DP3g95maf05d
```
After filtering, kept 77 out of 77 Individuals
After filtering, kept 35141 out of a possible 50247 Sites
```
filter_hwe_by_pop.pl -v DP3g95maf05d.recode.vcf -p popmap -c 0.5 -o SNP.DP3gdp5MIp25g9HWE
Processing population: BA (17 inds)
Processing population: GA (20 inds)
Processing population: MA (19 inds)
Processing population: SA (18 inds)
Processing population: TA (20 inds)
Outputting results of HWE test for filtered loci to 'filtered.hwe'
Kept 35073 of a possible 35141 loci (filtered 68 loci)
```
```
rad_haplotyper.pl -v SNP.DP3gdp5MIp25g9HWE.recode.vcf  -x 10 -mp 5 -r reference.fasta
```
###### Filtered 7027 loci below missing data cutoff
###### Filtered 1264 possible paralogs
###### Filtered 0 loci with low coverage or genotyping errors
###### Filtered 0 loci with an excess of haplotypes
```
[evelyn-takyi@n040 Aurita_Final2]$ cp stats.out stats.out.HF
[evelyn-takyi@n040 Aurita_Final2]$ mawk ...'/Missi/' stats.out.HF | mawk '$9 > 30' > HF.missing
[evelyn-takyi@n040 Aurita_Final2]$ mawk '/Complex/' stats.out.HF | cut -f1 > loci.to.remove
[evelyn-takyi@n040 Aurita_Final2]$ ./remove.bad.hap.loci.sh loci.to.remove SNP.DP3gdp5MIp25g9HWE.recode.vcf
(rad_haplotyper_env) [evelyn-takyi@n040 Aurita_Final2]$ mawk '!/#/' SNP.DP3gdp5MIp25g9HWE.filtered.vcf | wc -l
```
###### 17405 loci remaining
```
vcfallelicprimitives -k -g SNP.DP3gdp5MIp25g9HWE.filtered.vcf | sed 's:\.|\.:\.\/\.:g' > TRSdp5MIp25g9.prim
vcftools --vcf TRSdp5MIp25g9.prim --recode-INFO-all --recode --out SNP.DP3g95maf05d --remove-indels
```
###### After filtering, kept 77 out of 77 Individuals
###### After filtering, kept 19015 out of a possible 20524 Sites
```
(ddocent_env) [evelyn-takyi@n040 Aurita_Final2]$ vcftools --vcf SNP.DP3g95maf05d.recode.vcf --recode-INFO-all --max-missing 0.5 --out SNP.dp5a --recode
```
###### After filtering, kept 77 out of 77 Individuals
###### After filtering, kept 1658 out of a possible 19015 Sites
```
(ddocent_env) [evelyn-takyi@n040 Aurita_Final2]$ vcftools --vcf SNP.dp5a.recode.vcf  --recode-INFO-all --max-alleles 2 --out SNP.7a --recode
```
###### After filtering, kept 77 out of 77 Individuals
###### After filtering, kept 1640 out of a possible 1658 Sites

### Basic statistics
### Global F-stats calculated
```{r}
$FST
[1] 0.001116235
$FIS
[1] -0.5623167
```
| Population | No.of individuals| Sites | Polymorphic Sites | % Polymorphic Loci | Obs Het | Exp Het | Fis    |
|------------|-----------------|-------|-------------------|--------------------|---------|---------|---------|
| Benin      | 13              | 1640  | 1562              | 95                 | 0.61    | 0.37  | -0.43     |
| Ghana      | 15              | 1640  | 1594              | 97                 | 0.59    | 0.37  | -0.42     |
| Mauritania | 16              | 1640  | 1579              | 96                 | 0.60    | 0.37  | -0.44     |                 
| Senegal    | 16              | 1640  | 1613              | 98                 | 0.60    | 0.38  | -0.42     |              
| Togo       | 17              | 1640  | 1629              | 99                 | 0.61    | 0.38  | -0.441    |


#### Pairwise FST values was calculated using the program Genodive
 Values of Fst for all pairs of populations is significant at (p<0.05)

  |            | Benin  | Ghana| Mauritania | Senegal |
 |------------|--------|-------|--------|------------|
 | Benin      |        |       |        |            |  
 | Ghana      | 0.000  |       |        |            |         
 | Mauritania | -0.001 | 0.001 |        |            |     
 | Senegal    | 0.002  | 0.003 | 0.001  |            |         
 | Togo       | 0.002  | 0.004 | 0.002  | -0.002     |



#### 3. To determine if any population structure exist in the populations.
#### A dendrogram  was generated using the function aboot in the poppr package in R
```{r}
bov_pop <- genind2genpop(genindB)
set.seed(20150428)
pop_tree <- aboot(bov_pop, sample = 1000, cutoff = 50)
```
![Plot](https://github.com/evelyn-takyi/Sardinella-project/blob/master/All%20plot/AUTNOGT.png)

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
![plot2](https://github.com/evelyn-takyi/Sardinella-project/blob/master/All%20plot/AUTNOGP.png)  
##### The percent contribution of each PC for representing variation.
```{r}
eig.perc <- 100*rubi.pca$eig/sum(pca$eig)
head(eig.perc)
PC1 0.03711317
PC2 0.03381282
PC3 0.02162289
PC4 0.01827759
PC5 0.01741653
```
#### Discriminant analysis of principal components (DAPC) was conducted in R using  the package Adegenet 1.3.0 to generate the number of clusters or groups present in our population

```
set.seed(20160308) # Setting a seed for a consistent result
grp <- find.clusters(genindB, max.n.clust = 10, n.pca = 35, choose.n.clust = TRUE)
names(grp)
grp$grp
```
###### the BIC plot showing the number of groups.
![Dapc_BIC](https://github.com/evelyn-takyi/Sardinella-project/blob/master/dapc_BIC.png)-

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
![Plot3](https://github.com/evelyn-takyi/Sardinella-project/blob/master/All%20plot/noGUI2.png)




## S. maderensis
### Denovo Assembly of references

a.The script ReferenceOpt.sh was run  to pick the cut off values of K1 and K2 and a similarity threshold.
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

The similarity threshold of 90% was  observed to be the appropriate cut off value.

b. The script RefMapOpt.sh was run to pick K1, K2 values which showed number of reads that properly paired with the reference contigs,  have good coverage and minimizes mismatched reads.

```
bash RefMapOpt.sh 2 5 2 5 0.9 20 PE
```
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

###### c. The script  remake_reference.sh was used to remake the reference with the cut off value of K1=2, K2=3, and a c value of 0.9

```
bash remake_reference.sh 2 3 0.90 PE 20
mawk '/>/' reference.fasta | wc -l
```
**61264** Contigs were assembled for *S.maderensis*

#### Blast sequences from ncbi to the denovo reference assembly on the command line
#####  First build a database of the reference assembly
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
##### Next is perform a nucleotide blast on references
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

##### The dDocent pipeline was used to map all the reads to the reference assembly and variant  calling.
##### The average coverage per contig per sample was determined using samtools depth command from SAMtools and the  and average contig mapped by each sample was determine using the coverage statistics outputed by the ddocent pipeline.
```
samtools depth *bam  |  awk '{sum+=$3} END { print "Average = ",sum/NR}'
cat *cov.stats | awk '$4>0{c++} END{print c+0}'
```

#### Results of mapping
| Sample  | Country    | Average contig mapped | Average coverage per contig |
|---------|------------|-----------------------|-----------------------------|
| MM_10A  | Mauritania | 20066.5               | 5.5                         |
| MM_11A  | Mauritania | 13644                 | 2.9                         |
| MM_11B  | Mauritania | 10513                 | 10.1                        |
| MM_12A  | Mauritania | 14686.5               | 3.8                         |
| MM_1A   | Mauritania | 12652.5               | 2.8                         |
| MM_2A   | Mauritania | 20268.5               | 5                           |
| MM_3A   | Mauritania | 1013                  | 3.1                         |
| MM_4A   | Mauritania | 11447                 | 5.5                         |
| MM_4B   | Mauritania | 8600.5                | 3.17                        |
| MM_5A   | Mauritania | 20415.5               | 5.1                         |
| MM_6A   | Mauritania | 13481.5               | 3.3                         |
| MM_6B   | Mauritania | 8082.5                | 2.8                         |
| MM_7A   | Mauritania | 12173                 | 2.9                         |
| MM_7B   | Mauritania | 17455.5               | 3.4                         |
| MM_8A   | Mauritania | 14304                 | 3.3                         |
| MM_9A   | Mauritania | 21060                 | 6.4                         |
| MM_9B   | Mauritania | 17317                 | 3.43                        |
| MM_D10  | Mauritania | 35891.5               | 8.3                         |
| MM_D4   | Mauritania | 33971.5               | 6.6                         |
| MM_D5   | Mauritania | 32672                 | 4.7                         |
| MM_D6   | Mauritania | 36386.5               | 8.4                         |
| MM_G7   | Mauritania | 32847.5               | 7.4                         |
| MM_G9   | Mauritania | 178.5                 | 2                           |
| SM__1B  | Senegal    | 17379                 | 4.3                         |
| SM_1C   | Senegal    | 8975.5                | 2.3                         |
| SM__2B  | Senegal    | 18301                 | 5.2                         |
| SM__2C  | Senegal    | 16627                 | 4.2                         |
| SM__3B  | Senegal    | 16582                 | 5                           |
| SM__3C  | Senegal    | 18992.5               | 4                           |
| SM_4C   | Senegal    | 10538.5               | 8.1                         |
| SM__4C  | Senegal    | 16979                 | 5.8                         |
| SM__5C  | Senegal    | 19967                 | 14.7                        |
| SM_H10  | Senegal    | 11871.5               | 7.1                         |
| SM_H1   | Senegal    | 28819.5               | 7.43                        |
| SM_H2   | Senegal    | 36959.5               | 9.2                         |
| SM_H3   | Senegal    | 39627                 | 9.4                         |
| SM_H4   | Senegal    | 37214                 | 6.9                         |
| SM_H5   | Senegal    | 35896                 | 6.6                         |
| SM_H6   | Senegal    | 36111.5               | 6.5                         |
| SM_H7   | Senegal    | 37034                 | 7.4                         |
| SM_H8   | Senegal    | 33626                 | 6.5                         |
| SM_H9   | Senegal    | 17263                 | 10.1                        |
| GM_10E  | Guinea     | 20311.5               | 8.3                         |
| GM_23   | Guinea     | 2069                  | 4.8                         |
| GM_25   | Guinea     | 1564.5                | 4.7                         |
| GM_26   | Guinea     | 4473                  | 4.8                         |
| GM_27   | Guinea     | 1964                  | 3.3                         |
| GM_28   | Guinea     | 5374                  | 4.6                         |
| GM_29   | Guinea     | 4225                  | 3.9                         |
| GM_30   | Guinea     | 2602.5                | 4.3                         |
| GM_33   | Guinea     | 1217.5                | 4.47                        |
| GM_34   | Guinea     | 1492                  | 5.4                         |
| GM_35   | Guinea     | 993.5                 | 4.9                         |
| GM_36   | Guinea     | 5907.5                | 6.4                         |
| GM_37   | Guinea     | 3009.5                | 3.3                         |
| GM_38   | Guinea     | 6420                  | 3.7                         |
| GM_39   | Guinea     | 3256.5                | 4                           |
| GM_40   | Guinea     | 15566                 | 3.6                         |
| GM_6E   | Guinea     | 11302                 | 4                           |
| GM_6F   | Guinea     | 13644                 | 2.8                         |
| GM_7E   | Guinea     | 24546.5               | 2.9                         |
| GM_8E   | Guinea     | 14686.5               | 5.8                         |
| TM_10B  | Togo       | 24446.5               | 5.3                         |
| TM_11A  | Togo       | 8040                  | 4.5                         |
| TM_11B  | Togo       | 28482.5               | 6.8                         |
| TM_12A  | Togo       | 20463                 | 3.5                         |
| TM_12B  | Togo       | 12991                 | 2.9                         |
| TM_26   | Togo       | 21156.5               | 5.6                         |
| TM_37   | Togo       | 19946.5               | 5.1                         |
| TM_38   | Togo       | 25566                 | 6.4                         |
| TM_39   | Togo       | 18995.5               | 4.9                         |
| TM_3A   | Togo       | 10546                 | 3.5                         |
| TM_45   | Togo       | 11683                 | 7.3                         |
| TM_4A   | Togo       | 2805.5                | 3.3                         |
| TM_4B   | Togo       | 17519.5               | 6.2                         |
| TM_5A   | Togo       | 14571                 | 4.3                         |
| TM_5B   | Togo       | 32199.5               | 8.6                         |
| TM_6A   | Togo       | 13275.5               | 8.9                         |
| TM_6B   | Togo       | 15181                 | 2.4                         |
| TM_8A   | Togo       | 19150                 | 4.2                         |
| TM_8B   | Togo       | 13276.5               | 4.4                         |
| TM_8B   | Togo       | 22952.5               | 6.9                         |
| BM_10E  | Benin      | 16863                 | 7.1                         |
| BM_11E  | Benin      | 24546.5               | 6.3                         |
| BM_12E  | Benin      | 20436.5               | 5.8                         |
| BM_1F   | Benin      | 24892                 | 4.5                         |
| BM_2F   | Benin      | 20242                 | 5.4                         |
| BM_3F   | Benin      | 16164.5               | 5.5                         |
| BM_4F   | Benin      | 19979                 | 4.9                         |
| BM_5F   | Benin      | 18287.5               | 4.5                         |
| BM_7F   | Benin      | 17848                 | 9.5                         |
| BM_A11  | Benin      | 40130.5               | 3.5                         |
| BM_A12  | Benin      | 37131                 | 10.5                        |
| BM_B11  | Benin      | 39898                 | 6.6                         |
| BM_B12  | Benin      | 34648.5               | 10.1                        |
| BM_C11  | Benin      | 32522.5               | 6.7                         |
| BM_D11  | Benin      | 36982                 | 6.3                         |
| BM_E11  | Benin      | 33914                 | 6.7                         |
| BM_F11  | Benin      | 39138                 | 6.6                         |
| BM_G11  | Benin      | 34197.5               | 7.5                         |
| BM_H11  | Benin      | 37002.5               | 6.3                         |
| NM_10F  | Nigeria    | 5959.5                | 3                           |
| NM_10G  | Nigeria    | 6676                  | 4.6                         |
| NM_11F  | Nigeria    | 2486.5                | 2.1                         |
| NM_11G  | Nigeria    | 11511.5               | 3.6                         |
| NM_12F  | Nigeria    | 417                   | 1.5                         |
| NM_12G  | Nigeria    | 24446.5               | 5.3                         |
| NM_1G   | Nigeria    | 9007                  | 4.2                         |
| NM_1H   | Nigeria    | 5588                  | 2.7                         |
| NM_2G   | Nigeria    | 5818                  | 3.4                         |
| NM_2H   | Nigeria    | 6470.5                | 4.6                         |
| NM_3G   | Nigeria    | 6783                  | 5                           |
| NM_3H   | Nigeria    | 6984.5                | 3.8                         |
| NM_4G   | Nigeria    | 4978.5                | 2.8                         |
| NM_5G   | Nigeria    | 2304.5                | 2.1                         |
| NM_6G   | Nigeria    | 6186.5                | 3.1                         |
| NM_7G   | Nigeria    | 5998                  | 2.8                         |
| NM_8F   | Nigeria    | 6367.5                | 3.1                         |
| NM_8G   | Nigeria    | 6966                  | 5.2                         |
| NM_9F   | Nigeria    | 2816                  | 2.3                         |
| NM_9G   | Nigeria    | 3002                  | 2.8                         |


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
After filtering, kept 142840 out of a possible 142840 Sites
Individuals removed are; SM_H10, NM_9F,NM_9G, NM_5G, NM_11F, NM_11G, NM_12F, NM_12G, MM_G9, MM_3A, GM_37, GM_30, GM_33, GM_34, GM_35, GM_23, GM_25.
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

| Population | Average contig mapped | Average  coverage | No. of individuals | Sites | Polymorphic sites | % polymorphic loci | Obs Het | Exp Het | FIS   |
|------------|-----------------------|-------------------|--------------------|-------|-------------------|--------------------|---------|---------|-------|
| Mauritania | 17788                 | 4.7               | 21                 | 1559  | 902               | 57.8               | 0.25    | 0.18    | -0.11 |
| Senegal    | 24145                 | 6.8               | 18                 | 1559  | 867               | 55.6               | 0.25    | 0.18    | -0.12 |
| Guinea     | 7231                  | 4.5               | 12                 | 1559  | 713               | 45.7               | 0.24    | 0.17    | -0.08 |
| Togo       | 17662                 | 6.8               | 21                 | 1559  | 885               | 56.7               | 0.26    | 0.18    | -0.12 |
| Benin      | 28674                 | 6.5               | 19                 | 1559  | 954               | 61.1               | 0.26    | 0.19    | -0.13 |
| Nigeria    | 6538                 | 3.4               | 15                 | 1559  | 1013              | 64.9               | 0.22    | 0.25    | 0.19  |



##### The overall FST and FIS values were calculated using the diffcalc function in the genepop package in R
```test_result <- diffCalc(infile = "SNPmadp.neutralonly.recode.gen", outfile = "madresults",fst = TRUE, pairwise = TRUE, bs_locus = TRUE, bs_pairwise = TRUE, boots = 1000, para = TRUE)
```

```{r}
overall FST  =  0.1931	 CI (0.0858 - 0.3720)
overall FIS  = -0.1857	CI (-0.4258	- -0.0848)
```

##### Pairwise FST values calculated using the program Genodive
|            | Mauritania | Senegal | Guinea | Togo   | Benin |
|------------|------------|---------|--------|--------|-------|
| Mauritania |            |         |        |        |       |
| Senegal    | 0.006      |         |        |        |       |
| Guinea     | 0          | 0.006   |        |        |       |
| Togo       | 0.007      | 0.009   | 0.016  |        |       |
| Benin      | 0          | 0.002   | 0.003  | -0.005 |       |
| Nigeria    | 0.38       | 0.36    | 0.39   | 0.37   | 0.39  |

#### Neighbor Joining tree
 ```{r}
 bov_pop <- genind2genpop(genindB)
 set.seed(20150428)
 pop_tree <- aboot(bov_pop, sample = 1000,
                            cutoff = 50)
```                            
![plot1](https://github.com/evelyn-takyi/Sardinella-project/blob/master/All%20plot/jessy7.png)

#### DAPC

```set.seed(20160308) # Setting a seed for a consistent result
grp <- find.clusters(genindB, max.n.clust = 10, n.pca = 55, choose.n.clust = TRUE)
names(grp)
grp$grp
dapc1 <- dapc(genindB, grp$grp, n.pca = 10, n.da = 2)
scatter(dapc1) # plot of the group
```
![Dapc_BIC](https://github.com/evelyn-takyi/Sardinella-project/blob/master/BIC_MAD.png)

#### structure-like plot using Posterior probability from dapc function
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


### Analysis performed excluding  Nigerian Populatiion
#### Basic Statistic

| Population | Private Alleles | Sites | Polymorphic Sites | % Polymorphic Loci | Obs Het | Exp Het | nucleotide diversity | Fis     |
|------------|-----------------|-------|-------------------|--------------------|---------|---------|----------------------|---------|
| Benin      | 22              | 1112  | 954               | 85.7               | 0.372   | 0.270   | 0.284               | -0.187   |
| Guinea     | 2               | 1112  | 713               | 64.1               | 0.345   | 0.242   | 0.285               | -0.113   |
| Mauritania | 12              | 1112  | 902               | 81.1               | 0.355   | 0.258   | 0.276               | -0.167   |
| Senegal    | 24              | 1112  | 867               | 77.96              | 0.359   | 0.256   | 0.276               | -0.172   |
| Togo       | 17              | 1112  | 885               | 79.58              | 0.367   | 0.263   | 0.282               | -0.176   |


##### The overall FST and FIS values were calculated using the diffcalc function in the genepop package in R

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

#### Neighbor joining tree
   ```{r}
   bov_pop <- genind2genpop(genindB)
   set.seed(20150428)
   pop_tree <- aboot(bov_pop, sample = 1000,
                              cutoff = 50)
   ```
![Plot3](https://github.com/evelyn-takyi/Sardinella-project/blob/master/All%20plot/jessy10.png)

#### structure-like plot using Posterior probability from dapc function

![Plot3](https://github.com/evelyn-takyi/Sardinella-project/blob/master/All%20plot/jessy11.png)

#### Reference assembly generated with only  Nigerian samples and blast with sequences of s. maderensis from ncbi to determine whether sequence reads from Nigeria matches any.
```
Database: mad
           23,229 sequences; 7,545,084 total letters



Query= KX062183.1 Sardinella maderensis isolate SMAD4 tRNA-Glu (trnE) gene,
partial sequence; and cytochrome b (cytb) gene, partial cds;
mitochondrial

Length=414
                                                                      Score     E
Sequences producing significant alignments:                          (Bits)  Value

dDocent_Contig_1727                                                   215     4e-56

Query= KP307702.1 Sardinella maderensis voucher TAU<ISR_:P.15439 cytochrome b (cytb) gene, partial cds; mitochondrial

Length=458
                                                                      Score     E
Sequences producing significant alignments:                          (Bits)  Value

dDocent_Contig_1727                                                   252     4e-67

uery= NC_009587.1 Sardinella maderensis mitochondrion, complete genome

Length=16651
                                                                      Score     E
Sequences producing significant alignments:                          (Bits)  Value

dDocent_Contig_3659                                                   416     4e-115
dDocent_Contig_18336                                                  379     6e-104
dDocent_Contig_446                                                    363     6e-99
dDocent_Contig_2143                                                   327     2e-88
dDocent_Contig_2021                                                   327     2e-88
dDocent_Contig_1727                                                   324     3e-87
dDocent_Contig_10543                                                  320     4e-86
dDocent_Contig_7764                                                   300     5e-80
dDocent_Contig_5329                                                   289     1e-76
dDocent_Contig_824                                                    287     4e-76
dDocent_Contig_219                                                    259     8e-68
dDocent_Contig_4319                                                   255     1e-66
dDocent_Contig_517                                                    250     5e-65
dDocent_Contig_3168                                                   198     2e-49
dDocent_Contig_612                                                    193     8e-48
dDocent_Contig_340                                                    182     2e-44
dDocent_Contig_9701                                                   174     3e-42
```



### Analysis performed combining both reads of *s. aurita* and *S.maderensis*
##### AIM: To show whether there is clear differentiation between *s.aurita* and *s.maderensis*

 **1203 neutral loci FINAL FILTERED SNPS**

###### Packages loaded in R
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
###### This code reads the SNP VCF file into R and converts it into a genlight  object.
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
###### This code converts the file into a genind object
```
genindB <- vcfR2genind(AU1)
strata<- read.table("~/Desktop/FINALANALYSIS/popmap.txt", header=TRUE)
strata_df <- data.frame(strata)
strata(genindB) <- strata_df
setPop(genindB) <- ~Population
```
###### Determine the overall FST and FIS values
```
fstat(genindB)
wc(genindB)
```          
$FST
[1] 0.1279823

$FIS
[1] -0.2260168

###### construct a Neighbor joining tree
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
