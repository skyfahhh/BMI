import java.util.*;
class BMI
{ public static void main (String[]args)
    { Scanner sc = new Scanner (System.in);
      System.out.print("Enter your weigh(kg.) ="); 
      double weigh = sc.nextDouble();
      System.out.print("Enter your tall(m.) ="); 
      double tall = sc.nextDouble();
      System.out.println(weigh/(tall*tall));
    }
}
