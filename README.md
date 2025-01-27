# 31.SIMPLE-INTEREST-
package smpleinterest;
import java.util.Scanner;
/**
 *
 * @author 1BSCCSA04
 */
public class SmpleInterest {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        // TODO code application logic here
        Scanner sc = new Scanner(System.in);
        System.out.println("Enter the principal amount :");
        double principal = sc.nextDouble();
        System.out.println("Enter the rate of interest (in percentage):");
        double rate=sc.nextDouble();
        System.out.println("Enter the time period (in years):");
        double time = sc.nextDouble();
        double simple_interest =(principal*rate*time)/100;
        System.out.println("The simple interest is :" + simple_interest);
                
    }
    
}

O/P:
Enter the principal amount :
15000
Enter the rate of interest (in percentage):
2
Enter the time period (in years):
1
The simple interest is :300.0
