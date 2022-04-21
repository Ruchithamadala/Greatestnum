# Greatestnum

package assignment2;

import java.util.*;

public class greatestnum {
    
    public static void main(String[] args) {
        
        Scanner sc = new Scanner(System.in);
        
        int a=3, b=5,c=7; // System.out.print("Enter 3 numbers:"
        
        if(a>b && a>c)
        { 
            System.out.println("The greatest num is "  +a);
        }
        
        else if(b>a && b>c)
        {
            System.out.println("The greatest num is "  +b);
        }
        else
        {
            System.out.println("The greatest num is "  +c);
        }
    }
}
