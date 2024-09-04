# Car Price Prediction

This project implements a car price prediction model using Linear Regression Model. The goal is to predict the price of a car based on various features such as the car’s brand, year of manufacture, kilometers driven, fuel type, seller type, transmission, owner type, mileage, engine capacity, max power, and the number of seats.
LINKEDIN POST(https://www.linkedin.com/feed/update/urn:li:activity:7237243646754865152/)

![Car price prediction](https://github.com/user-attachments/assets/3e703780-2bc3-4acd-a39f-685b55e026e6)
![Car price prediction1](https://github.com/user-attachments/assets/c955e57e-eaa8-4c42-81b1-21deaa879b4c)


## Key Features
**Interactive Web Interface**: Developed using Streamlit, this interface lets users easily input car details such as brand, year of manufacture, mileage, and more.

**Linear Regression Model**: The core of the application, this model predicts car prices based on input features. It is trained using historical data and is serialized with pickle for easy reuse.

**Data Processing**: Includes data cleaning and preprocessing steps to ensure high-quality inputs and accurate predictions.

## Technologies Used

Python: The primary programming language used.

Pandas: For data manipulation and analysis.

NumPy: For numerical operations.

Scikit-learn: For building and training the Linear Regression model.


Pickle: For saving and loading the trained model.

Streamlit: For creating the user-friendly web interface.

CSV: For data input and output operations.

## Getting Started ##

Install Dependencies

1.Ensure you have Python/VS code installed and then install the necessary packages:



pip install pandas numpy scikit-learn pickle streamlit

2.Prepare Data

Ensure you have the dataset Cardetails.csv containing car details.

3.Run the Application

Start the Streamlit application in installed IDE run app.py the main script there and then in terminal run:

-streamlit run app.py

This will launch a web server, and you can access the application through the URL provided by Streamlit in your browser.


Contributions to improve the model or enhance the application are welcome. Feel free to contribute to this project by submitting pull requests or reporting issues. For major changes, please open an issue first to discuss what you would like to change.

































