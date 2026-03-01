# GUIA DE TRABALHO E COLABORAÇÃO NO GITHUB

Este documento descreve o fluxo de trabalho (GitHub Flow), as formas de colaboração e as melhores práticas para manter um repositório saudável.

---

## 1. O FLUXO DE TRABALHO (GITHUB FLOW)

O GitHub Flow é um modelo leve baseado em branches que suporta entregas contínuas.

### Passos do Processo:
1. **Crie uma Branch:** Nunca trabalhe na 'main'. Use nomes como 'feature/nome' ou 'fix/nome'.
2. **Adicione Commits:** Salve suas alterações com mensagens claras.
3. **Abra um Pull Request (PR):** Inicie a discussão sobre suas mudanças.
4. **Revisão:** Aguarde o feedback e aprovação de colegas.
5. **Merge:** Após aprovado, o código é mesclado à branch principal.

---

## 2. FORMAS DE COLABORAÇÃO

* **Modelo de Repositório Compartilhado:** Comum em empresas. Todos têm acesso ao mesmo projeto e criam branches nele.
* **Modelo Fork & Pull:** Usado em Open Source. Você clona o projeto para sua conta, altera e depois envia um PR para o dono original.

---

## 3. BOAS PRÁTICAS

### Commits
- Use o padrão de Commits Convencionais:
  * feat: para novas funcionalidades.
  * fix: para correção de bugs.
  * docs: para mudanças na documentação.
- Faça commits pequenos e frequentes (Commits Atômicos).

### Branches
- Mantenha sua branch atualizada com a 'main' para evitar conflitos.
- Delete a branch após o merge para manter o repositório limpo.

### Pull Requests
- Descreva o que você fez no PR.
- Adicione prints ou GIFs se houver mudanças visuais.
- Peça a revisão de pelo menos um colega.

---

## 4. FERRAMENTAS ÚTEIS

* **Issues:** Para relatar bugs ou sugerir tarefas.
* **Projects:** Quadros Kanban para organizar quem faz o quê.
* **Actions:** Para automação de testes e deploy.

---
> Nota: A branch 'main' deve estar sempre estável e pronta para uso.