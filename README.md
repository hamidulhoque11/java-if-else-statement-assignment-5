# java-if-else-statement-assignment-5

import java.util.Scanner;

class Main {

    public static void main(String[] args) {
    
        Scanner sc= new Scanner(System.in);
        System.out.println("------Chack you are Valid or invalid for voter-----");
        int number;
        String name;
        
        System.out.print("Enter your Name :");
        name=sc.nextLine();
        System.out.print("Enter your age :");
        number=sc.nextInt();
        sc.nextLine();
        if (number>=18){
            System.out.println("Congretulation "+name+" you are valid for voter");
        }else{
            System.out.println("Sorry "+name+" you are Invalid.");
        }
        
        
    }
}
