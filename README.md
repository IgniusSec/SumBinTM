# Binary Sum Turing Machine

Este projeto implementa uma Máquina de Turing (MT) para somar dois números binários, conforme especificado no trabalho prático da disciplina **Fundamentos Teóricos da Computação**, do curso de Ciência da Computação.

O código gerado é compatível com o simulador online disponível em:  
[https://morphett.info/turing/turing.html](https://morphett.info/turing/turing.html)

## 📄 Sobre o projeto

A MT foi projetada para receber na fita uma operação de soma binária no seguinte formato:

<num1>+<num2>=


Onde:
- `<num1>` e `<num2>` são números binários positivos,
- `+` é o operador de soma,
- `=` indica o final da operação.

**Exemplos de entrada esperada na fita:**
- `010+1100=`
- `1001+11=`
- `01001+11111=`

**Exemplos de saída esperada após execução:**
- `010+1100=1110`
- `1001+11=1100`
- `01001+11111=101000`

O cabeçote da MT começa posicionado no primeiro caractere da entrada.

## ✅ Funcionalidades

✔️ Soma de dois números binários diretamente na fita;  
✔️ Mantém a entrada original e concatena o resultado após o `=`;  
✔️ Implementação programada para ser usada no simulador online de MT.

## 🚀 Como usar

1. Acesse o [simulador de Máquina de Turing](https://morphett.info/turing/turing.html).
2. Cole a descrição da MT gerada neste projeto no campo de código do simulador.
3. Insira a fita com a operação no formato descrito (ex.: `010+1100=`).
4. Execute a simulação para ver a fita com o resultado da soma binária.

## 📝 Trabalho acadêmico

Este projeto foi desenvolvido como parte do **3º Trabalho Prático** da disciplina **Fundamentos Teóricos da Computação**, ministrada pelo professor Walace de Almeida Rodrigues.

## 📚 Requisitos do trabalho

- Desenvolver uma MT que realiza a soma de inteiros binários.
- Utilizar o simulador indicado para testar a solução.
- Entregar o código da MT e demonstrar seu funcionamento em exemplos.

---

> **Observação**: O código da MT encontra-se no arquivo `turing_machine_code.txt`
