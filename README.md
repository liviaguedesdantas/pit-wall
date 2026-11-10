# 🏎️ DESAFIO PIT WALL — GP de São Paulo

Projeto de estudo desenvolvido para a disciplina de **Linguagem de Marcação (LIMA)**, com o objetivo de recriar a página do GP de São Paulo de Formula 1 (Interlagos) utilizando apenas **HTML5** e **CSS3** puros, mantendo total fidelidade ao layout proposto e suporte a dispositivos móveis.

---

## 🧰 Tecnologias e Conceitos Utilizados

* **HTML5 Semantic:** Estruturação da página (`<header>`, `<main>`, `<section>`, `<table>`, `<form>`, `<footer>`).
* **CSS3 Moderno:**
  * Variáveis CSS (`:root` e `var()`) para centralizar a paleta de cores e temas das equipas.
  * **Flexbox:** Alinhamento do topo (`topbar`), conteúdo do `hero` e barra de filtros.
  * **CSS Grid (`auto-fit`):** Layout responsivo dos cards dos pilotos sem necessidade de *frameworks*.
  * **Form Grid (`form-grid`):** Organização em grelha do formulário de reserva de bilhetes.
  * **Degradê com corte seco & Zebra da pista:** Aplicação de `linear-gradient` e `repeating-linear-gradient` para os detalhes visuais da pista.
  * **Responsividade (`@media`):** Adaptação completa para ecrãs de telemóvel (ex.: 390px / 768px).
* **Google Fonts:** Importação e aplicação da fonte *Titillium Web*.

---

## 📂 Estrutura do Projeto

```text
pit-wall/
├── index.html        # Estrutura HTML da página
├── styles.css        # Estilos e regras de layout CSS
└── img/
    └── piloto.jpg    # Imagem de fundo da secção Hero

---
