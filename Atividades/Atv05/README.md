<h1>Atividade 05</h1>

<h2>Passos para resolução</h2>

- Criação da public class Atv05.
- Criação do método main.
- Inicialização das variaveis fixas.
- Inicialização da variavel com a soma dos valores.
- Printa mensagem na tela com a soma.
- Inicialização a variavel da médiaMensal, com a soma dividida pelo número de variaveis da soma.
- Printa na tela a mensagem da médiaMensal.

<h3>Código Java</h3>

~~~~
public class Atv05 { //Criação da public class Atv05
    public static void main (String[] args) { //Criação do método main
        double gastosJaneiro = 30000.00; 
        double gastosfevereiro   = 33030.77; //Inicialização das variaveis fixas 
        double gastosMarço = 23899.01;
        
        double gastosTrimestre = gastosJaneiro + gastosfevereiro + gastosMarço; //Inicialização da variavel com a soma dos valores
        System.out.println("O total de gastos do trimeste é R$ " + gastosTrimestre); //Printa mensagem na tela com a soma
        
        double mediaMensal = gastosTrimestre/3; //Inicialização a variavel da médiaMensal, com a soma dividida pelo número de variaveis da soma
        System.out.println("Valor da média mensal = "+ mediaMensal); //Printa na tela a mensagem da médiaMensal
    }
}
~~~~
