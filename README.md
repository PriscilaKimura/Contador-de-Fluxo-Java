# Desafio Controle de Fluxo - DIO

## Descrição

Este é um desafio prático para aplicar os conceitos de Controle de Fluxo em Java. O desafio consiste em criar um programa que recebe dois números inteiros via terminal e, com base nesses números, realiza a impressão no console de uma sequência de números incrementados.

O programa segue as seguintes regras:

1. Recebe dois números inteiros via terminal, representando dois parâmetros.
2. Calcula a quantidade de iterações (para) com base nos parâmetros fornecidos.
3. Utiliza um loop (for) para imprimir no console os números incrementados.
4. Lança uma exceção customizada chamada `ParametrosInvalidosException` se o primeiro parâmetro for MAIOR que o segundo parâmetro, com a mensagem: "O segundo parâmetro deve ser maior que o primeiro".
5. O programa deve ser organizado em um projeto chamado `DesafioControleFluxo`.
6. Dentro do projeto, crie uma classe chamada `Contador.java` para implementar a lógica do programa.
7. Crie também uma classe chamada `ParametrosInvalidosException` para representar uma exceção de negócio no sistema.

## Como Executar

Para executar o programa, siga os passos abaixo:

1. Clone o repositório em sua máquina local:

```
git clone https://github.com/seu-usuario/DesafioControleFluxo.git
```

2. Navegue até o diretório do projeto:

```
cd DesafioControleFluxo
```

3. Compile o projeto:

```
javac -d bin src/*.java
```

4. Execute o programa, fornecendo os dois números inteiros via terminal:

```
java -cp bin Contador
```

Siga as instruções no terminal e observe a saída do programa.

## Estrutura do Projeto

A estrutura de pastas e arquivos do projeto é a seguinte:

```
DesafioControleFluxo/
    src/
        Contador.java
        ParametrosInvalidosException.java
    bin/
    README.md
```

- `Contador.java`: Contém a lógica do programa que realiza a contagem e a impressão dos números.
- `ParametrosInvalidosException.java`: Classe de exceção personalizada para tratar parâmetros inválidos.
- `bin/`: Diretório onde serão armazenados os arquivos compilados.
- `README.md`: Este arquivo com informações sobre o desafio e instruções de execução.

## Contribuição

Sinta-se à vontade para contribuir com melhorias, correções de bugs ou aprimoramentos no código deste desafio. Basta criar um fork deste repositório, fazer suas alterações e enviar um pull request.

## Licença

Este projeto é distribuído sob a licença MIT. Consulte o arquivo [LICENSE](LICENSE) para obter detalhes.



