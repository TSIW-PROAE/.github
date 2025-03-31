<h1>PROAE - Sistema de Gestão para Pró-Reitoria de Ações Afirmativas e Assistência Estudantil</h1>
<div align="center">
<img src="../img/logo_pgcomp.png" alt="Logo PROAE" width="150">
</div>
🚀 Missão: Aprimorar a gestão da assistência estudantil da UFBA, promovendo inclusão e equidade.

✨ Visão: Ser referência em gestão de ações afirmativas e assistência estudantil, com um sistema moderno, eficiente e transparente.

Índice:

🎯 Objetivo e Contexto
✨ Funcionalidades Principais & Detalhes
🛠️ Tecnologias & Frameworks
📂 Estrutura do Projeto & Repositórios
🚀 Como Executar o Projeto (Frontend e Backend)
⚙️ Fluxo de Trabalho (Git) & Padrões de Código
🧪 Testes (Frontend e Backend)
💻 Ambiente de Desenvolvimento (Docker)
🔐 Segurança & Autenticação
📄 Documentação Detalhada & Organização
🤝 Colaboradores & Contribuições
📝 Licença & Direitos Autorais
📞 Contato & Suporte
1. 🎯 Objetivo e Contexto
Desenvolvido para a disciplina Tópicos em Sistemas de Informação e Web I (IC045/MATE85) na UFBA, o PROAE visa construir um sistema de gestão completo para a Pró-Reitoria de Ações Afirmativas e Assistência Estudantil. O projeto é mantido pela organização TSIW-PROAE no GitHub e busca centralizar informações, automatizar processos, melhorar a comunicação com estudantes e aprimorar a transparência na gestão da assistência estudantil.

2. ✨ Funcionalidades Principais & Detalhes
Requisitos Funcionais:

Centralização de Informações: Consolidar documentos, dados de estudantes e familiares, histórico de processos e pareceres em um único sistema.
Gestão de Processos Seletivos:
Cadastro de editais com baremas e documentos específicos.
Inscrições online com validação automática de documentos e análise de renda.
Emissão de pareceres com opções pré-definidas para indeferimentos.
Acompanhamento do status da inscrição e comunicação com o estudante.
Divulgação de resultados (preliminares, recursos, finais).
Validação de Documentos: Automatizar a verificação de documentos com alertas para inconsistências.
Comunicação com Estudantes: Envio de alertas, notificações e respostas automatizadas sobre o status das solicitações.
Relatórios e Análises: Geração de relatórios e análises para tomada de decisões estratégicas.
Integração com Outros Sistemas: Integração com o sistema de matrícula e outros sistemas relevantes da UFBA.
Manutenção de Histórico: Preservação de dados históricos pelo período legalmente exigido.
Requisitos Não Funcionais:

Segurança e Sigilo de Dados: Acesso restrito, níveis de sigilo para informações sensíveis e histórico de observações.
Usabilidade: Interface intuitiva e fácil de usar.
Performance: Tempo de resposta rápido e eficiente.
Escalabilidade: Capacidade de lidar com um grande volume de usuários e dados.
Disponibilidade: Sistema acessível 24/7.
Manutenibilidade: Código limpo, documentado e modular para facilitar a manutenção.
3. 🛠️ Tecnologias & Frameworks
Frontend:

React.js: Biblioteca JavaScript para construção de interfaces de usuário.
TypeScript: Superset de JavaScript que adiciona tipagem estática.
Vite: Ferramenta de build para desenvolvimento web rápido.
Backend:

Node.js: Ambiente de execução JavaScript para backend.
NestJS: Framework para construir aplicações Node.js escaláveis e eficientes.
PostgreSQL: Sistema de gerenciamento de banco de dados relacional.
Docker: Plataforma para conteinerização de aplicações.
Docker-Compose: Ferramenta para orquestrar múltiplos containers Docker.
TypeScript: Superset de JavaScript que adiciona tipagem estática.
4. 📂 Estrutura do Projeto & Repositórios
O projeto é dividido em três repositórios:

Documentação:
Contém documentos de requisitos, arquitetura, design, atas de reunião, cronogramas e outros artefatos relevantes para o projeto.
project_management/
technical_documentation/
requirements/
design/
guidelines/
references/
miscellaneous/
Use code with caution.
Frontend:
proae-frontend/
├── public/
├── src/
│   ├── assets/
│   ├── components/
│   ├── context/
│   ├── features/
│   ├── hooks/
│   ├── pages/  
│   ├── services/
│   ├── styles/
│   ├── utils/
│   ├── App.tsx
│   ├── main.tsx
│   └── setupTests.ts
├── .env
├── package.json
└── README.md
Use code with caution.
Backend:
(Estrutura detalhada não fornecida no material original)
5. 🚀 Como Executar o Projeto (Frontend e Backend)
Frontend:

Clonar o repositório: git clone https://github.com/TSIW-PROAE/proae_frontend.git
Navegar até o diretório: cd proae_frontend
Instalar dependências: npm install
Renomear .env.example para .env e configurar as variáveis de ambiente.
Iniciar o servidor de desenvolvimento: npm run dev
Backend:

Clonar o repositório: git clone https://github.com/TSIW-PROAE/proae_backend.git
Navegar até o diretório: cd proae_backend
Instalar dependências: npm install
Renomear .env.example para .env e configurar as variáveis de ambiente.
Executar o Docker Compose: docker-compose up -d
Iniciar o servidor de desenvolvimento: npm run start:dev
6. ⚙️ Fluxo de Trabalho (Git) & Padrões de Código
Gitflow: Utilização do workflow Gitflow para organização das branches (develop, feature, release, hotfix).
Pull Requests: Abertura de Pull Requests para revisão de código antes da integração com a branch principal.
Commit Messages: Padronização das mensagens de commit para clareza e organização do histórico do projeto (ex: feat: adiciona nova funcionalidade, fix: corrige bug).
Coding Standards: Definir e seguir padrões de código para garantir a qualidade e consistência do código-fonte (ex: ESLint, Prettier). (Padrões não especificados no material original)
7. 🧪 Testes (Frontend e Backend)
Frontend: Testes unitários e de integração utilizando Jest e React Testing Library.
Backend: Testes unitários e de integração utilizando Jest.
8. 💻 Ambiente de Desenvolvimento (Docker)
Utilização de Docker e Docker Compose para criar um ambiente de desenvolvimento consistente e replicável.
Configuração do ambiente através do arquivo docker-compose.yml. (Detalhes da configuração não fornecidos no material original)
9. 🔐 Segurança & Autenticação
JWT (JSON Web Tokens): Utilização de JWT para autenticação e autorização de usuários.
Controle de Acesso Baseado em Roles: Níveis de acesso diferenciados para diferentes tipos de usuários (administradores, assistentes sociais, alunos).
Medidas de segurança: Implementar medidas para prevenir ataques comuns como SQL Injection, Cross-Site Scripting (XSS) e Cross-Site Request Forgery (CSRF). (Detalhes das medidas não especificadas no material original)
10. 📄 Documentação Detalhada & Organização
Documentação da API (Backend): Utilizar Swagger para documentar a API REST, facilitando a compreensão e o uso pelos desenvolvedores frontend e por sistemas externos.
Documentação do Código: Documentar o código-fonte utilizando comentários e ferramentas como JSDoc para gerar documentação automaticamente.
Arquitetura do Sistema: Criar diagramas e descrições detalhadas da arquitetura do sistema, incluindo componentes, fluxos de dados e interações entre os módulos. (Diagramas não fornecidos no material original)
Organização da Documentação: Manter a documentação organizada e atualizada no repositório proae_documents, seguindo a estrutura de pastas definida.
11. 🤝 Colaboradores & Contribuições
Frontend:

Hevelin Freitas: [Link para o GitHub]
Mauricio Menezes: [Link para o GitHub]
Caio Alcarria: [Link para o GitHub]
Backend:

Thales Macêdo: [Link para o GitHub]
Mauricio Menezes: [Link para o GitHub]
Hugo Chaves: [Link para o GitHub]
Jessica Ellen: [Link para o GitHub]
Lucas Lima: [Link para o GitHub]
Marcos Vinicius: [Link para o GitHub]
Contribuições: Seguir o guia de contribuição definido no repositório proae_documents para participar do desenvolvimento do projeto. (Detalhes do guia não fornecidos no material original)

12. 📝 Licença & Direitos Autorais
O projeto PROAE é licenciado sob a Creative Commons Attribution 4.0.

13. 📞 Contato & Suporte
Email: tsiw-proae@ufba.br
GitHub: TSIW-PROAE
Observações:

Este README detalhado expande as informações fornecidas nos READMEs originais, organizando-as de forma mais estruturada e adicionando detalhes relevantes para a compreensão do projeto.
Complete os links para o GitHub dos colaboradores e adicione informações mais específicas sobre a estrutura do backend, configurações do Docker, padrões de código e guia de contribuição, consultando a documentação do projeto no repositório proae_documents.
Diagramas de arquitetura e outras informações visuais podem ser incluídas para enriquecer a documentação.
