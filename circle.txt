package stacy.shapes;
import java.util.*;
public class rectangle extends shapess {
    public static void main (String[] args){
        Scanner sc=new Scanner(System.in);
        System.out.println("enter number one for rectangle");
        int rectangle=sc.nextInt();
        System.out.println("enter number of rows");
        int rows=sc.nextInt();
        System.out.println("enter number of column");
        int column=sc.nextInt();
        for (int i=1; i<=rows; i++){
            for(int j=1; j<=column; j++){
                System.out.print("*  ");
            }
                System.out.println();
        }
        
        }
}
