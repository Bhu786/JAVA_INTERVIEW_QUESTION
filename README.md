# JAVA_INTERVIEW_QUESTION

## Ques. 1. When was java develope and who is the inventor of java? Why we use java for programming?
**
A. Java was developed in 1991 by James Gosling and his team at Sun Microsystems.
B. Java is used for programming because it is platform independent, object-oriented, and has a vast
library of APIs and tools. **

## Ques. 2. What are the features of java.
**
A. Java is a platform independent, object-oriented, and has a vast library of APIs and tools
B.Provide more security.
c.
**

## Ques. 3. what is JDK, JRE, JVM?
**
 A. JDK (Java Development Kit) is a software development kit that includes the JRE, development
tools, and documentation. 
JRE (Java Runtime Environment) is a software package that includes the JVM
and class libraries. 
JVM (Java Virtual Machine) is a software program that runs Java bytecode on a
computer. 
**

## Ques. 4. what is the structure of java program. write a program to print hello world.
**
A. The structure of a Java program consists of a class with a main method. Here is a
program to print "Hello World": 

Example:
**
```java
package first_demo;

public class first_demo {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		
		String abc = "Hello World ";

		System.out.println(abc);
		
		

	}

}

```





## Ques. 5. Define Variables in java. Explain different scope of variable.
**
A. In Java, a variable is a name given to a location in memory where a value can
be stored. The scope of a variable determines where it can be accessed in a program.
The scope of a variable can be local, instance(global), or class.
**
## Ques. 6. Define data types in java.
**
A. In Java, data types are the categories of values that a variable can hold. There are
primitive data types (int, double, boolean, etc.) and reference data types (String, Array)
**

## Ques. 7. What is type casting in java?
**
A. Type casting in Java is the process of converting a value of one data type to another data
type. There are two types of type casting: implicit and explicit.
**

## Ques. 8. Write a program to add two number by taking input from user.
A. Here is a program to add two numbers by taking input from the user:
```java
package first_demo;

public class first_demo {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		
		int a = 20;
		int b = 10;
		int add= a + b;
		System.out.println(add);
		
		

	}

}

```





## Ques. 9. Define operator and its type?
**
A. In Java, an operator is a symbol that is used to perform a specific operation on one
or more operands. There are several types of operators in Java, including:
Arithmetic operators (+, -, \*, /, etc.)
Assignment operators (=, +=, -=, etc.)
Comparison operators (==, !=, >, <, etc.)
Bitwise operators
**
## Ques. 10. Write a program individually to perform operators operation.
**
A. Here is a program to perform individual operator operations:
**
```java
package first_demo;

import java.util.Scanner;

public class cal_program {

	public static void main(String[] args) {
		// TODO Auto-generated method stub

		
		 Scanner scanner = new Scanner(System.in);
	        
	        System.out.println("Enter the first number:");
	        double num1 = scanner.nextDouble();
	        
	        System.out.println("Enter the operator (+, -, *, /):");
	        char operator = scanner.next().charAt(0);
	        
	        System.out.println("Enter the second number:");
	        double num2 = scanner.nextDouble();
	        
	        double result = 0;

	        switch (operator) {
	            case '+':
	                result = num1 + num2;
	                break;
	            case '-':
	                result = num1 - num2;
	                break;
	            case '*':
	                result = num1 * num2;
	                break;
	            case '/':
	                if (num2 != 0) {
	                    result = num1 / num2;
	                } else {
	                    System.out.println("Error! Division by zero.");
	                    return;
	                }
	                break;
	            default:
	                System.out.println("Invalid operator!");
	                return;
	        }

	        System.out.println("The result is: " + result);
		
		
		
		
	}

}
```










