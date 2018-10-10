//10.	Faça um algoritmo que valide uma data, formada por dia, mês e ano. Por exemplo,
a data 30/2 é inválida, porém a data 29/2/2012 é válida.

package listaexercicios2;

import java.util.Scanner;

public class Exercicio10 {
    public static void main(String[] args) {
        int dia, mes, ano;
        Scanner entrada = new Scanner(System.in);
        
        System.out.print("Entre com o dia: ");
        dia = entrada.nextInt();
        System.out.print("Entre com o mes: ");
        mes = entrada.nextInt();
        System.out.print("Entre com o ano: ");
        ano = entrada.nextInt();
        if (ano >= 1900) {
            switch (mes) {
                case 4: case 6: case 9: case 11:
                    if ((dia < 1) || (dia > 30)) {
                        System.out.println("Dia inválido");
                    }
                    break;
                case 1: case 3: case 5: case 7: case 8: case 10: case 12:
                    if ((dia < 1) || (dia > 31)) {
                        System.out.println("Dia inválido");
                    }
                    break;
                case 2:
                    if ((ano % 4) == 0) {
                        if ((dia < 1) || (dia > 29)) {
                            System.out.println("Dia inválido");
                        }
                    }
                    else {
                        if ((dia < 1) || (dia > 28)) {
                            System.out.println("Dia inválido");
                        }
                    }
                    break;
                default: {
                    System.out.println("Mês inválido");
                }    
            }
        }
        else {
            System.out.println("Ano inválido");
        }
    }
}
