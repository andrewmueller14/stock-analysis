# stock-analysis/VBA-Challenge:


##Purpose:

The purpose of stock market analysis is to loop all code through a data set in a single macro. We refactor to clean up the messier code that was initially used to run 
the dataset. We clean the data because it is easier for others to read and edit, which is important when more than one person is editing the code.
We will also compare run time speed to see if refactoring affects computer performance versus our inital code.

##Results:

The initial script used on the data was broken up into more than one macro, while the refactored program was in a single macro.  Suprisingly, the refactored code ran the script slower than the initial code, shown below. 
 
##Summary:

Advantages of Refactoring:
-Code is well structured, making it easier to read and find errors.
-Code is not running on underlying code that could cause problems when edited.

Disadvantages of Refactoring:
-Code runs faster when it is broken up in separate macros.
-No need for duplicate lines of code in one function. 
-Duplicate logic can be better placed in a new macro and can call from prior functions.
