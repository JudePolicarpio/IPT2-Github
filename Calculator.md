import java.util.Scanner;

public class Calculator{

    public static void main(String[]args){
        Scanner scanner = new Scanner (System.in);
        System.out.println("Enter first number: ");
        int a = scanner.nextInt();

        System.out.println("Enter second number: ");
        int b = scanner.nextInt();

        System.out.println("Addition: " + add(a,b));
        System.out.println("Subtraction: " + sub(a,b));
        System.out.println("Multiplication: " + mul(a,b));
        System.out.println("Division: "  + div(a,b));
        System.out.println("Modulus: "  + mod(a,b));

        scanner.close();
      }


        public static int add(int a, int b){
            return a + b;
        }
         public static int sub(int a, int b){
            return a - b;
         }
         public static int mul(int a, int b){
            return a * b;
         }
         public static int div(int a, int b){
            return a / b;
         }
         public static int mod(int a, int b){
            return a % b;
         }
    }