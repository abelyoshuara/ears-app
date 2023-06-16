# Machine Learning Path Repository 
This repository is designed for efficient Data Preprocessing and model creation for EARS (Emergency Assistance and Routing System). Our approach involves utilizing an android-based application built on the Google Maps API and employing content-based filtering techniques to determine the nearest path and recommend hospitals to the user. To ensure seamless integration, we plan to convert the model into tflite (TensorFlow Lite) format at the final stage. This enables the model to be deployed efficiently on resource-constrained devices while maintaining its functionality and accuracy.
# Work Flow 
1. Data Collecting 
2. Gmaps API Processing
3. Creating Model of Recommendation Hospital 
4. Convert to TF-Lite
5. Deploy to Android 
# Data Collecting 
We gather our data from :
1. Hospital Address
   Collect name of hospital in Surabaya 
3. Ordinate Point Hospital
   Use Latitude - Longtitude of Hospital and Distance from City Center
5. Hospital Capacity
   Cost of Service Price, Number of Hospitalization Room Services.
7. Ratings 
   Diseases that can be succesfully treated and user facility ratings 
# Creating Model 
We tried some hyperparameters in creating the model. These are some of the result.
__________100 Epoch Attempt
<div align="center" style="display:flex;">
<img style="width:45%" src="./../assets/loss.png">
<img style="width:45%" src="./../assets/accuracy.png">
<img style="width:45%" src="./../assets/mse.png">

</div>
