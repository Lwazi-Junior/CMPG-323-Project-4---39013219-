# CMPG-323-Project-4---39013219-

# NWU Tech Trends Telemetry Portal - User Acceptance Testing Automation

This project implements a **Robotic Process Automation (RPA)** bot using **UiPath** to automate User Acceptance Testing (UAT) for the NWU Tech Trends Telemetry Portal. The automation bot reads input data from an Excel file, submits it to the web application, and verifies if the records are successfully created.

## Prerequisites

- **UiPath Studio**: Install [UiPath Studio Community Edition](https://www.uipath.com/community).
- **GitHub**: Clone this repository to your local machine.
- **Excel File**: Ensure the test data is prepared in the correct format (e.g., columns for Name, Date, etc.).

## How to Use the Automation Bot

1. Clone this repository to your local machine:
    ```bash
    git clone https://github.com/YourUsername/CMPG-323-Project-4.git
    ```

2. Open **UiPath Studio** and load the project.

3. Update the **Excel file** (`InputData.xlsx`) with the input data for testing.

4. Run the automation in **UiPath Studio** or trigger it from **UiPath Orchestrator**.

5. After the bot finishes, the results (Pass/Fail) will be recorded in the Excel file (`OutputData.xlsx`).

## Project Structure

- `Main.xaml`: The main workflow that orchestrates the automation process.
- `InputData.xlsx`: The Excel file containing test data.
- `OutputData.xlsx`: The Excel file where test results (Pass/Fail) are recorded.
- `ReadMe.md`: This file contains information about the project, including how to set it up and use it.

## Next Steps

- Explore additional test scenarios by modifying the input data in the Excel file.
- Integrate with other UiPath workflows for extended automation capabilities.
