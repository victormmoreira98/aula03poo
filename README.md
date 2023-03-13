Victor Matheus, Thiago Freitas Saraiva

O que é programação orientada a objetos?
Programação orientada a objetos (POO) é um paradigma de programação que se concentra em objetos e suas interações para resolver problemas de programação. Em vez de escrever código como uma série de instruções lineares, a POO organiza o código em objetos que possuem atributos e métodos que podem ser manipulados para realizar uma tarefa específica.

Quais são os pilares da programação orientada a objetos?
Existem quatro pilares da programação orientada a objetos: encapsulamento, abstração, herança e polimorfismo. O encapsulamento é a ideia de que cada objeto deve manter seus dados e métodos privados, e só deve permitir que outras partes do programa acessem os dados e métodos relevantes. A abstração é a ideia de que você deve ser capaz de representar entidades complexas com objetos simples. A herança é a ideia de que uma classe pode herdar características de uma classe pai. O polimorfismo é a ideia de que objetos diferentes podem ser tratados de maneira semelhante, mas responder de forma diferente a métodos comuns.

O que é uma classe em Java?
Em Java, uma classe é um modelo ou uma estrutura que define as propriedades e comportamentos de um objeto. Ela é usada para criar objetos, que são instâncias dessa classe. A classe define os atributos (variáveis) que o objeto contém e os métodos (funções) que o objeto pode executar. Em outras palavras, a classe é uma definição abstrata de um objeto, e um objeto é uma instância concreta dessa definição. Classes são a base da programação orientada a objetos em Java.

Como criar um objeto a partir de uma classe em Java?
Definir a classe: crie a classe com as propriedades e métodos necessários.
Declarar um objeto: declare uma variável do tipo da classe que você deseja instanciar.
Instanciar a classe: use a palavra-chave "new" seguida do nome da classe e parênteses vazios para criar uma nova instância da classe.
Atribuir valores aos atributos: use o operador "." para atribuir valores aos atributos do objeto.
Executar métodos: use o operador "." para chamar métodos do objeto.
Por exemplo, considere a seguinte classe "Carro" com propriedades "marca" e "modelo" e um método "acelerar":

typescript
Copy code
public class Carro {
    String marca;
    String modelo;
    
    public void acelerar() {
        System.out.println("O carro está acelerando.");
    }
}
Para criar um objeto dessa classe e atribuir valores às suas propriedades, você pode fazer o seguinte:

javascript
Copy code
// Declarar o objeto
Carro meuCarro;

// Instanciar a classe
meuCarro = new Carro();

// Atribuir valores às propriedades
meuCarro.marca = "Ford";
meuCarro.modelo = "Fiesta";

// Executar um método do objeto
meuCarro.acelerar();
Nesse exemplo, você criou um objeto "Carro" chamado "meuCarro" e atribuiu valores às suas propriedades "marca" e "modelo". Em seguida, você chamou o método "acelerar" do objeto "meuCarro".

O que faz a palavra new no Java?
A palavra-chave "new" em Java é usada para criar uma nova instância de uma classe. Quando você usa a palavra-chave "new", o Java aloca memória para o novo objeto e chama o construtor da classe para inicializar o objeto. A sintaxe para usar a palavra-chave "new" é a seguinte:

java
Copy code
NomeDaClasse nomeDoObjeto = new NomeDaClasse();
Onde "NomeDaClasse" é o nome da classe que você deseja instanciar e "nomeDoObjeto" é o nome que você deseja dar ao novo objeto. Depois de usar a palavra-chave "new" para criar um novo objeto, você pode usar o objeto para acessar as propriedades e métodos da classe.

Quais as semelhanças entre Java e C?
Java e C ANSI são duas linguagens de programação com muitas semelhanças e diferenças. Ambas são linguagens de programação de propósito geral que permitem criar aplicativos para diversas finalidades, como desktop, web e mobile. Ambas possuem sintaxe semelhante, estruturas de controle de fluxo, suporte a funções, ponteiros e arrays. No entanto, a principal diferença entre as duas é que o Java é uma linguagem orientada a objetos, enquanto o C ANSI é uma linguagem de programação estruturada. Isso significa que o Java possui recursos avançados de orientação a objetos, como encapsulamento, herança e polimorfismo, enquanto o C ANSI não possui. 

Quais as diferenças entre Java e C?,
Java e C são duas linguagens de programação diferentes com diferenças significativas em sua sintaxe, recursos e aplicabilidade. Uma das principais diferenças entre Java e C é que Java é uma linguagem orientada a objetos, enquanto C é uma linguagem de programação estruturada. Java é compilado em bytecode, que é interpretado por uma máquina virtual Java (JVM), enquanto C é compilada diretamente em código de máquina.

Outra diferença é que Java possui recursos avançados de segurança, como gerenciamento automático de memória e execução em sandbox, enquanto C não oferece esses recursos, exigindo que o desenvolvedor gerencie manualmente a memória. Java também é conhecido por ser mais portátil e independente de plataforma do que C, permitindo que o código Java seja executado em diferentes sistemas operacionais.

Por fim, Java é frequentemente usado para desenvolvimento de aplicativos para a web, desenvolvimento móvel e criação de aplicativos corporativos, enquanto C é frequentemente usado para desenvolvimento de sistemas operacionais, drivers de dispositivo, aplicativos de baixo nível e outras aplicações que exigem controle de hardware e desempenho.

O que é a classe InputReader e qual é a sua função no programa?
A classe InputReader é uma classe em Java que pode ser usada para ler dados de entrada do usuário ou de um arquivo. Sua função é fornecer uma interface fácil de usar para ler entradas de dados, como números inteiros, números de ponto flutuante e strings, entre outros tipos de dados. A classe InputReader geralmente é usada para criar aplicativos interativos em que o usuário é solicitado a fornecer informações ao programa. Com a classe InputReader, os programadores podem evitar a leitura direta de dados do sistema padrão de entrada, o que pode ser mais complexo e suscetível a erros. Em resumo, a classe InputReader simplifica a leitura de entrada de dados em Java e é útil para criar aplicativos interativos.

Qual é a finalidade do método readDouble na classe InputReader?
O método readDouble na classe InputReader é usado para ler um número de ponto flutuante (double) da entrada do usuário ou de um arquivo. A finalidade do método é permitir que os programadores obtenham um número de ponto flutuante específico da entrada do usuário e usem esse número em seu programa. Quando chamado, o método espera que o usuário forneça um número de ponto flutuante válido e, em seguida, o retorna como um double. Se o usuário fornecer uma entrada inválida, o método lançará uma exceção, indicando que o valor fornecido não pode ser convertido em um double. Em resumo, o método readDouble na classe InputReader é usado para ler números de ponto flutuante (double) da entrada do usuário ou de um arquivo e é útil para criar aplicativos que requerem entrada de números de ponto flutuante.

O que é a interface PaymentType e como ela é utilizada no programa?
A interface PaymentType é um contrato em Java que define diferentes tipos de pagamento que podem ser aceitos em um sistema de pagamento. Ela fornece uma forma de implementar diferentes tipos de pagamento como classes e permite que o programa processe e gerencie esses pagamentos de forma unificada, independente do tipo de pagamento que está sendo usado.


