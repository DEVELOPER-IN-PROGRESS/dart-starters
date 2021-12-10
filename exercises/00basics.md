void main() { }  - This function is the main entry point to our application
Dart is type safe language.

# Fundamental data types
String , int (upto 64 bit precision)  , bool , double , float

# Basic String Operation
 ### printing to console  - print(' ')
 ## mixing string and variables - print('Hey Everyone My Name is' + firstName + lastName)
 or print('Hey Everyone My Name is  $firstName  $lastName')
 ${variable + expressions}
in order to escape escape characters  like \' \\ which maybe used inside strings  we can use print(r'string')
i.e r at the beginning indicates if it is a raw string or not

Multiline Strings -- print(""" this is
a multiline string
without using \n character """ )

# Basic string Methods
Tip :  we need to add () at end of every function to execute it
toUpperCase() - To convert the whole string to uppercase
toLowerCase() - To convert the whole string to lowercase
.contains('string')  - To check whether a string contains a substring .it putputs true or false
.replaceAll( 'string to replace' , 'preferred string') - Find and replace all occurence of the string to be replaced . Case sensitive !!

toString() - Convert any datatype to String.
isNotEmpty() -

statements do not hold a value at runtime whereas expressions hold a value at runtime

// - single line comment
/* ......              */ -- Multiline comments

#  DART TYPE SYSTEM
the var keyword can hold any type of data but once assigned it can only hold that particular datatype and nothing else 