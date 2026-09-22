// JAVA PROGRAMING LANGUAGE
// CODE PROPER 
// SYNTAX
// import the java.util.Scanner;
// caling out the java scanner

public class Main{
  public static void main(String[]args){
    Scanner scanner = new Scanner(System.in);
    // To get the variable or call the scanner

// Declaring the output 
    System.out.println("Hello, World! ");

//DATA TYPES OF JAVA
int age = 19;
// Whole Number
double price = 67.7; // double precisions of decimal number 
float weight = 42.5; // single precisions of decimal number
//'f' how many decimal places.
char grade = 'F'; // single character using a single quotes
boolean isStudent; // true or false 
String name ="Jai"; // not primitive TypeNotPresentException
//Increment/ Decrement Expressions
int counter = 5;
System.out.println("\ncounter ++ (post)"+ counter++);//
System.out.println("counter now: " +counter); //6
System.out.println("++counter (pre): "+ ++counter); //7

//Counter Flow (if/else condition, switch case statement, loops(for, while, do while)) 
// if/else
System.out.print("Enter your exam score: ");
int Examscore = scanner.nextInt();

if (Examscore >= 90){
  System.out.println("Grade: A");
} else if (Examscore >= 80){
  System.out.println("Grade: B");
} else if (Examscore >= 70){
  System.out.println("Grade: C");
} else{
  System.out.println("Grade: F");
}

// Switch Case Statement 
switch(day){
  case 1: System.out.println("Monday"); break;
  case 2: System.out.println("Tuesday"); break;
  case 3: System.out.println("Wendesday"); break;
  case 4: System.out.println("Thursday"); break;
  case 5: System.out.println("Friday"); break;
  case 6: System.out.println("Saturday"); break;
  case 7: System.out.println("Sunday"); break;


}

scanner.close();

  }
}
