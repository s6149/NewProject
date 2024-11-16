System.out.println("Hello World");
// This is a comment

/*
This is a multi-line comment
*/

// Variables

int myNum = 5;
float myFloatNum = 5.99f;
char myLetter = 'D';
boolean myBool = true;
String myText = "Hello";

// Print Variables

System.out.println(myNum);
System.out.println(myFloatNum);
System.out.println(myLetter);
System.out.println(myBool);
System.out.println(myText);

// Change Variable Value

myText = "Hello World";
System.out.println(myText);

// Final Variables

final int myNum2 = 15;
myNum2 = 20;  // will generate an error: cannot assign a value to a final variable

// Operators

int sum1 = 100 + 50;        // 150 (addition)
int sum2 = sum1 + 250;      // 400 (addition)
int sum3 = sum2 + sum2;     // 800 (addition)
int sub1 = sum2 - sum1;     // 150 (subtraction)
int sub2 = sum3 - sum1;     // 650 (subtraction)
int mul1 = sum1 * sum2;     // 100000 (multiplication)
int div1 = sum1 / sum2;     // 0 (division)
int div2 = sum3 / sum1;     // 8 (division)
int mod1 = sum3 % sum1;     // 0 (modulus)
int mod2 = sum2 % sum1;     // 50 (modulus)
int inc1 = sum1++;          // 150 (postfix increment)
int inc2 = ++sum1;          // 152 (prefix increment)
int dec1 = sum2--;          // 400 (postfix decrement)
int dec2 = --sum2;          // 398 (prefix decrement)

// Assignment Operators

int x = 10;
x += 5;     // x is now 15 (x = x + 5)
x -= 3;     // x is now 12 (x = x - 3)
x *= 2;     // x is now 24 (x = x * 2)
x /= 4;     // x is now 6 (x = x / 4)
x %= 3;     // x is now 0 (x = x % 3)

// Comparison Operators

int x = 5;
int y = 3;
System.out.println(x == y);  // returns false, because 5 is not equal to 3