
This repository contains two files one with the data obtained with an in-phase tone (thresholds_n_itd_s_0.csv), the other with the results obtained with an out-of-phase tone (thresholds_n_itd_s_pi.csv). The Files are formated as comma seperated values. The first line of each file contains the column names with each following line containg one dataset.

Description of the data contained in the two files

| Column Name | Datatype    | Description                       |
|-------------|---------|---------------------------------------|
| subject     | integer | The subject ID (0-6)                  |
| itd         | float   | The noise ITD in seconds              |
| thr         | float   | The tone level at detection threshold |
| bw          | float   | The noise bandwidth in Hz             |
