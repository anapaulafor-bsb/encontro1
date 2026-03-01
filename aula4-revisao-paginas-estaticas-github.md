# GITHUB PAGES: CRIANDO PÁGINAS ESTÁTICAS

O GitHub Pages é um serviço de hospedagem que permite publicar sites diretamente de um repositório no GitHub.

---

## 1. O QUE SÃO PÁGINAS ESTÁTICAS?

Diferente de sites dinâmicos (que usam banco de dados como o Facebook ou WordPress), as páginas estáticas são compostas apenas por arquivos que o navegador lê diretamente:
* HTML (Estrutura)
* CSS (Estilo/Cores)
* JavaScript (Interação)
* Imagens e fontes

---

## 2. PASSO A PASSO PARA CRIAR SUA PÁGINA

### Passo 1: O Repositório
Crie um novo repositório no seu GitHub. 
> DICA: Se o nome do repositório for 'seu-usuario.github.io', seu site ficará na página principal do seu perfil.

### Passo 2: O Arquivo Principal
Suba um arquivo chamado 'index.html' para a branch 'main'. Esse arquivo é a "capa" do seu site.

### Passo 3: Ativando o Site
1. No seu repositório, clique na aba 'Settings' (Configurações).
2. No menu à esquerda, clique em 'Pages'.
3. Em 'Build and deployment', selecione a branch 'main'.
4. Clique em 'Save'.

Aguarde alguns minutos e o GitHub fornecerá um link azul com o endereço do seu site!

---

## 3. VANTAGENS DO GITHUB PAGES

* 100% Gratuito: Sem taxas de hospedagem.
* Deploy Automático: Alterou o código e deu 'push'? O site atualiza sozinho.
* Segurança (HTTPS): Seu site já nasce com o cadeado de segurança ativado.
* Domínio Personalizado: Você pode usar o seu próprio '.com.br' se tiver um.

---

## 4. GERADORES DE SITES (SSG)

Se você não quiser escrever HTML puro, pode usar ferramentas que transformam Markdown em sites bonitos automaticamente:
* Jekyll (Já vem integrado ao GitHub)
* Hugo
* Astro

---
> Importante: O GitHub Pages não suporta linguagens de servidor como PHP, Python ou Node.js (Back-end). Ele serve apenas a interface visual (Front-end).