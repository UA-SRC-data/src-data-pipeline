# src-data-pipeline

## STEP 1: Assmeble the Data
For now, i have extracted the sample data in the sample_data directory.  Visit that directory for instructions on assembling the sample data

## STEP 2: Running the Reasoner
Run the ontology-data-pipeline using the input data file `sample_data/sample.csv` as input data

```
python ../ontology-data-pipeline/pipeline.py -v --drop_invalid  sample_data/sample.csv sample_data/output https://raw.githubusercontent.com/UA-SRC-data/srpdio/master/srpdio-full.owl config
```
