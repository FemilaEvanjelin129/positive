package guvi1;
import java.util.Scanner;
public class positive {
	private static Scanner input;
public static void main(String args[]){
		input = new Scanner(System.in);
		System.out.println("enter a number");
		int a=input.nextInt();
		if(a<0)
			System.out.println("The number is negative");
		else if(a>0)
			System.out.println("The number is positive");
		else
			System.out.println("the number is zero");
	}
}
