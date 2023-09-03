# Factorial
import java.util.Scanner;
public class fact_recurs {
    static int factorial(int num)
    {
        int fact=1;
        if(num==0 || num==1){
            return 1;
        }else
        return num*factorial(num-1);
    }
    public static void main(String[] args) {
        Scanner sc=new Scanner(System.in);
        System.out.print("Enter any number: ");
        int n=sc.nextInt();
        System.out.println(factorial(n));
    }
}
