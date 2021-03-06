# Disease-identification-in-tomato-plant-Django

<h2> <b> Abstract: </b> </h2>

Agriculture is the backbone of economy of Indian government. There is a requirement of a lot of production of crops to fulfill the need of Indian population. Because of
diseases, large amount of crop production is decreased. There are various types of diseases on the plant leaf that causes problem in development of crops. Human eyes are not so much stronger to see the leaf diseases so humans do not observe variation in the infected part of leaf. These diseases sometimes may not be visible to human eyes and they directly affecting to the crop. 
<br></br>
For this a farmer takes the image of a leaf and uploads it in a website that we have developed. Now the patterns of the uploaded image are compared with patterns available in dataset, which is almost accurate, resulting in identification of the plant disease. At starting stage, the disease can be easily identified.

<h2><b> Requirements: </b></h2>

* Python  

* Tensorflow

* Keras

* Django 

* PIL 

* Numpy 

<h2><B> Steps to run the Application: </b></h2>
<h4> <b> This application requires Python 3.6 </b> </h4>

1. Download the repository by clicking on the download button or type the following command in CMD to clone the repository:

       git clone https://github.com/AkhilaMadduri/PlantDiseaseDjango.git

2. Download model from the following link and paste it in the `\plant_diseases\plant_app` folder: 

       https://drive.google.com/file/d/1IJ_9kHXTRpW744ymq1V5L0pkv1TMJdwh/view?usp=sharing

3. (Optional) Create a virtual enviourment. Refer this tutorial to learn how to create a virtual enviourment: https://www.youtube.com/watch?v=APOPm01BVrk  If you create a           virtual enviourment, make sure it is activated and you execute all commands from within the virtual enviournment. Skip this step if you are unsure about how it works.
  
4. Install required packages:

       pip install -r req.txt

5. Navigate to `\plant_diseases` directory and run the application with the following command:

       py manage.py runserver

6. A link will appear in your command prompt. Copy this link and paste it in your browser, press enter.

7. Your application is running. Choose any infected image to get results.

<h2><b> Screenshots </b></h2>


![](screenshots/home.PNG "Home Page")


![](screenshots/choose_img.png "Choose Image")


![](screenshots/Output_img.PNG "Output of running manage.py")



       
       


