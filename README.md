# Daily Diary Console Application

## Overview

The Daily Diary Console Application allows users to manage a daily diary text file. Users can read, add, delete, count, and search diary entries through a simple console interface.

## Features

- **Read Diary**: Display all entries in the diary.
- **Add Entry**: Add a new entry with a specified date and content.
- **Delete Entry**: Delete an entry based on the specified date.
- **Count Lines**: Count the total number of lines in the diary.
- **Search Entries**: Search for entries based on a specified date.

## Usage

1. **Run the Application**: Execute the application from the console.
2. **Choose an Option**: Select an option from the menu to perform the desired action.

### Menu Options

1. **Read Diary**: Displays all entries in the diary.
2. **Add Entry**: Prompts for a date (YYYY-MM-DD) and content to add a new entry.
3. **Delete Entry**: Prompts for a date (YYYY-MM-DD) to delete the corresponding entry.
4. **Count Lines**: Displays the total number of lines in the diary.
5. **Search Entries**: Prompts for a date (YYYY-MM-DD) to search for entries.
6. **Exit**: Exits the application.

## Date Format

All dates must be in the `YYYY-MM-DD` format. The application validates the date format before performing any operations.

## Error Handling

The application includes error handling for file operations and invalid user inputs.

## Unit Tests

Unit tests are provided using Xunit to verify the core functionalities of the application.

## License

This project is licensed under the MIT License.
