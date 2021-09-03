[![DOI](https://zenodo.org/badge/397271076.svg)](https://zenodo.org/badge/latestdoi/397271076)

This repository contains three files. The first contains the indivual subject data for in-phase tone (thresholds_n_itd_s_0.csv), the second contains the results obtained with an out-of-phase tone (thresholds_n_itd_s_pi.csv). The third (model_and_subject_median.csv) contains the inter-subject median as well as the results obtained with the model.

All Files are formated as comma seperated values. The first line of each file contains the column names with each following line containg one dataset.

Description of the data contained in thresholds_n_itd_s_0.csv and thresholds_n_itd_s_pi.csv

| Column Name | Datatype    | Description                       |
|-------------|---------|---------------------------------------|
| subject     | integer | The subject ID (0-6)                  |
| itd         | float   | The noise ITD in seconds              |
| thr         | float   | The tone level at detection threshold |
| bw          | float   | The noise bandwidth in Hz             |

Description of the data contained in model_and_subject_median.csv.

| Column Name | Datatype    | Description                                      |
|-------------|---------|------------------------------------------------------|
| erb         | integer | The gammatone ERB, no value in case of subject data  |
| bw          | float   | The noise bandwidth in Hz                            |
| itd         | float   | The noise ITD in seconds                             |
| thr         | float   | The tone level at detection threshold                |
