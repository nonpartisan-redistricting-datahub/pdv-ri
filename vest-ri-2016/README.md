# vest-il-2018

Our final election results validation report for this dataset is available [here](https://redistrictingdatahub.org/dataset/vest-2016-rhode-island-precinct-and-election-results/).

We do not have the raw data sources available on this Github due to file constraints, but we are happy to share them if needed. 

Please reach out to info@redistrictingdatahub.org to reach our support team if you have any questions, or if you would like to request a full validation report. 

## Raw from source

### Accessible files:

- File: VEST RI 2016 file
   - Date accessed: 7/22/2021
   - Link: https://dataverse.harvard.edu/file.xhtml?fileId=4789391&version=64.0
   - File: `ri_2016.zip`
- File: VEST documentation file, 2016
   - Date accessed: 7/22/2021
   - Link: https://dataverse.harvard.edu/file.xhtml?fileId=4931775&version=63.0
   - File: `documentation.txt`
- Election results from Rhode Island Board of Elections
    - Date accessed: 7/22/2021
    - Link: https://www.ri.gov/election/results/2016/general_election/data/
    - Note: The Long Format file was used for validation
- File: Data description file for Long Format
    - Date accessed: 7/22/2021
    - Link: https://www.ri.gov/election/results/2016/general_election/data/
    - Note: Data description pdf file is not necessary to run the notebook, but useful for disambiguation

## File processing:

`vest-ri-2016-validation.ipynb` is the script that is the basis of the validation report
