# 🎬 Projeto 4: Página de Filme

Quarto projeto do curso da **EBAC**, desenvolvido por [DiegoNT1](https://github.com/DiegoNT1).

EsEste projeto consiste na criação de uma **página dedicada ao filme Duna: Parte 2**, com layout visual moderno e foco na apresentação de conteúdo cinematográfico utilizando **HTML**, **CSS (SCSS)**.

🔗 **Visualize online:**  
👉 [https://projeto-4-filme-five.vercel.app](https://projeto-4-filme-five.vercel.app)

---

## 🎥 Visão Geral

A página apresenta um filme com os seguintes elementos:

- 🖼️ Imagem de destaque (capa/poster)
- 📝 Sinopse.
- 🎞️ Trailer.
- 🎨 Design estilizado com foco na estética cinematográfica
- 🎭 Elenco com imagens e personagens
- ⭐ Formulário para avaliação do filme

---

## 🚀 Tecnologias Utilizadas

- **HTML5** – estrutura semântica
- **CSS3** – design visual e responsividade
- **Sass (SCSS)** – organização e compilação dos estilos
- **Fontes personalizadas** – identidade visual do projeto
- **Gulp** – automação de tarefas e build
- **Vercel** – deploy da aplicação

---

## 📁 Estrutura do Projeto

```bash
Projeto_4_Filme/
├── assets/
│   └── fonts/               # Fontes personalizadas
├── src/
│   ├── images/              # Imagens do filme e atores
│   └── styles/              # Arquivos SCSS
│       ├── _actors.scss
│       ├── _footer.scss
│       ├── _hero.scss
│       ├── _review.scss
│       ├── _synopsis.scss
│       ├── _trailer.scss
│       ├── _variaveis.scss
│       └── main.scss
├── dist/                    # Arquivos gerados pelo Gulp
├── index.html
├── gulpfile.js
├── package.json
└── package-lock.json
```


---

## 🧪 Como Usar Localmente

```bash
# 1. Clone este repositório
git clone https://github.com/DiegoNT1/Projeto_4_Filme.git

# 2. Acesse a pasta do projeto
cd Projeto_4_Filme

# 3. Instale as dependências
npm install

# 4. Gere os arquivos de CSS e imagens
npm run build

# 5. Abra o index.html utilizando o Live Server do VSCode
```
