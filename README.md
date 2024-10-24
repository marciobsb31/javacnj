# RESUMO
Resumo do curso de java do CNJ
# MOD1
# MOD 2
 estrutura Java é uma linguagem de programação orientada a objetos; é um modelo de programação onde diversas classes possuem características que definem um objeto na vida real. A estrutura básica do Java são os arquivos fonte , as classes e metodos.
###Arquivo fonte:
É o arquivo de texto que contém o código-fonte Java e normalmente possui a extensão .java.
Cada arquivo fonte pode conter uma ou mais classes, interfaces ou enumerações, mas normalmente segue a convenção de conter uma única classe pública, e o nome do arquivo deve coincidir com o nome dessa classe pública.
Exemplo: Se você tem uma classe pública chamada MinhaClasse, o arquivo fonte deve ser chamado *MinhaClasse.java.*

## Classes:
São blocos de código que servem como a estrutura básica do programa. Uma classe define o comportamento (métodos) e os estados (atributos/variáveis) que os objetos daquela classe podem ter.
As classes podem ser públicas (acessíveis de qualquer parte do programa) ou privadas (acessíveis apenas dentro de certos limites).
Uma classe pode conter outros elementos como métodos, variáveis, construtores e blocos estáticos.

public class Carro {
    String modelo;
    int ano;

    void acelerar() {
        System.out.println("O carro está acelerando");
    }
}

## Métodos:

São blocos de código dentro de uma classe que realizam uma tarefa ou operação específica. Eles definem o comportamento dos objetos da classe.
Um método pode receber parâmetros e retornar um valor, convecionalmente no infinitivo.
Métodos são chamados para executar ações sobre os objetos da classe.
Exemplo de método.

public void acelerar() {
    System.out.println("Acelerando...");
}

## Resumindo:

*O arquivo fonte* é o arquivo que contém o código Java (.java).
*As classes* são as estruturas que definem os objetos no programa.
*Os métodos* são ações ou comportamentos que podem ser executados pelas classes ou pelos seus objetos.

