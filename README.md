![pexels-pixabay-38537](https://user-images.githubusercontent.com/85582924/202362268-cbc01875-aa6f-4536-ad35-bb3a886492e7.jpg)

# Weather Classification & Prediction

Weather classification and prediction affects many aspects of our daily lives, for example, weather forecast, road condition monitoring, transportation, agriculture, forestry management, and the detection of the natural environment. In contrast, few studies aim to classify actual weather phenomenon images, usually relying on visual observations from humans.

In this project we aim to identify and predict weather conditions from images as well as daily summaries data of weather using Convolutional Neural Networks (CNN) and Recurrent Neural Network (RNN) Tensorflow - Keras.

# The Data

The data that's used in this project was obtained from NOAA Climate Data https://www.ncdc.noaa.gov/cdo-web and Mendeley Data https://data.mendeley.com/datasets/4drtyfjtfy/1. NOAA data consist of the daily summaries data from Jan / 2010 - Oct / 2022. The Mendeley data is an image data consist of 1128 images of weather types and how the day looks like. The images are divided into four Rain, Cloudy, Shine, and Sunrise images. The following are some of the few images that we used to classify our weather.

<img width="950" alt="Screenshot 2022-11-16 at 09 35 46" src="https://user-images.githubusercontent.com/85582924/202359794-c7cfb970-1df3-42c7-994d-ce463e573433.png">

# Exploritory Data Analysis

Image Classification Data Distribution: 

<img width="636" alt="Screenshot 2022-11-16 at 00 43 45" src="https://user-images.githubusercontent.com/85582924/202360143-ce6d74bd-8d87-47f7-9fb8-024dd2492b38.png">

Daily Summaries Data Distribution

<img width="992" alt="Screenshot 2022-11-16 at 00 36 03" src="https://user-images.githubusercontent.com/85582924/202360284-99fdcb03-1e0d-4d2c-ac72-17c0740464a2.png">

Average Temperature Time-Series

<img width="952" alt="Screenshot 2022-11-16 at 09 52 05" src="https://user-images.githubusercontent.com/85582924/202360447-5b519cf6-472b-4ca0-bfb4-7b5fb1560401.png">


# Model Prediction

Temperautre Prediction (RNN - LSTM)

<img width="956" alt="Screenshot 2022-11-16 at 10 05 04" src="https://user-images.githubusercontent.com/85582924/202360831-c1607bef-32bc-4969-90ef-1e6c3847096d.png">

Image Classification Prediction

<img width="550" alt="Screenshot 2022-11-16 at 10 12 26" src="https://user-images.githubusercontent.com/85582924/202361872-379239b6-f512-4423-a51f-8343db8e3bdd.png">


<img width="529" alt="Screenshot 2022-11-16 at 10 28 21" src="https://user-images.githubusercontent.com/85582924/202361105-d6937080-408d-4b5b-936e-38e32a240f0b.png">
<img width="530" alt="Screenshot 2022-11-16 at 10 30 17" src="https://user-images.githubusercontent.com/85582924/202361142-1c81dc94-9b40-459a-a447-88bab795f35e.png">
<img width="518" alt="Screenshot 2022-11-16 at 23 08 05" src="https://user-images.githubusercontent.com/85582924/202361312-280b80a4-6c89-4230-b104-c09da1d58ebb.png">

<img width="521" alt="Screenshot 2022-11-16 at 23 08 31" src="https://user-images.githubusercontent.com/85582924/202361331-ffd4e670-4205-4e06-960b-a1418a5c82fa.png">


# Conclusion

Our weather prediction model was trained and tested to predict the temperature accuracy 90% of the time. And from this we were able to detect pattern over a period of time. And as showing above it has picked up the annual trend of increasing temperature around summer time and decreasing temperature around winter.

And for the image classfication (RNN) model we can successfully say that our model can accurately predict or identify the weather type out of those images 93% of the time as showing in our graph. And as we can see in those images our model predicted Cloudy, Rain, Shine, and Sunrise weather type accurately.
