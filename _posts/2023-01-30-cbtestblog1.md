---
title: CB Test 1 Blog
description: Blog on experiences takng the test, questions I had, and research I did
image: /images/collegeboard.png
tags: [collegeboard]
layout: post
---
# Results
![]({{site.baseurl}}/images/results1.png)
Overall, I did better on this test compared to the last. I was able to finish this test in a shorter window of time, and I found that I could answer more questions without the help of outside resoureces. Here are notes on the four questions I got wrong. These questions fall under a category of questions that I found the most difficult. I will be discussing this, patterns I found, and strategies in the reflection portion of this blog. 

# Corrections
Here are the four problems that I answered incorrectly. There are other problems on the test that made me stop to think but those problems fall under the categories that these four problems address. 

## 27
Which of the following code segments can be used to move the robot to the gray square along the path indicated by the arrows?
![]({{site.baseurl}}/images/cb/cb1.png)
My answer: 
![]({{site.baseurl}}/images/cb/cb2.png)
The correct answer: 
![]({{site.baseurl}}/images/cb/cb3.png)
N should be assigned a value one greater than n after the loops. Otherwise, the robot does not reach the right place since n is incremented incorrectly, given the initial assignment n=1. I think the reason that this problem stumped me is because the answer choices were so similar. Avoiding this mistake is simple, I would just have to read the choices more carefully and imagine the output of the code if it were to run. Writing down the results of each segment could be helpful. 

## 30
The drawCircle procedure is to be used to draw the following figure on a coordinate grid. Which of the following code segments can be used to draw the figure
![]({{site.baseurl}}/images/cb/cb4.png)
My answer: 
x ← 4
y ← 1
r ← 0
REPEAT 3 TIMES
{
drawCircle(x, y, r)
r ← r + 1
y ← y + 1
}
The correct answer: 
x ← 4
y ← 1
r ← 0
REPEAT 3 TIMES
{
r ← r + 1
y ← y + 1
drawCircle(x, y, r)
}
This is correct because the r and y values must be incremented before the drawCircle method is called. This is very similar to the mistake I made on number 27. I think I need to work more on simulating the results of each code option in my head. 


## 32
The figure below shows a robot in a grid of squares. The robot is represented as a triangle, which is initially facing upward. The robot can move into a white or gray square but cannot move into a black region.
![]({{site.baseurl}}/images/cb/cb5.png)
My answer: 
![]({{site.baseurl}}/images/cb/cb6.png)
The correct answer: 
![]({{site.baseurl}}/images/cb/cb7.png)
This answer is correct due to the middle block. ** Be more careful when reading code block answers. Try to draw them out. This is a little different from the previous two mistakes because this mistake does not involve increments. However, I think I just misread the answer choices because looking back, it is clear that 4-3 is the answer. 

## 39
Programs I and II below are each intended to calculate the sum of the integers from 1 to n. Assume that n is a positive integer (e.g., 1, 2, 3, …).
Which of the following best describes the behavior of the two programs?
![]({{site.baseurl}}/images/cb/cb8.png)
My answer: 
Program II displays the correct sum, but program I does not.
The correct answer: 
Both program I and program II display the correct sum.
I thought the first one did not work. However it does work and this mistake could have been avoided if I took note of how the variable result was affected through the loops. 

## Hexa to Decimal
- to convert hexadecimal, take each digit of the hexadecimal from right to left and multiply by powers of 16 starting from 0 and replace the digits. 

# Reflection
Overall, most of these mistakes I had could be avoided through drawing out the results or writing down my thoughts. It will be importnt that I learn where the increments should go within the loops. Also it was mentioned above in questions but I had to search up how to convert hexa decimal to decimal. 
- Heuristic: not every problem can be solved with code without sacrificing perfection for the sake of simplicity and time
- Make sure to check every single option
- For problems with multiple selections, make sure to look at each very carefully