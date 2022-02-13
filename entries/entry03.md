# Entry 3
##### 2/11/22

## Overview / Sources

In my previous entry, I went over my goals for my project and <b>Swift</b>. <b>Swift</b> is a general-purpose computer language developed and marketed by Apple Inc. <b>Swift</b> is tailored for iOS application development. I went over what I wanted my app to do and my ambitions. This entry will go over what I have done to move closer to my project goals, "The Programmer Notebook". I wasn't able to continue my "full-dive" that was planned to do over break as I had a family emergency that pulled me away. I will spread it over the free time I have and plan for my next break to finish my research. In this entry, I will go over what I have done and how I have gotten closer to my end goal, my end product. 

## Storing Data

This code snippet is for creating a note. Specifically, this is to introduce methods to resolve, confirm, and handle requests to create notes. 

`protocol INCreateNoteIntentHandling`


### Protocol

A <b>protocol</b> defines a blueprint of methods, properties, and other requirements that suit a particular task or piece of functionality

## Rertieve Data
```
optional func resolveContent(for intent: INCreateNoteIntent, 
                        with completion: @escaping (INNoteContentResolutionResult) -> Void)
```
This code snippet is a example how to retreieve stored user data. 

### intent
The intent object contains details about the user’s request. This object is used to get the  information

### completion
This execute the resolution. You must execute this at some point during your implementation of this method. Has no return value and takes the following parameter:

### resolutionResult
The object contains the details of the proposed resolution. For successful resolutions, create a resolution object with the text or image that you intend to use as the main content of the note.


#### Sources: <b><a href="https://developer.apple.com/">Apple Developer Pages</a></b>

## Engineering Design Process (EDP)

The Engineering Design Process (EDP) is a <b>7-step process of *planning, designing, creating, testing, and then improving on*</b>. Therefore, the process doesn't end as there are always ways to improve upon your design. Improvements that can be done through testing and user feedback, both I plan on hosting. To begin I have to recognize the problem, lack of programmer-focused note applications. First I have to understand what makes a note-taking app a *note-taking app*. Going past the bare bones of taking in and saving user inputs it is important to make the process as easy for the user. Note-taking on your phone should be just as easy as putting pencil to paper. Currently I am at stage 2, testing. My project, *"The Programmers Notebook"*, ambitiously speaking will have the quality of life features to make note-taking easier and more code-friendly. But in a Minimal Viable Product sense, I first need to just create a program that takes in a user input, saves and stores them, then pull them from the local device whenever. 
 
After I have that I can countinue this passion project and leave something behind the next generation of coders at my Highschool can utilize fully. 
 
## Knowledge/ Goals

I have done research but I ran into issues regarding my laptop running x-code. I will fix this and continue trying different ways to save user data. I have a lot of questions regarding concepts and relationships being used. I will leave the specifics of my gaols open-ended as It is still generally learning more about Swift and its fundamentals. 

 
<b>Sources To Review</b>
<li><a href="https://www.youtube.com/watch?v=Ulp1Kimblg0&t=84s">Swfit Tutorial Beginners </li>
<li><a href="https://www.youtube.com/watch?v=comQ1-x2a1Q">Swfit Full Course </li>
<li><a href="https://www.youtube.com/watch?v=Pd8IvykiW20">Swfit Crash Course </li>


## Skills
Skills that I will need to utilize during the coming break are...
  <li>Analysis</li>
  <li>Active Reading</li>
  <li>Evaluate</li>



[Previous](entry02.md) | [Next](entry04.md)

[Home](../README.md)
