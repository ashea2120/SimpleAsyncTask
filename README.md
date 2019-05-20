# CE-450 Lab 6 (2019 Spring)
---
This repository is for Lab 6 submission.
 
## 1.1 Simple Async Task
 
This repo is for the following Practice Set:
- CodeLabs Android Fundamentals 07.1 - AsyncTask
 
## Issues and Lessons
 
A short description about the issues that you faced and the lessons that you learned.
- Simple app that only has one TextView and Button. When button is pressed, the app will sleep for a random amount of time and specify how long it slept in the TextView
- Learned about the abstract AsyncTask subclass and the following structure: onPreExecute(), doInBackground(), onProgressUpdate(), and onPostExecute()
- Learned about how all of these UI and Worker Threads work together
- Learned about WeakReferences and how to correctly implement them
- Learned about the loader callbacks and how to implement them utilizing the OnCreateLoader()
- AsycTask isn't well suited for tesks which may be interrupted by the destruction of an Activity <- IMPORTANT!!! Need to utilize the onSaveInstanceState() to preserve UI elements
---
Written by Ashley Shea
