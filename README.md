// this is my first java projeect for calculation

import java.util.Scanner;

public class Calculation1 {

    static void method1(int num1, int num2) {
        int add = (num1 + num2);
        System.out.println("addition : " + add);// for add
    }

    static void method2(int num1, int num2) {
        int add1 = (num1 * num2);
        System.out.println("multiplication : " + add1);// for multiply
    }

    static void method3(int num1, int num2) {
        int add2 = (num1 / num2);
        System.out.println("division : " + add2);// for divide
    }

    static void method4(int num1, int num2) {
        int add3 = (num1 - num2);
        System.out.println("subtraction : " + add3);// for substract
    }

    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        System.out.println("enter first num :");
        int num4 = sc.nextInt();// input first num

        System.out.println("Enter 2nd number :");
        int num5 = sc.nextInt();// input 2nd num

        System.out.println("1 for addition." + "\n" + "2 for multiplication" + "\n" + "3 for division" + "\n" + "4 for subtraction");
        int num3 = sc.nextInt();// input operator 

        if (num3 == 1) {
            method1(num4, num5); // for add
        }
        if (num3 == 2) {
            method2(num4, num5);// for multiply
        }
        if (num3 == 3) {
            method3(num4, num5);// for divide
        }
        if (num3 == 4) {
            method4(num4, num5);// for substract
        }
    sc.close();

    }
}
