#"End_To_End_Edinburgh_Airbnb_Price_Prediction_Project"
## Run from terminal:

docker build -t airbnbpriceprediction.azurecr.io/airbnb_prediction:latest .

docker login airbnbpriceprediction.azurecr.io/airbnb_prediction:latest

docker push airbnbpriceprediction.azurecr.io/airbnb_prediction:latest
