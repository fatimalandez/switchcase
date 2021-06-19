# switchcase
code in loop

package switchcase;

import java.util.Scanner;

/**
 
 */
public class Switchcase {

   
    public static void main(String[] args) {
        
        int choice;
        System.out.println("Pick one : 1. Good\t2. Better\t3. best\t");
        Scanner s = new Scanner (System.in);
        choice = s.nextInt();
        switch(choice)
        {
            case 1 : System.out.println("You said Hi");
            break;
            case 2 : System.out.println("You said Hi");
            break;
            case 3 : System.out.println("You said Hi");
            break;
        }
    }
    
}
