# ocr_detection

For this project , I am trying to detect words from an image file and will store it to datbase .

This can be used when we have lots of documents to scan and want to get output of document in web application

How I solved this problem? 

 1) Importing all the necessary libraries required 
 2) importing image (which is scanned form) and 
opencv library  is used to import image and preprocess it.
Our form look like below which we want to process 



 3) Tessaract is used for ocr(optical charected detection
 4)After detecting charecters , we want to  remove all unnecessary raw and only need field which we want to insert into databease. Python's regular function help us to achive this goal.
 
 5) After processing text , our data look like below 
 
Given Name: IRONMAN
FamiyName: [Stark
Address 1: Malibu point House nr: 1 0880
Address 2: Santa bay
Postcode: City:| california
Country: United states a
Gender: Man [=]
Height (cm): 150
Driving License: oO

6) we can use dictionary or pandas dataframe to convert data into tabular format which we want ultimately
Our final data in tabular form look like below 

![Screenshot 2019-10-07 at 10 50 22 AM](https://user-images.githubusercontent.com/33773505/66286747-683af480-e8f0-11e9-95ab-d61193a0c67c.png)
