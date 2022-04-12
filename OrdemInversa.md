#Utilizado NetBeans IDE 8.2

public class OrdemInversa {
/*
Crie um vetor de 6 números inteiros
e mostre-os na ordem inversa.
*/
    public static void main(String[] args) {
        
        Scanner entrada = new Scanner (System.in);
        int[] vetor;//definição de ponteiro para matriz
        vetor = new int [6]; //alocação dinâmica de memória
      
        
   
        int count = (vetor.length - 1); //o contador deverá ser um número menor que o tamanho do vetor.
        System.out.print("Vetor Inverso: "); //Frase ilustrativa
        //loop
        while (count >= 0) { //enquanto o contador tiver o valor maior ou igual 0
            System.out.print(vetor[count] + " "); //imprima o valor do elemento do vetor na posição indicada pelo contador.
            count--; //diminua o valor 1 do contador a cada loop
        }

        System.out.println("\n--------------"); //separar os vetores

        System.out.print("Vetor: "); //Frase ilustrativa
        //loop for-each
        for (int elemento : vetor) { //para cada elemento dentro do vetor
            System.out.print(elemento + " "); //imprima o elemento
        }
    }
}
