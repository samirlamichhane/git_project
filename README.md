# git_project
This is the first class of the git project


import java.util.Scanner;
public class main {

	  public static void main(String[] args) {

	    char operator;
	    Double num1, num2, result;

	  
	    Scanner sc = new Scanner(System.in);

	   
	    System.out.println("Choose an operator: +, -, *, or /    :");
	    operator = sc.next().charAt(0);

	 
	    System.out.println("Enter first number :");
	    num1 = sc.nextDouble();

	    System.out.println("Enter second number :");
	    num2 = sc.nextDouble();

	    switch (operator) {

	      
	      case '+':
	        result = num1 + num2;
	        System.out.println(num1 + " + " + num2 + " = " + result);
	        break;

	     
	      case '-':
	        result = num1 - num2;
	        System.out.println(num1 + " - " + num2 + " = " + result);
	        break;

	      
	      case '*':
	        result = num1 * num2;
	        System.out.println(num1 + " * " + num2 + " = " + result);
	        break;

	     
	      case '/':
	        result = num1 / num2;
	        System.out.println(num1 + " / " + num2 + " = " + result);
	        break;

	      default:
	        System.out.println("Invalid operator!");
	        break;
	    }
	    	System.out.println("Type exit to terminate");
	    	
			if(sc.next().equals("exit")) {
	    		sc.close();
	    	}
	  
	  }
	

}



