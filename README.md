# MDSSB-MET-02 Task Regular Expressions

## Introduction

### Overview

This week you get to work on some regex examples. 

### Editing

You can create documents and edit them directly in GitHub's web interface. This is a very convenient way of creating and editing the files. 
In most cases, the preferred way of working is to create and edit the files on your own machine. 


## Task Explanation

Below is today's task. We will be working with regular expressions. 

For this task, you need to provide the answers in the file you are currently reading. It is a Markdown file. More explanations about the Markdown syntax can be found [on GitHub's Mastering Markdown page](https://guides.github.com/features/mastering-markdown/).

* Under the heading _Your Task_ you will find several questions. 
* Try to find the regular expressions needed to fulfil the criteria. 
  * You might want to use Notepad++ or a website like [regular expressions 101](https://regex101.com/) or [RegExr](https://regexr.com/) to test your regular expressions. 


**Commit early, commit often** - that way you can go back if you have made a mistake and I can see all the work you have done. It doesn't matter if your early commits contain mistakes.  

Once you are done be sure to commit your changes (that will save them to the repository) and to push them to GitHub (so that I can see the work you have done).


## Your Task

#### Question 1

Let's assume a Constructor University student number looks like this: G31485694. 

Find a regular expression that will match this kind of student number.
 
`[G][0-9]{8}`

**Answer:** Replace this text with your answer.

#### Question 2

Sometimes people will write the G as a lower case character or leave out the letter altogether. 
Find a regular expression that will match a student number, based on the additional information presented in this question. 
 
`[Gg]?[0-9]{8}`

**Answer:** Replace this text with your answer.

#### Question 3

Let's assume that sometimes you see other letters in front of the number (instead of G), e.g. if students sign up for a certificate that will not form part of their degree classification. 
Find a regular expression that will match a student number, based on the additional information presented in this question. 
 
`[a-zA-Z]?[0-9]{8}`

**Answer:** Replace this text with your answer.

#### Question 4a

Think of different ways of writing down a German phone number. and write them down as your answer to this question (one per line).

Example: 0421 / 200 40, +49 421 200 40 
 
`0421 / 200 40,
+49 421 200 40,
0421 200 40,
421 200 40,
042120040,
42120040`

**Answer:** Replace this text with your answer.


#### Question 4b

Find a regular expression that matches all of the different phone number formats from Question 4a. If you cannot match all try to match as many as possible. If you can't match all, don't change Question 4a by pretending you came up with fewer phone number formats, but you matched them all. It's better if you come up with lots of formats you can't match than if you only come up with very few formats, but you can match all. 
 
`[+]?[0-9]+`

**Answer:** Replace this text with your answer.
