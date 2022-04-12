#Utilizado NetBeans IDE  8.2

import java.util.Scanner;

/**
 * 
 * @author Andressa Vieira Couto
 */
public class GeradorTabuada {
    
    /*
Desenvolva um gerador de tabuada,
capaz de gerar a tabuada de qualquer número inteiro entre 1 a 10.
O usuário deve informar de qual numero ele deseja ver a tabuada.
A saída deve ser conforme o exemplo abaixo:
Tabuada de 5:
5 X 1 = 5
5 X 2 = 10
...
5 X 10 = 50
*/


    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in); //Abertura da entrada de dados através do teclado

        System.out.println("Número: " ); //Pedido de um número
        int numero = scanner.nextInt(); //Entrada de dados, neste caso de um int da variável numero

        System.out.println( "\n" + "Tabuada de " + numero + ":" + "\n");//frase para indicar o início da tabuada solicitada
     

        //para: variável i = 0, até i menor ou igual a 10, adicionando 1 ao valor de i a cada loop.
        for (int i = 0; i <= 10; i = i + 1) {
            //número escolhido pelo usuário "X" o valor de i "=" a multiplicação do número com o i.
            System.out.println(numero + " x " + i + " = " + (numero * i));
        }
    }

    
}
