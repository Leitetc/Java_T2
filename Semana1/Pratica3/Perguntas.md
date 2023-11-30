# 1 O que é uma exceção em Java e qual é o propósito de usá-las em programas?

>Em Java, uma exceção é um evento que ocorre durante a execução do programa, interrompendo o fluxo normal de instruções. O objetivo fundamental das abordagens é lidar com erros e situações específicas de maneira estruturada, melhorando a robustez do código. Eles permitem que o código esteja sujeito a erros seja colocado em blocos “try”, com tratamento específico em blocos “catch”. As soluções ajudam a separar o código de tratamento de erros do código principal, facilitando a manutenção e a compreensão do programa. Além disso, suportamos uma posição que permite lidar com diferentes categorias de problemas de forma eficiente.


# 2. Pesquise sobre a diferença entre exceções verificadas e não verificadas em Java. Dê exemplos de cada uma.

>São propostas que o compilador não verifica durante a compilação.
>Geralmente apresentam erros de programação, como divisão por zero ou acesso a índices inválidos.
>Não exclua declarações "throws" ou blocos "try-catch".
>Exemplo: ArithmeticExceptioné uma exceção não verificada que ocorre em operações aritméticas inválidas.

>public class ExemploUncheckedException {
 
 >   public static void main(String[] args) {
  
  >
  
  >      int resultado = 10 / 0; // Isso causará uma ArithmeticException
   
   > }

>}

# 3. Como você pode lidar com exceções em Java? Quais são as palavras-chave e as práticas comuns para tratamento de exceções?


# 4. O que é o bloco "try-catch" em Java? Como ele funciona e por que é importante usá-lo ao lidar com exceções?


# 5. Quando é apropriado criar suas próprias exceções personalizadas em Java e como você pode fazer isso? Dê um exemplo de quando e por que você criaria uma exceção personalizada.

