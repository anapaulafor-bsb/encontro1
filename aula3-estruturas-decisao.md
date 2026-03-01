# Estruturas de Decisão na Lógica de Programação

As estruturas de decisão (ou condicionais) são fundamentais para criar fluxos lógicos em um software. Elas permitem que o programa execute diferentes instruções baseadas em condições que resultam em **Verdadeiro** ou **Falso**.

---

## 1. Estrutura Condicional Simples (`SE`)
A forma mais básica de decisão. O código só entra no bloco se a condição for atendida.


[Image of if statement flowchart]

---

## 2. Estrutura Condicional Composta (`SE / SENÃO`)
Utilizada quando temos duas alternativas: uma ação para caso a condição seja verdadeira e outra para caso seja falsa.

---

## 3. Estruturas Encadeadas (`SE / SENÃO SE / SENÃO`)
Quando precisamos verificar múltiplas condições em sequência. Assim que uma condição é atendida, as demais são ignoradas.

---

## 4. Estrutura de Escolha (`ESCOLHA / CASO`)
Ideal para quando uma variável pode assumir vários valores específicos (como um menu ou dias da semana). É mais legível que vários `SE` encadeados.

---

##  Operadores Lógicos e Relacionais

Para criar as condições dentro dos parênteses, utilizamos operadores:

### Operadores Relacionais
| Operador | Descrição |
| :---: | :--- |
| `==` | Igual a |
| `!=` | Diferente de |
| `>` | Maior que |
| `<` | Menor que |
| `>=` | Maior ou igual |
| `<=` | Menor ou igual |

### Operadores Lógicos
* **E (AND):** Resulta em verdadeiro apenas se **todas** as condições forem verdadeiras.
* **OU (OR):** Resulta em verdadeiro se **pelo menos uma** condição for verdadeira.
* **NÃO (NOT):** Inverte o valor lógico (Verdadeiro vira Falso e vice-versa).

---
> **Dica de Ouro:** No GitHub, arquivos `.md` são renderizados automaticamente. Use este arquivo para documentar seus estudos de lógica!