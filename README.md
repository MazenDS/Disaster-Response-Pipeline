# Disaster-Response-Pipeline project


# Description
The project use data engineering skills to classifiy the disaster messages.The date used from figure eight which contained pre labelled messages from real time disasters. 
The project has 3 component. 
1. Data Processing, ETL Pipeline to extract data from source, clean data and save them in a proper databse structure
2. Machine Learning Pipeline to train a model able to classify text message in categories
3. Web App to show model results in real time


# get this repo:
https://github.com/MazenDS/Disaster-Response-Pipeline.git

# run this program: 
  1. to run this ETL :
   python data/process_data.py data/disaster_messages.csv data/disaster_categories.csv data/DisasterResponse.db
  2. to run the ML:
   python models/train_classifier.py data/DisasterResponse.db models/classifier.pkl
  
  3. Run the following command in the app's directory to run your web app:
   python run.py
   
   # link to the app.
   https://view6914b2f4-3001.udacity-student-workspaces.com
   
   # screenshot
the below screenshot on the web runs to classify the messages and retun the categories. 

![Capture52](https://user-images.githubusercontent.com/55158582/71307738-c8c3d300-2403-11ea-8bc7-b5e42db597bc.PNG)
![Capture53](https://user-images.githubusercontent.com/55158582/71308070-abddce80-2408-11ea-9234-0b66acfc8afa.PNG)
![Capture54](https://user-images.githubusercontent.com/55158582/71308084-e47da800-2408-11ea-94e7-c2d1bd6dabc6.PNG)   
   


