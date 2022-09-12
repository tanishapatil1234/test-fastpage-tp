---
toc: true
comments: true
layout: post
title: Creative Development Blog
description: AppLab Planning/Blogging. A plan and notes of the steps taken during the process.
image: /images/.png
tags: [creative_development]
---
# Creative Development Blog
## AppLab Creations
[AppLab Creation](https://studio.code.org/projects/applab/GNqP9uqVldcpC2TuXJe3ODTIQCi8o-hUPEj9pb4qwHY)
[Personality Quiz](https://studio.code.org/projects/applab/uq_3a5cbrbF5wLUIUBATLDYPnfTIJETCG-L6hTMwqWU)

**Program Purpose**
This purpose of this program is to test the user's ability to recognize popular luxury brand logos. 
**Program Functionality**
This program consists of three questions in order to quiz the user on their ability to recognize logos. It starts at the home page and navigates through each question page. If the answer selected is wrong, the program leads the user to an 'incorrect' question that allows the user to either retry the question or get a hint. The last screen desplays the results of the quiz. 
**Program Testing**
I tested this program multiple times. At first I did not use hints and realized that for someone without knowledge of brands, not having hints or retries could be discouraging. Also, the score calculator was not displaying because the if statement was not under an 'on event statement'. After changing this and reassigning score values to each answer I got better results. 
## App Planning - Logos Quiz
- Home page (introduces quiz, leads to q1)
- Q1: question with four options A B C D. If correct answer isn't chosen, lead user to 'incorrect' page. Incorrect page displays that the user input was incorrect and has option to return to the question or recieve a hint. When correct answer choice is clicked, leads to 'correct' page which leads to question 2. 
- Q2: choose between four image options using check box. If correct answer isn't checked, lead user to 'incorrect' page. Incorrect page displays that the user input was incorrect and has option to return to the question or recieve a hint. When correct answer choice is clicked, leads to 'correct' page which leads to question 2. 
- Q3: choose between two images. If incorrect, lead to incorrect page and option to return to question

## Additions 
- Successes: use of correct/incorrect pages, check boxs
- Failures: tried to use a for loop but wasn't able to because when looped the incorrect answers had to go to different pages based on the question that was incorrect, drop down failed because dropdown only changed the screen and did not give an output
- Adjustments: could not use the dropdown so I used the checkbozes instead. Loops did not work due to the fact that each user input needed specific screen changes. So I did not use loops. Ideally I would have figured out the loops because the code was very long. 



## Extra
- created a second quiz inspired by buzzfeed quix
- created a series of questions that determine whether you are an introvert or extrovert
- I created a variable 'score' and for whichever answer I added/subtracted it a specific value to be added to var score. 
- In the end I used an if/else statement and said that if score was greater than 0, to display the score and 'introvert'
