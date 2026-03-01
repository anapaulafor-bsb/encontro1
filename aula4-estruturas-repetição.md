# ESTRUTURAS DE REPETIÇÃO (LOOPS)

As estruturas de repetição são ferramentas da lógica de programação que permitem executar um bloco de código várias vezes até que uma condição seja atingida.

---

## 1. POR QUE USAR?

* **Eficiência:** Evita escrever o mesmo código várias vezes.
* **Automação:** Ideal para processar listas, somar valores ou validar entradas de dados.
* **Manutenção:** Facilita a alteração da lógica em um único lugar.

---

## 2. OS PRINCIPAIS TIPOS

### WHILE (Enquanto)
O código é executado ENQUANTO a condição for verdadeira. A verificação é feita no INÍCIO.
> Exemplo: Enquanto a senha estiver incorreta, peça a senha novamente.

### DO WHILE (Faça Enquanto)
O código é executado pelo menos UMA VEZ, e só depois a condição é testada.
> Exemplo: Imprima o menu de opções e depois verifique se o usuário quer sair.

### FOR (Para)
Usado quando você sabe exatamente QUANTAS VEZES quer repetir a ação. Geralmente usa um contador.
> Exemplo: Para cada aluno de uma sala de 30 pessoas, calcule a média.

---

## 3. COMPONENTES DO LOOP

Para um loop funcionar sem erros, ele precisa de:
1. **Inicialização:** Onde o contador começa (ex: i = 0).
2. **Condição de Parada:** Até onde o loop vai (ex: i < 10).
3. **Atualização:** Como o contador muda a cada volta (ex: i = i + 1).

---

## 4. CUIDADOS IMPORTANTES (PERIGO!)

* **LOOP INFINITO:** Acontece quando a condição de parada nunca é atingida. Isso faz o programa travar ou consumir toda a memória do computador.
* **ERRO DE "OFF-BY-ONE":** Quando o loop roda uma vez a mais ou a menos do que o esperado (comum ao confundir < com <=).

---
> Dica: Sempre teste seus loops com valores pequenos antes de rodar com grandes volumes de dados!