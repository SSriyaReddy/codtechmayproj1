package program2;

import java.util.Scanner;

public class Student {

	public static void main(String[] args) {
		int marks[] = new int[6];
		        int i;
		        float total=0, avg;
		        Scanner scanner = new Scanner(System.in);
				
		        System.out.println("Enter marks obtained in each subject:");
		        for(i=0; i<6; i++) { 
		           
		        	if(i==0) {
		        		System.out.println("Mathematics:");
		        		marks[i]=scanner.nextInt();
		        		total = total + marks[i];
		        	}
		        	else if(i==1) {
		        		System.out.println("Science:");
		        		marks[i]=scanner.nextInt();
		        		total = total + marks[i];
		        	}
		        	else if(i==2) {
		        		System.out.println("English:");
		        		marks[i]=scanner.nextInt();
		        		total = total + marks[i];
		        	}
		        	else if(i==3) {
		        		System.out.println("Sanskrit:");
		        		marks[i]=scanner.nextInt();
		        		total = total + marks[i];
		        	}
		        	else if(i==4) {
		        		System.out.println("Social:");
		        		marks[i]=scanner.nextInt();
		        		total = total + marks[i];
		        	}
		        	else {
		        		System.out.println("Computer:");
		        		marks[i]=scanner.nextInt();
		        		total = total + marks[i];
		        	}
		           
		           
		        }
		        scanner.close();
		        //Calculating average here
		        avg = total/6;
		        System.out.println("The student Average Grade is: ");
		        if(avg>=80)
		        {
		            System.out.print("A");
		        }
		        else if(avg>=60 && avg<80)
		        {
		           System.out.print("B");
		        } 
		        else if(avg>=40 && avg<60)
		        {
		            System.out.print("C");
		        }
		        else
		        {
		            System.out.print("D");
		        }
		        //calculating overall grade here
		        System.out.println("The student Overall Grade is: ");
		        if(total>=80)
		        {
		            System.out.print("A");
		        }
		        else if(total>=60 && avg<80)
		        {
		           System.out.print("B");
		        } 
		        else if(total>=40 && avg<60)
		        {
		            System.out.print("C");
		        }
		        else
		        {
		            System.out.print("D");
		        }

	}

}# codtechmayproj1
