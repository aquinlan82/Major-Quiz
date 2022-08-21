# What Major Should I Be Quiz

**What does it do?**
Many incoming college students are unsure what they want to study, which creates unhelpful pressure to decide on something "before its too late". The New Student Registration Office tasked me with creating a quiz that uses current student survey responses to aid new students in making that decision. Since there are already plenty of quizzes that do this by asking leading questions and a simple scoring system, I also wanted to take a new approach that would hopefully perform better than a Buzzfeed quiz.

**How does it work?**
The notebook contains my conclusions about the data. During exploration, I created a correlation matrix and some graphs to more easily visualize what I was working with. I was excited to find that there was a descent correlation between a few of the questions and the actual majors of students! 
![Correlation Matrix](img/correlaiton.png)
Using that I built a simple regression model to predict the major based on the answers to these questions. After tweaking the model, I saved the model so it could be loaded and run any time a person finishes the quiz, and presents them with the result.

**Project Goals, Skills, and Tools**
* I wanted to get some practice with machine learning, since I'm interested in the field in general. Though it wasn't explicitly required in the project layout, I did want to be more creative in how I implemented the quiz. So using regression allowed me to do both at once
* The skills I used in the making of this project:
    * Lots of researching- This was my first personal project with python, and my first time ever using Jupyter Notebooks or sklearn. So I had to visit StackOverflow for help quite often
    * Patience- I had to transform the data in bunch of different ways and spend a lot of time looking at charts before my regression model was passable. So it took quite awhile for all my work to pay off, but it eventually did.


**Reflection**
This was a really valuable experience. While the final product is really only a few lines of code, it took hours of research, problem solving, and iterative adjustments to make sure it was the right few lines of code. I also learned a lot about machine learning in general, and I hope to keep building these skills in the future.
