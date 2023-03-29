# AulaJava
                                       TIPOS DE DADOS EM JAVA 
  
-Tipos primitivos: byte, short, int, long, boolean, char, float, double;

BYTE: Inteiro de 8 bits;
SHORT: Inteiro de 16 bits;
INT: Inteiro de 32 bits;
LONG: Inteiro 64 bits;
BOOLEAN: Valor true ou false (Verdadeiro ou Falso);
CHAR: Caracter em notação Unicode de 16 bits;
FLOAT: Números em notação de ponto flutuante, 32 bits:
DOUBLE: Números em notação de ponto flutuante, 64 bits;



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

O Switch case irá testar o valor contido na variável, comparando com cada uma das opções, determinadas pelo Case, assim quando o o valor corresponden ao valor da variável o sistema irá executar, caso nenhuma se relaciona, o último blobo( default ) irá ser executado.

Obs: Cada Case precisa de uma "terminação", sendo determinada pelo palavra Break



                                 ESTRUTURA DE REPETIÇÃO 




