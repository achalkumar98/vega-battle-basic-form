# vega-battle-basic-form
VegaBattel Form

Description:
This is an HTML form for collecting user information, specifically designed for VegaBattel. The form includes fields for:

Name
College Name
Current Year
Year of Passing Out
Profile Picture (image upload)
Favourite Language (select from a list of options)
Form Structure
The form is wrapped in a <form> element with the following attributes:

action: set to /submit-form, indicating the URL to submit the form data to
method: set to post, specifying the HTTP method to use for form submission
enctype: set to multipart/form-data, allowing for file uploads (in this case, the profile picture)
Form Fields
Text Fields
Name: a required text input field for the user's name
College Name: a required text input field for the user's college name
Current Year: a required number input field for the user's current year, with a minimum value of 1 and a maximum value of 6
Year of Passing Out: a required number input field for the user's year of passing out, with a minimum value of 1900 and a maximum value of 2100
File Upload Field
Profile Picture: a required file input field for uploading a profile picture, accepting only image files
Select Field
Favourite Language: a required select field for choosing a favourite programming language from a list of options
Submit Button
A submit button with the value "Submit" to submit the form data
Stylesheet
The form uses an external stylesheet, linked via the <link> element in the <head> section of the HTML document. The stylesheet is located in a file named style.css.

Note
This README file provides a brief overview of the HTML form structure and fields. For further information or customization, please refer to the HTML code itself or the accompanying stylesheet.
