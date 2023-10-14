# Arithmetic-Operators
import java.util.Scanner;

public class ArithmeticOperators
{
	  public static void main(String[] args)
	  {
		 int a;
         int b;
         int result;
		 int c;
         
		 Scanner sc = new Scanner(System.in);
         System.out.println("Enter the value for a and b: ");
		 
         a = sc.nextInt();
		 b = sc.nextInt();
		 
		 
		 
         result =  a+b;
		 System.out.println("addition of a and b is:" + result);
		 
		 result = a-b;
		 System.out.println("subtraction of a and b is:" + result);
		 
		 result = a/b;
		 System.out.println("division of a and b is:" + result);
         
		 result = a*b;
		 System.out.println("multiplication of a and b is:" + result);
			
         			
		   
	  }
}
