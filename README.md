#  Tempus — Banco de Tempo

## Problema

No contexto acadêmico da Universidade de Brasília (UnB), observa-se um sistema onde alunos possuem diversas habilidades técnicas e teóricas — como escrita acadêmica, programação, tradução e ensino — mas carecem de recursos financeiros para contratar serviços de apoio.

Como Sistema de Informação, o **Tempus** visa mitigar as seguintes falhas do cenário atual:
- Existência de competências ociosas (oferta).
- Necessidade de suporte especializado não atendida (demanda).
- Ausência de um meio de troca eficiente e auditável que dispense o uso de moeda fiduciária.

---

## Escopo

O **Tempus** propõe um sistema de troca baseado na Teoria Geral de Sistemas, onde o "tempo" é o insumo principal.

- **Unidade de Troca:** A moeda do sistema é a **hora**.
- **Regra de Conversão:** 1 hora de serviço prestado = 1 crédito de tempo.
- **Fluxo:** Créditos acumulados podem ser consumidos para solicitar serviços de qualquer outro usuário da rede.

O sistema será documentado como um MVP (Produto Mínimo Viável) compreendendo:
- Documentação de Requisitos e Backlog.
- Modelagem Conceitual de Dados (MER/DER).
- Protótipo de Alta Fidelidade (Figma).

---

## Stakeholders (Interessados)

Para o desenvolvimento deste sistema de informação, identificamos os seguintes atores principais:
* **Alunos (Usuários):** Prestadores e tomadores de serviços.
* **Administradores (Equipe Tempus):** Responsáveis pela moderação de conflitos e manutenção da integridade dos dados.
* **Universidade (Ambiente):** Provedora do ecossistema onde a troca ocorre.

---

## Requisitos Funcionais

1. **Cadastro de Perfil e Skills**
    * O usuário define sua oferta (skills) e sua demanda (o que precisa).
2. **Mural de Ofertas/Serviços**
    * Listagem categorizada (Acadêmico, Técnico, Consultoria, Manutenção).
3. **Sistema de Agendamento/Solicitação**
    * Fluxo de solicitação e confirmação mútua entre as partes.
4. **Carteira de Créditos (Time Wallet)**
    * Gestão automatizada do saldo de horas do usuário.
5. **Histórico de Transações**
    * Registro detalhado de interações e durações dos serviços.
6. **Sistema de Avaliação e Feedback**
    * Reputação baseada em estrelas e comentários pós-serviço.
7. **Chat Interno**
    * Canal direto para negociação de escopo e horários.
8. **Painel de Disputas/Moderação**
    * Interface para resolução de problemas e ajustes de créditos.

---

## Requisitos Não Funcionais

1. **RNF1 (Segurança e Autenticação)**: O sistema deve garantir que apenas usuários com e-mail institucional válido da Universidade de  Brasília (@aluno.unb.br ou @unb.br) possam se cadastrar.

---

## Requisitos Restritivos

Os requisitos restritivos representam limitações, decisões externas e condições de contexto que influenciam o desenvolvimento do sistema Tempus, mas que não correspondem diretamente às funcionalidades implementadas pelo software.

1. **RR1:** O sistema deve ser desenvolvido considerando o contexto acadêmico da Universidade de Brasília.
2. **RR2:** O sistema deve restringir o cadastro a usuários vinculados à comunidade universitária da UnB, por meio de e-mail institucional válido, como @aluno.unb.br ou @unb.br.
3. **RR3:** O sistema deve utilizar a hora como unidade de troca entre usuários.
4. **RR4:** O sistema deve ser documentado no repositório GitHub Tempus da organização si-2026-1.
5. **RR5:** A modelagem de dados deve permitir a representação por MER/DER, incluindo entidades, atributos, relacionamentos e cardinalidades.
6. **RR6:** O sistema deve ser planejado como uma aplicação web.
7. **RR7:** O sistema deve utilizar ferramentas compatíveis com desenvolvimento web, como HTML, CSS, JavaScript e/ou frameworks relacionados.
8. **RR8:** A modelagem do sistema deve ser compatível com futura implementação em banco de dados relacional.
9. **RR9:** O sistema deve considerar a disponibilidade de acesso por navegadores modernos, evitando dependência de instalação local por parte dos usuários.
10. **RR10:** As entregas das etapas do sistema devem respeitar o prazo definido pelos professores da disciplina de Sistemas de Informação ministrada na Universidade de Brasília no semestre 1/2026.
    
---

## Regras de Negócio

1. **RN1 Saldo inicial de créditos:** Todo usuário cadastrado receberá um saldo inicial de créditos de tempo ao ingressar na plataforma, permitindo novos membros solicitarem serviço antes de realizar alguma prestação.
2. **RN2 Saldo será sempre positivo:** O usuário não poderá solicitar serviços que resultem em saldo negativo.

---

## Exemplos de Uso (User Stories)

* *"Como **estudante de Letras**, quero oferecer revisão de ABNT para acumular créditos e poder solicitar monitoria de Python no futuro."*
* *"Como **estudante de Engenharia**, preciso de ajuda com tradução de um artigo técnico para poder finalizar meu TCC."*

---

## Detalhes do Produto

### Modelo de Troca
- 1 hora = 1 crédito (Modelo igualitário, independente da complexidade da tarefa).

### Metodologia de Desenvolvimento
O projeto segue as diretrizes da disciplina CIC0101, com foco em:
* **Versionamento:** GitHub para documentação e controle de commits.
* **Modelagem:** BPMN para processos e MER para dados.
* **Prototipagem:** Figma para a entrega T2.

---

## Épicos do Projeto (Backlog T1)

1.  **Gestão de Usuários:** Perfis, Login e Skills.
2.  **Marketplace:** Criação e busca de ofertas com filtros.
3.  **Sistema de Trocas:** Ciclo de vida da solicitação (Aceite/Finalização).
4.  **Carteira de Tempo:** Lógica de débito/crédito e extrato.
5.  **Reputação:** Ciclo de feedback e confiança.
6.  **Comunicação:** Chat e notificações.
7.  **Moderação:** Fluxo de disputas e auditoria administrativa.

---

## Autores

* Carlos Cauã - 231034304
* Thomas Jefferson - 202033561
* Gabriel Bismarck - 170103323
* Bruno Gabriel - 241022460
* Gabriel Alexandre - 241038942
* Mike Dantas - 140064338
