# Real Estate Price Estmation for Torontro, Canada
***
## Task of the Project
The task of the project: to estimate the key factors effects on real estate prices in Toronto (Canada)
***
## Files description
* `toronto_real_estate_dataset.zip` - archive with a final dataset for analysis
* `Web_Scraping_tranio.ipynb` - scraper for data from [www.tranio.com](https://tranio.com/canada/)
* `part_1_toronto_real_estate.ipynb` - preprocessing of row scrapped data
* `part_1_toronto_real_estate.ipynb`- data analysis and models building
* `Presentation.pdf` - presentation of the Project and main results
***
## Data Collection
1) Data was collected from https://tranio.com/canada/ which contains information about real estate prices in Toronto
2) We used modules `requests`, `json`, `BeautifulSoup` in Python
3) We collected data in a loop for unique flat's id from site
4) We created DataFrame in a same loop automatically (it contains all available information about ad)
5) Parse details in a file `Web_Scarping_tranio.ipynb`
***
## Data Preprocessing
* Data was collected 2020-12-02
* We split words in description and create dummies for unique words if description contains this word
* Examples of unique words: Garage, Schools, Luxary, etc.
* There are 7501 observations and 74 features of real estate in Toronto in a final dataset `toronto_real_estate_dataset.zip`
***
## Authors
* **Anastasia Tsepyuk**  - [NasTsepyuk](https://github.com/NasTsepyuk)
* **Anna Anikina**  - [anyaanikina98](https://github.com/anyaanikina98)
