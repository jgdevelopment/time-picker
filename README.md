# time-picker

Overview: In this project, you will implement a flexible, extensible time picker React component. Below, we show an example feature and outline a set of requirements. To get started, clone https://github.com/skiff-org/time-picker! 

Even if you do not complete all of the extensions, we suggest reading them to determine component and app data best practices.

Steps to completion

Define an enclosing functional component, <App />. 

App should define some state variables for the current app, including 12 vs 24 hour time. 

TimePicker should contain the following fields / properties:

Create an <Input /> for the user to enter an initial time.

Integrate the state variable from App to support 12-hour versus 24-hour time. 

Time permitting, use a custom React hook to re-populate the time increments.

Create a dropdown  populated with a list of time options.

Add a validator to the textfield for custom times (display error / red if invalid).

Note: there’s no need to validate the time format as a user types. e.g. “930” instead of“9:30” is fine.

On selection, TimePicker should pass the selected or entered time back to the parent App component. 

Use useContext to support light and dark themes for the picker (extremely simple visuals suffice, e.g. just change background and text color).

Ensure the dropdown remains within the screen bounds, shifting upward if it overflows.

Optional/Bonus Extensions:

Create a <TimeLabel /> component inside of App displaying the time in bolded red on white (or bolded white on black depending on context) as “The selected time is: XX:XX AM/PM”. 

Wrap <TimePicker /> in a dialog that you open with a button and close by clicking outside of the dialog.  
