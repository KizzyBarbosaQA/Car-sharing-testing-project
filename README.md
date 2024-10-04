# Car Sharing Testing Project

## Overview
This project involves testing the car sharing functionality in two different environments and following a structured approach to ensure that the requirements and design are properly validated. It includes creating checklists, test cases, and performing functional and layout tests.

## Testing Steps

### 1. Checklist for the Booking Form Layout
The first step is to create a checklist to test the layout of the booking form.

- Choose the "Luxury" ride option.
- Check the spelling, arrangement, and appearance of the elements.
- Validate the pop-ups, such as "Car reserved", "Are you sure you want to cancel your trip?" and "Trip canceled".
- **Note**: Field validation and the "Add driver's license", "Payment method", and "Add card" windows do not need to be tested.

You should place the checklist in the first tab of your spreadsheet called: **"1. Layout Checklist"**.

### 2. Checklist for the "Payment Method" and "Add Card" Windows
Create a checklist to test the functionality of the payment-related windows. Use techniques such as equivalence class partitioning and boundary value analysis.

- Make sure to test positive and negative scenarios.
- Base the checklist on the requirements sections related to "Payment Method" and "Add Card".

Place the checklist in the second tab of the spreadsheet: **"2. Checklist for 'Payment Method' and 'Add Card'"**.

### 3. Test Cases for the "Book" Button
Develop test cases for the "Book" button, which should display information about the trip distance and time.

- Refer to the requirements for the "Book" button.
- Test positive and negative scenarios.
- **Note**: It is not necessary to verify whether the distance and time data are calculated correctly or if the free waiting timer works.

Add the test cases to the third tab of the spreadsheet: **"3. Test Cases for the 'Book' Button"**.

### 4. Test Cases for the Car Rental Function
Test the car rental functionality based on the requirements in the "Book Car" section. Be sure to include both positive and negative tests.

- Analyze the car rental scenarios.

Test cases should be added to the fourth tab of the spreadsheet: **"4. Test Cases for Car Rental"**.

### 5. Running the Tests and Bug Reporting
Now it's time to execute the tests using the checklists and test cases you've created. Test the application in two environments:

- **Google Chrome** with a 800x600 screen resolution
- **Firefox** with a 1920x1080 screen resolution

- Perform the layout test in both environments.
- Verify the application logic in just one environment.
  
- **Note**: The 30-second timer for the driver's license verification is not implemented, so it is not necessary to wait during the tests.

Mark the test results as **PASSED** or **FAILED**. If a test fails, document the bug in Jira and include the bug report link in the corresponding column of the spreadsheet.

---

## Project Structure

- **Test Spreadsheet**: Contains the checklists and test cases.
  - Tab 1: Layout Checklist
  - Tab 2: Checklist for "Payment Method" and "Add Card"
  - Tab 3: Test Cases for the "Book" Button
  - Tab 4: Test Cases for Car Rental

---

## Technologies Used

- **Testing Tools**: Jira for bug reports.
- **Browser Environments**: Google Chrome and Firefox.

## Test Environments:
- **Google Chrome**, screen resolution 800x600
- **Firefox**, screen resolution 1920x1080

 ![Jira](car-sharing-testing-project/imagem/jira.jpeg)
