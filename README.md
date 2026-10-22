# Página Pessoal — Desenvolvimento Web (ARA0062)

Página web pessoal desenvolvida inteiramente à mão como parte das atividades práticas da disciplina de **Desenvolvimento Web (ARA0062)** do curso de **Ciência da Computação** no **Centro Universitário Newton Paiva**.

O projeto adota o princípio de *progressive enhancement* (melhoria progressiva), mantendo a separação estrita de responsabilidades: marcação semântica com **HTML5**, estilização com **CSS3** e manipulação dinâmica de DOM com **JavaScript puro (Vanilla JS)**.

---

## 🚀 Funcionalidades

- **Estrutura Semântica & Acessibilidade:**
  - Marcação com tags semânticas (`<header>`, `<nav>`, `<main>`, `<section>`, `<aside>`, `<footer>`).
  - Formulário acessível utilizando `<fieldset>`, `<legend>`, `<label>` vinculados por `for`/`id` e validações nativas (`required`, `maxlength`).
  - Atualização do contador de caracteres anunciada para leitores de tela via `aria-live="polite"`.
- **Tipografia:** Integração da fonte `Poppins` via Google Fonts com otimização por `preconnect`.
- **Alternador de Tema (Claro / Escuro):** Alternância da folha de estilos `tema-noite.css` por meio do atributo `disabled` controlado via script.
- **Saudação Dinâmica:** Script em `js/script.js` para manipulação dinâmica do elemento `#saudacao`.
- **Contador de Caracteres em Tempo Real:** Leitura dinâmica do limite definido no atributo `maxlength` da `<textarea>` e exibição em `#contador`.
- **Tabela Estruturada:** Grade de horários com tags semânticas (`<thead>`, `<tbody>`, `<caption>`, `th scope="col"`, `th scope="row"`).

---

## 📂 Estrutura do Projeto

```text
├── index.html            # Estrutura e conteúdo semântico da página
├── css/
│   ├── estilo.css        # Folha de estilo padrão (tema claro)
│   └── tema-noite.css    # Regras de sobrescrita para o tema escuro
├── js/
│   └── script.js         # Lógica da saudação, tema e contador
└── img/
    └── foto.jpg          # Imagem utilizada na seção de gostos
