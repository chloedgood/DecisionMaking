# DecisionMaking

package decision_making;

import java.util.Scanner;

public class DecisionMaking {

	public static void main(String[] args) {
		
		Scanner in = new Scanner(System.in);
		
		System.out.println("Enter a number between 1 and 100: ");
		int num = in.nextInt();
		String answer= "";
		
		
		{if((num % 2) == 0 && num < 25) {
			System.out.println("Even and less than 25");
		}if((num % 2) == 0 && num < 60) {
				System.out.println("Even");
		}if((num % 2) == 0 && num > 60) {
				System.out.println(num + " and Even");
		}if((num % 1) == 0 && num > 60) {
				System.out.println("Odd and over 60.");
		} else {
				System.out.println("Odd");
		
				System.out.println("Would you like to continue? (y/n)");
		answer = in.next();
		
		
}
}
}
}
