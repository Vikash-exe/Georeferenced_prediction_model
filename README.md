# Georeferenced_prediction_model
It reads the tiff metadata and stores in array before classification, then reassigns the metadata to the tiff file later for a georeferenced prediction image. This code takes the whole folder and saves the output to desired directory in the drive.
The model uses weights from training over 50epochs, and the dataset consist of FCC and Mask from 2012, 2014 and 2018 of bangalore urban area. 

Here the code v2_6_model_sent_data_2025.py takes any resolution data (Sentinal 2 data here) as input, stretches its histogram to match LISS4 data's histogram. Then again it preprocesses the data same as before i.e. during training and then the model predicst the classes as per weight.
