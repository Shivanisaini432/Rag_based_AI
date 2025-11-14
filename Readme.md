# How to use this RAG AI Teaching assistant on your own data
## Step 1 - Collect your videos
Move all your videos files to the videos folder

## step 2 - Convert to mp3
Convert all the videos files to mp3 by running video_to_mp3

## Step 3 - Convert mp3 to json
Convert all the mp3 files to json by running mp3_to_json

## Step 4- Convert the json files to Vectors
Use the file preprocessing_json to convert the files to a dataframe with Embedings and save it as a joblib pickle

## Step 5 - Prompt generations and fedding to LLM
Read the joblib file and load it into the memmory. Then create a relavent prompt as per the user query and feed it to the LLM

