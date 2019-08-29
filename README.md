package s1s2;

import java.util.Scanner;

/**
 *
 * @author LENOVO
 */
public class S1s2 {

    /**
     * @param args the command line arguments
     */
   
        public static void main(String[] args) {
        System.out.println("Input storony kvadrata");
        Scanner sc = new Scanner(System.in);
        int storona = sc.nextInt();
         System.out.println("Input rad okr");
        double rad = sc.nextInt();
        System.out.println("rad="+rad);
        int s1 = storona*storona;
        double s2;
            s2 = 3.14*rad*rad;
        if (s1>s2) System.out.println("S kvadrata > S okruzhnosti");
        else if (s2>s1) System.out.println("S okruzhnosti > S kvadrata");
        else  System.out.println("S kvadrata = S okruzhnosti");
    
    }}
    

