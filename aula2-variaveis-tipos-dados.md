# Lógica de Programação: Variáveis e Tipos de Dados

Este guia prático explica os conceitos fundamentais que servem como base para qualquer linguagem de programação. Compreender como o computador armazena e processa informações é o primeiro passo para criar algoritmos eficientes.

---

##  1. O que são Variáveis?

Imagine que uma **variável** é uma pequena caixa na memória do computador. Você pode guardar algo dentro dessa caixa, dar um nome a ela e, mais tarde, abrir a caixa para ver ou alterar o que está lá dentro.

* **Identificador:** É o nome da "caixa" (ex: `idade`, `preco`, `nome_usuario`).
* **Valor:** É o conteúdo guardado (ex: `25`, `19.90`, `"Ana"`).

### Regras de Nomeação (Boas Práticas)
1.  **Sem espaços:** Use `camelCase` (ex: `minhaVariavel`) ou `snake_case` (ex: `minha_variavel`).
2.  **Autoexplicativo:** O nome deve dizer o que a variável guarda. Em vez de `x`, use `distancia_percorrida`.
3.  **Não começar com números:** A maioria das linguagens proíbe nomes como `1valor`.

---

##  2. Tipos de Dados

Cada "caixa" (variável) precisa ser de um tipo específico para que o computador saiba como lidar com ela. Os tipos principais são:

### A. Inteiro (Integer)
Números sem casas decimais. Podem ser positivos ou negativos.
* **Exemplos:** `-5`, `0`, `42`, `2024`.
* **Uso:** Contagens, idades, anos.

### B. Real / Ponto Flutuante (Float/Double)
Números com casas decimais.
* **Exemplos:** `3.14`, `-10.50`, `1.99`.
* **Uso:** Preços, coordenadas geográficas, peso, altura.

### C. Caractere / Texto (String)
Sequências de letras, números ou símbolos. Geralmente delimitadas por aspas.
* **Exemplos:** `"Olá Mundo!"`, `"usuario123"`, `"A"`.
* **Uso:** Nomes, endereços, mensagens de erro.

### D. Lógico / Booleano (Boolean)
Representa apenas dois estados possíveis: verdadeiro ou falso.
* **Exemplos:** `true` (verdadeiro), `false` (falso).
* **Uso:** Verificações (ex: `usuario_logado?`, `maior_de_idade?`).

---

##  3. Resumo Comparativo

| Tipo | Nome Comum | Exemplo | Descrição |
| :--- | :--- | :--- | :--- |
| **Inteiro** | `int` | `10` | Números inteiros |
| **Real** | `float` / `double` | `15.50` | Números decimais |
| **Texto** | `string` / `char` | `"Dev"` | Texto ou caracteres |
| **Lógico** | `boolean` | `true` | Verdadeiro ou Falso |

---

##  4. Constantes vs. Variáveis

* **Variável:** O valor pode mudar durante a execução do programa. 
    * *Exemplo:* `saldo_bancario` (muda conforme você gasta).
* **Constante:** O valor é fixo e nunca muda após ser definido.
    * *Exemplo:* `PI = 3.1415`, `DIAS_NA_SEMANA = 7`.
