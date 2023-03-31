# AulaJava
                                       TIPOS DE DADOS EM JAVA 
  
-Tipos primitivos: byte, short, int, long, boolean, char, float, double (Tipos básicos)

BYTE: Inteiro de 8 bits;
SHORT: Inteiro de 16 bits;
INT: Inteiro de 32 bits, número interiro sem decimais;
LONG: Inteiro 64 bits;
BOOLEAN: Valor true ou false (Verdadeiro ou Falso);
CHAR: Caracter em notação Unicode de 16 bits;
FLOAT: Números em notação de ponto flutuante, 32 bits, números quebrados ou com vírgula;
DOUBLE: Números em notação de ponto flutuante, 64 bits;


-Tipos de dados por referência: string, array/matriz; (Tipos utilizados para armazenar as localizações dos objetos da memória do computador)

ARRAY: Responsável por guardar uma variedade de valores, são como vetores; 
Ex: intArray = {2,5,46,12,34}; - guarda múltiplos valores de inteiros;
STRING: Caracteres formando um texto/conjunto de palavras, por exemplo "Programar é top". É um tipo mais complexo, possuindo métodos, sendo um deles o length() que nos diz quantos caracteres contêm aquela string;


                                   ESTRUTURAL CONDICIONAL EM JAVA



Estrutura que possibilitam ao programa a tomar decisões e alterar seu fluxo de execução.

-If/Else: Tipo booleano que analisa a questão do verdadeiro ou falso, quando a condição dentro do IF for verdadeira será executada, já o ELSE será utilizado para definir o que irá acontecer se o If for falso. 


Estruturas condicionais permitem criar possibilidades diferentes em um sistema, determinado um comando específico e criando novos caminhos por meio das estruturas condicionais 
   Existem 2 principais, são elas : If/Else e Switch/Case



                               ● If/Else

If= se 
Else= Senao 

Exemplo utilizando o if 

Int idade =23 
  If (idade > 18) {
System.out.println("A entrada é permitida");
}

Comentando o Código 
Analisando o código vemos que o valor da variável idade é igual a 23;
Portanto, se o número que o usuário digital for maior que 18 o sistema irá apresentar a seguinte mensagem (" entrada é permitida"), caso a condição não for atendida nada irá acontecer.

Exemplo utilizando if e else 

Int idade =23 
  If (idade > 18) {
    System.out.println("A entrada é permitida");
}
  else {
System.out.println("Entrada negada");
}

Comentando o Código 
A mesma linha de raciocínio, no entanto se a idade digitado do usuário foi menor que 18,a seguinte mensagem será apresentada ("Entrada Negada")




                                              ● Switch/Case




-Switch/Case: Ela vem como alternativa para "susbtituir os IF/ELSE", em grandes quantidades, "opções de escolha".  
 Usa-se o Switch/Case para substituir múltiplos if/elses, e de certa forma deixando o código mais organizado 

Switch = Troca
Case = Caso

Exemplo de uso 


Int   mes = 3

Switch (mes) {

Case 1 :
System.out.println (" O mês é janeiro);
Break;

Case 2 :
System.out.println (" O mês é fevereiro);
Break;

Case 3 :
System.out.println (" O mês é março);
Break;

Case 4 :
System.out.println (" O mês é abril );
Break;
         

default:
   System.out.println(“Mês inválido”);
   break;
  }


ANALISANDO O CÓDIGO 

O Switch case irá testar o valor contido na variável, comparando com cada uma das opções, determinadas pelo Case, assim quando o o valor corresponden ao valor da variável o sistema irá executar, caso nenhuma se relaciona, o último blobo (default) irá ser executado.

Obs: Cada Case precisa de uma "terminação", sendo determinada pelo palavra Break



                                        ESTRUTURA DE REPETIÇÃO

Estruturas que permitem repetir uma série de operações. Simplesmente repetir uma operação até que uma condição seja executada, também conhecidas como loops

For: estrutura na qual seu ciclo será executado por um tempo determinado, em quantidade determinada por nós.
While: diferente do FOR, o while é utilizado quando não sabemos de forma firme quantas vezes o código será repetido.


                                  * For

For = para.

Estrutura do FOR

for (<variavel de controle>, <analise da variavel>, <incremento>) {
//código determinado
}

Exemplo utilizando o FOR

public class ExemploUtilizacao {
	
    public static void main(String[] args) {
        for (int i = 0; i <= 10; i++) {
            System.out.println(“A variável i agora vale “ + i);
        }
    }
	
}

ANALISANDO O CÓDIGO

O exemplo acima retrata a situação de que "A variável i vale 0, A variável i vale 1, A variável i vale 2, A variável i vale 3..." e assim até parar na variável i valendo 10. Isso acontece porque o i tem como valor inicial 0, e logo depois foi determinado que o "limite" seria 10, quando chega no 10, a repetição para. 
A parte "i++" significa que no fim de cada execução é incrementado, somado 1.


                                 * While
 
 While = enquanto
 
 Estrutura do WHILE
 
 While (<condicao>) {
 //trecho a ser repetido
 }
 
 Exemplo utilizando o WHILE
 
 import java.util.Scanner;

public class Exemplo {
	
    public static void main(String[] args) {
        Scanner in = new Scanner(System.in);
        int numero = -1;
        while (numero != 10) { 
// enquanto a variável não for 10, o trecho de código será repetido
            System.out.println(“Digite um número: “);
            numero = in.nextInt();
            if (numero == 10) {
                System.out.println(“Você acertou!“);
            } else {
                System.out.println(“Você errou :(“);
            }
        }
    }
								   
}

ANALISANDO O CÓDIGO

O exemplo representado, é pedido para que o usuário tente advinhar o número. Enquanto não acerta, é pedido ao usuário que digite qual número ele acha que é. Este trecho sempre será repetido, até que o usuário acerte. 


                                     TIPOS DE ELEMENTOS VISUAIS NO ANDROIDSTUDIO

Existem diversos tipos de elementos visuais presentes no AndroidStudio, cada um com uma função e características diferentes. Dentro muitos existem os principais, são eles:

TextView = utilizado como caixa de texto;
Button = utilizado  


TIPO CONTAINERS - Spinner
Representa uma ComboBox 
O Spinner permite selecionar um valor de um conjunto de dados




TIPO HELPERS - Group





TIPO GOOGLE - Adview




TIPO LEGACY - Gridlayout
