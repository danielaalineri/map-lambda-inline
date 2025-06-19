# 🔠 Transformação de Nomes com Function e Lambda (Java)

Este projeto em Java demonstra o uso da interface funcional `Function<T, R>` com **expressão lambda** para converter os nomes de produtos 
de uma lista para letras maiúsculas, utilizando a API de Streams.

---

## 🚀 Objetivo

- Criar uma nova lista contendo os nomes dos produtos em letras maiúsculas.
- Utilizar `Function<Product, String>` com expressão lambda.
- Praticar a transformação de dados com `Stream.map()`.

---

## 🧩 Estrutura do Projeto

src/
├── app/
│ └── Program.java // Classe principal
├── entities/
│ └── Product.java // Classe representando o produto
└── util/
├── UpperCaseName.java // (opcional, não utilizado diretamente aqui)
└── PriceUpdate.java // (opcional)

---

## 🔧 Como funciona

1. O programa cria uma lista de objetos `Product`.
2. Define uma função lambda com `Function<Product, String>` para converter o nome para maiúsculas:
   ```java
   Function<Product, String> func = p -> p.getName().toUpperCase();

   Utiliza stream().map(func) para aplicar a transformação.

Coleta os resultados com Collectors.toList() e imprime os nomes no console.

Exemplo de Saída

TV
MOUSE
TABLET
HD CASE

📚 Conceitos Utilizados

    Java 8+

    Interface funcional Function<T, R>

    Expressões lambda

    API de Streams (stream(), map(), collect())

    Estrutura de dados List

    Referência de método para saída (System.out::println)

▶️ Como Executar
Requisitos:

    JDK 8 ou superior

    IDE Java (Eclipse, IntelliJ, etc.) ou terminal

Execução via terminal:

javac app/Program.java
java app.Program

👩‍💻 Autora

Daniela Alineri 👩‍💻

  
