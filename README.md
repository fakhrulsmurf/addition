# addition
Java - Addition Calculator

import java.util.Scanner;
 
class AddNumbers
{
   public static void main(String args[])
   {
      int a, b, sum;
      System.out.println("Enter two integers to calculate their sum ");
      Scanner in = new Scanner(System.in);
      a = in.nextInt();
      b = in.nextInt();
      sum = a + b;
      System.out.println("Sum of entered integers = ");
      System.out.print(sum);
   }
}
