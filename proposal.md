# X-Team 48 Autocomplete Project Proposal

See https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#code for tips on using *Markdown* tags to format __.md__ files

## Goal

Work as a team to create a project proposal for your X-team to complete together.
The project does not have to be extremely difficult,
but there must be work to do for each member of your team.
You may reference figures using "See figure 1".  
Be sure to submit corresponding image files, i.e. figure1.png (or figure1.jpg) for each figure.

## Grading: To earn full credit, your team's proposal must include:

* (md) documentation: [this file] describing purpose and use of your program

* Description of a program that has:

  ** a main Java program class in a file named Main.java
  
  ** a custom data structure designed and built by your team
  
  ** comprehensive testing of individual units
  
 Caution: You are not being asked to implement this program, at least not yet. 
 We just want your group to make a proposal or pitch for your program.
 
 Tip: Your custom data structure can be composed of or extensions of data structures that you have learned and used in previous programming assignments.  We're looking for decisions about how to build a high-level data structure that will likely have lower-level components.

## Problem Description

Our problem is slow and incorrect typing.
Our program would implement a tree that contains connections between letters and builds up words as you traverse it. 
The program would then suggest words to auto-complete the word the user is typing. The program would suggest the 3 shortest words
that match the user's input.

## Questions to answer for Exercise #2

1. Name: Give your project proposal a name (and edit the top line of this file)
Auto-complete


2. Output: Describe the output your program will produce.  Include an example format of the output produced.

Our program would produce 3 options to complete a given word, with the shortest option being the first.
*See figure 1

3. Input: Describe the data that is needed to solve your problem. Include an example format of the input data.

The actual auto-complete feature will simply require a user's incomplete word input, so that it can (hopefully) give the correct word.
Before the user can input words, however, the program will also require a dictionary file so that we know what words are available to autocorrect. A default dictionary will be provided within the program.
An examplle dictionary file could be a simple text file formatted as such:
Aardvark
Ape
Balloon
Billiard
Dictionary
...

4. User Interface: Describe a user interface for your program.  Use text menus or a simple graphic user interface.
The user will type in a textbox and word suggestions will appear beneath it. The user will be able to click on the word to select it. 
For a rough idea of the user interface, see Figure 1.


5. Types List: Break your solution idea down into units that you think can be implemented with a single class.



Name each interface or class and briefly describe its function or purpose.


## Edit and Submit this file and any figures referenced by this document.
*Figure 1
![alt text](https://i.imgur.com/Lx5o35O.jpg)
