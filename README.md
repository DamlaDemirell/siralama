import java.util.Scanner;

public class test {
    public static void main(String[] args) {


        int a, b, c;
        Scanner input = new Scanner(System.in);

        System.out.print("1.Sayı:");
        a = input.nextInt();

        System.out.println("2.Sayı:");
        b = input.nextInt();

        System.out.println("3.Sayı");
        c = input.nextInt();

        if((a<b) && (a<c)) {
            if(b<c);
            System.out.println("a<b<c");
        }else {
            System.out.println("a<c<b");

        } if ((b>a) && (b>c)) {
            if (a < c) {
                System.out.println("b<a<c");
            } else {
                System.out.println("b<c<a");
            }
        }else {
            if ((c < a) && (c < b)) {
                System.out.println("c < a < b");
            } else {

            }
        }


        }
    }
