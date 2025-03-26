# AI With Python - Tutorial Calendar

![Calendar Preview](https://i.imgur.com/JQhGx8L.png)

A responsive web application that displays the tutorial schedule for the "AI With Python" course, including both calendar and list views with CSV export functionality.

## Features

- 📅 **Interactive Calendar View**
  - Monthly grid layout showing all scheduled sessions
  - Color-coded days with tutorial sessions
  - Session details on hover

- 📋 **Complete Session List**
  - Tabular view of all tutorial sessions
  - Sortable by date, day, or session type

- ⬇️ **CSV Export**
  - One-click download of full schedule
  - Formatted for easy import to Outlook/Google Calendar

- 🎨 **Responsive Design**
  - Works on desktop, tablet, and mobile
  - Consistent styling with the main learning platform

## Installation

No installation required! This is a standalone HTML file that can be opened directly in any modern web browser.

1. Download the `index.html` file
2. Open it in your preferred browser (Chrome, Firefox, Edge, etc.)

## Usage

### Viewing the Calendar

1. Open the webpage in your browser
2. Click the "Tutorial Calendar" tab
3. Browse through the months using the scrollable interface

### Using the Session Table

1. Scroll down to the "All Sessions" section
2. View all sessions in a sortable table format
3. Click on column headers to sort by that field

### Exporting to Calendar Apps

1. Click the "Download Schedule as CSV" button
2. Save the file to your computer
3. Import into your preferred calendar application:
   - **Google Calendar**: Settings → Import & Export
   - **Outlook**: File → Open & Export → Import/Export
   - **Apple Calendar**: File → Import

## Data Format

The calendar uses the following session structure:

```javascript
{
  date: 'DD/MM/YYYY',  // Session date
  day: 'DayName',      // Day of week
  time: 'HH:MM AM/PM - HH:MM AM/PM', // Session time
  type: 'SessionType'  // e.g., "Saturday Session"
}