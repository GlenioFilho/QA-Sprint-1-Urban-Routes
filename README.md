# QA Sprint 1 - Urban Routes Regression Testing

## 🛠️ Project Description
In this project, we conducted a **regression test** for the **Urban Routes** application. This application calculates the routes and estimates the time and cost of travel for different transportation types. As a QA analyst, the goal was to identify bugs in the application by running the test cases and reporting any discrepancies between expected and actual results.

The **Urban Routes** app has a simple interface with two address fields ("From" and "To"), and three transportation modes ("Optimal", "Flash", "Personal"). Additionally, users can choose between various types of transportation, such as car, walking, taxi, bike, scooter, and car-sharing.

After users input their start and end locations, the app calculates the time and total cost of the trip using a specific algorithm.

## 🎯 Objective
The goal of this project was to:
- Execute regression test cases on the **Urban Routes** application.
- Identify and report any bugs found during testing.
- Ensure that the application's features, such as route calculation and transportation modes, work as expected after recent changes.

## 🚀 Tools Used
- **Google Sheets**: Used for documenting test cases and bug reports.
- **Manual Testing**: Executed using Google Chrome.
- **Bug Reporting**: Reports were created using the "Bug Reports" tab in the Google Sheets model.

## 📝 Key Tasks and Workflow
1. **Start the Server**:
   - Initialize the application by starting the server. This may take up to 2 minutes.
   - If the server is not fully initialized, a message will appear asking to wait until it is ready.

2. **Execute Test Cases**:
   - Follow the test cases listed in the provided model (Google Sheets).
   - Test cases include different scenarios such as entering start and destination addresses, selecting transportation modes, and verifying the time and cost calculations.
   - For each test case, document the status (Pass, Fail, or Ignored) and note any bugs.

3. **Create Bug Reports**:
   - If a test case fails, create a bug report in the Google Sheets document, filling in all required fields, including:
     - Bug ID
     - Title
     - Steps to Reproduce
     - Expected and Actual Results
     - Priority (e.g., Blocker, Critical, Major, Minor, Trivial).

4. **Use the Latest Version of Google Chrome**:
   - Ensure to use the most up-to-date version of Google Chrome for testing the application.

## 🔗 How to Contribute
Feel free to fork this repository, submit a pull request, or suggest improvements. Contributions to improve the documentation, test cases, or bug reports are always welcome!

## 🧪 Created by GlenioFilho as part of QA training.
