Task 1:

Monefy App Testcases:

Smoke: P0 Scenarios
1.	Verify if the user is able to successfully add an expense made using Cash to a selected category by entering the expense amount on the amount field and note on the Add note field 
2.	Verify if the user is able to successfully add an expense made using Cash to a selected category by entering the expense amount on the amount field and does not enter a note 
3.	Verify if the user is able to successfully add an expense made using Payment Card to a selected category by entering the expense amount on the amount field and note on the Add note field 
4.	Verify if the user is able to successfully add an expense made using Payment Card to a selected category by entering the expense amount on the amount field and does not enter a note 
5.	Verify if the expense added is reflected on the home screen on the Pie chart and the Balance field 
6.	Verify if the user is able to successfully add a new expense by clicking on the Add New Expense button from the Home Screen and select a desired category of expense
7.	Verify if the user is able to successfully add a new income by clicking on the Add New Income button from the Home Screen and select a desired category of income
8.	Verify if the user is able to change the Account type (All Accounts, Cash and Payment Card) from the filter drawer
9.	Verify if the expenses and income get displayed on the Home Screen based on the Account type selection
10.	Verify if the user is able to edit the expense recorded and the balance is updated successfully
11.	Verify if the user is able to delete the expense recorded and the balance is updated successfully
12.	Verify if the user is able to edit the income recorded and the balance is updated successfully
13.	Verify if the user is able to delete the income recorded and the balance is updated successfully
14.	Verify if the user is able to transfer amount from Payment Card to Cash and the balance is updated successfully
15.	Verify if the user is able to transfer amount from Cash to Payment Card and the balance is updated successfully
16.	Verify if the user is able to add a New Account type to the Accounts from the App bar menu
17.	Verify if the user is able to add a recurring expense 
18.	Verify if the user is able to add a recurring income 

Functional Test Cases:
Filter Drawer:
1.	Verify if the Filter drawer opens when the user clicks on the Filter button on the Home screen – P1
2.	Verify if the user is able to change the Account type and gets updated on the Home screen – P2
3.	Verify if the user is able to see the newly added account type on the accounts drop down  - P2

4.	Verify if the user is able to select the current day and Home screen gets updated with the current day’s expenses and incomes  - P2
5.	Verify if the user is able to select the current week’s expenses and incomes and Home screen gets updated with the current week’s expenses and incomes – P2
6.	Verify if the user is able to select the current month’s expenses and incomes and Home screen gets updated with the current month’s expenses and incomes – P2
7.	Verify if the user is able to select the current year’s expenses and incomes and Home screen gets updated with the current year’s expenses and incomes – P2
8.	Verify if the user is able to view all the expenses and income until the current date by selecting the All option- P2
9.	Verify if the user is able to select a particular date to view the expenses and income – P2
10.	Verify that the opened Filter drawer closes when the Filter button is clicked again – P3

New Transfer:
1.	Verify if the user lands on the New Transfer Screen when the user clicks on the New Transfer button on the Home screen – P1
2.	Verify if the user is able to change the From account from which the fund has to be transferred – P2
3.	Verify if the user is able to change the To account to which the fund has to be transferred – P2
4.	Verify if “0” is displayed by default on the Amount field – P3
5.	Verify if the Numeric Keypad pops up when the user taps on the Amount field – P2
6.	Verify if the user is able to key in amount to be transferred by clicking on the digits in the numeric keypad – P2
7.	Verify if the user is allowed to enter with decimal point and with only two decimal precisions – P3
8.	Verify if the user is allowed to enter only 9 digits in the amount field – P3
9.	Verify if the user is able to perform Arithmetic Operations (addition, subtraction, multiplication and division) on the amount entered and the correct calculation gets reflected in the amount field – P3
10.	Verify that the Keyboard pops up when the user taps on the Add Note field – P2
11.	Verify if the user is able to add a note in the Add Note field for the New Transfer – P3
12.	Verify if the user is able to successfully transfer the funds between accounts with the Amount field and Add Note field (optional field) entered and the balance on the home screen is updated along with the pie chart – P1
13.	Verify if the user is able to successfully transfer the funds between accounts with only the Amount field entered and the balance on the home screen is updated along with the pie chart – P1
14.	Verify if the Numeric Keyboard pops open when the user taps on the Keyboard icon – P1
15.	Verify if the user is able to delete the entered amount in the Amount field by clicking on the delete button – P2
16.	Verify that the user is not allowed to enter “0” in the amount field – P2
17.	Verify if the current date is displayed on the New Transfer Screen – P2
18.	Verify if the Date picker opens when the user clicks on the Date field – P2
19.	Verify if the user is able to change the date on the New Transfer Screen – P2
20.	Verify that the numeric keypad closes when the Back button is clicked – P3
21.	Verify that the user is taken back to the Home screen when the Cancel button is clicked and the transfer was not made – P1

App Bar Menu:
1.	Verify that the App bar opens when the App Bar button is clicked – P1
2.	Verify that the App bar displays the Categories, Accounts, Currencies and Settings – P2
3.	Verify that the opened App bar closes when the App bar button is clicked again – P3
4.	Verify if the user is able to change the App settings from the Settings option – P2
5.	Verify if the user is able to change the currencies from the Currencies option – P3


-Categories:
1.	Verify if the user is able to edit the names of the Expense and Income categories – P2
2.	Verify if the user is able to delete the Expense and Income categories by clicking on the delete button – P2
3.	Verify if the user is able to merge two categories – P3
4.	Verify if the user is able to disable a category – P3
5.	Verify if the user is able to enable a category – P3
6.	Verify that the Category Name field blinks red when the name is deleted and Done button is clicked – P3 Error Scenario

-Accounts:
1.	 Verify if the user is able to successfully Add a New Account with the Account  Name with the currency choice, Exchange rate, Initial account balance, Initial balance date by entering valid data and clicking on the Add button – P1
2.	 Verify if the user is Add an account with no Initial account balance entered – P3
3.	Verify if the user is able to choose an image for the Account type – P3
4.	Verify if the user is able to choose to include the account in the balance by turning on the radio button – P3
5.	Verify if the user is able to choose to not include the account in the balance by turning on the radio button – P3
6.	Verify that the currency type is UD Dollar by default – P2
7.	Verify that the Initial Balance date is current date by default – P2
8.	Verify that the Date picker opens when the user clicks on the Initial Balance date field – P3
9.	Verify if the user is able to change the Initial Balance Date – P3
10.	Verify if the Name field blinks red when the when the Add button is clicked with no name entered – P3 Error Scenario
11.	Verify if the user is taken back to the App bar menu when the Back button is clicked – P3
12.	Verify that the New Account is not created when the Back button is clicked – P1








Home Screen:
1.	Verify if the user is able to add a New Expense by clicking on the Add Expense button on the Home Screen – P1
2.	Verify if the user is able to add a New Income by clicking on the Add Income button on the Home Screen – P1
3.	Verify if the categories get deleted on the Home screen when the user deletes it from the Categories option in the App bar menu – P1
4.	Verify if the categories get added on the Home screen when the user adds it from the Categories option in the App bar menu – P1
5.	Verify if the Home screen is updated with the current day, week, month, year or specific date display as per the selection made from the Filter drawer – P2
6.	Verify if the Home Screen gets updated with the Expense and Income details based on the date selection – P2
7.	Verify if the Balance is updated as per the expense and income added – P1
8.	Verify if the Pie chart is updated as per the expense and income added – P1
9.	Verify if the Balance is updated as per the expense and income deleted – P1
10.	Verify if the Pie chart is updated as per the expense and income deleted – P1
11.	Verify if the percentage of spending updated under the categories around the pie chart – P1
12.	Verify that the detailed Balance Summary/Split up is displayed when the user taps on the Balance field – P2
13.	Verify if the user is able to edit the account details and balance by tapping on the specific account type – P2
14.	Verify if the user is able to delete the account details and balance by tapping on the specific account type – P2
15.	Verify if the income/credits are displayed in red color – P3
16.	Verify if the expense/debits are displayed in green color – P3
17.	Verify if the opened Balance drawer closes when the user taps on the Balance field – P3
18.	Verify that the pie chart is distributed in the specific colors matching to the category – P3


UI Verification Scenarios: P3 Scenarios
1.	Verify all the UI elements are displayed on the Home Screen when the application is launched 
UI Elements:
a.	Title of the application
b.	Account type
c.	Filter Option
d.	New Transfer option
e.	App bar menu
f.	Current month
g.	Expense Categories
h.	Balance field
i.	Adding new expense button
j.	Adding new income button
2.	Verify the UI Elements on the Filter drawer
3.	Verify the UI Elements on the New Transfer Screen
4.	Verify the UI Elements on the Balance drawer
5.	Verify the UI Elements on the New Expense Screen
6.	Verify the UI Elements on the New Income Screen
7.	Verify the UI Elements on the App bar Screen



Task 2: 

GNU Cash App Test Cases:

Scenarios:
1.	Verify if the user is able to view the Recent, All and Favorite accounts – P2 Automated
2.	Verify if the user is able to create a new account with default currency set and account description added – P0 Automated
3.	Verify if the user is able to delete an Account – P0 Automated
4.	Verify if the user is able to create a new account with no account description added – P2 Automated
5.	Verify if the user is able to choose an Account type while creating a new account – P1 Automated
6.	Verify if the user is able to pick a color for the Account while creating it – P3 Not Automatable
7.	Verify if the inline error text is displayed when user clicks on the Save button without entering the Account name on the Create Account screen – P2 Automated
8.	Verify if the Create Account screen is closed when the user clicks the close button and the Account is not created successfully – P2 Automated
9.	Verify if the user is able to add a Sub-Account to the Account – P2 Automated
10.	Verify if the user is able to edit an Account – P1 Automated
11.	Verify if the user is able to search for an Account – P2 Automated
12.	Verify if the user is able to add a New Transaction to the Account – P2 Automated
13.	Verify if the user is able to add an Account as Favorite Account – P3 Automated
14.	Verify if the user is able to view the Reports by clicking on the Reports button on the Hamburger Menu – P2 Automated
15.	Verify if the transaction is not exported when the close button is clicked – P2 Automated
16.	Verify if the user is able to Export the transactions – P1 Automated
17.	Verify if the user is able to view the Scheduled Actions – P2 Automated
18.	Verify if the user is able to delete a transaction after being exported – P3 Yet to be Automated
19.	Verify if the user is able to create a recurring transaction schedule – P2 Automated
20.	Verify if the account is not deleted when the Cancel button is clicked on the Delete Confirmation Alert – P2
21.	Verify if the user is able to view the summary of the Sub-Accounts – P2 Yet to be Automated
22.	Verify that the color of the Account is displayed as per the color choice made during the Account creation – P3 Yet to be Automated
23.	Verify if the user is able to navigate to Manage the Books – P2 Yet to be Automated
24.	Verify if the user is able to add new Books – P2 Yet to be Automated
25.	Verify if the user is able to rename the Books added – P3 Yet to be Automated
26.	Verify if the user is able to delete the Books added – P3 Yet to be Automated

UI Scenarios: P3
27.	Verify the UI elements on the Create Account Screen - Automated
28.	Verify the UI elements on the Sub Account Screen - Yet to be Automated
29.	Verify the UI elements on the New Transaction Screen - Yet to be Automated























