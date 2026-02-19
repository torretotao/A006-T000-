# A006-T000-
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        String input = scanner.nextLine();
        String result = input.replace(" ", "");
        System.out.println(result);

        scanner.close();
    }
}
