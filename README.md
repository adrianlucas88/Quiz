# Quiz


A multiple choice Quiz built using HTML and Vanilla JavaScript with different categories and a total score at the end of each quiz.
This app is my second project in JavaScript and I have created the architecture and design without any online influence, being more a challenge to myself in order to see how I will handle a project from start to end. I am planning to add a chat and more categories in the near future.


The code contains functions that control the flow of the quiz, change the questions and answers based on user input, and calculate the score.

The code first selects the necessary HTML elements using their IDs and creates variables to store them. There is a function called closeProjects() that reloads the page and hides the quiz window.

The quiz() function is the main function that controls the whole app when triggered. When this function is called, it displays the quiz window and hides the project container. It sets the initial values for the quiz questions and answers, sets the user points to zero, and calls the showAnswers() function to display the quiz categories.

The showAnswers() function fills the quiz answers with the categories and sets click functionality to each button. It also checks the current question and adds new click functionality to each button and triggers the next function based on the current question.

The pickAnswer() function checks the value of the clicked button and fills the question and answers accordingly. If the clicked button is the correct answer, it adds points to the user's score.

The goQuest2() and goQuest3() functions fill the question and answers with the second and third property of the selected object, respectively.

Finally, there is a variable to store the clicked button and another variable to store the user's score. There is also an array that holds the quiz categories.
