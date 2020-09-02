# Security audit logs for Process-Mining
This repository contains an artificially created dataset that contains data that can be obtained from security audits. Data are prepared for process mining analysis. This dataset consists of three CSV files.
## data_flow.csv
This file contains information on how files were sent across the organization.
Its structure is: *case_id;activity;start_date;end_date;sensitive;filename*.
## file_operations.csv
This file contains the file operations that were performed by the organization's employees.
Its structure is: *case_id;operation;timestamp*.
## user_activity.csv
This file contains information about the 30 days application usage of one employee. Then it contains five safe and five malicious traces that can be used for the conformance checking. This file was preprocessed to be usable by process mining analysis.
Its structure is: *case_id;start;activity;user_id*.
