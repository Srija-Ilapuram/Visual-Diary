Visual Diary Project

Project Description

The Visual Diary project is a web-based application developed using the Angular framework and Firebase as its database and authentication server. The purpose of this visual diary is to provide users with an effective mode of diary entry, allowing them to write about their day and attach photos, videos, or audio files to each entry. The user interface is designed to resemble a book, providing a nostalgic feel to the diary-writing experience.

Features

User authentication through login credentials
Dashboard for easy navigation
Diary entry creation with the option to attach photos, videos, and audio files
Preview of past diary entries with attached memories
Intuitive and attractive user interface resembling a book

How to Install and Run the Project

To install and run the Visual Diary project, follow these steps:

Prerequisites

NodeJS
NPM Manager
Angular

Installation Steps

Download the project repository as a zip folder.
Extract the zip folder to your desired location.
Open a terminal and navigate to the project folder.

Setting Up Angular Project

Create a new Angular project using the following command:
ng new your-project-name

Copy the contents of the extracted src/app/components and src/app/services folders into the corresponding folders in your Angular project.

Setting Up Server

Create a new folder named server in your project directory.

Copy the server.js file from the extracted src/server folder into the newly created server folder.

Running the Application

In the terminal, navigate to your Angular project directory.

cd your-project-name

Start the Angular application:
ng serve

Open a new terminal and navigate to the server folder.

cd your-project-name/server

Start the server:
node server.js

Open your web browser and go to http://localhost:4200 to access the Visual Diary application.

How to Use the Project
Login/Signup:
On the home page, log in using your credentials or sign up if you're a new user.

Dashboard:
After logging in, navigate to the dashboard where you can choose to make a new diary entry or preview past entries.

Diary Entry:
If creating a new entry, write about your day and attach photos, videos, or audio files. Save the entry.

Preview Entries:
Choose the preview option on the dashboard to view past diary entries. Select the date to see the entry along with attached memories.

Sign Out:
When done, sign out from the dashboard.

Contribution
I welcome contributions to enhance and add features to the Visual Diary project. Feel free to fork the repository, make your changes, and submit a pull request. I would love to collaborate and improve this project together!

Happy diary writing! 📖✨
