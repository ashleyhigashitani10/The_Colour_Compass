# The_Colour_Compass
BABI4005 assignment 4: Unstructured data

This script pulls travel photos from popular destinations from the Unsplash API and extracts dominant colour palettes. It then applies clustering, feature engineering, and similarity analysis to determine possible travel destination aesthetics. This project was made to transform unstructured data (in this case, images) with the help of an AI coding tool.

I created this project to help me determine what colour palette of clothes/outfits I should bring to future vacation destinations. I wanted to combine some things that I enjoy (fashion and travel!) to code.

## Citations
ChatGPT 5.2 was used as the AI coding assistant: https://chatgpt.com/
All photos used were taken from the Unsplash API: https://api.unsplash.com/search/photos
For Photographer info, please refer to the metadata_backup.csv in data/ 

## In scripts/
the_colour_compass.ipynb

This script includes:

Collecting travel photography metadata via Unsplash API
4 Countries were explored; Greece, Japan, Thailand & Italy
Freeze the dataset (for reproductivity)
Download then normalize images
Extract dominant colours to create a palette (KMeans)
Explore features (brightness & warmth)
Compare destination palettes
Create a "guidebook" of what colours to pack on vacation!

## In data/
metadata_backup.csv
colours_backup.csv

This script can be ran with a different set of images, but for this project in specific I froze the metadata, colour data for the specific destinations I analyzed in this project.

## AI Disclosure

This project was done with support of an AI coding tool (ChatGPT 5.2, plus). AI supported decision-making, code interpretation, debugging, implementation and any clarification. 
The overall project concept, aesthetic modeling framework, feature engineering decisions (brightness and warmth), clustering, and recommendation logic were developed and refined through independent experimentation and analysis.
Evaluation and interpretation of outputs were completed independently.

