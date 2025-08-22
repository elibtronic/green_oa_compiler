# green_oa_compiler

Creates a dataset on the following criteria
- Builds ORCIDs from _current affiliation_ search of institution you name
- Retrieves (via CrossRef) corresponding DOIs published by these ORCIDs
- Looks for _Journal Articles_ only!
- Can specify start date

## Next
- Connect to PolicyFinder API to see what Green OA options exist for a particular paper

## Needed
- Will need an ORCID API key/pass ([details](https://info.orcid.org/documentation/api-tutorials/api-tutorial-read-data-on-a-record/))
- Will need a PolicyFinder API key/pass ([details](https://openpolicyfinder.jisc.ac.uk/help/developers/use-our-api))

## Notebook

This will shell a notebook that requries API keys etc to build data as CSV file.

### Dataset ORCID DOI Step
Will retrieve information from associated CrossRef and ORCID. [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/elibtronic/green_oa_compiler/blob/main/Green_OA_Compiler.ipynb)

### Dataset Policy Finder Step
Opens the CSV file generated in the first part and retrieves information from PolicyFinder API [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/elibtronic/green_oa_compiler/blob/main/Green_OA_Dataset_Policy_Finder_Data.ipynb)

### Dataset Explore
Pulls in final completed version of data in order to make sense of it. [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/elibtronic/green_oa_compiler/blob/main/Green_OA_Dataset_Analysis.ipynb)
