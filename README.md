# DIO - Trilha Java Básico  
# 🔢 Desafio: Controle de Fluxo com Contador Personalizado

Este projeto foi desenvolvido como parte do bootcamp da **[DIO (Digital Innovation One)](https://www.dio.me/)**, com o objetivo de praticar os conceitos de **controle de fluxo** em Java, como estruturas condicionais, laços de repetição e tratamento de **exceções customizadas**.

---

## 📋 Descrição do desafio

> Crie um programa Java que receba dois parâmetros inteiros via terminal.  
> O sistema deve calcular a diferença entre eles e realizar uma contagem (usando `for`) com base nessa diferença.

- ✅ O programa deve **imprimir no console** os números de 1 até a diferença entre os dois valores informados.
- ✅ Caso o **primeiro número seja maior** que o segundo, deve ser lançada uma **exceção customizada** chamada `ParametrosInvalidosException` com a mensagem:
> `"O segundo parâmetro deve ser maior que o primeiro"`

---

### 🧪 Exemplo de execução:

**Entrada:**
```
Digite o primeiro parâmetro
5
Digite o segundo parâmetro
10
```
**Saída:**
``` 
Imprimindo o número 1
Imprimindo o número 2
Imprimindo o número 3
Imprimindo o número 4
Imprimindo o número 5
``` 

Se o usuário digitar valores invertidos (ex: 10 e 5), a saída será:
```
"O segundo parâmetro deve ser maior que o primeiro"
```
---

## 🚀 Tecnologias utilizadas

- **Java 21 LTS** (JDK 21)
- **AWS Corretto 21.0.7** (distribuição do OpenJDK mantida pela Amazon)
- IDE: IntelliJ IDEA / Eclipse / VS Code (opcional)
- Terminal para entrada e saída de dados

---

## 📦 Como executar o projeto

1. Clone o repositório:
```bash
git clone https://github.com/AllenJordan01/controle-fluxo.git
```

2. Acesse a pasta do projeto:
```bash
cd controle-fluxo/DesafioControleFluxo
```

3. Verifique se possui o Java JDK 21 instalado (ou JDK 17+, se preferir). Este projeto foi desenvolvido usando o AWS Corretto 21.

4. Compile os arquivos
```bash
javac Contador.java ParametrosInvalidosException.java
```

5. Execute o programa:
```bash
java Contador
```
