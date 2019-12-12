# Disaster Response Pipeline Project

### Instructions:
1. Run the following commands in the project's root directory to set up your database and model.

    - To run ETL pipeline that cleans data and stores in database
        `python data/process_data.py data/disaster_messages.csv data/disaster_categories.csv data/DisasterResponse.db`
    - To run ML pipeline that trains classifier and saves
        `python models/train_classifier.py data/DisasterResponse.db models/classifier.pkl`
2. Copy classifier.pkl to workspace folder

3. Run the following command in the app's directory to run your web app.
    `python run.py`

4. Go to https://view6914b2f4-3001.udacity-student-workspaces.com

The page includes 2 visualizations which gives an overview of the training set


You can analyze a new message in the 'Enter message' section

Unable to upload the model file, please use the above instructions to generate one
