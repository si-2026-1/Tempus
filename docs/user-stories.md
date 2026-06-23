# User Stories — Tempus

User Stories alinhadas aos épicos e requisitos funcionais refatorados.

\---

## Épico 1 — Gestão de Identidade e Perfil

### Cadastro de Perfil e Skills

**US01 — Cadastro institucional**

> Como aluno da UnB, quero me cadastrar com e-mail institucional para acessar a plataforma com vínculo validado.

* Apenas `@aluno.unb.br` e `@unb.br`; sem duplicatas (RNF1 / RR2)

**US02 — Definição de oferta e demanda**

> Como usuário, quero cadastrar minhas skills e necessidades para participar das trocas.

* Múltiplas habilidades e demandas por perfil, vinculadas a categorias

\---

## Épico 2 — Marketplace de Competências

### Mural de Ofertas/Serviços

**US03 — Publicação de oferta**

> Como usuário, quero publicar uma oferta de serviço no mural para disponibilizar minhas competências.

* Título, descrição, duração estimada e categoria (Acadêmico, Técnico, Consultoria, Manutenção)

**US04 — Busca e visualização de ofertas**

> Como estudante, quero buscar e filtrar ofertas no mural para encontrar serviços relevantes.

* Busca textual e filtros por categoria com resultados dinâmicos

\---

## Épico 3 — Ciclo de Vida da Troca

### Sistema de Agendamento/Solicitação

**US05 — Solicitação de serviço**

> Como usuário, quero solicitar um serviço publicado para iniciar uma troca.

* Saldo suficiente exigido (RN2); prestador notificado

**US06 — Aceite e finalização**

> Como prestador, quero aceitar/recusar solicitações e confirmar a conclusão do serviço.

* Confirmação mútua obrigatória; créditos liberados após ambas as partes confirmarem

\---

## Épico 4 — Carteira do Tempo

### Carteira de Créditos (Time Wallet)

**US07 — Gestão de saldo**

> Como usuário, quero visualizar e gerenciar meu saldo de créditos para acompanhar minhas horas.

* 1 hora = 1 crédito; saldo inicial ao cadastro (RN1); saldo nunca negativo (RN2)

### Histórico de Transações

**US08 — Extrato de transações**

> Como usuário, quero consultar meu histórico para acompanhar serviços prestados e recebidos.

* Data, participantes e créditos movimentados por transação

\---

## Épico 5 — Confiança e Governança

### Sistema de Avaliação e Feedback

**US09 — Avaliação pós-serviço**

> Como usuário, quero avaliar um serviço recebido com estrelas e comentário.

* Apenas participantes da troca podem avaliar

### Painel de Disputas/Moderação

**US10 — Abertura e gestão de disputas**

> Como usuário, quero abrir uma disputa; como administrador, quero analisá-la e agir.

* Usuário informa motivo; administrador visualiza histórico e registra ações

\---

## Épico 6 — Colaboração Direta

### Chat Interno

**US11 — Chat de negociação**

> Como usuário, quero conversar com outro participante para alinhar escopo e horários.

* Mensagens em tempo real com histórico armazenado

