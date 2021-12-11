# petal_bach_goldberg-variations
data sets for performance analyses of Johann Sebastian Bach’s 'Goldberg Variations' BWV 988

This repository introduces the data sets created during research on recorded performances of Johann Sebastian Bach’s 'Goldberg Variations' BWV 988. It complements the following  article:

Motavasseli, Majid. 2021. “Interpretation of Cyclic Form in Bach’s ‘Goldberg Variations’ through Performance History.” *Zeitschrift der Gesellschaft für Musiktheorie* 18. Special Issue: *Musikalische Interpretation als Analyse. Historische, empirische und analytische Annäherungen an Aufführungsstrategien musikalischer Zyklen*: 19–69. https://doi.org/10.31751/1119

# main content

The data discussed in Motavasseli 2021 refer to 76 different recordings of Goldberg Variations as detailed in the discography published in the appendix of the article.

## (1) raw data (76 recordings)
The Excel sheet **[Goldberg Variations_raw data_tpo_76 rec.xlsx](https://github.com/petal2020/petal_bach_goldberg-variations/blob/main/Goldberg%20Variations_raw%20data_tpo_76%20rec.xlsx)** contains the tempo values of each recording in **76 separate worksheets**. The worksheets provide raw tempo values for the initial tempo (first 8 bars) of each aria and variation. Based on these data, the tempo values of different segments (such as mm. 1-8, 2-7, 1-4, and 5-8) have been calculated. The worksheets also show the *standard deviation* (SD) and *deviation* (mm. 2-7 vs. 1-8; mm. 5-8 vs. 1-4) within and between each segment (in %), visualised by a red colour scale. 

## (2) repeats (76 recordings)

The tsv-file **[Goldberg Variations_Repeats.tsv](https://github.com/petal2020/petal_bach_goldberg-variations/blob/main/Goldberg%20Variations_Repeats.tsv)** indicates the execution of repeats for each aria and variation in the 76 selected recordings.

## (3) tempo table (76 recordings)

Corresponding to the tempo table (for the tempo segment mm. 2-7) already published in Motavasseli 2021, the tsv-files **[Goldberg Variations_Tempo mm. 1-8.tsv](https://github.com/petal2020/petal_bach_goldberg-variations/blob/main/Goldberg%20Variations_Tempo%20mm.%201-8.tsv)**; **[Goldberg Variations_Tempo mm. 1-4.tsv](https://github.com/petal2020/petal_bach_goldberg-variations/blob/main/Goldberg%20Variations_Tempo%20mm.%201-4.tsv)**; **[Goldberg Variations_Tempo mm. 5-8.tsv](https://github.com/petal2020/petal_bach_goldberg-variations/blob/main/Goldberg%20Variations_Tempo%20mm.%205-8.tsv)** contain tempo tables providing an overview of the tempo values of the remaining tempo segments (mm. 1-8, 1-4 and 5-8).
