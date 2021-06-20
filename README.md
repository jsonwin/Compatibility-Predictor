# Compatibility-Predictor
Datahouse is looking to add new members to its team. The task is to build an application that takes an input: an array of applicants and an array of team
members, and produces an output: an array of applicants with their respective compatibility
score. Input and Output must be in JSON andCompatibility score for each applicant should fall in a range from [0, 1]

Built With
Visual Studio 2017
JS
Jquery Plugin
Bootstrap

Authors
Jason Nguyen

License
This project is licensed under the MIT License - see the LICENSE.md file for details

Method: 
1. Create a Html form with Inputs (Select, Button, Submit, Delete) to collect attributes from Applicants and Team.
2. Data collected from form are push to two Arrays.
3. Loop through the Array the using parseInt to collect the scores for four different attributes.
4. Let say that there are 4 different attributes, and the highest scores possible for each category is 10. 
5. Scores from all four categories are added together and divided by the possible highest point of 40.
6. Applicant scores will range from 0.1 to 1 
7. Applicants whose has the scores closest to 1 will have the highst compatibility. 

The $(document).ready() method allows us to execute a function when the document is fully loaded. 
Jquery Selector used to select elements by Id (  $("#addApplicantBtn").on("click", calculateScore);
Callback function
clearForm
Clears the form elements. This method emptys all of the text inputs, password inputs and textarea elements, clears the selection in any select elements, and unchecks all radio and checkbox inputs. It does not clear hidden field values.





