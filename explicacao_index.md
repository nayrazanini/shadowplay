# explicacao_index.html - ShadowPlay

Este arquivo HTML representa a **página inicial do projeto ShadowPlay**, um site colaborativo para prática de inglês com vídeos do YouTube e a técnica de shadowing.

---
## 🧠 Estrutura Geral do Código

### `<!DOCTYPE html>` e `<html>`
- Define que o documento é um HTML5.
- A tag `<html lang="en">` indica que o conteúdo está em inglês (padrão web internacional).

## <head> – Cabeçalho invisível da página

```html
<meta charset="UTF-8" />
```
- Define a codificação de caracteres. `UTF-8` permite usar acentos corretamente.

```html
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
```
- Garante que a página se ajuste corretamente em dispositivos móveis (responsividade).

```html
<title>ShadowPlay - Prática de Inglês com Vídeos</title>
```
- O título que aparece na aba do navegador.

---

## <style> – Estilização CSS

- O CSS está embutido no próprio HTML para facilitar o uso inicial.
- Estiliza:
  - Cores (azul escuro, branco, cinza)
  - Espaçamentos e margens
  - Aparência dos cartões de vídeo
  - Layout responsivo e limpo

---

## <body> – Corpo visível do site

### <header>
```html
<header>
  <h1>ShadowPlay</h1>
  <p>Pratique inglês com vídeos e a técnica de shadowing</p>
</header>
```
- Mostra o nome do site e seu propósito.
- Tem fundo azul escuro e texto branco para destaque.

---

### <main> – Conteúdo principal

#### Seção 1: Explicação

```html
<section>
  <h2>Como Funciona?</h2>
  <p>Assista a vídeos curtos, repita as frases...</p>
</section>
```
- Informa o usuário como usar o site.

#### Seção 2: Exibição de vídeo

```html
<iframe src="https://www.youtube.com/embed/NiTSZ3cs1zA" ...></iframe>
```
- Incorpora um vídeo do YouTube usando embed (forma legal e oficial).

```html
<div class="transcription">...</div>
```
- Exibe a transcrição do vídeo, para que o usuário acompanhe e pratique o shadowing.

---

## <footer>
```html
<footer>
  ShadowPlay © 2025 - Projeto Educacional Colaborativo
</footer>
```
- Rodapé com nome do projeto e indicação de que é um site educativo.

---

## ✅ Objetivo deste arquivo

Este HTML é ideal para:
- Testar o layout inicial do projeto.
- Praticar estrutura sem frameworks.
- Publicar diretamente no GitHub Pages.
