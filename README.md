# Personal-Budget-Planning-wpf
#### ============TABLE OF CONTENTS===============

1. Overview.
2. Features of the project.
3. Development dependencies.
4. Technology + software required.
5. Implementation of feedback from task 2.
6. Running of the project.
7. Contributors and sources.

#### =================OVERVIEW===================

This interactive application is a personal budget planning application that is used to solve the problem of not being able to fully calculate and plan out your budget. This application provides an easier seamless way of calculating all of the important aspects of creating a budget, by asking the user to input their expenses, monthly income, tax deductions and also whether they are renting and paying a monthly rental or they are buying and paying a monthly repayment. The application will then ask the user if they want to purchase a car and whether or not they would like to save up for something special. The application uses the users input and calculates how much is available at the end of the month along with how much they actually pay on either their monthly rental or monthly repayment.

The motivation behind the project was to be able to create a user-friendly application that won't confuse the user along with the coder who wrote this program. From personal experience a lot of people do struggle with being able to plan out their finances and create a budget because it is so time consuming. With this application I just wanted to create something that will be less time consuming for the user and as accurate as possible. A little something to make your life easier.               


#### ============FEATURES OF THE PROJECT==============
This project includes the following:

1. Welcome page with a start button.
2. Window to request the user to enter their monthly income before deductions and tax deducted.
3. Window to request the user to enter their monthly expenses.
4. Ability to calculate the users monthly money available if they choose to rent and their monthly home loan repayment if they choose to buy property.
5. Ability to calculate loan repayments of a vehicle if the users chooses to purchase a vehicle.
6. Regular notices of whether your expenses are over your monthly income.
7. Ability to calculate how much the user needs to save per month in order to reach their savings goal if they had chosen to save up for something special.
#### ============DEVELOPMENT DEPENDENCIES=============

1. Microsoft.NETCore.App
2. Visual studio 2019.
3. Visual studio windows presentation framework.
#### ===========TECHNOLOGY + SOFTWARE REQUIRED==========
1. A laptop that supports windows10 and microsoft with atleast 2GB of RAM space.
2. Not supported on: 
   Linux 
   MS-DOS (IBM PC DOS) 
   Windows 3.1 
   Windows NT 3.51 
   Windows 9x 
   Windows NT 4.0.
3. Microsoft visual studio 2019 version 16.9.4.
4. Microsoft.NET framework version 4.8.04084..
5. Windows presentation framework.
#### =========IMPLEMENTATION OF THE FEEDBACK FROM TASK 2=======
Hi there,

I penalized you for not taking care of special characters when validating your inputs and you did not get full marks for coding standard (No one did)
#### ===================================================
In my task 2 I had validated for strings and negative numbers through a try catch block, however I did not validate for special characters such as "@,$,#,%". This is very important because the user can enter anything they like to enter and I need to have measures in place that will prevent this from happening because it would essentially disrupt the flow of code including calculations. In order to fix this mistake, in my task 3 (wpf) I had a try catch block that will throw an exception/error to the user if they enter, strings, characters and negative numbers. In addition to the try catch block I used a method called Regex() that prohibts the user from having the ability to use the letters on the keyboard, the only thing that will work on the keyboard is the numbers. This forces the user to enter just numbers and nothing else.

In my task 2 I did take notice of the fact that my code does have alot of comments and that is not in line with the coding standard, my code was also not clean in terms of structure. In order to fix this, in my task 3 (wpf) I made sure that the structure of my code is clean, there are spaces between sections of code and everything is aligned to the left hand side of the margin. The comments in my code as well have been reduced, with my code sticking to the same naming convention throughout.
#### ============RUNNING OF THE PROJECT===================

1. Open the one drive link.
2. Download the file on the one drive.
3. In the file explorer unzip the zipped file by extracting it.
4. Unzip the PersonalBudgetPlanning_wpf file by extracting it.
5. Click the unzipped PersonalBudgetPlanning_wpf file.
6. Select the solution file called PersonalBudgetPlanning_wpf.
7. Visual studio 2019 will open now.
8. Go to the MainWindow.xaml.cs and click the green button called start on the visual studio toolbar to run the program.
9. The programme start with a welcome page and a start button it will also ask you to input data, all of this needs to be in the form of a decimal number.
#### =============CONTRIBUTORS + SOURCES===================

1. Reneilwe-Kutlwano Motlhabi.
2. https://www.geeksforgeeks.org/.
3. Troelsen, A. and Japikse, P. 2017. Pro C# 7 with .NET and .NET Core. 8th ed. Minnesota and Ohio: Andrew and Philip.
4. https://www.w3resource.com/csharp-exercises/array/csharp-array-exercise-10.php. 

