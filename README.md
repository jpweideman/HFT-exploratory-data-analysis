# HFT-exploratory-data-analysis

This project involves large datasets that are too big to store directly in this GitHub repository. To efficiently handle these datasets, we use DVC (Data Version Control) for versioning and tracking, and Google Cloud Storage as a remote storage location.

To import the data from DVC, run the following command:
```bash
dvc import-url gs://hft-d-a-t-a Data
