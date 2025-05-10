# Alura ScreenMatch

Este projeto foi desenvolvido como parte da formação em Java da Alura, com o objetivo de aplicar conceitos de programação orientada a objetos, consumo de APIs e manipulação de dados em Java.([GitHub][1])

## 📚 Descrição

O **Alura ScreenMatch** é uma aplicação Java que permite buscar e exibir informações sobre filmes e séries, utilizando dados obtidos de uma API externa. O projeto foca no aprendizado prático de:([GitHub][2])

* Modelagem de classes e hierarquias com herança e interfaces
* Consumo de APIs REST e manipulação de dados JSON
* Tratamento de exceções e manipulação de listas
* Organização de código em pacotes e boas práticas de desenvolvimento([GitHub][2])

## 🛠️ Tecnologias Utilizadas

* Java 17
* Maven
* Biblioteca GSON para serialização/desserialização de JSON
* API OMDb (The Open Movie Database)([GitHub][2], [GitHub][1])

## 📁 Estrutura do Projeto

O projeto está organizado da seguinte forma:

```

Alura-ScreenMatch/
├── .idea/
├── src/
│   └── main/
│       └── java/
│           └── br/
│               └── com/
│                   └── alura/
│                       └── screenmatch/
│                           ├── calculos/
│                           ├── excepcion/
│                           ├── modelos/
│                           └── principal/
├── .gitignore
└── pom.xml
```



* **calculos/**: Contém classes responsáveis por cálculos e filtros, como recomendação de títulos.
* **excepcion/**: Define exceções personalizadas para o projeto.
* **modelos/**: Inclui as classes que representam os modelos de dados, como filmes e séries.
* **principal/**: Contém as classes principais que executam a aplicação.([GitHub][3])

## 🚀 Como Executar

1. Certifique-se de ter o Java 17 e o Maven instalados em sua máquina.
2. Clone este repositório:([GitHub][4])

   ```bash
   git clone https://github.com/abdieldeathayde/Alura-ScreenMatch.git
   ```



3. Navegue até o diretório do projeto:

   ```bash
   cd Alura-ScreenMatch
   ```



4. Execute o projeto utilizando o Maven:

   ```bash
   mvn clean install
   mvn exec:java -Dexec.mainClass="br.com.alura.screenmatch.principal.Principal"
   ```



## 📄 Licença

Este projeto é de uso educacional e foi desenvolvido como parte dos cursos da Alura.([GitHub][4])
