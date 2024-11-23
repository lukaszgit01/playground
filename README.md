import java.util.Scanner;//TIP To <b>Run</b> code, press <shortcut actionId="Run"/> or
// click the <icon src="AllIcons.Actions.Execute"/> icon in the gutter.
public class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        System.out.printf("Podaj liczbę całkowitą dodatnią: ");
        int liczba = scanner.nextInt();

        for (int i=1; i <= liczba; i +=2){

            System.out.printf(i + " ");
        }

    }
}
