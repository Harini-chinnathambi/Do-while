# Do-while
package pkgdo.pkgwhile.java;
import java.util.Scanner;
/**
 *
 * @author 1BSCCSA56
 */
public class DoWhileJava {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        // TODO code application logic here
        Scanner sc= new Scanner (System.in);
        int i;
        System.out.println("first no:");
        i=sc.nextInt();
        do
                {
                    System.out.println(i);
                    i++
                            
                }
        while(i<=5);
    }
    
}
output
1
2
3
4
5
