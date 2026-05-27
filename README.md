#  Tempus — Banco de Tempo

##  Problema

No contexto acadêmico da Universidade de Brasília (UnB), observa-se um sistema onde alunos possuem diversas habilidades técnicas e teóricas — como escrita acadêmica, programação, tradução e ensino — mas carecem de recursos financeiros para contratar serviços de apoio.

Como Sistema de Informação, o **Tempus** visa mitigar as seguintes falhas do cenário atual:
- Existência de competências ociosas (oferta).
- Necessidade de suporte especializado não atendida (demanda).
- Ausência de um meio de troca eficiente e auditável que dispense o uso de moeda fiduciária.

---

##  Escopo

O **Tempus** propõe um sistema de troca baseado na Teoria Geral de Sistemas, onde o "tempo" é o insumo principal.

- **Unidade de Troca:** A moeda do sistema é a **hora**.
- **Regra de Conversão:** 1 hora de serviço prestado = 1 crédito de tempo.
- **Fluxo:** Créditos acumulados podem ser consumidos para solicitar serviços de qualquer outro usuário da rede.

O sistema será documentado como um MVP (Produto Mínimo Viável) compreendendo:
- Documentação de Requisitos e Backlog.
- Modelagem Conceitual de Dados (MER/DER).
- Protótipo de Alta Fidelidade (Figma).

---

##  Stakeholders (Interessados)

Para o desenvolvimento deste sistema de informação, identificamos os seguintes atores principais:
* **Alunos (Usuários):** Prestadores e tomadores de serviços.
* **Administradores (Equipe Tempus):** Responsáveis pela moderação de conflitos e manutenção da integridade dos dados.
* **Universidade (Ambiente):** Provedora do ecossistema onde a troca ocorre.

---

##  Requisitos Funcionais

1.  **Cadastro de Perfil e Skills**
    * O usuário define sua oferta (skills) e sua demanda (o que precisa).
2.  **Mural de Ofertas/Serviços**
    * Listagem categorizada (Acadêmico, Técnico, Consultoria, Manutenção).
3.  **Sistema de Agendamento/Solicitação**
    * Fluxo de solicitação e confirmação mútua entre as partes.
4.  **Carteira de Créditos (Time Wallet)**
    * Gestão automatizada do saldo de horas do usuário.
5.  **Histórico de Transações**
    * Registro detalhado de interações e durações dos serviços.
6.  **Sistema de Avaliação e Feedback**
    * Reputação baseada em estrelas e comentários pós-serviço.
7.  **Chat Interno**
    * Canal direto para negociação de escopo e horários.
8.  **Painel de Disputas/Moderação**
    * Interface para resolução de problemas e ajustes de créditos.

---
 Requisitos Não Funcionais

1.  RNF1 (Segurança e Autenticação): O sistema deve garantir que    apenas usuários com e-mail institucional válido da Universidade de  Brasília (@aluno.unb.br ou @unb.br) possam se cadastrar.

---
 Regras de Negócio

1. **RN1 Saldo inicial de créditos:** Todo usuário cadastrado receberá um saldo inicial de créditos de tempo ao ingressa na plataforma, permitindo novos membros solicitarem serviço antes de realizar alguma prestação.
2. **RN2 Saldo será sempre positivo:** O usuário não poderá solicitar serviços que resultem em saldo negativo.

---

##  Exemplos de Uso (User Stories)

* *"Como **estudante de Letras**, quero oferecer revisão de ABNT para acumular créditos e poder solicitar monitoria de Python no futuro."*
* *"Como **estudante de Engenharia**, preciso de ajuda com tradução de um artigo técnico para poder finalizar meu TCC."*

---

##  Detalhes do Produto

###  Modelo de Troca
- 1 hora = 1 crédito (Modelo igualitário, independente da complexidade da tarefa).

###  Metodologia de Desenvolvimento
[cite_start]O projeto segue as diretrizes da disciplina CIC0101[cite: 2], com foco em:
* [cite_start]**Versionamento:** GitHub para documentação e controle de commits.
* [cite_start]**Modelagem:** BPMN para processos e MER para dados[cite: 12, 13].
* [cite_start]**Prototipagem:** Figma para a entrega T2[cite: 28].

---

##  Épicos do Projeto (Backlog T1)

1.  ** Gestão de Usuários:** Perfis, Login e Skills.
2.  ** Marketplace:** Criação e busca de ofertas com filtros.
3.  ** Sistema de Trocas:** Ciclo de vida da solicitação (Aceite/Finalização).
4.  ** Carteira de Tempo:** Lógica de débito/crédito e extrato.
5.  ** Reputação:** Ciclo de feedback e confiança.
6.  ** Comunicação:** Chat e notificações.
7.  ** Moderação:** Fluxo de disputas e auditoria administrativa.

---

##  Autores

* Carlos Cauã - 231034304
* Thomas Jefferson - 202033561
* Gabriel Bismarck - 170103323
* Bruno Gabriel - 241022460
* Gabriel Alexandre - 241038942
* Mike Dantas - 140064338
