# Plan for Work Schedule App

Author: Adrian Tarantino

Created: September 18, 2022
Last Updated: September 18, 2022

### Intentions of The Project

- Learn how to use Yew
- Learn how to use Rust with Google Sheets
- Make it easier to remember my work schedule
- Make it easier to update my work schedule

### Core functionality

- Grab schedule from my work spreadsheet (the one I made on Google Sheets)
- Turn each shift into a struct containing
    - Job (Guarding, Cash, Instructing a Level)
    - Pool (Almost)
    - Time
    - Pay
    - Totals
- Create a list of five to ten lessons (five if it takes too long)
    - This will allow me to scroll between the different days

##### Optional
- Allow users to update or edit days
- Allow users to create work schedule blocks

### Similar Projects
> 1. [stocks_app](https://github.com/AdrianTheHacker/stocks_app)
    - Displays the prices of:
        - Bitcoin
        - Etherium
        - Dogecoin
    - Uses Yew to create the frontend
    - Made by me (AdrianTheHacker)

### Tools
##### Languages
> 1. Rust

##### Reading / Writing to the spreadsheet
> 1. Either sheets or serde_sheets
    - Both of these are used for managing google spreadsheets in rust

##### Frontend
> 1. Yew
    - A frontend framework
    - Works sort of like React except with Rust instead of JaveScript

##### Other Dependencies
None at the moment


### Implementation Plan
##### Step 1
This step mainly focuses on the frontend

1. Using the template, create an example HTML file

2. Convert the HTML file into a Yew app
    - Turn all the parts into different components

##### Step 2 
This step mainly focuses on Reading the spreadsheet

1. Grab five to ten schedule blocks (Each day is divided into a block)

2. Turn each block into a struct containing:
        - Job (Guarding, Cash, Instructing a Level)
        - Pool (Almost)
        - Time
        - Pay
        - Totals

3. Display each struct as a component on the webpage

##### Step 3
1. Implement the buttons that allow you to scroll between the days

##### Step 4 (Optional Features)
1. Implement way of editing schedule blocks or even adding new blocks

2. Deploy the app on the cloud
