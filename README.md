# Food-Hub App


Android application for ordering food 🍔 <br>
Download App by clicking <a href="">here</a> 

| Part of app |	Programming Language |
|-------|------|
|Front-end  |xml	|
|Back-end	|Kotlin	|
###

<br>
Only the Front-end part of app (xml files) is given in this repository. <br>
The Back-end part of this app (kotlin code) is made private. If you are interested in collabrating to this app, do <a href="https://www.linkedin.com/in/dharshan-kumar-ba09521a0/">message me in LinkedIn</a>
<br>
<hr style=\"border:0.5px solid gray\"> </hr>

## Pictures of App:
<p align="left">
  <img src="./Screenshots of App/LogIn.jpg" width="200" alt="app pic">
  <img src="./Screenshots of App/Navigation Bar.jpg" width="200" alt="app pic">
  <img src="./Screenshots of App/Dashboard (List of all Restaurants).jpg" width="200" alt="app pic">
  <img src="./Screenshots of App/Restaurants Menu.jpg" width="200" alt="app pic">
</p>
<hr style=\"border:0.5px solid gray\"> </hr>


## Link for JSON files:
I Retrieved data from these links to make this app:<br>

| Page |	JSON file Link |
|-------|------|
|Login  | http://13.235.250.119/v2/login/fetch_result/	|
|Registration	| http://13.235.250.119/v2/register/fetch_result/ |
|Forgot Password | http://13.235.250.119/v2/forgot_password/fetch_result/ |
|All Restaurants | http://13.235.250.119/v2/restaurants/fetch_result/ |
|Restaurant Menu | http://13.235.250.119/v2/restaurants/fetch_result/id/ |
|Cart | http://13.235.250.119/v2/place_order/fetch_result/ |
|Order History | http://13.235.250.119/v2/orders/fetch_result/user_id/ |
###

This Food-Hub app fetches data from these API links and displays it in each section of the app <br><br>

<hr style=\"border:0.5px solid gray\"> </hr>

## Libraries used:
This app is made using Adroid Studio SDK which is highly recommended by Google Inc. for developing native apps in android
I used few external libraries other than the libraries provided by the SDK, those are:
1. <b>ROOM persistance library</b> - For storing app data using SQL Relative database
2. <b>Volley</b> - For fetching JSON files for text data
3. <b>Picasso</b> - For fetching JSON files for Image data 
4. <b>Google Android Material</b> - For customize font styles
5. <b>Makeramen</b> - To customize images styles

