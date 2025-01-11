import java.util.Scanner;
 class SimpleInterestCalculator {
 public static void main(String[] args) {
 Scanner scanner = new Scanner(System.in);
 System.out.print("Enter Principal amount: "); 
double principal = scanner.nextDouble(); 
System.out.print("Enter Annual Interest Rate (in %): "); 
double rate = scanner.nextDouble(); 
System.out.print("Enter Time (in years): "); 
double time = scanner.nextDouble();
 double simpleInterest = (principal * rate * time) / 100; 
System.out.println("Simple Interest is: " + simpleInterest); scanner.close();
 }
 }   

OUTPUT:

PS C:\Users\MY\OneDrive\Pictures\Documents\java emc 1> javac hello.java
PS C:\Users\MY\OneDrive\Pictures\Documents\java emc 1> java hello.java
Enter Principal amount: 20000
Enter Annual Interest Rate (in %): 5
Enter Time (in years): 3
