# ASR_Notebook.

The Objective here is to develop a machine learning ASR model capable of accurately recognizing spoken words in Swahili.


# Dataset.

I have 4 files.

- test.csv - This is the dataset that will be used for model testing.

- train.csv  - Train contains the target. This is the dataset that that will be used to train the model.

- test_audios.zip - Test audios that will be used to test the model.

- train_audios.zip - Train the audios that will be used to train the model.

### Step 1:
To start with the problem , I look on data. CSV files and Audio Data. I converted mp3 audio data to wav file format. I thought this being compactible and best format with Machine Learning Algorithm for this. 

### Step 2:
After uploading csv files we convert them into intergers , then encoding and decoding functions were defined , data were splitted into training and validation.

### Step 3:
This step we define CTC Loss function , model function after that decoding of test data were defined.

### Step 4:

Model training and after that we check the result using our validation data.

# Progress

With the notebook given here in the table, I have built the pipeline. But when I finally trained the model, I got no predictions.


![Screenshot 2023-08-15 010234](https://github.com/MGASALUCAS/ASR_Notebook./assets/88959075/8240498e-7fbb-468a-9d9b-27ebf5debc9e)