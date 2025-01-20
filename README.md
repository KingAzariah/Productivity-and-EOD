Productivity and EOD Tracker

The Productivity and EOD Tracker is a web application designed to streamline the process of tracking daily tasks and generating End-Of-Day (EOD) reports. This tool simplifies task management for mailroom employees and helps generate a formatted report to send to supervisors.

Features

Task Selection: Choose tasks from a dropdown menu with pre-defined time values.

Quantity Input: Enter the quantity of tasks performed, and the total time will be calculated.

Dynamic Time Tracking: Tracks remaining time starting at 435 minutes and adjusts dynamically as tasks are added or removed.

Task Deletion: Remove tasks from the list if entered incorrectly.

EOD Report: Automatically generates a report with all tasks and their total time.

Mobile Friendly: The app is responsive and adapts to various screen sizes.

Technologies Used

HTML: Provides the structure of the application.

CSS: Styles the application with a clean, futuristic design inspired by USPS branding colors.

JavaScript: Implements dynamic functionality such as task management and time tracking.

Installation

Clone the repository:

git clone <repository-url>

Navigate to the project folder:

cd productivity-eod-tracker

Open the index.html file in any modern web browser to run the application.

Usage

Select a Task:

Choose a task from the dropdown menu.

Enter the quantity of the task performed.

Add Task:

Click the "Add Task" button to add the task to the list.

View Total Time:

The app updates the total remaining time dynamically.

If the total time goes negative, it highlights the overage percentage.

Delete a Task:

Remove a task from the list by clicking the red ✖ button next to the task.

Generate Report:

The EOD report displays all completed tasks and their total time.

Click "Save and Send Report" to finalize the report (currently displays an alert for demonstration purposes).

Customization

Task List: Update the predefined tasks in the select element in the HTML file.

Time Values: Modify the time values associated with each task.

Styling: Adjust the styles in the <style> section of the HTML file for custom branding.

File Structure

productivity-eod-tracker/
├── index.html       # Main application file
├── README.md        # Documentation file

Screenshots



License

This project is licensed under the MIT License. You are free to use, modify, and distribute it as per the terms of the license.

Contributions

Contributions are welcome! Feel free to fork the project and submit pull requests for enhancements or bug fixes.

Contact

For questions or feedback, please contact [your email or GitHub profile].

