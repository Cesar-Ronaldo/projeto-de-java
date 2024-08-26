import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        // Cria uma instância da classe Scanner para ler a entrada do usuário
        Scanner scanner = new Scanner(System.in);

        // Solicita ao usuário que informe sua idade
        System.out.print("Digite a sua idade: ");
        int idade = scanner.nextInt();

        // Classifica a idade e exibe a categoria correspondente
        if (idade >= 0 && idade <= 12) {
            System.out.println("Você é uma criança.");
        } else if (idade >= 13 && idade <= 17) {
            System.out.println("Você é um adolescente.");
        } else if (idade >= 18) {
            System.out.println("Você é um adulto.");
        } else {
            System.out.println("Idade inválida.");
        }

        // Fecha o scanner
        scanner.close();
    }
}
