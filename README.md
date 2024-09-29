# NWU Tech Trends Telemetry Portal - User Acceptance Testing Automation

This project implements a **Robotic Process Automation (RPA)** bot using **UiPath** to automate User Acceptance Testing (UAT) for the NWU Tech Trends Telemetry Portal. The automation bot reads input data from an Excel file, submits it to the web application, and verifies if the records are successfully created.

## Prerequisites

- **UiPath Studio**: Install [UiPath Studio Community Edition](https://www.uipath.com/community).
- **GitHub**: Clone this repository to your local machine.
- **Excel File**: Ensure the test data is prepared in the correct format (e.g., columns for Name, Date, etc.).

## Installation Instructions

1. Download and install **UiPath Studio**.
2. Clone this repository:
    ```bash
    git clone https://github.com/YourUsername/CMPG-323-Project-4.git
    ```
3. Open **UiPath Studio** and load the project.
4. Update the **Excel file** (`InputData.xlsx`) with the input data for testing.

## How to Use the Automation Bot

1. Run the automation in **UiPath Studio** or trigger it from **UiPath Orchestrator**.
2. After the bot finishes, the results (Pass/Fail) will be recorded in the Excel file (`OutputData.xlsx`).

## Project Structure

- `Main.xaml`: The main workflow that orchestrates the automation process.
- `InputData.xlsx`: The Excel file containing test data.
- `OutputData.xlsx`: The Excel file where test results (Pass/Fail) are recorded.
- `ReadMe.md`: This file contains information about the project, including how to set it up and use it.

## Troubleshooting

- **Issue**: The bot fails to input data into the web form.
  - **Solution**: Ensure that the web application is accessible and that the fields in the form correspond to the column names in the Excel file.

- **Issue**: The Excel file is not found.
  - **Solution**: Double-check the file path in the `Excel Application Scope` activity and ensure the file is in the correct directory.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Thanks to the **UiPath Academy** for the invaluable resources that guided the development of this automation.
- Special thanks to the community forums for troubleshooting help and inspiration.

## Next Steps

- Explore additional test scenarios by modifying the input data in the Excel file.
- Integrate with other UiPath workflows for extended automation capabilities.
