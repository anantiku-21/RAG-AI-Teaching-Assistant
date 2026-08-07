# RAG-AI-Teaching-Assistant
# How to use this Rag AI Teaching Assistant on your own data

## STEP-1 Collect your Own videos
Move all your video files to one dedicated folder

## STEP-2 Convert Videos to mp3
Convert all the videos to mp3 by running video_to_mp3

## STEP-3 Convert mp3 to json
Convert all the mp3 files to json by running mp3_to_json

## STEP-4 Convert the json to Vectors
Use the files PreProcess_json to convert the json files to a DataFrame with Embeddings and save it as a Joblib Pickle 

## STEP-5 Prompt Generation and feeding to LLM
Read the Joblib file and load it into the memory, then create a relevent prompt as per the user query and feed it to the LLM
