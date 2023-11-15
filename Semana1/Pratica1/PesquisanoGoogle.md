# **O que é uma classe em Java e qual é a diferença entre uma classe e um objeto? Dê 5 exemplos mostrando-os em C++ e em Java.**

Em Java, uma classe é um modelo para criar objetos. Ela define os atributos e comportamentos que todos os objetos desse tipo terão.

A diferença entre uma classe e um objeto é que a classe é um modelo, enquanto o objeto é uma instância concreta da classe. Um objeto é criado a partir de uma classe, e ele possui todos os atributos e comportamentos definidos na classe.

# Exemplo 1

***C++***

>Classe `Retangulo`:
``` 
class Retangulo {
public:
    double comprimento;
    double largura;
    double calcularArea() {
        return comprimento * largura;
    }
};
```
>Objeto `retangulo:` 

``` 
Retangulo retangulo;
retangulo.comprimento = 5;
retangulo.largura = 3;
cout << retangulo.calcularArea() << endl;
``` 

# Exemplo 2 
***C++***

>Classe `Livro`:
``` 
class Livro {
public:
    string titulo;
    string autor;
    int anoPublicacao;
     void imprimir() {
      cout << "titulo: " << titulo << endl;
      cout << "autor: " << autor << endl;
      cout << "anoPublicacao: " << anoPublicacao << endl;
    }
};
```
>Objeto `Livro:` 

``` 
Livro livro;
livro.titulo = "Aventuras de Sherlock Holmes";
livro.autor = "Arthur Conan Doyle";
livro.anoPublicacao = 1892;
Livro.Imprimir();
``` 

