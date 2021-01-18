# stepscrape
Tool to Scrape Data from Stepstone
## Getting started / Prerequisites
1. Install Python (3.9 recommended)
2. Install pipenv (```pip install pipenv```)
3. Switch into project directory
4. run `pipenv install` and wait!
5. run `pipenv shell`
6. run `jupyter lab`
7. In "Jupyter lab" select "Stepscrape.ipynb"

## To get list of links to Job-Offers:
1. Un-Comment Cell [...]
2. Restart Kernel and run all cells

## To get a selection of Job-Offers from list:
1. Comment Cell [...]
2. Un-Comment-Cell[...]
3. Restart Kernel and run all cells


##To change parameters (EG Search-Query)
1. Switch entry      "Requirements Engineer" to desired value
    urls = [build_stepstone_search_query("Requirements Engineer", i) for i in range(10)]