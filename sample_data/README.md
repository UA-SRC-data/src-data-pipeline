Our sample directory contains sample data for the UA-SRC project
with theh sample.csv containing the first 10 lines of the following files
from the data_loaders repository:

```
./waterquality/scrutinizer.csv
./usgs/scrutinizer.csv
```

NOTES:
  * There are other directories with files which contain data but are either incomplete
or i had questions about how to incorporate those datasets. for now, just using the above directories.
  * I added a column/attribute called directory which corresponds to the directory from the
data_loaders repository
  * The column `variable_desc` i manually fixed to use ontology terms.. We need a lookup file
created in data_loaders to map these.
