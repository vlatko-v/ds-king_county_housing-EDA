# King County Housing: Exploratory Data Analysis

The goal of this project was to analyse the King County housing market based on a dataset containing various characteristics of over 20,000 housing units and make recommendations for a fictitious client looking to buy a house in the area.

--- 

## Project overview

* Examined client characteristics and formed testable hyptoheses
* Selected existing and created new relevant features to be analysed
* Testing hypotheses via correlations
* Visualisations: Geographical, scatterplots and boxplots (correlations)
* Insights and recommendations for the client
</br>

## Client characteristics

* Wants a waterfront
* Has limited budget
* Wants a nice and isolated but central neighborhood without many children
</br>

## Variables in the dataset

* Date
* Price
* House_id'
* Number of bedrooms
* Number of bathrooms
* Sq. footage of living space
* Sq. footage of the lot
* Number of floors
* Located at a waterfront
* Has been viewed
* Overall Condition
* Grade based on King County grading system
* Sq. footage of house apart from basement
* Sq. footage of the basement
* Year built
* Year renovated
* Zipcode
* Latitutde and longitude
* Sq. footage of interior housing living space for the nearest 15 neighbors
* Sq. footage of the land lots of the nearest 15 neighbors

Only a subset of the variables was used in the analysis, since the client had specific requirements about the house and the neighbourhood.

</br>

## Data cleaning

After deciding on the variables based on the client's needs, I took a look at the data at hand and made the following changes: 

* Created a new column **price/sq. foot** to normalize house price against house size
* Rounded up and down the number of bathrooms, since many housed contained decimal numbers
* Created a new column **bedrooms/bathroom**
* Classified zipcodes into *Urban Outskirts*, *Urban Center* and *Suburbs*
* Classified the price/sq. foot into 5 quantiles to create new price categories
* 


## Repository content
* **Presentation:** Project insights and recommendations (PDF and PPT)
* **Visualisations:** Contains graphs and visualisations
* King County Housing dataset
* Description of features/columns (markdown)
* Fetching data from a database using psycopg2 (python notebook)
* King County Housing EDA (python notebook)

</br>

## Resources used
* **Python version:** pyenv with python 3.11.3
* **Packages**: pandas, numpy, matplotlib, seaborn


</br>
