Página Pessoal — Desenvolvimento Web (ARA0062)
Página web pessoal desenvolvida inteiramente à mão como parte das atividades práticas da disciplina de Desenvolvimento Web (ARA0062) do curso de Ciência da Computação no Centro Universitário Newton Paiva.

O projeto foca na separação clara de responsabilidades no front-end: estruturação semântica e acessível com HTML5, estilização e responsividade com CSS3, e manipulação dinâmica de DOM com JavaScript puro (Vanilla JS) seguindo o princípio de progressive enhancement (melhoria progressiva).

🚀 Funcionalidades
Estrutura Semântica & Acessibilidade:

Uso de tags semânticas (<header>, <nav>, <main>, <section>, <aside>, <footer>).

Formulário acessível com <label>, <fieldset>, <legend> e atributos de validação nativos.

Alerta em tempo real com aria-live="polite" para leitores de tela.

Tipografia Otimizada: Integração com Google Fonts (Poppins) utilizando preconnect para acelerar o carregamento.

Alternador de Tema (Claro / Escuro): Alternância dinâmica do arquivo de folha de estilos tema-noite.css via manipulação do atributo disabled pelo JavaScript.

Saudação Dinâmica: Script que ajusta a mensagem do cabeçalho de acordo com o contexto/horário.

Contador de Caracteres em Tempo Real: Monitoramento dinâmico do <textarea>, calculando os caracteres restantes com base no atributo maxlength="500".

Tabela de Horários Semestrais: Organização das aulas com tags estruturadas (<thead>, <tbody>, <caption>, th scope).

📂 Estrutura de Arquivos
Plaintext
├── index.html            # Estrutura e conteúdo semântico da página
├── css/
│   ├── estilo.css        # Folha de estilo padrão (tema claro)
│   └── tema-noite.css    # Sobrescrita de regras para o tema escuro
├── js/
│   └── script.js         # Lógica de saudação, tema e contador
└── img/
    └── foto.jpg          # Imagem exibida na seção de gostos
🛠️ Tecnologias Utilizadas
HTML5

CSS3

JavaScript (ES6+)

Google Fonts

💻 Como Executar o Projeto
Clone o repositório ou faça o download dos arquivos:

Bash
git clone https://github.com/seu-usuario/seu-repositorio.git
Certifique-se de manter a hierarquia de pastas descrita acima.

Abra o arquivo index.html em qualquer navegador web moderno (Google Chrome, Firefox, Edge, etc.) ou utilize a extensão Live Server no Visual Studio Code.

👤 Autora
Raquel Pacheco Mendes

Curso: Ciência da Computação — Centro Universitário Newton Paiva

Semestre: 2026/2
