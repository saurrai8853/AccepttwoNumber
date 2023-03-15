# AccepttwoNumber
Accept two Number as input and give output as user choice
package mypackage;

import java.util.Scanner;

public class AccepttwoNumber {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		Scanner sc=new Scanner(System.in);
		System.out.print("Enter your First Number:");
		int n=sc.nextInt();
		System.out.print("Enter your Second Number:");
		int m=sc.nextInt();
		System.out.print("Enter choice:");
		int ch=sc.nextInt();
		switch(ch) {
		case 1:
			double result=m+n;
			System.out.print("Addition of two Number is:"+result);
			break;
		case 2:
			double result2=m*n;
			System.out.print("Multiplication of two Number is:"+result2);
			break;
		case 3:
		double result3=m-n;
			System.out.print("Substraction of two Number is:"+result3);
			break;
		case 4:
			double result4=m/n;
			System.out.print("Division of two Number is:"+ result4);
			break;
			default:
				System.out.print("Invaild input");
		}
         
	}

}
