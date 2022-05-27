# What is Firebase?

Google’s Firebase is a back-end platform that allows developers to create full-stack applications. Authentication, storage, databases, hosting, A/B testing, and other features are available to programmers.

> In a nutshell, Firebase allows us to engage on the front-end of our applications while it takes control of the back-end tasks.

# Installation

- Using the node package manager (npm) by installing it through the terminal in our project folder. – npm i firebase

# Setting Up a Firebase Realtime Database

**Sign Into Firebase**

- First sign in or sign up to firebase account using your Gmail.

- After a successful sign in, You can find a button Go to Console at the top-right corner of the page, then click it

- Then you will be redirected to your dashboard where you can add a project

# Create a project

- Click on the add project button

- Give your Project a Name and Click on continue

- If you need Google Analytics for your project, you can enable this switch.

- Click on Create Project and wait till it’s done. Then click on Continue.

# Create a Realtime Database

- On the sidebar by the left, find the Realtime Database and click on it

- Now you can find and click Create a RealTime Database button on the page.

- Select your preferred location and click next. United States is a better location to use

- Next, you have to choose to database in test mode and click on the Enable button and wait for the process to complete.
  - This will create an empty database.

# Project Setup

We will have 1 file named **index.html.**

# Create the view of the application
> languages:

- html
- css
- js
- jquery

# Building the Functionality
First we need to tell our application about the Realtime Database now we have created and initialize Firebase at the top of our file
So let’s build the configurations of our Realtime Database.

# Getting Our Realtime Database Configurations

- Back in our Firebase console or dashboard, click on the gear icon at the top of the sidebar.

- Click on Project Settings from the options that pop up

**This opens up the settings page**

- In the General tab, scroll down to the Your Apps section and click on the web icon

- In the page that follows, enter your app a nickname and click on Register App

  - This will now open up your configurations:now copy scripts into the bottom of ur body tag.

- Finally, copy the Firebase configuration and initialization

