# PROAE - Sistema de Gestão para Pró-Reitoria de Ações Afirmativas e Assistência Estudantil

<div align="center">
  <img src="../img/logo_pgcomp.png" alt="Logo PROAE" width="150">
</div>

🚀 **Missão:** Aprimorar a gestão da assistência estudantil da UFBA, promovendo inclusão e equidade.

✨ **Visão:** Ser referência em gestão de ações afirmativas e assistência estudantil, com um sistema moderno, eficiente e transparente.

## Índice

* [Objetivo e Contexto](#objetivo-e-contexto)
* [Funcionalidades](#funcionalidades)
* [Tecnologias](#tecnologias)
* [Estrutura do Projeto](#estrutura-do-projeto)
* [Como Executar o Projeto](#como-executar-o-projeto)
* [Fluxo de Trabalho](#fluxo-de-trabalho)
* [Testes](#testes)
* [Ambiente de Desenvolvimento](#ambiente-de-desenvolvimento)
* [Segurança](#segurança)
* [Documentação](#documentação)
* [Colaboradores](#colaboradores)
* [Licença](#licença)
* [Contato](#contato)


---

## Objetivo e Contexto <a name="objetivo-e-contexto"></a>

Desenvolvido para a disciplina Tópicos em Sistemas de Informação e Web I (IC045/MATE85) na UFBA, o PROAE visa construir um sistema de gestão completo para a Pró-Reitoria de Ações Afirmativas e Assistência Estudantil. O projeto é mantido pela organização [TSIW-PROAE](https://github.com/TSIW-PROAE) no GitHub e busca centralizar informações, automatizar processos, melhorar a comunicação com estudantes e aprimorar a transparência na gestão da assistência estudantil.


## Funcionalidades <a name="funcionalidades"></a>

**Requisitos Funcionais:**

* **Centralização de Informações:** Consolidar documentos, dados de estudantes e familiares, histórico de processos e pareceres em um único sistema.
* **Gestão de Processos Seletivos:**
    * Cadastro de editais com baremas e documentos específicos.
    * Inscrições online com validação automática de documentos e análise de renda.
    * Emissão de pareceres com opções pré-definidas para indeferimentos.
    * Acompanhamento do status da inscrição e comunicação com o estudante.
    * Divulgação de resultados (preliminares, recursos, finais).
* **Validação de Documentos:** Automatizar a verificação de documentos com alertas para inconsistências.
* **Comunicação com Estudantes:** Envio de alertas, notificações e respostas automatizadas sobre o status das solicitações.
* **Relatórios e Análises:** Geração de relatórios e análises para tomada de decisões estratégicas.
* **Integração com Outros Sistemas:** Integração com o sistema de matrícula e outros sistemas relevantes da UFBA.
* **Manutenção de Histórico:** Preservação de dados históricos pelo período legalmente exigido.

**Requisitos Não Funcionais:**

* **Segurança e Sigilo de Dados:** Acesso restrito, níveis de sigilo para informações sensíveis e histórico de observações.
* **Usabilidade:** Interface intuitiva e fácil de usar.
* **Performance:** Tempo de resposta rápido e eficiente.
* **Escalabilidade:** Capacidade de lidar com um grande volume de usuários e dados.
* **Disponibilidade:** Sistema acessível 24/7.
* **Manutenibilidade:** Código limpo, documentado e modular para facilitar a manutenção.



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
* **TypeScript:** Superset de JavaScript que adiciona tipagem estática.


## Estrutura do Projeto <a name="estrutura-do-projeto"></a>

O projeto é dividido em três repositórios:

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

3. **[Backend](https://github.com/TSIW-PROAE/proae_backend):**  A estrutura do backend será definida de acordo com as melhores práticas do NestJS e poderá incluir pastas como `src`, `dist`, `node_modules`, entre outras.  Detalhes da estrutura serão documentados no repositório do backend.


## Como Executar o Projeto <a name="como-executar-o-projeto"></a>

**Frontend:**

1. Clonar o repositório: `git clone https://github.com/TSIW-PROAE/proae_frontend.git`
2. Navegar até o diretório: `cd proae_frontend`
3. Instalar dependências: `npm install`
4. Renomear `.env.example` para `.env` e configurar as variáveis de ambiente.
5. Iniciar o servidor de desenvolvimento: `npm run dev`

**Backend:**

1. Clonar o repositório: `git clone https://github.com/TSIW-PROAE/proae_backend.git`
2. Navegar até o diretório: `cd proae_backend`
3. Instalar dependências: `npm install`
4. Renomear `.env.example` para `.env` e configurar as variáveis de ambiente.
5. Executar o Docker Compose: `docker-compose up -d`
6. Iniciar o servidor de desenvolvimento: `npm run start:dev`


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
