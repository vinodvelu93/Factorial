# Factorial
package com.payil.poly;

import java.util.Scanner;

public class Factorial {

	public static void main(String[] args) {
		int fact=1;
		System.out.println("Enter a number :" );
		Scanner s = new Scanner(System.in);
		int n =s.nextInt();
		while(n>0){
			fact= fact*n;
			n--;
		}
		System.out.println("The factorial is:"+fact);
		// TODO Auto-generated method stub

	}

}
