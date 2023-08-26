
# Stock Market Visualisation Using Dash 

You will be creating a single-page web application using Dash (a python framework) and
some machine learning models which will show company information (logo, registered
name and description) and stock plots based on the stock code given by the user. Also the
ML model will enable the user to get predicted stock prices for the date inputted by the
user.


## Requirements

![App Screenshot](https://raw.githubusercontent.com/Kalyanspunk/Stock-Market-Visualisation-Using-Dash-with-Flask-app/main/screenshots/requirements.png)

You may follow the convention mentioned below -

• app.py contains web layout and server function. We will be referring to it as our main file.

• model.py is where we will implement a machine learning model for forecasting
the stock price.

• The assets folder is where we keep our CSS files for styling and any other
miscellaneous files like images (if u wish to include it in your site)

• requirements.txt is created so that other developers can install the correct
versions of the required Python packages to run your Python code.

• The Procfile is created for deployment using Heroku. It is not needed to run
the app locally.


## Usage
To run the application, navigate to the project directory and run the following command:
```javascript
python app.py

```
This will start the Flask server and make the application accessible at 'http://127.0.0.1:8050/'.

click the "Predict" button to see the predicted stock prices graph  for the given next future days.
