# PROAE - Sistema de Gestão para Pró-Reitoria de Ações Afirmativas e Assistência Estudantil

<div align="center">
  <img src="../img/logo_pgcomp.png" alt="Logo PROAE" width="150">
</div>

🚀 **Missão:** Aprimorar a gestão da assistência estudantil da UFBA, promovendo inclusão e equidade.

✨ **Visão:** Ser referência em gestão de ações afirmativas e assistência estudantil, com um sistema moderno, eficiente e transparente.

## Índice

* [Objetivos e Contexto](#objetivos-e-contexto)
* [Tecnologias](#tecnologias)
* [Estrutura do Projeto](#estrutura-do-projeto)
* [Fluxo de Trabalho](#fluxo-de-trabalho)
* [Testes](#testes)
* [Ambiente de Desenvolvimento](#ambiente-de-desenvolvimento)
* [Segurança](#segurança)
* [Documentação](#documentação)
* [Colaboradores](#colaboradores)
* [Licença](#licença)
* [Contato](#contato)


---

## Objetivos e Contexto <a name="objetivos-e-contexto"></a>

Desenvolvido para a disciplina Tópicos em Sistemas de Informação e Web I (IC045/MATE85) na UFBA, o PROAE visa construir um sistema de gestão completo para a Pró-Reitoria de Ações Afirmativas e Assistência Estudantil. O projeto é mantido pela organização [TSIW-PROAE](https://github.com/TSIW-PROAE) no GitHub e busca centralizar informações, automatizar processos, melhorar a comunicação com estudantes e aprimorar a transparência na gestão da assistência estudantil.

## Tecnologias <a name="tecnologias"></a>

**Frontend:**

* **React.js:** Biblioteca JavaScript para construção de interfaces de usuário.
* **TypeScript:** Superset de JavaScript que adiciona tipagem estática.
* **Vite:** Ferramenta de build para desenvolvimento web rápido.

**Backend:**

* **Node.js:** Ambiente de execução JavaScript para backend.
* **NestJS:** Framework para construir aplicações Node.js escaláveis e eficientes.
* **PostgreSQL:** Sistema de gerenciamento de banco de dados relacional.
* **Docker:** Plataforma para conteinerização de aplicações.
* **Docker-Compose:** Ferramenta para orquestrar múltiplos containers Docker.
* **Type-ORM:** Ferramenta que permite a interação com bancos de dados relacionais usando a abordagem orientada a objetos.
* **TypeScript:** Superset de JavaScript que adiciona tipagem estática.


## Estrutura do Projeto <a name="estrutura-do-projeto"></a>

O projeto é dividido em três repositórios com algumas documentações em destaque, como:

1. **[Documentação](https://github.com/TSIW-PROAE/proae_documents):**
content_copy
download
Use code with caution.
Markdown
project_management/
technical_documentation/
requirements/
design/
guidelines/
references/
miscellaneous/

2. **[Frontend](https://github.com/TSIW-PROAE/proae_frontend):**
content_copy
download
Use code with caution.
proae-frontend/
├── public/
├── src/
│ ├── assets/
│ ├── components/
│ ├── context/
│ ├── features/
│ ├── hooks/
│ ├── pages/
│ ├── services/
│ ├── styles/
│ ├── utils/
│ ├── App.tsx
│ ├── main.tsx
│ └── setupTests.ts
├── .env
├── package.json
└── README.md

<ol start="3">
  <li>
    <strong><a href="https://github.com/TSIW-PROAE/proae_backend" target="_blank">Backend</a>:</strong>
    A estrutura do backend será definida de acordo com as melhores práticas do NestJS e poderá incluir pastas como <code>src</code>, <code>dist</code>, <code>node_modules</code>, entre outras. Detalhes da estrutura serão documentados no repositório do backend.
  </li>
  <li>
    <strong><a href="https://github.com/TSIW-PROAE/proae_documents/tree/main/requirements" target="_blank">Documento de requisitos</a>:</strong>
    Esse documento contém todos os requisitos do projeto definidos pela equipe junto ao cliente através de conversas e reuniões formais.
  </li>
  <li>
    <strong><a href="https://www.figma.com/design/40hh19XODV4sDGmFYP2X33/PROAE-PROJECT?m=auto&t=GCeBpKKnjMlg3FL6-1" target="_blank">Prototipação</a>:</strong>
    Esse documento contém a prototipação do projeto levando em consideração todos os requisitos funcionais decididos previamente.
  </li>
  <li>
    <strong><a href="https://github.com/TSIW-PROAE/proae_documents/tree/main/project_management/meeting_minutes" target="_blank">Atas de reunião gerais</a>:</strong>
    Essa pasta contém todas as atas de reuniões realizadas. Nessas atas buscamos expor todas as tomadas de decisões da equipe, assim como todos os detalhes das nossas reuniões de time.
  </li>
</ol>


## Fluxo de Trabalho <a name="fluxo-de-trabalho"></a>

* **Gitflow:** Utilização do workflow Gitflow para organização das branches (develop, feature, release, hotfix).
* **Pull Requests:** Abertura de Pull Requests para revisão de código antes da integração com a branch principal.
* **Commit Messages:** Padronização das mensagens de commit para clareza e organização do histórico do projeto (ex: `feat: adiciona nova funcionalidade`, `fix: corrige bug`).
* **Coding Standards:**  ESLint e Prettier serão utilizados para garantir a qualidade e consistência do código.  As configurações serão definidas em arquivos de configuração específicos em cada repositório.


## Testes <a name="testes"></a>

* **Frontend:** Testes unitários e de integração utilizando Jest e React Testing Library.
* **Backend:** Testes unitários e de integração utilizando Jest.  A cobertura de testes será monitorada para garantir a qualidade do código.


## Ambiente de Desenvolvimento <a name="ambiente-de-desenvolvimento"></a>

* Docker e Docker Compose serão utilizados para garantir um ambiente de desenvolvimento consistente e facilitar a configuração.
* Um arquivo `docker-compose.yml` será criado para definir os serviços e suas dependências.


## Segurança <a name="segurança"></a>

* **JWT (JSON Web Tokens):** Utilização de JWT para autenticação e autorização de usuários.
* **Controle de Acesso Baseado em Roles:** Níveis de acesso diferenciados para diferentes tipos de usuários (administradores, assistentes sociais, alunos).
* **Medidas de segurança:** Implementação de medidas para prevenir ataques comuns como SQL Injection, Cross-Site Scripting (XSS) e Cross-Site Request Forgery (CSRF).  Serão utilizadas bibliotecas e técnicas de segurança para proteger o sistema contra essas vulnerabilidades.


## Documentação <a name="documentação"></a>

* **Documentação da API (Backend):** Swagger será utilizado para documentar a API REST.
* **Documentação do Código:** JSDoc será utilizado para documentar o código-fonte.
* **Arquitetura do Sistema:** Diagramas e descrições detalhadas da arquitetura do sistema serão incluídos na documentação. Diagramas serão criados utilizando ferramentas como Mermaid ou Draw.io.
* **Organização da Documentação:** A documentação será mantida organizada e atualizada no repositório `proae_documents`.


## Colaboradores <a name="colaboradores"></a>

**Frontend:**
<table>
  <tr>
    <td align="center">
      <a href="#" title="defina o título do link">
        <img src="https://avatars.githubusercontent.com/u/55918680?v=4" width="100px;" alt="Foto do Hevelin no GitHub"/><br>
        <sub>
          <b>Hevelin Freitas</b>
        </sub>
      </a>
    </td>
    <td align="center">
      <a href="#" title="defina o título do link">
        <img src="https://avatars.githubusercontent.com/u/20570844?v=4" width="100px;" alt="Foto do Hevelin no GitHub"/><br>
        <sub>
          <b>Mauricio Menezes</b>
        </sub>
      </a>
    </td>
    <td align="center">
      <a href="#" title="defina o título do link">
        <img src="https://avatars.githubusercontent.com/u/101140937?v=4" width="100px;" alt="Foto do Steve Jobs"/><br>
        <sub>
          <b>Caio Alcarria</b>
        </sub>
      </a>
    </td>
  </tr>
</table>


**Backend:**

<table>
  <tr>
    <td align="center">
      <a href="#" title="defina o título do link">
        <img src="https://avatars.githubusercontent.com/u/24979899?s=96&v=4" width="100px;" alt="Foto do Thales no GitHub"/><br>
        <sub>
          <b>Thales Macêdo</b>
        </sub>
      </a>
    </td>
    <td align="center">
      <a href="#" title="defina o título do link">
        <img src="https://avatars.githubusercontent.com/u/20570844?v=4" width="100px;" alt="Foto do Maurício no GitHub"/><br>
        <sub>
          <b>Mauricio Menezes</b>
        </sub>
      </a>
    </td>
    <td align="center">
      <a href="#" title="defina o título do link">
        <img src="https://avatars.githubusercontent.com/u/83249854?s=64&v=4" width="100px;" alt="Foto do Hugo no GitHub"/><br>
        <sub>
          <b>Hugo Chaves</b>
        </sub>
      </a>
    </td>
    <td align="center">
      <a href="#" title="defina o título do link">
        <img src="https://avatars.githubusercontent.com/u/95954597?s=64&v=4" width="100px;" alt="Foto da Jessica no GitHub"/><br>
        <sub>
          <b>Jessica Ellen</b>
        </sub>
      </a>
    </td>
    <td align="center">
      <a href="#" title="defina o título do link">
        <img src="https://avatars.githubusercontent.com/u/53127444?s=64&v=4" width="100px;" alt="Foto do Lucas no GitHub"/><br>
        <sub>
          <b>Lucas Lima</b>
        </sub>
      </a>
    </td>
    <td align="center">
      <a href="#" title="defina o título do link">
        <img src="https://avatars.githubusercontent.com/u/11302968?s=70&v=4" width="100px;" alt="Foto do Marcos no GitHub"/><br>
        <sub>
          <b>Marcos Vinicius</b>
        </sub>
      </a>
    </td>
  </tr>
</table>

## Licença <a name="licença"></a>

O projeto PROAE é licenciado sob a [Creative Commons Attribution 4.0](LICENSE).


## Contato <a name="contato"></a>

* **Email:** tsiw-proae@ufba.br
* **GitHub:** [TSIW-PROAE](https://github.com/TSIW-PROAE)
