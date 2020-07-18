# final-code-quize
The application has a few multiple choice questions and the ability to store top scores on the user's device. The number of questions decides the length of time for the quiz (15 seconds/question) once the user clicks "Start", but they are penalized 10 seconds if they answer a question incorrectly. The final score is based on the amount remaining on the timer. This entire activity was very difficult. I really don't understand what I'm doing with the DOM and Local storage and it took forever just to figure out how to get my timer working. I didn't understand how to display the questions individually or if I needed to use JSON methods so I couldn't move forward for the longest time. I do so many search in google and class activities so many times and was still confused.

Once the final question is answered, the user's final score is shown, and a prompt is given for the user to enter their initials. When the "Submit" button is clicked, the initials and score are saved to local storage, so even after the browser is refreshed the score will be saved. The list of saved scores can be seen by clicking the "View High Scores" button.

An interesting challenge in creating this app was creating the html for the quiz questions dynamically using javascript, rather than creating them in the html document and modifying them in javascript. This was also done for generating the list of high scores. This provided good practice in navigating the DOM in javascript, along with the use of "this" when creating a button and defining its on-click behavior to check its own text and compare to the correct answer. Additionally, this app uses a recursive function to generate the quiz questions - the "generateQuestion" creates the buttons for the current question, and defines the on-click behavior of those buttons, which include changing the current question and executing "generateQuestion" again.











*https://metasabeya.github.io/final-code-quize/.