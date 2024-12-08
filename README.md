# Recursion-01
basic of recursion
import java.util.Scanner;

public class firstRecursion {
    public firstRecursion() {
    }

    static void func(int N) {
        if (N >= 1) {
            func(N - 1);
            System.out.println("" + N + " ");
        }

    }

    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int N = sc.nextInt();
        func(N);
    }
}
