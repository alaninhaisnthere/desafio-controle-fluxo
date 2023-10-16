# Desafio Controle de Fluxo em Java (DIO)

Este projeto implementa um simples programa em Java que recebe dois números inteiros como entrada e, com base nesses números, realiza uma contagem utilizando um loop `for`. Além disso, o programa trata a exceção de negócio caso o primeiro número seja maior ou igual ao segundo.

## Funcionalidades

- Leitura de dois números inteiros a partir da entrada do terminal.
- Verificação se o primeiro número é menor que o segundo.
- Contagem e impressão dos números incrementados a partir do primeiro número até o segundo.
- Tratamento de exceção customizada (ParametrosInvalidosException) quando o primeiro número é maior ou igual ao segundo.

## Como rodar o projeto

Para executar este projeto em sua máquina, siga os passos abaixo:

### Pré-requisitos

- Você deve ter o Java Development Kit (JDK) instalado em seu computador. Você pode verificar se o JDK está instalado digitando `java -version` no seu terminal. Caso não tenha o JDK instalado, siga as instruções da seção "Instale o Java Development Kit (JDK)" deste README.

### Passos para rodar o projeto

1. Clone o repositório para o seu computador:

   ```bash
   git clone https://github.com/seu-usuario/DesafioControleFluxo.git
   ```

2. Navegue para o diretório do projeto:

   ```bash
   cd DesafioControleFluxo
   ```

3. Compile os arquivos Java:

   ```bash
   javac -d out src/Contador.java src/ParametrosInvalidosException.java
   ```

4. Execute o programa:

   ```bash
   java -cp out Contador
   ```

5. Siga as instruções no terminal para inserir os valores dos dois parâmetros (primeiro e segundo).