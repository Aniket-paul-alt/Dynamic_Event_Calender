CalendarApp
CalendarApp is a React application that allows users to view a calendar, add events, edit events, and delete events. The events are saved in the local storage so that they persist across page reloads.

live demo : https://dynamically-event-calender.netlify.app/

Features
View Calendar: Navigate through months and years to view different dates.

Add Events: Add events on future dates with a specified time and description.

Edit Events: Edit existing events to update the time or description.

Delete Events: Remove events that are no longer needed.

Local Storage: Events are stored in the browser's local storage to persist across sessions.

Installation
To run this application locally, follow these steps:

Clone the repository:

bash
git clone https://github.com/Aniket-paul-alt/Dynamic_Event_Calender
cd CalendarApp
Install dependencies:

bash
npm install
Start the development server:

bash
npm start
Open your browser: Open http://localhost:3000 to view the application.

Usage
Viewing the Calendar
Use the navigation buttons to move between months and years.

Today's date is highlighted in the calendar.

Adding an Event
Click on a date to open the event popup.

Enter the event time and description.

Click on the "Add Event" button to save the event.

Editing an Event
Click on the edit icon next to the event you want to edit.

Update the event time and description as needed.

Click on the "Update Event" button to save the changes.

Deleting an Event
Click on the delete icon next to the event you want to delete.

The event will be removed from the list and local storage.

Components
CalendarApp
This is the main component that renders the calendar, event list, and handles all the state management.

State Variables
currentMonth - Tracks the current month being viewed.

currentYear - Tracks the current year being viewed.

selectedDate - Tracks the date selected for adding/editing events.

showEventPopup - Controls the visibility of the event popup.

events - Stores the list of events.

eventTime - Tracks the time input for the event.

eventText - Tracks the text input for the event.

editingEvent - Tracks the event being edited.

Functions
prevMonth - Navigates to the previous month.

nextMonth - Navigates to the next month.

handleDayClick - Handles date click to show the event popup.

isSameDay - Checks if two dates are the same.

handleEventSubmit - Handles the submission of a new or edited event.

handleEditEvents - Prepares the event data for editing.

handleDeleteEvent - Deletes an event from the list.

handleTimeChange - Updates the event time input.

License
This project is licensed under the MIT License. See the LICENSE file for more details.

Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

Acknowledgements
React

Box Icons