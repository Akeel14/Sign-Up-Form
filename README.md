# Sign-Up-Form
This repository contains an HTML form for users to sign up for your web application. The form includes fields for the user's first and last name, email, age, education level, and password. When the user submits the form, their data is sent to the specified action URL (**`https://httpbin.org/post`** ) and rendered in a **JSON format**.

<img width="1383" alt="Screen Shot 2022-12-09 at 12 15 35 AM" src="https://user-images.githubusercontent.com/58542001/206635575-9c00452c-5201-446c-bd70-a81244f68197.png">

## Features
Validates user input using HTML input validation attributes, such as required, min, and max
Uses the pattern attribute to ensure that the user's first and last name are in the correct format (e.g., starting with a capital letter followed by one or more lowercase letters and spaces, with a lowercase letter at the end)
Includes hidden fields to store additional user information that is not visible in the form
Submits user data to the specified action URL and renders it in **JSON format**.

## Usage
To use the sign-up form, simply clone this repository and open the **index.html** file in a web browser. The form should display in the browser, and you can fill it out and submit it to the specified action URL. The data you enter will be sent to the **`https://httpbin.org/post`** URL and rendered in **JSON format**. You can customize the form and its validation rules by modifying the HTML code in the **index.html** file.

## Dependencies
This repository has no external dependencies, so it should run on any system with a web browser.


