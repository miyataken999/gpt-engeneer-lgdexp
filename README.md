# Google Sheets to Google Calendar Registration Program

This program registers Google Sheets content to Google Calendar.

## How to use

1. Create a new Google Sheets document.
2. Create a new Google Calendar.
3. Set the calendar ID in the `registerSheetToCalendar` function.
4. Run the `registerSheetToCalendar` function to register the sheet content to the calendar.
5. Use the `registerSheetToCalendarJSON` function to return the result of registration as JSON.

## Note

* Make sure to replace `your_calendar_id` with your actual calendar ID.
* This program assumes that the sheet has the following format:
  | Title | Start Date Time | End Date Time |
  | --- | --- | --- |
  | Event 1 | 2023-03-01 10:00 | 2023-03-01 11:00 |
  | Event 2 | 2023-03-02 14:00 | 2023-03-02 15:00 |
  ...