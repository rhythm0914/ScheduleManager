# Schedule Manager

## Description

The Schedule Manager is a web application designed to help users manage their exam schedules. The application allows users to add, edit, and delete subjects, dates, times, sections, and descriptions of their exams. The data is stored locally in the browser using `localStorage`, making it available across page reloads.

## Features

- **Add Subject**: Users can input subject details, including name, date, time, section, and description.
- **Edit Subject**: Users can edit existing subject details.
- **Delete Subject**: Users can remove subjects from the schedule.
- **Responsive Design**: The application is styled to be user-friendly on both desktop and mobile devices.
- **Data Persistence**: Subject data is saved in the browser's `localStorage` for persistent storage.

## Installation

To use the Schedule Manager:

1. Clone the repository or download the HTML file.
2. Open the HTML file in a web browser.

No server setup is required as this is a static HTML file with internal CSS and JavaScript.

## Usage

1. **Add a Subject**:
   - Enter the subject name, date, time, section, and description into the respective input fields.
   - Click the "Add Subject" button to save the subject.

2. **Edit a Subject**:
   - Click the "Edit" button next to the subject you wish to modify.
   - Update the input fields as needed and click "Save Changes".

3. **Delete a Subject**:
   - Click the "Delete" button next to the subject you want to remove.

4. **View Schedule**:
   - The schedule is displayed in a table format with options to edit or delete each entry.

## Code Overview

The application consists of a single HTML file with embedded CSS and JavaScript:

- **HTML**: Defines the structure of the form and schedule display.
- **CSS**: Provides styling for the form, buttons, table, and overall layout.
- **JavaScript**: Handles adding, editing, deleting, and displaying subjects, as well as managing data in `localStorage`.

## Code Structure

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <!-- Meta tags and title -->
    <style>
        /* CSS styles for body, form, buttons, and table */
    </style>
</head>
<body>
    <!-- Form for managing subjects -->
    <div class="form-container">
        <!-- Input fields and button for adding/updating subjects -->
    </div>

    <!-- Container for displaying schedule -->
    <div class="schedule-container">
        <!-- Table for showing subjects -->
    </div>

    <script>
        // JavaScript functions for handling actions (add, edit, delete)
    </script>
</body>
</html>
