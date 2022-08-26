# Assignment 0 

## Due 09/03

## Computer Preparation

<details><summary>Win10</summary>
<p>

  * If the Ubuntu app is not installed, then follow [these instructions](https://github.com/cbirdlab/wlsUBUNTU_settings/blob/master/InstallLinuxOnWindows_Automated.pdf)
  
  * Log into your Ubuntu terminal.  _We will not use `gitbash` unless you can't get Ubuntu running._ After logging in, You are in your home directory. 
  
  * If you are using an Ubuntu terminal that hasn't been setup (you'll know because it will ask you to create a new user name and password) or you notice odd cursor behavior when editing text in the terminal, then run the following code:
  
    ```bash
    git clone https://github.com/cbirdlab/wlsUBUNTU_settings.git
    . ./wlsUBUNTU_settings/updateSettings.bash
    rm -rf wlsUBUNTU_settings
    ```
    
  * If the `CSB` directory does not exist in your home directory (check with `ls`), then run the following code to clone the `CSB` repository into your home directory:
  
    ```bash
    git clone https://github.com/CSB-book/CSB.git
    ```
  * It's always a good idea to keep your apps in `Ubuntu` up to date. _The first time you do this, it could take a long time to finish. After that, if you do this when you log in, it should go quickly._
    ```bash
    sudo apt update
    sudo apt upgrade
    ```
    
</p>
</details>

<details><summary>MacOS</summary>
<p>
 
  * Open a terminal window

  * Consider installing [homebrew](https://brew.sh/).  You will be able to use homebrew to install linux software, such as `tree`, which is used in the slide show.
  
  * If the `CSB` directory does not exist in your home directory (check with `ls`), then run the following code to clone the `CSB` repository into your home directory:
  
    ```bash
    git clone https://github.com/CSB-book/CSB.git
    ```
 </p>
</details>


## Description of Assignment

We have a steep learning curve to traverse, so we are going to "flip" the classroom next week. Flipping the classroom means that you work on the material to be covered before we address it in lecture.  Then we can spend time in lecture going over the most challenging topics, as identified by you. Then we will continue together in lecture through new material that builds upon this assignment.

Your assignment is to work through [**Chapter 1**](https://github.com/tamucc-comp-bio-2020/classroom_repo/blob/master/text_book_resources/ComputingSkillsforBiologists_Chapter1.pdf) to "Intermezzo 1.2". The chapter is set up in an interactive fashion, where you are expected to type in the 
```
code blocks
``` 
to learn the material.  


## Resources to Help You

I highly recommend that you print out the [Linux Cheat Sheet](https://github.com/tamucc-comp-bio-2020/classroom_repo/blob/master/resources/CheatSheetLinux_8-12-2016.pdf) which I created for myself and my students when I was learning `bash`.  It's unique because it translates english into `bash`.


## Text Book Vs. Lecture Slides
The [**Lecture_01 Slides**](https://github.com/tamucc-comp-bio-2020/classroom_repo/blob/master/lectures/Week01_files/Lecture01_WelcomeToTheMatrix.pdf) closely follow the book but there is some additional information that is not provided in the book (and vice versa). In the lecture slides, the `code blocks` are represented by green text on a black background, mimicking the terminal.

**Use _BodyMass.csv_ (slides) rather than _BodyM.csv_ (book)**


## Evaluation of Learning
To evaluate your performance on the _Intermezzos_ and ask other questions to evaluate your progress, I have created a _Mind Expander_ for each _Intermezzo_, and they follow the same numbering format. You are expected to complete Mind Expanders 1.1 and 1.2, which are linked below. You need to be logged into your [TAMUCC email account](https://outlook.tamucc.edu) for the _Mind Expanders_ to record your work.


**_You can resubmit your answers as neccessary_**

### [CSB Mind Expander 01.01](https://forms.office.com/Pages/ResponsePage.aspx?id=8frLNKZngUepylFOslULZlFZdbyVx8RLiPt1GobhHnlUM1FFUUZLT01LR0ZGODU2WVNSV1c0NEpWMi4u)

### [CSB Mind Expander 01.02](https://forms.office.com/Pages/ResponsePage.aspx?id=8frLNKZngUepylFOslULZlFZdbyVx8RLiPt1GobhHnlUM0VSMlJZMFg2VzlNNjZVUTJINk9TRlBSOC4u)

## Advice on Entering _Mind Expander_ Answers
It is important when completing the _Mind Expanders_ to be cognizant of spaces both in your code and at the end of the code. The answers will never end with a space so make sure when you copy and paste your code that there's no space at the end. As long as you're making an honest effort, you will be graded on your completion of the work, not whether the form grader recognized your answer as correct or incorrect.  I foresee that there will be many cases where your code works but I may have added a slightly different pattern of spacing.  The important thing is that your code worked, but I try to make the answers to the _Mind Expanders_ follow a particular format that will be emphasized later on in the course, so pay attention to the differences in the spacing between your code and my answers because consitent spacing makes code more readable.


