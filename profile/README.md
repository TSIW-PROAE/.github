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
