Questão 10 

import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        i-;

        do {
            System.out.println("\nMenu:");
            System.out.println("1 - Mostrar 'Olá'");
            System.out.println("2 - Mostrar 'Bem-vindo'");
            System.out.println("0 - Sair");
            System.out.print("Escolha uma opção: ");

            opcao = scanner.nextInt();

            switch (opcao) {
                case 1:
                    System.out.println("Olá");
                    break;
                case 2:
                    System.out.println("Bem-vindo");
                    break;
                case 0:
                    System.out.println("Saindo...");
                    break;
                default:
                    System.out.println("Opção inválida!");
            }

        } while (opcao != 0);

        scanner.close();
    }
}

Questão 11

import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        int n=0;

        for (int a=2; a<=100; a=a+2)
        {
            n += a;
        }
                System.out.println(n);


    }
}

Questão 12

import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner g = new Scanner(System.in);

        int n = 0;
        int p = 0;

        for (int a=-10;a<=10;a++) {
            if (a > 0) {
                p++;
            } else if (a < 0) {
                n++;
            }
        }
            System.out.println( "negativo - "+ n);
            System.out.println("positivo + "+ p);
    }
}

Questão 13

import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner g = new Scanner(System.in);

        System.out.println("Tabuada do 1");

            for (int a = 0; a <=10; a++){
                System.out.println(a);}

        System.out.println("Tabuada do 2");
            for (int a = 0; a <=20; a = a +2){
                System.out.println(a);
            }
        System.out.println("Tabuada do 3");
            for (int a = 0; a <=30; a = a+3) {
                System.out.println(a);
            }

        System.out.println("Tabuada do 4");
            for (int a = 0; a <=40; a = a+4) {
                System.out.println(a);
            }
        System.out.println("Tabuada do 5"); 
            for (int a = 0; a <=50; a = a+5) {
                System.out.println(a);
            }
    }
}

Questão 14


import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner no = new Scanner(System.in);

        int a = 0;
        int b = 0;
        int c = 0;
        int d = 0;
        int e = 0;

    System.out.println("Primeira nota: ");
        a=no.nextInt();

    System.out.println("Segunta nota: ");
        b=no.nextInt();

    System.out.println("Terceira nota: ");
        c=no.nextInt();

    System.out.println("Quadro nota: ");
        d=no.nextInt();

    System.out.println("Quinto nota: ");
        e=no.nextInt();

    int soma = (a+b+c+d+e) / 5;

    if (soma>=70) {
        System.out.println("Aprovado");
    }
    else if (soma >= 50) {
            System.out.println("Recuperação");
        }
        else {
            System.out.println("Reprovado");
    }

    System.out.println(soma);

    }
} 


Questão 15

package lino;
import java.util.Scanner;

public class Lino {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        int opcao;

 
        do {
            System.out.println("\n--- MENU ---");
            System.out.println("1 - numeros de 1 a 10");
            System.out.println("2 - pares de 1 a 20");
            System.out.println("3 - tabuada do 3");
            System.out.println("0 - Sair");
            System.out.print("Escolha uma opção: ");
            
            
            opcao = scanner.nextInt();


            switch (opcao) {
                case 1:
                    for (int a=0; a<=10;a++){
                    System.out.println(a);}
                    break;
                case 2:
                    for (int b=0; b<=20;b=b+2){
                    System.out.println(b);}
                    break;
                 case 3:
                    for (int c=0; c<=30;c=c+3){
                    System.out.println(c);}
                    break;
                case 0:
                    System.out.println("Saindo do sistema...");
                    break;
                default:
                    System.out.println("Opção inválida! Tente novamente.");
            }

        } while (opcao != 0); // Repete enquanto a opção for diferente de 0

        scanner.close();
    }
}

Questão 16

package lino;
import java.util.Scanner;

public class Lino {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        int n= 5 ;
        int f = 1;
        for (int a=1; a<=n; a++){
            f*=a;
            
        }
        System.out.println(f);
 
        
    }
}

Questão 17

package lino;
import java.util.Scanner;

public class Lino {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        int n= 5 ;
     
        for (int a=1; a<=100; a++){
            if (a % 3 == 0) {
 
            System.out.println(a);  
        }
      
 
        
    }
   }
}


Questão 18

import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner no = new Scanner(System.in);

        System.out.println("Valor 1");
        int a1 = no.nextInt();

        System.out.println("Valor 2");
        int a2 = no.nextInt();

        System.out.println("Valor 3");
        int a3 = no.nextInt();

        System.out.println("Valor 4");
        int a4 = no.nextInt();

        System.out.println("Valor 5");
        int a5 = no.nextInt();

        int m = a1;
        if (a2 > m) m = a2;
        if (a3 > m) m = a3;
        if (a4 > m) m = a4;
        if (a5 > m) m = a5;

        int n = a1;
        if (a2 < n) n = a2;
        if (a3 < n) n = a3;
        if (a4 < n) n = a4;
        if (a5 < n) n = a5;

        System.out.println("maior numero e "+m);
        System.out.println("menor numero e "+n);

    }
}

Questão 19

import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner no = new Scanner(System.in);

      int s = 0;
      int a = 1;

      while (a!=0){
          System.out.println("qual numero: ");
          a = no.nextInt();
          s+=a;
        }
      System.out.println(s);

    }
}	

Questão 20 

import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner no = new Scanner(System.in);

        int opcao;

        do {

            System.out.println("1-Soma");
            System.out.println("2-Subtrair");
            System.out.println("3-Multiplicar");
            System.out.println("4-Dividir");
            System.out.println("0-sair");

            opcao = no.nextInt();

            switch (opcao) {
                case 1:
                    System.out.println("Soma de dois numero: ");
                    int a = no.nextInt();
                    System.out.println("+");
                    int b = no.nextInt();
                    int soma = a + b;
                    System.out.println(a + "+" + b + "=" + soma);
                    break;

                case 2:
                    System.out.println("Subtrair de dois numero: ");
                    int a1 = no.nextInt();
                    System.out.println("-");
                    int b1 = no.nextInt();
                    ;
                    int subtracao = a1 - b1;
                    System.out.println(a1 + "-" + b1 + "=" + subtracao);
                    break;

                case 3:
                    System.out.println("Multiplicacao");
                    int a2 = no.nextInt();
                    System.out.println("x");
                    int b2 = no.nextInt();
                    int multiplicacao = a2 * b2;
                    System.out.println(a2 + "x" + b2 + "=" + multiplicacao);
                    break;

                case 4:
                    System.out.println("Dividicao");
                    int a3 = no.nextInt();
                    System.out.println("/");
                    int b3 = no.nextInt();
                    int dividicao = a3 % b3;
                    System.out.println(a3 + "/" + b3 + "=" + dividicao);
                    break;

                case 0:
                    System.out.println("Saindo do sistema");

                }
            } while (opcao != 0) ;

    }
    }
