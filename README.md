# CPE micro:bit Term Project

Term project for students in the CPE 1040 course at MSUD, Fall 2018.

## Assignment

Design and implement some application of the [micro:bit](https://microbit.org/) educational computer. It can be a new design of your own or an already existing design from the Web.

### Language requirement

The implementation has to be in [MicroPython](https://microbit-micropython.readthedocs.io/en/latest/) (the version of Python that works on the micro:bit). 

**Note:** It is perfectly acceptable to take a project implemented in JavaScript/Blocks and rewrite it in MicroPython.

## Submission

### 1. Github

Fork and clone this directory and submit the URL of your fork (remote) on [Canvas](https://canvas.instructure.com/courses/1397722/assignments/10046266?module_item_id=20700270).

### 2. Individual

You can collaborate with one or two team mates on the design, implementation, and testing of the project, but you have to have *your own* separate Github repository and make an *individual* submission on Canvas.

### 3. Due date

**Sun, Dec 2, 2018, by 23:59**

**Note:** You can submit your URL at any time before the deadline on Canvas, but only your latest commit on Github before the deadline will be evaluated.

### 4. Project report

Write the project report in your README using the template provided below. 

**Note:** Projects without reports will receive **0 points** for the whole project.

### 5. Project demo

The project has to be demonstrated by the team in the lab period on **Wed, Nov 28**. Presentation slides are *optional* but will be noted in the evaluation of your submission. If you can't make this date, you can demo at any *earlier* date, but no later dates.

**Note:** The demo is not optional. If a project is not demonstrated, the grade will be at the discretion of the instructor.

## Grading

The project is worth a total of 600 points. Breakdown:

| Criterion | Points |
| --- |:---:|
| Functionality of application | 300 |
| Good use of [micro:bit](https://microbit.org/) capabilities | 100 |
| Input and output | 50 |
| Complexity of the application | 50 |
| Quality of demo | 50 |
| Clarity of report | 50 |

# Project Report

Fill out this template in place in the README of your own fork of the assignment repository. Put any supporting materials (diagrams, schematics, pictures, presentation slides, etc) in the [assets](assets) folder. You can reference them from this report. For example, [todo file](assets/todo.md). Use this [Markdown cheat sheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) to format the report.

**Acknowledgement:** Adopted from [Bob Yusko](mailto:ryusko1@msudenver.edu).

## 1. Project Title

*Our project name was Multiplayer R.P.S.L.S.*

## 2. Team

*My partner in crime to achieve this project was Daniela Lujan.*

## 3. Project Objective

*In the end we set out to make the game rock, paper, scissors, lizard, spock feel more like a real game with various features.  It is modification to the previous project you can say it’s the 2.0 version. The micro:bit’s capabilities that were necessary and useful for this project was basically all the amazing things this little computer could do. But the most crucial were its ability to communicate with other devices, as well as its ability to produce sound, and its accelerometer. If it weren’t for these capabilities our project would be a project that only displayed images*

## 4. Research

*This project would not have been done with only our creative minds. Due to having no experience with python and the micro:bit itself we had to seek help from online resources as well as from our professor. The main microb:bit website (https://microbit.org/) was the most crucial specifically the reference and features guide.*

## 5. Design

*Our design involved a various amount of inputs that resulted in outputs. Without the help if its processing and storage our design would have not worked properly or at all. The design was meant to play as many rounds as the players would like and when one of the players reaches a certain score it will immediately send a “You Lose” message to the opponent. The micro:bit was also designed in our project to have speech commands throughout.  Within the project the inputs used were the buttons and the accelerometer when it was shaken.  The outputs that resulted from this was the increase of the score by the press of the a button:if the b was pressed then the game would quit, and if the reset button was pressed it would reset and start over. However to get your weapons it would randomly chose when you would shake it. The processing that goes on was more crucial when it came the processing the data and generating the sound. But without the help of the storage it wouldn’t have been able to even store our code or run it. We also used calls already in its memories along with new variables storing our code.*

## 6. Development

1.  Adding features to the base rock paper scissors game.
2.  We wanted to add a timer but we were not effective in doing so
3.  We initially thought the micro bits would be paired through bluetooth but instead used the radio feature.


## 7. Testing


1.  Coded the images for the weapons
2.  Coding it to add a point when button was pressed
3. Tried adding a timer but failed
4. Continuous adaptations didnt let it run
5. Adjusted to end game after certain wins instead. 
6. Tried sending images to other micro bit but failed.
7.  Instead sent messages instead.
8.  The project was a bit too simple and we didn't know what else to add and luckily Daniela found a speech command that let us make the micro:bit ‘talk’


## 8. Demo

*The in-class demo wasn't as effective as we had been running it. We added some last minute adjustments into adding headphones through the use of alligator clips. However on one of the headphones, you had to hold them at a certain angle and way for it to not glitch. The issue was not because of our own coding but more so physical hardships with the micro:bit. We also did not have a speaker to make it sound louder but were able to still walk around and demonstrate throughout the class the full program. Other than that the demo went smoothly.*

## 9. Summary

*Our project consisted of developing a design that was simple yet effectively implemented as many features the micro:bit could do. We learned that it’s truly about trial and error and taking everything a step at a time, once we were able to effectively incorporate something only then will we move on to the next step. Thanks to the radio, sound, Micropython, and accelerometers were able to effectively program a more effective and productive design with a glimpse of the complexity that’s behind the micro:bit.*


