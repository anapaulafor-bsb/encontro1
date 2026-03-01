# Guia de Repositórios Remotos no Git

Um **repositório remoto** é uma versão do seu projeto hospedada em um servidor acessível pela internet ou rede interna (como GitHub, GitLab ou Bitbucket). Ele é essencial para colaboração em equipe e backup de segurança.

---

## 1. O que são?
Diferente do repositório local (que fica na sua máquina), o remoto serve como a **"fonte da verdade"**.
* **Local:** Onde você desenvolve, testa e faz commits privados.
* **Remoto:** Onde o código é compartilhado com outros desenvolvedores.



---

## 2. Comandos Essenciais

Para gerenciar a conexão entre seu computador e o servidor, utilizamos os seguintes comandos:

### Gerenciar Conexões
| Comando | Descrição |
| :--- | :--- |
| `git remote -v` | Lista os repositórios remotos conectados e suas URLs. |
| `git remote add origin <url>` | Conecta seu repositório local a um novo servidor remoto. |
| `git remote rm origin` | Remove a conexão com o repositório remoto chamado "origin". |

### Sincronização de Dados
* **`git push <nome-remoto> <branch>`**: Envia seus commits locais para o servidor.
* **`git fetch <nome-remoto>`**: Baixa o histórico do servidor, mas não altera seu código atual.
* **`git pull <nome-remoto> <branch>`**: Baixa as novidades e já faz o "merge" no seu trabalho (é a soma de `fetch` + `merge`).

---

## 3. Fluxo de Trabalho Comum

O ciclo de vida da colaboração geralmente segue este padrão:

1. **Clone:** Baixar um projeto existente pela primeira vez.
   ```bash
   git clone [https://github.com/usuario/projeto.git](https://github.com/usuario/projeto.git)