# Semester_Project
NAME : AMO GIDEON

INDEX NUMBER : UEB3222422

COURSE / CLASS : BSC INFORMATION TECHNOLOGY C


                                    PROJECT DESCRIPTION
This USSDsystem code header files for input/output operations (<iostream>) and exception handling (<stdexcept>).
The code defines several functions,each representing a specific action that the user can take within the USSD menu system.
Balance Inqiury() : displays the user's current balance,which is hardcoded to $100 in this eexample.
ProfileViewing() : displays the user's profile information,including name,email and phone number.
DataPlanActivation() : simulates the activation of a data plan and displays a success message.
TransactionHistory() : displays a sample transaction history with two transaction and thier corresponding amounts and descriptions.
AccountRecharge() : prompts the user to input an amount for account recharge,then displays a message indicating the recharge amount.
CustomerSupportAccess() : displays a message indicating that user is being connected to a customer support representative.
LanguageSelection() : provides the user with the option to select between English,Freench,Spanish and Twi languages,prints a message indicating the selected language and throws an exception for invalid selections.
The 'mainMenu()' function  defines the main menu of the USSD system which give the user a list of prompt option for the user to choose from corresponding to the number of the user's chioce.it uses a 'switch' statement to handle the different menu options and provides option to exit the program.
The 'main()' function wraps the execution of the 'mainMenu()' function in a try-catch block to handle any exceptions that might occur during the programs execution.
In wrap detail,this code create a simple simulation of a USSD menu system,allowing user's to navigathrough different options and perform actions within the simulated mobile service environment.  
