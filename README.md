# QuestionableQuestionsApp
## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Website Overview](#website-overview)
* [Acknowledgments](#acknowledgments)

## General info
This is an introductory web application that tracks any funny, memorable and questionable questions asked in lectures. It edits and displays a local database listing questions and who asked them (the questioner), along with search abilities. 

It is a side project to learn web development, C#, and HTML as well as database handling.
	
## Technologies
Project was created with the following tools:
- Visual Studio 2022
- ASP.NET Core 6.0
- SQL
- C#
- HTML
- CSS

## Website Overview
When accesing the application, the home screen is displayed:

<img
src="https://user-images.githubusercontent.com/78566536/224457399-c5e77b59-bc3f-41ce-b451-6219fc937eed.png"
alt="Alt text"
title="Home Screen">

To access the different parts of the website, use the heading at the top of the application to go to the following pages:
* [Home](#home)
* [Privacy](#privacy)
* [Questions](#questions)
* [Search](#search)

Additionally, click on the <i>Github</i> or <i>Youtube</i> graphics to get access to this repo or see the inspiraton for this project.

### Home
Displays the welcome to the website with an image.

### Privacy
Displays the autogenerated privacy statement, because this is running on my local server, the following message is displayed along with a gif:

<img
src="https://user-images.githubusercontent.com/78566536/224457529-ac021d50-e82d-45b0-a604-e9f5f7918e37.png" 
alt="Alt text"
title="Privacy Page">

### Questions
Displays the database of questions along with the questioner (person who asked the question). Additional "Create New", "Edit" "Details" and "Delete" links are visible.

<img
src="https://user-images.githubusercontent.com/78566536/220250176-07587cd8-1f7c-46ff-9b60-b338e97bf766.png" 
alt="Alt text"
title="Questions Page">

If "Details" is selected, the user is brought to a page that displays the Question and Questioner.

If "Create New", "Edit" or "Delete" are selected, the user is brought to the [login](#login) page. Then, the data entry is either edited (see below), created (see below) or deleted.

Edit Screen:

<img
src="https://user-images.githubusercontent.com/78566536/220252662-f883498b-2988-4791-ba94-777e52270649.png" 
alt="Alt text"
title="Edit">

Create New Screen:

<img
src="https://user-images.githubusercontent.com/78566536/220252770-81c17ab5-f6c9-46d0-af33-553e14360c4d.png" 
alt="Alt text"
title="Create New">

### Search
Displays the option to either search for Question or Questioner.

<img
src="https://user-images.githubusercontent.com/78566536/220251541-8b108bf4-897f-400f-906d-ac18d8a0cba7.png" 
alt="Alt text"
title="Search Page">

For example, if we wanted to search for a question about Africa, the results are shown below:

<img
src="https://user-images.githubusercontent.com/78566536/220251807-5d397977-d0e0-40e3-ae63-a133d549d574.png" 
alt="Alt text"
title="Africa Search">

Similarily, the Questioner's name can be searched.

### Login
The user is asked to log-in in order to edit, delete, or add questions to the database. 

<img
src="https://user-images.githubusercontent.com/78566536/220250848-d621d63a-9545-48d6-8b60-23bfa1dce841.png" 
alt="Alt text"
title="Login Page">



## Acknowledgments
Thank you to Shad Sluiter for his video <a href="https://www.youtube.com/watch?v=BfEjDD8mWYg">ASP.NET Core Crash Course</a>, serving as inspiration for this project.
