# Calculadora - Aplicação de Calculadora com Interface Gráfica

Este é um projeto de uma calculadora simples com interface gráfica, implementada em Java. A aplicação permite que os usuários realizem operações matemáticas básicas, como soma, subtração, multiplicação e divisão, por meio de uma interface gráfica intuitiva.

# Funcionalidades

- Operações Básicas: A calculadora suporta operações de soma, subtração, multiplicação e divisão.
- Interface Gráfica (GUI): A interface gráfica é construída com o uso de JFrame, JButton e outros componentes Swing para criar uma interface amigável ao usuário.
- Limpeza de Tela: O usuário pode limpar a tela da calculadora e reiniciar as operações.
- Exibição de Resultados: O resultado das operações é exibido diretamente na tela da calculadora.

# Requisitos  

- DK 11 ou superior
- Ambiente de desenvolvimento de sua escolha (IDE como IntelliJ, Eclipse, NetBeans ou terminal)
- Biblioteca Swing (já incluída no JDK)

# Como Rodar o Projeto

1. Clonar o Repositório
- Clone este repositório para sua máquina local:

``` bash
git clone https://github.com/seu-usuario/calculadora-java.git
```

2. Compilar e Rodar
- Importe o projeto na sua IDE favorita (IntelliJ, Eclipse, NetBeans).
- Execute a classe App.java como um programa Java.
- Navegue até o diretório do projeto e compile os arquivos .java:

``` bash
javac App.java Tela.java Calculadora.java
```

- Execute a classe App para iniciar a aplicação da calculadora:

``` bash
java App
```

3. Estrutura do Código
- App.java: Classe principal que inicializa e exibe a interface gráfica da calculadora, gerenciando os eventos dos botões.
- Tela.java: Classe que define a interface gráfica da calculadora, incluindo os botões, o visor e a disposição da tela.
- Calculadora.java: Contém a lógica para realizar as operações matemáticas. Essa classe é responsável por processar os cálculos com base nos números inseridos pelo usuário.
