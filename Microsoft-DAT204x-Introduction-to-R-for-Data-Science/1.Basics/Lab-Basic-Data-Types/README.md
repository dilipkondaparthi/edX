##1. Basic Data Types
* # What is the answer to the universe?
* my_numeric <- 42
* # The quotation marks indicate that the variable is of type character
* my_character <- "forty-two"
* # Change the value of my_logical
* my_logical <-FALSE

##2. Back to Apples and Oranges
* # Assign a value to the variable called my_apples
* my_apples <- 5 
* # Print out the value of my_apples
* my_apples       
* # Assign a value to the variable my_oranges and print it out
* my_oranges <- 6 
* my_oranges 
* # New variable that contains the total amount of fruit
* my_fruit <- my_apples + my_oranges 
* my_fruit

##3. What's that data type?
* 4. a's class is numeric, b is a character, c is a logical.

##4. Coercion: Taming your data
* # Create variables var1, var2 and var3
* var1 <- TRUE
* var2 <- 0.3
* var3 <- "i"
* # Convert var1 to a character: var1_char
* var1_char <- as.character(var1)
* # See whether var1_char is a character
* is.character(var1_char)
* # Convert var2 to a logical: var2_log
* var2_log <- as.logical(var2)
* # Inspect the class of var2_log
* class(var2_log)
* # Coerce var3 to a numeric: var3_num
* var3_num <- as.numeric(var3)

##5. Coercion for the sake of cleaning
* # Convert age to numeric: age_clean
* age_clean <- as.numeric(age)
* # Convert employed to logical: employed_clean
* employed_clean <- as.logical(employed)
* # Convert salary to numeric: salary_clean
* salary_clean <- as.numeric(salary) 


