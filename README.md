# Learn to listen to live data feeds in Python

Publish/subscribe messaging, or pub/sub messaging, is a form of asynchronous service-to-service communication used in serverless and microservices architectures. In a pub/sub model, any message published to a topic is immediately received by all of the subscribers to the topic. Pub/sub messaging can be used to enable event-driven architectures, or to decouple applications in order to increase performance, reliability and scalability.Ω
## What will I learn during this workshop?

In this hands-on Beginners Machine Learning online workshop, you will learn how to listen to live feeds, parse save the received messages.

During the workshop we will listen to Network Rail's live train describer data a Jupyter notebook. We first will look at how one can listen to these messages, then how we can define our own behaviours to save and parse messages received.

## Learning Objectives

- How can one listen to live data feeds
- How can one save messages received from live data feeds
- What are the differences between pub-sub feeds and APIs
- What is JSON and how can one parse it into tabular format

## Steps

This workshop consists of 6 lessons and 1 projects:

**LESSONS**
1. Pub-Sub messaging systems and how to subscribe to one
2. Saving messages from live feeds as you listen to them
3. Parsing JSON semi-structured messages into a tabular structure

**PROJECTS**
1. Listen to another network rail data feed, and save the messages received in CSV format after parsing them into tables

## YOUTUBE TUTORIAL

> Youtube Video tutorial is currently being filmed and edited. Please check back later for a link to the video.

## Prerequisites

While you won't need prior experience with pub-sub systems, we will assume basic programming experience with Python and package/environment managers such as pip, conda or pipenv.
1. Conda installed locally (https://docs.anaconda.com/anaconda/install/)
2. Jupyter Notebook installed locally (https://jupyter.readthedocs.io/en/latest/install.html) 

For refresher on python programming we recommend the following free course:
- Python programming language: See [Udacity - Intro to Python](https://eu.udacity.com/course/introduction-to-python--ud1110)


## Setup
Use the following guides to setup your development environment

1. Create your local environment (see prerequisite No. 1): `conda create --name ${environment_name}`
2. Activate the env: `conda activate ${environment_name}`
3. Install your dependencies `pip install -r requirements.txt`

- If using VirtualEnv

3a. Add virtual env to jupyter notebook kernel
    `python -m ipykernel install --user --name=${environment_name}`
    this should print "Installed kernelspec ${environment_name} in ${dir}
    

4. Go to /notebooks/Lesson 1 - Basic Image Operations and select `kernel/change kernel/${environment_name}`
(every time you open a new lesson you're likely to have to select your kernel again)
5. You're ready to go!

## Flow

1. Clone this git repository using `git clone https://github.com/beginners-machine-learning-london/intro-live-data-feeds.git` or download the repo as a zip file to get started
2. Setup your development environment using conda or pipenv using the `requirements.txt` file.
3. Listen to lectures then work your way through the notebooks in `notebooks` folder.
4. Complete the project sections in the notebooks after the workshop.
5. Join our [slack group](http://tiny.cc/joinbmlslack) to get access to this workshop's private channel so that you can ask questions and connect with your classmates
6. Submit the github repo link to your completed projects on our [website](https://beginnersmachinelearning.com) for grading and a chance to earn a course certificate 

> **IMPORTANT NOTE**: Attempt to complete the projects by yourself using the youtube tutorial and googling online. If you get stuck and cannot progress any further, then take a look at the solutions in the `solutions` folder

## Primary Tools:

- [Python](https://www.python.org/): Python is a programming language that lets you work more quickly and integrate your systems more effectively.
- [Pandas](https://pandas.pydata.org): pandas is a fast, powerful, flexible and easy to use open source data analysis and manipulation tool,
built on top of the Python programming language. 
- [Stomp](http://jasonrbriggs.github.io/stomp.py/api.html): Stomp.py is a Python library providing access to a message broker using the STOMP protocol - either programmatically or using a command line client.

## Learn More:

- **[Stomp Documentation](http://jasonrbriggs.github.io/stomp.py/index.html)** - Use this resource as the main resource for this class.
- **[Network Rail Open Data Feeds](https://www.networkrail.co.uk/who-we-are/transparency-and-ethics/transparency/open-data-feeds/)** - Refer to this resource to understand what data feeds are available to subscribe to.
- **[Open Rail Data Feeds Wiki](https://wiki.openraildata.com/index.php/About_the_Network_Rail_feeds)** - Check out this resource which has information on the Open Data available from the rail industry in Great Britain.

## Collaboration, Questions and Discussions

- [**BML Slack Channel**](http://tiny.cc/joinbmlslack) - Join our slack workspace to collaborate with others, discuss ideas and post any questions you have about our group or the workshops

## Workshop Feedback

- How was this workshop? Please provide us with some feedback [**here**](http://tiny.cc/BMLfeedback) so that we can improve the content and delivery of future workshops.

