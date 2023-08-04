# ClientManagement
Registration Page (registration.html)
The registration page is a user interface for new users to sign up and create an account. It contains a form with various fields, such as name, email, address, and password, which the user needs to fill out to complete the registration process.

Name: The user can enter their full name in a text area.
Email: The user must provide a valid email address for communication and login purposes.
Address: A multiline text area for the user to input their address details.
Password: The user should create a secure password for their account.
Register Button: Upon clicking the "Register" button, the user's data will be processed for account creation.
Meeting Schedule Creation Page (meeting.html)
The meeting schedule creation page allows authenticated users to create new meeting schedules for various events or discussions. It includes fields to specify the meeting topic, number of participants, start date, start time, and AM/PM choice.

Meeting Topic: The user can enter a topic or title for the meeting in a text field.
Number of People: The user can specify the expected number of participants for the meeting.
Start Date and Time: The user selects the date and time for the meeting to start using date and time input fields.
AM/PM Choice: The user selects either "AM" or "PM" from a dropdown to indicate the time of day for the meeting start.
Create Meeting Button: By clicking this button, the meeting schedule details will be processed and saved.
Navigation between Pages

The application uses Angular routing to navigate between the registration page and the meeting schedule creation page. After successful registration, the user will be redirected to the meeting page to create a new meeting schedule.
