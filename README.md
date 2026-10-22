<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>README — Raquel Pacheco Mendes | Página Pessoal</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700&family=JetBrains+Mono:wght@400;500&display=swap" rel="stylesheet">
  <style>
    :root {
      --bg: #0d1117;
      --card-bg: #161b22;
      --border: #30363d;
      --text: #c9d1d9;
      --text-heading: #f0f6fc;
      --text-muted: #8b949e;
      --accent: #58a6ff;
      --accent-hover: #79c0ff;
      --code-bg: #1f242c;
      --tag-bg: #21262d;
      --success: #3fb950;
    }

    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: 'Poppins', -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
      background-color: var(--bg);
      color: var(--text);
      line-height: 1.6;
      padding: 2.5rem 1rem;
      display: flex;
      justify-content: center;
    }

    .container {
      width: 100%;
      max-width: 860px;
      background-color: var(--card-bg);
      border: 1px solid var(--border);
      border-radius: 12px;
      padding: 2.5rem;
      box-shadow: 0 8px 24px rgba(0, 0, 0, 0.4);
    }

    header {
      border-bottom: 1px solid var(--border);
      padding-bottom: 1.5rem;
      margin-bottom: 2rem;
    }

    h1 {
      color: var(--text-heading);
      font-size: 2rem;
      font-weight: 700;
      margin-bottom: 0.5rem;
    }

    .badges {
      display: flex;
      flex-wrap: wrap;
      gap: 0.5rem;
      margin-top: 1rem;
    }

    .badge {
      font-family: 'JetBrains Mono', monospace;
      font-size: 0.75rem;
      padding: 0.25rem 0.6rem;
      border-radius: 20px;
      background-color: var(--tag-bg);
      border: 1px solid var(--border);
      color: var(--text-muted);
      display: inline-flex;
      align-items: center;
      gap: 0.4rem;
    }

    .badge.active {
      border-color: rgba(63, 185, 80, 0.4);
      color: var(--success);
    }

    h2 {
      color: var(--text-heading);
      font-size: 1.35rem;
      font-weight: 600;
      margin-top: 2rem;
      margin-bottom: 1rem;
      border-bottom: 1px solid var(--border);
      padding-bottom: 0.4rem;
      display: flex;
      align-items: center;
      gap: 0.5rem;
    }

    h3 {
      color: var(--text-heading);
      font-size: 1.1rem;
      font-weight: 600;
      margin: 1.25rem 0 0.5rem;
    }

    p {
      margin-bottom: 1rem;
      color: var(--text);
    }

    a {
      color: var(--accent);
      text-decoration: none;
    }

    a:hover {
      color: var(--accent-hover);
      text-decoration: underline;
    }

    ul, ol {
      margin-left: 1.5rem;
      margin-bottom: 1.25rem;
    }

    li {
      margin-bottom: 0.35rem;
    }

    .task-list {
      list-style: none;
      margin-left: 0;
    }

    .task-list li {
      display: flex;
      align-items: flex-start;
      gap: 0.6rem;
      margin-bottom: 0.5rem;
    }

    .task-check {
      color: var(--success);
      font-weight: bold;
    }

    pre {
      background-color: var(--code-bg);
      border: 1px solid var(--border);
      border-radius: 8px;
      padding: 1rem;
      overflow-x: auto;
      font-family: 'JetBrains Mono', monospace;
      font-size: 0.85rem;
      color: #e6edf3;
      margin: 1rem 0 1.25rem;
    }

    code {
      font-family: 'JetBrains Mono', monospace;
      font-size: 0.85rem;
      background-color: var(--code-bg);
      padding: 0.2rem 0.4rem;
      border-radius: 4px;
      border: 1px solid var(--border);
      color: var(--accent);
    }

    pre code {
      background: none;
      border: none;
      padding: 0;
      color: inherit;
    }

    table {
      width: 100%;
      border-collapse: collapse;
      margin: 1.25rem 0;
      font-size: 0.9rem;
    }

    th, td {
      border: 1px solid var(--border);
      padding: 0.75rem 1rem;
      text-align: left;
    }

    th {
      background-color: var(--tag-bg);
      color: var(--text-heading);
      font-weight: 600;
    }

    .author-card {
      background: var(--tag-bg);
      border: 1px solid var(--border);
      border-radius: 8px;
      padding: 1.25rem;
      margin-top: 1rem;
    }

    .author-card p {
      margin-bottom: 0.4rem;
    }

    .author-card p:last-child {
      margin-bottom: 0;
    }
  </style>
</head>
<body>

  <main class="container">
    <header>
      <h1>Raquel Pacheco Mendes — Página Pessoal</h1>
      <p>
        Página pessoal desenvolvida como projeto prático na disciplina 
        <strong>ARA0062 (Desenvolvimento Web)</strong> do curso de 
        <strong>Ciência da Computação</strong> no 
        <strong>Centro Universitário Newton Paiva</strong>.
      </p>
      <div class="badges">
        <span class="badge active">● Semestre 2026/2</span>
        <span class="badge">HTML5 Semântico</span>
        <span class="badge">CSS3 Puro</span>
        <span class="badge">Vanilla JS</span>
        <span class="badge">Progressive Enhancement</span>
      </div>
    </header>

    <section id="visao-geral">
      <h2>📌 Visão Geral</h2>
      <p>
        O projeto segue o princípio de <strong>Melhoria Progressiva</strong> (<em>Progressive Enhancement</em>),
        garantindo que toda a estrutura semântica e acessibilidade da página funcionem de forma plena
        mesmo antes da ativação dos recursos de estilização dinâmica e scripts client-side.
      </p>
      <ul>
        <li><strong>HTML5:</strong> Estrutura de conteúdo, formulários semânticos e tags estruturais nativas.</li>
        <li><strong>CSS3:</strong> Design visual, variáveis e alternância de temas via especificidade da cascata.</li>
        <li><strong>JavaScript (ES6):</strong> Manipulação de DOM limpa e não obstrutiva.</li>
      </ul>
    </section>

    <section id="funcionalidades">
      <h2>🚀 Funcionalidades</h2>
      <ul class="task-list">
        <li>
          <span class="task-check">✔</span>
          <span><strong>Navegação Semântica:</strong> Estruturação com <code>&lt;header&gt;</code>, <code>&lt;nav&gt;</code>, <code>&lt;main&gt;</code>, <code>&lt;section&gt;</code>, <code>&lt;aside&gt;</code> e <code>&lt;footer&gt;</code>.</span>
        </li>
        <li>
          <span class="task-check">✔</span>
          <span><strong>Alternância de Tema (Light / Dark):</strong> Controle do arquivo <code>tema-noite.css</code> através da manipulação da propriedade <code>disabled</code> via JavaScript.</span>
        </li>
        <li>
          <span class="task-check">✔</span>
          <span><strong>Saudação Dinâmica:</strong> Texto do cabeçalho alterado dinamicamente com base no horário do sistema, com fallback estático nativo ("Olá!").</span>
        </li>
        <li>
          <span class="task-check">✔</span>
          <span><strong>Contador de Caracteres Acessível:</strong> Acompanhamento dinâmico do limite do <code>&lt;textarea&gt;</code> anunciado via leitores de tela com <code>aria-live="polite"</code>.</span>
        </li>
        <li>
          <span class="task-check">✔</span>
          <span><strong>Tabela Estruturada:</strong> Quadro de aulas com semântica completa (<code>&lt;caption&gt;</code>, <code>&lt;thead&gt;</code>, <code>&lt;tbody&gt;</code>, <code>scope="col"</code> e <code>scope="row"</code>).</span>
        </li>
        <li>
          <span class="task-check">✔</span>
          <span><strong>Formulário com Validação Nativa:</strong> Agrupamento com <code>&lt;fieldset&gt;</code> e <code>&lt;legend&gt;</code>, campos obrigatórios nativos (<code>required</code>) e tipos apropriados.</span>
        </li>
      </ul>
    </section>

    <section id="arquitetura">
      <h2>📂 Arquitetura de Diretórios</h2>
      <pre><code>meu-site/
├── index.html              # Documento principal estruturado em HTML5
├── css/
│   ├── estilo.css          # Folha de estilos base (tema padrão/claro)
│   └── tema-noite.css      # Folha de estilos alternativa (tema escuro)
├── js/
│   └── script.js           # Lógica cliente (saudação, tema e contador)
└── img/
    └── foto.jpg            # Imagem do campus Newton Paiva</code></pre>
    </section>

    <section id="tecnicas">
      <h2>🛠️ Técnicas Implementadas</h2>
      
      <h3>Otimização de Web Fonts</h3>
      <p>
        O carregamento da família tipográfica <strong>Poppins</strong> realiza pré-conexão com os servidores do Google Fonts, evitando bloqueios na renderização:
      </p>
      <pre><code>&lt;link rel="preconnect" href="https://fonts.googleapis.com"&gt;
&lt;link rel="preconnect" href="https://fonts.gstatic.com" crossorigin&gt;
&lt;link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet"&gt;</code></pre>

      <h3>Carregamento Diferido de Script</h3>
      <p>
        Uso do atributo <code>defer</code> para assegurar que a execução do script ocorra estritamente após a conclusão do parse do documento:
      </p>
      <pre><code>&lt;script src="js/script.js" defer&gt;&lt;/script&gt;</code></pre>

      <h3>Separação Estrita de Responsabilidades</h3>
      <p>
        Zero eventos inline (como <code>onclick=""</code>) ou estilos diretos (<code>style=""</code>). O HTML atua estritamente como estrutura e conteúdo.
      </p>
    </section>

    <section id="como-executar">
      <h2>💻 Como Executar o Projeto</h2>
      <ol>
        <li>Clone este repositório:
          <pre><code>git clone https://github.com/seu-usuario/pagina-pessoal.git</code></pre>
        </li>
        <li>Entre no diretório:
          <pre><code>cd pagina-pessoal</code></pre>
        </li>
        <li>Abra o arquivo <code>index.html</code> no navegador ou sirva localmente com o Live Server do VS Code ou via Python:
          <pre><code>python3 -m http.server 8000</code></pre>
        </li>
      </ol>
    </section>

    <section id="autoria">
      <h2>👤 Autoria</h2>
      <div class="author-card">
        <p><strong>Desenvolvedora:</strong> Raquel Pacheco Mendes</p>
        <p><strong>Curso:</strong> Ciência da Computação</p>
        <p><strong>Instituição:</strong> Centro Universitário Newton Paiva</p>
        <p><strong>Disciplina:</strong> ARA0062 — Desenvolvimento Web</p>
        <p><strong>Semestre:</strong> 2026/2</p>
      </div>
    </section>
  </main>

</body>
</html>
