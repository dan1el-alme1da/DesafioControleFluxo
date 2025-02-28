# Projeto Contador

Este é um projeto simples em Java que solicita dois números ao usuário e realiza uma contagem do primeiro número até o segundo, desde que o segundo número seja maior que o primeiro. Caso contrário, o programa lança uma exceção personalizada.

---

## Funcionalidades

- **Validação de Parâmetros:** O programa verifica se o segundo número é maior que o primeiro. Caso contrário, uma exceção personalizada é lançada.
- **Contagem:** Se os parâmetros forem válidos, o programa conta do primeiro número até o segundo e exibe cada número no console.
- **Tratamento de Exceções:** O programa utiliza uma exceção personalizada (`ParametrosInvalidosException`) para lidar com entradas inválidas.

---

## Estrutura do Projeto

O projeto é composto por dois arquivos principais:

1. **`Contador.java`:** Contém a lógica principal do programa, incluindo a leitura dos parâmetros e a execução da contagem.
2. **`ParametrosInvalidosException.java`:** Define uma exceção personalizada para tratar casos em que o segundo parâmetro é menor ou igual ao primeiro.

---

## Como Executar o Projeto

### Pré-requisitos

- **Java Development Kit (JDK):** Certifique-se de ter o JDK instalado na sua máquina. Você pode verificar isso executando o comando `javac -version` no terminal.
- **Ambiente de Desenvolvimento:** Você pode usar qualquer IDE (como IntelliJ IDEA, Eclipse ou VSCode) ou um terminal simples.

### Passos para Execução

1. **Clone o Repositório (se aplicável):**
   Se o projeto estiver em um repositório Git, clone-o para o seu ambiente local:

   ```bash
   git clone https://github.com/dan1el-alme1da/DesafioControleFluxo.git