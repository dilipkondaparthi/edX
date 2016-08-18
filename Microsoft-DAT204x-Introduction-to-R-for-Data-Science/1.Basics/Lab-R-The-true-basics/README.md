##1. How it works
* 3 + 4
* 6 + 12

##2. Documenting your code
* # Calculate 3 + 4
* 3 + 4
* # Calculate 6 + 12
* 6 + 12

##3. Little arithmetics with R
* # Addition
* 5 + 5 
* # Subtraction
* 5 - 5 
* # Multiplication
* 3 * 5
* # Division
* (5 + 5) / 2 
* # Exponentiation
* 2^5
* # Modulo
* 28%%6

##4. R's pros and cons
* 3.statements (1) and (5) are correct; the others are false.

##5. Variable assignment
* # Assign the value 42 to x
* x <- 42
* # Print out the value of the variable x
* x

##6. Variable assignment (2)
* # Assign the value 5 to the variable called my_apples
* my_apples <- 5
* # Print out the value of the variable my_apples
* my_apples

##7. Variable assignment (3)
* # Assign a value to the variables my_apples and my_oranges
* my_apples <- 5

* my_oranges <- 6
* # Add these two variables together and print the result
* my_apples+ my_oranges
* # Create the variable my_fruit
* my_fruit <-  my_apples+ my_oranges

##8. The workspace
* # Clear the entire workspace
* rm(list = ls())
* # List the contents of your workspace
* ls()
* # Create the variable horses
* horses <- 3
* # Create the variable dogs
* dogs <- 7
* # Create the variable animals
* animals <- horses + dogs
* # Inspect the contents of the workspace again
* ls()
* # Remove dogs from the workspace
* rm(dogs)
* # Inspect the objects in your workspace once more
* ls()

##9. Build and destroy your workspace
* #Create the variables r and R
* r <- 2
* R <-6
* # Calculate the volume of the donut: vol_donut
* vol_donut <- 2 * pi^2 * r^2 * R
* # Remove all intermediary variables that you've used with rm()
* rm(r)
* rm(R)
* # List the elements in your workspace
* ls()
