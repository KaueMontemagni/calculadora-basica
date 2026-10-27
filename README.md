# 🧮 Calculadora Básica em Python

Uma aplicação simples e didática de calculadora desenvolvida em Python, com foco no aprendizado dos conceitos fundamentais de lógica de programação. O projeto realiza as quatro operações matemáticas básicas com código limpo, modular e comentado.

---

## 🚀 Funcionalidades

- ➕ **Adição:** Soma entre dois números inteiros ou decimais.
- ➖ **Subtração:** Diferença entre dois valores.
- ✖️ **Multiplicação:** Produto entre dois fatores.
- ➗ **Divisão com Proteção:** Divisão real com tratamento preventivo contra divisão por zero (`ZeroDivisionError`).
- 🔢 **Suporte a Números Reais:** Permite a entrada de números inteiros e decimais (ponto flutuante).
- 🛡️ **Validação de Operadores:** Identifica e avisa caso o usuário informe um operador não reconhecido.

---

## ⚙️ Como a Aplicação Funciona

O programa segue o ciclo clássico de processamento de dados (**IPO - Entrada, Processamento e Saída**):

1. **Entrada de Dados (`input` + `float`):**
   - O usuário digita o primeiro número, o símbolo da operação (`+`, `-`, `*`, `/`) e o segundo número.
   - Os valores digitados são convertidos de texto (`str`) para números decimais (`float`).

2. **Identificação e Tomada de Decisão (`if / elif / else`):**
   - O programa analisa qual operador foi digitado e direciona o fluxo para a função correspondente.

3. **Cálculo Modular com Funções (`def` e `return`):**
   - Cada operação matemática é isolada em sua própria função (`somar`, `subtrair`, `multiplicar`, `dividir`).
   - A função `dividir` checa previamente se o segundo valor é zero antes de tentar calcular.

4. **Apresentação Formatada (`print` + f-strings):**
   - O resultado é exibido na tela formatado de forma limpa e legível (ex: `10.0 + 5.0 = 15.0`).
   - Caso ocorra um erro, uma mensagem amigável de orientação é apresentada.

---

## 🖥️ Exemplo de Uso no Terminal

```text
========================================
     CALCULADORA BÁSICA EM PYTHON
========================================
Operações disponíveis:
  +  -> Adição
  -  -> Subtração
  *  -> Multiplicação
  /  -> Divisão
========================================
Digite o primeiro número: 12.5
Escolha a operação (+, -, *, /): *
Digite o segundo número: 4
----------------------------------------
Resultado: 12.5 * 4.0 = 50.0
----------------------------------------

📚 Conceitos Praticados Neste Projeto
Variáveis e Tipos de Dados:Uso deflutuador (números decimais) e str (textos).
Funções (definição/retornar):Modularização e reutilização de código.
Estruturas Condicionais: Tomada de decisão com se,Elifeoutro.
Prevenção de Falhas: Tratamento de divisão por zero.
Interpolação de Strings: Formatação com f-strings (f"{variavel}").
