Homework 5 - Work Day Scheduler

by Julian Secomb

Objective: To create a calender application that allows user to save events for each hour of the day. Once an event is entered, it is stored in local storage so that it will save in the scheduler when the page is refreshed. The events should also be color coded to show whether the activity event is in the past, present or future.

Work Done: Using jquery, a for loop renders a table that contains a row for each business hour of that day. Each row contains an input field for the user to enter an activity and a save button. When the user clicks the save button for a particular hour, the value of the matching input field is pushed into the corresponding position of the "schedule" array. Using JSON, the schedule array is saved in local storage. Using moment.js and several "if" statements, the table is color coded dynamically according to the time of day. Future hour blocks are green, the current hour block is grey, and hour blocks that have already passed are red.

