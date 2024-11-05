# Pet Chooser Game - Enhanced Version

This project is an upgraded **Pet Chooser** program, allowing users to interact with a pet database, view pet details, and edit specific pet information (name and age) using Python and MySQL. 

## Getting Started

1. **Clone the Project**: Clone this repository to a new PyCharm project.
2. **Database Setup**: Ensure you have the `pets` database configured and connection credentials stored in the `creds` module.
3. **Run the Program**: Start the program to begin interacting with the pets in the database.

## Features and Instructions

### Initial View

When the program starts:
1. The program lists all pets from the database and prompts the user to choose a pet by entering its ID number.
2. The user can quit the program at any time by typing `Q` or `q`.

### Pet Information

Once a pet is chosen, the program displays:
- The pet's name, type, age, and owner.

The user is then asked whether they would like to continue, edit the pet’s information, or quit the program.


- **`Q`** + `[ENTER]`: Quit the program nicely.
- **`C`** + `[ENTER]`: Continue and return to the Initial View, displaying the list of pets again.
- **`E`** + `[ENTER]`: Enter the Edit Process to modify the selected pet’s details.

### Edit Process

If the user chooses to edit a pet:
1. The program prompts the user to enter the ID of the pet they wish to edit.
2. The user can change the pet’s **name** and **age**.
   - Press `[ENTER]` to skip any field without making changes.
   - Type `QUIT` at any point to exit the program without saving changes.


After editing, the program displays a confirmation message and returns to the Initial View.

### Notes
- Only the pet’s name and age can be edited.
- During the Edit Process, typing `QUIT` (case insensitive) at any point will exit the program without saving changes.

## Requirements

- **Python** (version 3.7 or higher)
- **pymysql** library for MySQL connectivity
- **MySQL database** with the necessary `pets` table and `creds` module for database credentials

## Example Usage

Run the program and follow the prompts to view, select, and edit pets. The program offers a flexible user experience with easy quitting and editing options at every step.





