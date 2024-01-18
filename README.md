# largest-number-in-java
//Finding the largest number in java

import java.util.Scanner;
public class play{
    public static void main(String args[]){
        Scanner sc=new Scanner(System.in);                            //input the data
        System.out.println("Enter the value of A,B and C:");          
        int a=sc.nextInt();                                           //Enter the value of a
        int b=sc.nextInt();                                           //Enter the value of b
        int c=sc.nextInt();                                            //Enter the value for c
        if((a>=b)&&(a>=c)){                                            //checking for A     
            System.out.println("A is greater.");
        }
        else if(b>=c){                                                 //checking for B       
            System.out.println("B is greater");
        }
        else{                                                                  
            System.out.println("C is greater");
        }
    }
}
