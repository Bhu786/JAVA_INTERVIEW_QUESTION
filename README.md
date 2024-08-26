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



## Quest.1 Write a program to find the largest of the three given number. take input from the user.

```java
	package first_demo;
import java.util.Scanner;

public class Largest_0f_3_No {

	public static void main(String[] args) {
		// TODO Auto-generated method stub		
		
//	syso	
//	System.out.println();		
		Scanner first=new  Scanner(System.in);
		Scanner second=new  Scanner(System.in);
		Scanner third=new  Scanner(System.in);
		
		System.out.println("enter first no :");
		int first_no=first.nextInt();
		System.out.println("enter second no :");
		int second_no=second.nextInt();
		System.out.println("enter third no :");
		int third_no=third.nextInt();
		
		
		
		if(first_no>second_no&&first_no>third_no) {
			System.out.println("first is greater");
		}else if(first_no<second_no&&second_no>third_no) {
			System.out.println("second is greater");
		}else {
			System.out.println("third is greater");
		}
		
		

	}

}



```



## Quest.2 Write a program to display the grade of the student given marks. take input from the user.

```java



package first_demo;

import java.util.Scanner;

public class Grade_promgram {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		
		
Scanner input=new Scanner(System.in);
  System.out.println("inter the number");

  int number=input.nextInt();

  if(number>90){
	System.out.println("A+");
  }else if(number>80&&number<90){
	System.out.println("A");
  }else if(number>70&&number<80){
	System.out.println("B");
  }else if(number>60&&number<70){
	System.out.println("C");
  }else if(number>50&&number<60){
	System.out.println("D");
  }else if(number<40){
	System.out.println("failed");
  }



	}
	
}











```





## Quest.3 Write a program to compute the number of days in a month by using switch statement.

```java


package first_demo;
import java.util.Scanner;

public class Month_program {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		
		

		Scanner input= new Scanner(System.in);
		System.out.println("enter the month name:");
		String month=input.nextLine();	
		switch(month) {
		
		
		case "january":  System.out.println("31");
		break;
		case "february": System.out.println("28");
		break;
		case "march":System.out.println("31");
		break;
		case "april":System.out.println("30");
		break;
		case "may":System.out.println("31");
		break;
		case "june":System.out.println("30");
		break;
		case "july":System.out.println("31");
		break;
		
		case "august":System.out.println("30");
		break;
		
		case "september":System.out.println("31");
		break;
		
		case "octuber":System.out.println("30");
		break;
		
		case "november":System.out.println("31");
		break;
		
		case "december":System.out.println("30");
		break;
		
		
		default :
			System.out.println("Invalid hai ");
		
			break;
		
		}
		
		
		

	}

}



```


## Quest.4 Write a program to check the number is palindrome or not.


```java

package first_demo;

import java.util.Scanner;

public class Palindrom_promgram {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		
		
//		121
		
		int num;
		int result=0;
		int temp=0;
		int digit=0;
		int a=0;
		 Scanner scanner = new Scanner(System.in);
	        
	        System.out.println("Enter the first number:");
	        Scanner obj = new Scanner(System.in);
	        num = obj.nextInt();
	        temp=num;
		
		do {
			
			digit=temp%10;
			temp=temp/10;
			a=a*10+digit;
			
			
			
		}while(temp>0);
		
		
		if(a==num) {
			System.out.println("yes is palindrom");
		}
		else {
			System.out.println("not");
		}
		
		

	}

}


```



## Quest.5 Write a program to print fibonacci series.



```java

package first_demo;

import java.util.Scanner;

public class fibonacci_program {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		
		
		
		Scanner input= new Scanner(System.in);
		System.out.println("enter the number :");
		int number=input.nextInt();	

		// fibonacci == last ki do numbar ka sum == current number

		int a=0;
		int b=1;

		int c=0;

		for(int i=0;i<number;i++){

          c=a+b;
		  System.out.println(c);
		  a=b;
		  b=c;





		}
			

	}

}





```




## Quest.6 Write a program to check the number is armstrong number of not.

```java

```




## Quest.7 Write a program to print table. take input from the user.

```java

```

## Quest.8 Write a program to print right triangle by using star pattern.


```java
package first_demo;

public class Pattern_2 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub

		
//		
//		*
//	   **
//	  ***
//	 **** 
//	*****
		int n=5;
		int i;
		
//		row hogya
		
		for(i=1;i<=n;i++) {
			
//			now come to pattern
//			pattern me chej hai space and *
			
			
			
//			for space ki leye
			for(int j=i;j<n;j++) {
				System.out.print(" ");
			}
			
			
//			* 
			for(int  k=1; k<=i;k++) {
				System.out.print("*");
			}
			
			System.out.println();
			
		}
		
				
		
	}

}


```

## Quest.9 Write a program to print left angle triangle by using star pattern.


```java
package first_demo;

public class Pattern_1 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		
		
		
		int n=5;
//		
//		*
//		**
//		***
//		****
//		*****
		
		
		for(int i=1;i<=n;i++) {
			
			for(int j=1;j<=i;j++) {
				System.out.print("*");
				
			}
			
			System.out.println();
			
			
			
		}
				

	}

}


```


## Quest.10 Write a program to print pyramid by star pattern.

```java


package first_demo;

public class Pattern_2 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub

//		    * 
//		   * * 
//		  * * * 
//		 * * * * 
//		* * * * * 		

		int n=5;
		int i;
		
//		row hogya
		
		for(i=1;i<=n;i++) {
			
//			now come to pattern
//			pattern me chej hai space and *
			
			
			
//			for space ki leye
			for(int j=i;j<n;j++) {
				System.out.print(" ");
			}
			
			
//			* 
			for(int  k=1; k<=i;k++) {
				System.out.print("* ");
			}
			
			System.out.println();
			
		}
		
				
		
		
	}

}


```











