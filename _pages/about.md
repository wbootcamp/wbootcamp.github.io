---
layout: post
title: "Welcome to the Bootcamp !"
permalink: /about/
---
## Welcome to Winter Bootcamp 2018 !
<img src="https://cdn.pixabay.com/photo/2018/07/13/02/20/dog-3534781_960_720.jpg"/>

This page will guide you throughout your bootcamp.

### Part - I

#### Basic Git Primer (5 Points)
- What’s the difference between Git and GitHub?
- Make a git repository, use command line to add and commit and push to GitHub.
- Understand that these are the only three git commands will be frequently used. try running these commands
- git add . : Adds everything to git staging area (the files have been staged for committing - What does the “.” at the end signify ? Can you just add a specific file?)
- git commit -a -m “this is a commit message”
- git push origin master 
- Go through http://rogerdudler.github.io/git-guide/ 
- Follow steps here: https://help.github.com/articles/create-a-repo/ 
- If facing issues/not able to understand, take a cursory look at https://www.udacity.com/course/how-to-use-git-and-github--ud775 - No need to go deeper into Merge Requests etc. Just give it a few hours and DO IT YOURSELF.
- Helpful cheatsheet: https://education.github.com/git-cheat-sheet-education.pdf 
- Evaluation - _Demonstrate multiple Git repositories and ability to use Basic Git Command Line. Provide links, screenshots and your thoughts._



#### Basic Linux & Web Applications (10 Points)
- Connect and launch AWS EC2 instances. (2 Points)
- Host a REST-based API which can either do (1) or (2) (8 Points)
- Accepts a users date of birth and gives back his age in years and months. 
- Accepts a string of text, and outputs related news/dates to it using NYTimes API. (+5 Bonus Points)
- You can use Flask and Python for this task, and Postman for testing your API - 
- https://pythonspot.com/flask-web-app-with-python/
- https://medium.freecodecamp.org/how-to-build-a-web-application-using-flask-and-deploy-it-to-the-cloud-3551c985e492 

- Evaluation - _Screenshots and Links_


#### Make your Resume in LateX online at overleaf.com  (5 Points)


#### Make your online Portfolio to showcase the awesome work you’ve done this winter (10 Points)
- You may use GitHub to host a website for free. 
- https://learntocodewith.me/tutorials/github-pages/ 
- Make one for yourself.
- Pick a theme !: https://pages.github.com/themes/ 

_For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/)._



### Part - II (Bucket 2 – Data Science, AI & Machine Learning)
- **Part A: Data Science Primer (10 Points)**
    - [https://www3.cs.stonybrook.edu/~skiena/519/](https://www3.cs.stonybrook.edu/~skiena/519/) 
        - [https://www.youtube.com/watch?v=78dUCOF9zxE&list=PLOtl7M3yp-DVBdLYatrltDJr56AKZ1qXo](https://www.youtube.com/watch?v=78dUCOF9zxE&list=PLOtl7M3yp-DVBdLYatrltDJr56AKZ1qXo) OR [http://www3.cs.stonybrook.edu/~skiena/data-manual/lectures/](http://www3.cs.stonybrook.edu/~skiena/data-manual/lectures/) 
        - Go through the course, aim to finish videos in 1 week. The course is very lightweight.
            - Evaluation- 1 hour, online objective “Normal Exam” after watching videos which will comprise of questions **DIRECTLY** from the videos/slides.

- **Part B: Machine Learning Theory (20 Points)**
    1. Learn basic Machine Learning
        1. Start this course on Day 1 and follow religiously through your vacations. [https://www.coursera.org/learn/machine-learning/](https://www.coursera.org/learn/machine-learning/)
        2. Evaluation - **(10 Points) **Course Completion % scaled 

    2. Implement the following algorithms from scratch in language of your choice (Preferably Python / Jupyter Notebooks) and attach a visualization which shows these in action  (Hint - If using python, use something like [this](http://louistiao.me/notes/visualizing-and-animating-optimization-algorithms-with-matplotlib/)):
        1. Linear Regression **(2 Points) **
        2. K-Means Algorithm **(3 Points) **
        3. Support Vector Machines **(5 Points) **

- **Part C: Application** **(30 Points)**
    1. This part doesn’t comprise of points but will give you an understanding so that you can complete the project for this bucket. Head over to [https://www.udemy.com/machinelearning/](https://www.udemy.com/machinelearning/) - I’ll authorize the purchase for you. 
        1. Evaluation - Complete the course OR demonstrate equal understanding.

    2. **Project 2A ** **(15 Points) **- Participate in a Kaggle Contest (Should be started in parallel after finishing Week 1 and 2 of the ML Course)
        1. Install and try [Jupyter Notebooks](https://www.datacamp.com/community/tutorials/tutorial-jupyter-notebook).
        2. Take a cursory look at [https://github.com/ageron/handson-ml](https://github.com/ageron/handson-ml) 
        3. Pick a competition of your choice from [https://www.kaggle.com/competitions](https://www.kaggle.com/competitions) 
        4. Make a Jupyter Notebook and run Python Hello World.
        5. Use Jupyter Notebooks to participate in the competition and aim for the Prize!
        6. **Evaluation** will be 
            1. **5 Points **for Jupyter Python Notebook explaining your work, different models you tried
            2. **10 Points **which will be weighed according to your Kaggle Contest Percentile.

    3. **Project 2B ****(15 Points) **- Make an ML/Deep Learning model that can do either one of these-
        1. Detect how many cars are there in an image and their relative position (left/right/center) from the center of the image (Difficulty : Medium)
        2. Predict Stock Prices based on historical performance, and Tweets (Use Twiter API) (Difficulty : Medium)
        3. Given a piece of text, can you detect in which year it was written ? (Difficulty : Medium - Hard)
        4. Music Genre Classification via Machine Learning (Difficulty : Easy)
        5. Picture Summarizer - Given an image, can your ML model write a sentence on it. (Difficulty : Medium-Hard)
        6. Do facial features impact popularity of a celebrity ? - You can use [http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html](http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html) 
        7. **Evaluation** will be a 
            1. Project Proposal which details the following **(3 Points) ** 
                1. Introduction
                2. Your Model & Architecture and Features you intend to use
                3. Technologies, Libraries and Datasets you’ll be using
                4. Model Evaluation Statistics - How will you quantify how good/bad your model is?

            2. Project Report in Latex **(5 Points) **and a GitHub repository with project code **(5 Points) **, a Video of the actual Demonstration on Youtube OR A blog post on [Medium.com](http://medium.com/) which shows animations and describes how you’ve implemented it. **(2 Points) ** 

- Helpful links/Advanced
    1. “Understanding Machine Learning by Shai Ben David & Schwartz” - Highly abstract and very theoretical. Hard to understand.
    2. “Deep Learning” by Ian Goodfellow - Very good book
    3. [https://github.com/JasonShin/awesome-deep-learning-for-noobs](https://github.com/JasonShin/awesome-deep-learning-for-noobs) 
    4. [https://realpython.com/face-recognition-with-python/](https://realpython.com/face-recognition-with-python/)
    5. [https://www.pyimagesearch.com/2018/02/26/face-detection-with-opencv-and-deep-learning/](https://www.pyimagesearch.com/2018/02/26/face-detection-with-opencv-and-deep-learning/) 
    6. [https://realpython.com/python-keras-text-classification/](https://realpython.com/python-keras-text-classification/) 
