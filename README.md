# SWE642-hw2

# S3 links:
My Home Page: https://mysurveyhw2.s3.amazonaws.com/index.html
Survey Form: https://mysurveyhw2.s3.amazonaws.com/survey.html


# Introduction
This project enhances a University Survey Form using advanced web technologies, including JavaScript, Bootstrap, cookies, and Ajax. The primary goal was to create a more interactive and user-friendly web form that saves user data using cookies and improves the form's usability with dynamic content loading.

# Implementation Steps
# Navigation Bar
Used Bootstrap's navbar component to create a responsive navigation bar at the top of the page.
Ensured that each tab in the navbar links to different sections of the form or page for smooth navigation.
# Cookie and Greetings Implementation
Implemented cookie functionalities to store and retrieve the user's name.
Developed a greeting system that displays "Good Morning", "Good Afternoon", or "Good Evening" based on the user's local time, along with their stored name.
Provided an option for users to update their name if the current name stored in the cookie is different, which involved resetting the cookie with the new name.
# Survey Form Extension
Added additional fields to the form, including a "Data" input field for users to enter numbers.
Implemented JavaScript functions to calculate and display the average and maximum of the entered numbers dynamically.
# Form Validation
Created an event handler for the form's submit button to validate user inputs, including name, address, email format, checkbox selections, and radio button selections.
Displayed consolidated error messages using alert dialogs for any validation failures, ensuring only the fields with errors were cleared.
# Ajax and JSON for Zip Code Validation
Used Ajax to fetch a list of valid zip codes and their corresponding city and state information from a JSON file hosted on the server.
Implemented an event handler for the zip code field's onblur event to trigger the Ajax call and dynamically fill in the city and state fields based on the user's input.
