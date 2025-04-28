# EX-16-LEFT-SHIFT-OPERATION
## AIM
To write a C Program to perform the basic left shift operation for 44 integer number with 3 shifts.

## ALGORITHM
1.	Start the program.
2.	Assign values of a and b as 44 and 3.
3.	Use left shift operator (<<) and shift the value of a three times.
4.	Display the result.
5.	Stop the program.

## PROGRAM
```
#include <stdio.h>
int main() {
int a = 44, b = 3;
int result;
result = a << b;
printf("Result after left shifting 44 by 3 positions: %d\n", result);
return 0;

}
```

## OUTPUT
![image](https://github.com/user-attachments/assets/5692ce64-bab7-4528-818b-55f8eea474d1)


## RESULT
Thus the program to perform the basic left shift operation for 44 integer number with 3 shifts has been executed successfully.


# EX-17-TWO-NUMBERS-ARE-EQUAL-OR-NOT


## AIM

Write a C Program to check whether the two numbers are equal or not using simple if statement.

## ALGORITHM

1.	Start the program.
2.	Read two numbers.
3.	If first number is equal to second number, display both are equal.
4.	Otherwise display both are not equal.
5.	Stop the program.

## PROGRAM
```
#include <stdio.h>
int main() {
int num1, num2;
printf("Enter two numbers: ");
scanf("%d %d", &num1, &num2);
if (num1 == num2) {
printf("Both numbers are equal.\n");
} else {
print("Both numbers are not equal.\n");
}
return 0;
}
```
## OUTPUT
 ![image](https://github.com/user-attachments/assets/6cd25148-9eb6-48e1-ba11-7bc801926012)
          
## RESULT

Thus the program to check whether the two numbers are equal or not using simple if statement has been executed successfully
 
 
# EX-18-STRING-LOWERCASE-CONVERSION
## AIM
Write a C Program to convert the given string into lowercase.

## ALGORITHM
1.	Start the program.
2.	Read a string variable.
3.	Using tolower( ) function convert the given string into its lowercase.
4.	Display the result.
5.	Stop the program.

## PROGRAM
```
#include <stdio.h>
#include <ctype.h>
int main() {
char str[100];
int i;
printf("Enter a string: ");
gets(str);
for (i = 0; str[i] != '\0'; i++) {
str[i] = tolower(str[i]);
}
printf("String in lowercase: %s\n", str);
return 0;
}
```
## OUTPUT
![image](https://github.com/user-attachments/assets/fabedd58-0f29-4d36-b5c3-6d70946a289c)

## RESULT
Thus the program to convert the given string into lowercase has been executed successfully
 
 
# EX-19-COUNT-OF-WORDS-IN-A-STRING
## AIM
Write a C Program to count the total number of words in a given string using do While loop.

## ALGORITHM
1.	Start the program.
2.	Read a string variable.
3.	Using for loop, inspect the string character by character.
4.	Whenever a space is encountered increment count by 1.
5.	Display the result.
6.	Stop the program.

## PROGRAM
```
#include <stdio.h>
int main() {
char str[100];
int i = 0, count = 1;
printf("Enter a string: ");
gets(str);
do {
if (str[i] == ' ' && str[i+1] != ' ' && str[i+1] != '\0') {
count++;
}
i++;
} while (str[i] != '\0');
printf("Total number of words: %d\n", count);
return 0;
}
```
## OUTPUT
![image](https://github.com/user-attachments/assets/73dddcb0-4340-4117-8e45-4c514c3b399c)


## RESULT
Thus the program to count the total number of words in a given string using do While loop has been executed successfully
 
 


# EX  -20 -COMPARING TWO STRINGS
## AIM
write a Program to compare two strings without using strcmp().
## ALGORITHM
Step 1: Start the program.
Step 2: Declare two character arrays c1 and c2 of size 100 to store the strings. Also, declare an integer variable
             flag and initialize it to 0, and i for indexing.      
Step 3: Read the first string c1 using scanf("%[^\n]", c1); — this reads input until a newline is encountered 
            (i.e., can include spaces).
Step 4: Read the second string c2 using scanf("%s", c2); — this reads input until a space or newline (i.e., no 
            spaces in the second string).
Step 5: Start comparing characters of both strings from index i = 0.
Step 6: Repeat the following while neither c1[i] nor c2[i] is '\0' (i.e., end of string):
•	If c1[i] is not equal to c2[i], set flag = 1.
•	Increment i by 1.
Step 7: After the loop, check the value of flag:
•	If flag == 0, print "strings are same".
•	Otherwise, print "strings are not same".
Step 8: End the program.

## PROGRAM
```
#include <stdio.h>
#include <string.h>
int main() {
char c1[100], c2[100];
printf("Enter the first string: ");
scanf(" %[^\n]", c1);
getchar(); // consume leftover newline
printf("Enter the second string: ");
scanf(" %[^\n]", c2);
if (strcmp(c1, c2) == 0) {
printf("Strings are same.\n");
} else {
printf("Strings are not same.\n");
}
return 0;
}
```
## OUTPUT
 
![image](https://github.com/user-attachments/assets/8d3982dd-ce19-4d60-9cd4-2e34b93c40d2)

## RESULT
Thus the C Program to compare two strings without using strcmp() has been executed successfully
Thus the C Program to compare two strings without using strcmp() has been executed successfully.

