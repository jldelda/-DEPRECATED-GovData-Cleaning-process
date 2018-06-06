```
This Repo has been calified as Deprecated because some large files (larger than 100 MB) have been commited in local. When I tried to push them, github does not allow to push so big files into the system. 

The package BFG do not work for Windows, so I had to copy manually all updated files (expect the biog ones) in a new repository.
```
See here the new GovData-Cleaning-process repository.

# [DEPRECATED] GovData-Cleaning

This reporistory contains the files for the cleaning process GovData360 ingestion process. In the Spring 2018 ingestion process, 19 of the 38 data sources are updated. This process consist of:
1. Downloading all the files from the sources to update. (Done manually)
2. Transform the excel to the same format*. (Done with the Stata files)
3. Clean each file and make sure all of them have the right variables. (To do)
3. Join all the files in the same big 'master file'. (To do)
  3.1. These files are **MasterIND.csv** with the list of indicators and its metadata; and **Master.csv** with the values, years and countries.
4. *Get the metadata from previous ingestion file* (To do)
5. Append the no-updated data sources after the updated ones for both files (To do)

*Note: The step 4 is done and explained in the xxx document*


## Libraries used
