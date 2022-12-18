import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        Double eur = scanner.nextDouble();
        double dol;
        dol = eur * 1.3;
        System.out.println(eur + " EUR to USD is: " + dol);
    }
