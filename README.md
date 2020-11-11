# [Global Terrorism Dashboard](https://terrorismglobal.herokuapp.com/)

This repository contains files for this Dashboard.
This app is made with [Dash](https://plotly.com/dash/) interactive python framework developed by [Plotly](https://plotly.com/).
Dash is a simple and effective to bind user interface around python code.
## Overview -
  * The Project is a [Dashboard](https://terrorismglobal.herokuapp.com/) built for getting proper data insight through interactive visualization.
  * This is built around the [Global Terrorism Database](https://www.kaggle.com/START-UMD/gtd) (GTD) and more about the [data](https://www.start.umd.edu/gtd/), it's collection methodology, definitions, and coding schema can be found [here](https://start.umd.edu/gtd/downloads/Codebook.pdf).
  * The Project includes Terrorism activities around the world reported between [1970-2017] with more than 180,000 incidents.
  * This Project is more of the extension of the [Jupyter notebook](https://github.com/matsujju/Global-Terrorism-EDA) where more exploratory data analysis is done and can be looked if interested.

- Important highlights :
  * Geography: Worldwide
  * Time period: 1970-2017, except 1993
  * Unit of analysis: Attacks and Casualities
  * Variables: >100 variables on location, tactics, perpetrators, targets, and outcomes but used around <ins>30 parameters as most of them has more than *80% missing values*</ins>.
  * Sources: Unclassified media articles (<ins>Note: Please interpret changes over time with caution. Global patterns are driven by diverse trends in particular regions, and data collection is influenced by fluctuations in access to media coverage over both time and place.</ins>)
  * Definition of terrorism:
      "The threatened or actual use of illegal force and violence by a non-state actor to attain a political, economic, religious, or social goal through fear, coercion, or intimidation."
      
## Getting Started -
### Running the app locally
First create a virtual environment with conda or venv inside a temp folder, then activate it.
```
virtualenv venv

# Windows
venv\Scripts\activate
# Or Linux
source venv/bin/activate

```
Clone the git repo, then install the requirements with pip
```
git clone https://github.com/matsujju/Global-Terrorism-Dashboard.git
cd Desktop/temp_folder/Global-Terrorism-Dashboard/        (Here temp_folder is in Desktop...choose your own path if different)
pip install -r requirements.txt
```
Run the app (from your terminal)
```
python dash_app.py
```
Open a browser at http://127.0.0.1:8050

## About the app -
This Dashboard displays the terror attacks with respect to each country. It allows user to explore and compare terrorist activities and their details by selecting on the dropdown menu and sliding across the years. 

## Built with -
  * [Dash](https://dash.plotly.com/) - Main server and interactive components
  * [Plotly Python](https://plotly.com/python/) - Used to create the interactive plots
  * [Pandas](https://pandas.pydata.org/) - Exploring and Manipulating the data
  
## Screenshots -
Followings are the screenshots of the app in this repo:

![Image](https://github.com/matsujju/Global-Terrorism-Dashboard/blob/main/screenshots/screenshot_full.gif)

![Image](https://github.com/matsujju/Global-Terrorism-Dashboard/blob/main/screenshots/screenshot1.png)

![Image](https://github.com/matsujju/Global-Terrorism-Dashboard/blob/main/screenshots/screenshot2.png)

![Image](https://github.com/matsujju/Global-Terrorism-Dashboard/blob/main/screenshots/screenshot3.png)

## Credits -
  * Looking for more visualized dash apps? See [here](https://dash-gallery.plotly.host/Portal/)
  * [Dash Documentation](https://dash.plotly.com/introduction)
  * [Plotly Python Documentation](https://plotly.com/python/)
  * [Video tutorials](https://www.youtube.com/channel/UCqBFsuAz41sqWcFjZkqmJqQ)
  * [Awesome Community](https://community.plotly.com/) for helping
