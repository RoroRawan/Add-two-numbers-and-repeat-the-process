# Add-two-numbers-and-repeat-the-process

package Code;
import java.util.Scanner;
public class AddAndRepeat {

	public static void main(String[] args) {
	  Scanner reader = new Scanner(System.in);
	  int sum = 0;
	  char selection;
	  do{
	     System.out.println("Enter two numbers");
	     int num1= reader.nextInt();
	     int num2 = reader.nextInt();
	     sum = num1+num2;
	     System.out.println("The result of summation "+num1+" and "
	     +num2+" = "+sum);
	      
	  System.out.println("Do you wish to perform another operation, Y/N");
	  selection =reader.next().charAt(0);
	   }
	    while((selection=='Y')||(selection=='y'));
	}
}
