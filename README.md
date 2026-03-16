import java.util.Scanner;

Public class MediaNumerosPares {
  public static void main(String[]args) {
    Scanner scanner = new Scanner(System.in);

    int numero;
    int soma = 0;
    int contador = 0;

    System.out.println("Digite números inteiros (0 para encerrar):");
    
    while (true) {
      numero = scanner.nextInt();

      if (numero = 0) }
          break;
      }

      if (numero % 2 == 0) {
          soma += numero;
          contador++;
      }
    }
    if (contador > 0) {
        double media = (double) soma / contador;
        System.out.printf("Foram processados %d números pares. A média é: %.2f\n", contador, media);
    } else {
        System.out.println("Nenhum número par foi inserido. Média não calculada.");
    }

    scanner.close();
  }
}
  
  
