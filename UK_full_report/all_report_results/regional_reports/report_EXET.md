







# Lineages report for EXET




This report gives summaries of UK specific lineages sequenced by EXET for week 2020-06-19. 
There are time lags due to batching, curation and analysis, the most recently sampled sequence is 2020-06-03. The analysis (eg time since last sample) is therefore undertaken from this date.
<br/>
312 sequences in the UK from the sequencing centre EXET have been included in this analysis.


A few notes: the size of a lineage may be due to a low amount of transmission of this lineage, but it is likely also that it just hasn't been sampled as frequently, especially for newer lineages.
It's also important to realise that these lineages are *estimates* of how we think the virus is spreading in the UK after being introduced from abroad, as the low evolutionary rate of the virus makes it difficult to separate lineages with certainty.



The minimum number of introductions is 26 and the maximum is 189


Sequences which were replicates or too error-prone were removed from this analysis.



47 are lineages which only contained five sequences or fewer, and so have been left out of visualisation in the interests of clarity


Furthermore, those sequences which haven't been sampled in the last month are not shown.



Of the 4 that remain:
2 are pending extinction, ie last seen three weeks ago.
1 has reactivated.
1 lineage has been continuously circulating.



The following table contains information about the ten largest lineages lineages and the number of sequences the dataset. Information about other lineages is found in the appendix, along with the raw data for all of the other figures.


Each entry is the count of sequences from each lineage in each country, with the percentage of the total sequences from that lineage that this count represents.

"Activity score" is calculated by taking the average gap between sampling for each lineage, and dividing it by the number of days since the lineage was last sampled. Therefore the higher the number, the more active the lineage is.
If the score is above 1, then it has been sampled *more* recently than expected given its average gap size. We might interpret this as an increase in activity.
If the score is below 1, it has been sampled *less* recently than expect given its average gap size, so we might interpret this as a decrease in activity.



The global lineages are correct as of the data release on 2020-05-19


It is written to "summary_files" as "lineage_summary.tsv" for further use, and the full list of lineages is available in the same directory as "all_lineages.csv"



| Lineage name   | England      | Date range     |   Total sequences | Global lineage   |   Time since last sample (days) | Activity score   |
|:---------------|:-------------|:---------------|------------------:|:-----------------|--------------------------------:|:-----------------|
| UK5            | 100 (100.0%) | Mar-12, May-13 |               100 | B.1.1.1, B.1.1   |                              21 | 0.0298           |
| UK476          | 55 (100.0%)  | Mar-30, May-06 |                55 | B.1.1            |                              28 | 0.0245           |
| UK2916         | 20 (100.0%)  | Mar-22, May-01 |                20 | B.1              |                              33 | 0.0638           |
| UK63           | 16 (100.0%)  | Mar-23, May-10 |                16 | B.1.1            |                              24 | 0.1333           |
| UK497          | 8 (100.0%)   | Mar-17, Jun-03 |                 8 | A.2              |                               0 | active today     |
| UK5501         | 6 (100.0%)   | Apr-27, Jun-01 |                 6 | B.1.12           |                               2 | 3.5              |
| UK3692         | 6 (100.0%)   | Mar-31, May-01 |                 6 | B.1.1            |                              33 | 0.1879           |
| UK3929         | 6 (100.0%)   | Apr-12, Apr-27 |                 6 | B.1.1            |                              37 | 0.0811           |
| UK570          | 6 (100.0%)   | Mar-24, Apr-29 |                 6 | B.1.1            |                              35 | 0.2057           |


These data is represented in the figure one. Note that the number of sequences is likely to be due more to differing sampling efforts in different regions, rather than genuine differences in numbers of cases. 

The raw data for this bar chart are in the table above.


![Number of sequences sampled in a lineage by country](/cephfs/covid/bham/raccoon-dog/2020-06-19/analysis/7/regional_reports/EXET/figures/report_EXET_stacked_bars_by_country_1.png){#stacked_bars_by_country }


Different sequencing centres have different delays in turn around from receipt of samples to submission of sequence data. 
This will affect all of the figures shown after this if lineages have geographical variation, as some regions have less up to date data.


```
The lag for this sequencing centre is 16 days
```



The relative growth and decline of the ten most sampled lineages in terms of number of counties they are present in is shown in figure three. 



![Lineages by number of adm2 regions present by epiweek](/cephfs/covid/bham/raccoon-dog/2020-06-19/analysis/7/regional_reports/EXET/figures/report_EXET_geog_plot_1.png){#geog_plot }










These lineages are shown on the timeline. Each line represents the length of the cluster, from oldest to most recent sampling date.
The dots are sized by the number of sequences taken on that date, and again are colour coded by country.
The raw data has been written to a summary file.




![Timeline of lineages, sized by number of sequences from each country.](/cephfs/covid/bham/raccoon-dog/2020-06-19/analysis/7/regional_reports/EXET/figures/report_EXET_make_timeline_1.png){#make_timeline }


The date of first sequence in the cluster is shown in figure five for every cluster with date information. 






![Lineage starts per week, split by singletons and non-singletons](/cephfs/covid/bham/raccoon-dog/2020-06-19/analysis/7/regional_reports/EXET/figures/report_EXET_firsts_plot_1.png){#firsts_plot }

For comparison, here is a plot of the day that every sequence was taken, coloured by country. Note that sequences without dates were not included.


![Sequences taken on each day by country](/cephfs/covid/bham/raccoon-dog/2020-06-19/analysis/7/regional_reports/EXET/figures/report_EXET_seqs_over_time_1.png){#seqs_over_time }


The map shows the number of sequences sampled in each admin2 region in the UK. The colour scale is the same for all four countries, but with different underlying base colours.





```
All sequences have been assigned clean adm2 data this week.
```

![Map showing the number of sequences sampled by adm2 region](/cephfs/covid/bham/raccoon-dog/2020-06-19/analysis/7/regional_reports/EXET/figures/report_EXET_map_1.png){#map }












Other results modules for UK lineage analysis can be added in here if required.

\pagebreak

## Appendix









Below are the raw data tables for each of the figures in the report.

**Table S1** Description of all lineages that have been circulating in the last month, and have more than 5 sequences.


| Lineage name   | England      | Date range     |   Total sequences | Global lineage   |   Time since last sample (days) | Activity score   |
|:---------------|:-------------|:---------------|------------------:|:-----------------|--------------------------------:|:-----------------|
| UK5            | 100 (100.0%) | Mar-12, May-13 |               100 | B.1.1.1, B.1.1   |                              21 | 0.0298           |
| UK476          | 55 (100.0%)  | Mar-30, May-06 |                55 | B.1.1            |                              28 | 0.0245           |
| UK2916         | 20 (100.0%)  | Mar-22, May-01 |                20 | B.1              |                              33 | 0.0638           |
| UK63           | 16 (100.0%)  | Mar-23, May-10 |                16 | B.1.1            |                              24 | 0.1333           |
| UK497          | 8 (100.0%)   | Mar-17, Jun-03 |                 8 | A.2              |                               0 | active today     |
| UK5501         | 6 (100.0%)   | Apr-27, Jun-01 |                 6 | B.1.12           |                               2 | 3.5              |
| UK3692         | 6 (100.0%)   | Mar-31, May-01 |                 6 | B.1.1            |                              33 | 0.1879           |
| UK3929         | 6 (100.0%)   | Apr-12, Apr-27 |                 6 | B.1.1            |                              37 | 0.0811           |
| UK570          | 6 (100.0%)   | Mar-24, Apr-29 |                 6 | B.1.1            |                              35 | 0.2057           |

\pagebreak

**Table S2** Raw data for figure two showing lags between the most recent sequence and current date for each sequencing centre


|    | Centre   |   Lag in days |
|---:|:---------|--------------:|
|  0 | EXET     |            16 |

\pagebreak

**Table S3** Raw data for figure three showing the number of admin2 regions a lineage is present in over time


| Week commencing   |   UK5 |   UK63 |   UK497 |   UK5501 |
|:------------------|------:|-------:|--------:|---------:|
| 2020-03-08        |     1 |      0 |       0 |        0 |
| 2020-03-15        |     0 |      0 |       1 |        0 |
| 2020-03-22        |     1 |      1 |       1 |        0 |
| 2020-03-29        |     1 |      0 |       0 |        0 |
| 2020-04-05        |     1 |      1 |       0 |        0 |
| 2020-04-12        |     1 |      1 |       0 |        0 |
| 2020-04-19        |     1 |      1 |       1 |        0 |
| 2020-04-26        |     1 |      1 |       1 |        1 |
| 2020-05-03        |     2 |      1 |       0 |        1 |
| 2020-05-10        |     1 |      1 |       0 |        0 |
| 2020-05-17        |     0 |      0 |       0 |        1 |
| 2020-05-24        |     0 |      0 |       0 |        1 |
| 2020-05-31        |     0 |      0 |       1 |        1 |

\pagebreak


Table S4 is not appropriate for this report and so has been omitted.




\pagebreak

**Table S5** Raw data for figure five showing when lineages started per day, divided by singletons and non-singletons


| Day        |   Number of singleton starts |   Number of non-singleton starts |   Total |
|:-----------|-----------------------------:|---------------------------------:|--------:|
| 2020-03-12 |                            0 |                                1 |       1 |
| 2020-03-13 |                            0 |                                1 |       1 |
| 2020-03-14 |                            0 |                                1 |       1 |
| 2020-03-17 |                            0 |                                2 |       2 |
| 2020-03-22 |                            1 |                                1 |       2 |
| 2020-03-23 |                            0 |                                2 |       2 |
| 2020-03-24 |                            0 |                                2 |       2 |
| 2020-03-25 |                            3 |                                0 |       3 |
| 2020-03-26 |                            2 |                                0 |       2 |
| 2020-03-28 |                            1 |                                2 |       3 |
| 2020-03-29 |                            2 |                                0 |       2 |
| 2020-03-30 |                            0 |                                1 |       1 |
| 2020-03-31 |                            4 |                                1 |       5 |
| 2020-04-01 |                            1 |                                1 |       2 |
| 2020-04-02 |                            0 |                                1 |       1 |
| 2020-04-04 |                            0 |                                2 |       2 |
| 2020-04-06 |                            0 |                                2 |       2 |
| 2020-04-07 |                            1 |                                1 |       2 |
| 2020-04-09 |                            1 |                                0 |       1 |
| 2020-04-11 |                            1 |                                0 |       1 |
| 2020-04-12 |                            1 |                                3 |       4 |
| 2020-04-14 |                            0 |                                1 |       1 |
| 2020-04-15 |                            0 |                                1 |       1 |
| 2020-04-16 |                            1 |                                0 |       1 |
| 2020-04-20 |                            1 |                                2 |       3 |
| 2020-04-21 |                            3 |                                0 |       3 |
| 2020-04-24 |                            1 |                                0 |       1 |
| 2020-04-27 |                            0 |                                1 |       1 |
| 2020-04-29 |                            1 |                                0 |       1 |
| 2020-05-03 |                            1 |                                0 |       1 |
| 2020-05-04 |                            1 |                                0 |       1 |

\pagebreak

**Table S6** Raw data for figure six showing the number of sequences taken over time.


| Day        |   England |
|:-----------|----------:|
| 2020-03-12 |         1 |
| 2020-03-13 |         1 |
| 2020-03-14 |         1 |
| 2020-03-17 |         3 |
| 2020-03-22 |         3 |
| 2020-03-23 |         3 |
| 2020-03-24 |         2 |
| 2020-03-25 |         8 |
| 2020-03-26 |         3 |
| 2020-03-27 |         5 |
| 2020-03-28 |         5 |
| 2020-03-29 |         5 |
| 2020-03-30 |         2 |
| 2020-03-31 |         8 |
| 2020-04-01 |         5 |
| 2020-04-02 |         2 |
| 2020-04-03 |         4 |
| 2020-04-04 |        17 |
| 2020-04-05 |         5 |
| 2020-04-06 |        10 |
| 2020-04-07 |        11 |
| 2020-04-08 |         4 |
| 2020-04-09 |        10 |
| 2020-04-10 |        15 |
| 2020-04-11 |         6 |
| 2020-04-12 |        13 |
| 2020-04-13 |        12 |
| 2020-04-14 |        11 |
| 2020-04-15 |        17 |
| 2020-04-16 |         6 |
| 2020-04-17 |        13 |
| 2020-04-18 |         7 |
| 2020-04-19 |         2 |
| 2020-04-20 |        17 |
| 2020-04-21 |         7 |
| 2020-04-22 |         8 |
| 2020-04-23 |         4 |
| 2020-04-24 |         5 |
| 2020-04-25 |         2 |
| 2020-04-26 |         2 |
| 2020-04-27 |         6 |
| 2020-04-28 |         2 |
| 2020-04-29 |         9 |
| 2020-05-01 |         3 |
| 2020-05-03 |         6 |
| 2020-05-04 |         4 |
| 2020-05-05 |         3 |
| 2020-05-06 |         6 |
| 2020-05-10 |         1 |
| 2020-05-11 |         1 |
| 2020-05-13 |         1 |
| 2020-05-19 |         1 |
| 2020-05-25 |         1 |
| 2020-05-31 |         1 |
| 2020-06-01 |         1 |
| 2020-06-03 |         1 |

\pagebreak

**Table S7** Raw data for the figure seven with the number of sequences assigned to each admin2 region.


| Admin2    | Country   |   Number of sequences | Sequence group   |
|:----------|:----------|----------------------:|:-----------------|
| CORNWALL  | England   |                     2 | 1-10             |
| DEVON     | England   |                   306 | 300-400          |
| DORSET    | England   |                     2 | 1-10             |
| PLYMOUTH  | England   |                     1 | 1-10             |
| WILTSHIRE | England   |                     1 | 1-10             |

\pagebreak





