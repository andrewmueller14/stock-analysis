## OVERVIEW: VBA Stock Analysis
### Purpose
-The purpose of stock market analysis is to loop all code through a data set in a single macro. We refactor to clean up the messier code that was initially used to run 
the dataset. We clean the data because it is easier for others to read and edit, which is important when more than one person is editing the code.
We will also compare run time speed to see if refactoring affects computer performance versus our inital code.

### Results
-The initial script used on the data was broken up into more than one macro, while the refactored program was in a single macro.  Suprisingly, the refactored code ran the script slower than the initial code.


#### Unfactored Time 2017

-![Original_Green_Stock_2017](https://user-images.githubusercontent.com/75653235/104243960-105e3800-5427-11eb-8bf1-53fff437a5f8.PNG)

#### Unfactored Time 2018

-![Original_Green_Stock_2018](https://user-images.githubusercontent.com/75653235/104244000-2966e900-5427-11eb-970a-e9bc89c74550.PNG)

#### Refactored Time 2017

-![VBA_Challenge _2017](https://user-images.githubusercontent.com/75653235/104243324-038d1480-5426-11eb-94eb-503fc856c37d.PNG)
 
#### Refactored Time 2018 

-![VBA_Challenge_2018](https://user-images.githubusercontent.com/75653235/104243580-62eb2480-5426-11eb-9936-04b1441346a2.PNG)

### Summary

#### Advantages of Refactoring:

-Code is well structured, making it easier to read and find errors.

-Code is not running on underlying code that could cause problems when edited.

#### Disadvantages of Refactoring:

-Code runs faster when it is broken up in separate macros.

-No need for duplicate lines of code in one function. 

-Duplicate logic can be better placed in a new macro and can call from prior functions.
