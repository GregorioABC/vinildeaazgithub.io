# 🎵 Vinil de A a Z — Site

Site de apresentação da loja **Vinil de A a Z**, pronto para publicar no GitHub Pages.

---

## 📁 Estrutura de arquivos

```
vinil-de-a-a-z/
├── index.html   ← site completo
├── logo.png     ← logo da loja
└── README.md    ← este arquivo
```

---

## ⚙️ Antes de publicar: configure o site

Abra o `index.html` e edite as duas variáveis no `<script>` no final do arquivo:

```js
// Linha ~220
const WHATSAPP_NUMERO = '5585999999999'; // ← seu número (DDI + DDD + número)

// Linha ~229
const TOTAL_VINIS = 500; // ← quantidade real do seu acervo
```

**Formato do número:** só dígitos, sem espaços ou traços.  
Exemplo: Brasil (55) + Fortaleza (85) + número = `5585912345678`

---

## 🚀 Como publicar no GitHub Pages (passo a passo)

### 1. Crie uma conta no GitHub
Acesse [github.com](https://github.com) e crie uma conta gratuita.

### 2. Crie um repositório novo
- Clique em **"New repository"** (botão verde)
- Nome sugerido: `vinil-de-a-a-z`
- Deixe como **Public**
- Clique em **"Create repository"**

### 3. Faça upload dos arquivos
Na página do repositório vazio:
- Clique em **"uploading an existing file"**
- Arraste os 3 arquivos: `index.html`, `logo.png`, `README.md`
- Clique em **"Commit changes"**

### 4. Ative o GitHub Pages
- Vá em **Settings** (engrenagem no menu do repositório)
- No menu lateral, clique em **Pages**
- Em **"Branch"**, selecione `main` e pasta `/ (root)`
- Clique em **Save**

### 5. Acesse seu site 🎉
Em 1-2 minutos seu site estará em:
```
https://SEU-USUARIO.github.io/vinil-de-a-a-z/
```

---

## ✏️ Como atualizar o site depois

Para editar qualquer coisa (textos, número, acervo):
1. Vá ao repositório no GitHub
2. Clique no arquivo `index.html`
3. Clique no ícone de lápis (editar)
4. Faça as alterações e clique em **"Commit changes"**

O site atualiza automaticamente em ~30 segundos.

---

## 🔒 Segurança

- **Nenhuma senha** ou chave secreta está no código
- O número de WhatsApp fica visível no HTML (isso é normal para sites públicos)
- O GitHub Pages serve apenas arquivos estáticos — sem servidor próprio, sem banco de dados
- Para segurança extra, ative a opção **"Enforce HTTPS"** nas configurações do Pages

---

## 🎨 Personalização rápida

| O que mudar | Onde fica no `index.html` |
|---|---|
| Número WhatsApp | `const WHATSAPP_NUMERO = '...'` |
| Quantidade de vinis | `const TOTAL_VINIS = 500` |
| Nome da loja | Tags `<title>` e `<h1>` |
| Categorias dos cards | Elementos `.card-genre` e `.card-title` |
| Texto "Sobre nós" | Dentro de `.about-text` |
| Ano no rodapé | Dentro de `<footer>` |
