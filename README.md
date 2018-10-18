# CRISP-DM_on_Airbnb_Berlin

1. Installation
	- Anaconda  Navigator 1.8.7
	- Python 3.6
	- Packages: pandas, numpy, scikitlearn, matplotlib, seaborn, nltk
	
2. Project motivation

Due to decreasing living space in German major cities, following questions came into my mind as I got to know that Airbnb listings are available. So these are the questions I focused on:
- How many apartments/private rooms are there in each neighborhood and what is the average price?
- How many of them belong to hosts who do not live in Berlin?
- What are the most important features/amenities? Can they be summarized?
- Managing to buy an apartment/condominium, is there a chance to predict future listing price with given amenities, property type, .. from listing file?

3. File description

Following files are included in this repository:
- Airbnb Berlin.jpynb: Jupyter Notebook file containing 
- DataScienceHelperLibrary.py: My collection of functions for encoding/analyzing/working with dataframes incl. detailed logging

4. Interaction

Before interacting with this notebook, you need to download and extract from http://insideairbnb.com/get-the-data.html following Berlin relatet files:
- listings.csv.gz
- neighborhood.csv.gz

As mentioned above, I am creating a library that falilitates working with dataframes.
For example searching column names by wildcard is supported, extracting unique values out of columns with the ability to define a configuration value cleaning and preparation.
Feel free do modity parameters. 

5. Licensing

There is no licence. Don't hesitate to use my library. It is straight forward to use and if you use it, please give me feedback.


