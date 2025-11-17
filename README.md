
# 📘 HTML Básico — Guia de Referência

Bem-vindo ao repositório da **aula de HTML básico**!
Este material serve como um **manual de consulta rápida**, apresentando as principais tags HTML, seus usos e exemplos práticos.

---

## 📚 O que é HTML?

**HTML (HyperText Markup Language)** é a linguagem usada para estruturar páginas na web.
Ela usa **tags** para indicar títulos, textos, links, imagens, listas e muito mais.

---

## 🏗 Estrutura básica de um documento HTML

```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Título da Página</title>
</head>
<body>
    <h1>Olá, mundo!</h1>
</body>
</html>
```

---

## 🏷 Principais Tags HTML

### 📄 **Tags de Estrutura**

| Tag       | Significado     | Exemplo                   |
| --------- | --------------- | ------------------------- |
| `<html>`  | Documento HTML  | `<html lang="pt-BR">`     |
| `<head>`  | Cabeçalho       | `<head>...</head>`        |
| `<body>`  | Corpo da página | `<body>...</body>`        |
| `<title>` | Título da aba   | `<title>Meu site</title>` |

---

### 📝 **Tags de Texto**

| Tag             | Função            | Exemplo                       |
| --------------- | ----------------- | ----------------------------- |
| `<h1>` a `<h6>` | Títulos           | `<h1>Título principal</h1>`   |
| `<p>`           | Parágrafo         | `<p>Texto aqui.</p>`          |
| `<br>`          | Quebra de linha   | `Olá<br>Mundo`                |
| `<strong>`      | Negrito semântico | `<strong>Importante</strong>` |
| `<em>`          | Itálico semântico | `<em>Destaque</em>`           |
| `<span>`        | Texto inline      | `<span>texto</span>`          |
| `<hr>`          | Linha divisória   | `<hr>`                        |

---

### 🔗 **Links**

```html
<a href="https://google.com">Visitar Google</a>
```

Atributos úteis:

* `target="_blank"` → abre em nova aba
* `title="Descrição"` → mostra tooltip

---

### 🖼 **Imagens**

```html
<img src="imagem.jpg" alt="Descrição da imagem">
```

Atributo `alt` é essencial para acessibilidade.

---

### 📋 **Listas**

#### Lista não ordenada

```html
<ul>
    <li>Item 1</li>
    <li>Item 2</li>
</ul>
```

#### Lista ordenada

```html
<ol>
    <li>Passo 1</li>
    <li>Passo 2</li>
</ol>
```

---

### 📦 **Div e Section**

| Tag         | Uso                            |
| ----------- | ------------------------------ |
| `<div>`     | Contêiner genérico para blocos |
| `<section>` | Seção temática                 |
| `<header>`  | Cabeçalho                      |
| `<footer>`  | Rodapé                         |
| `<main>`    | Conteúdo principal             |
| `<article>` | Conteúdo independente          |

Exemplo:

```html
<section>
    <h2>Sobre mim</h2>
    <p>Texto da seção...</p>
</section>
```

---

### 🧩 **Tabelas**

```html
<table>
    <tr>
        <th>Nome</th>
        <th>Idade</th>
    </tr>
    <tr>
        <td>Ana</td>
        <td>20</td>
    </tr>
</table>
```

---

### 📝 **Formulários**

```html
<form>
    <label>Nome:</label>
    <input type="text" placeholder="Digite seu nome">

    <label>Email:</label>
    <input type="email">

    <button type="submit">Enviar</button>
</form>
```

Tipos de `<input>` comuns:
`text`, `email`, `password`, `number`, `checkbox`, `radio`, `submit`.

---

## 🎨 Tags Semânticas Modernas

* `<header>` — cabeçalho
* `<nav>` — menu de navegação
* `<section>` — seção do site
* `<article>` — conteúdo independente
* `<aside>` — conteúdo lateral
* `<footer>` — rodapé

