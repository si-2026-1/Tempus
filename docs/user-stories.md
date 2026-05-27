# 📖 User Stories — Tempus

Este documento descreve as User Stories do sistema Tempus com base no backlog funcional do projeto.

---

# 👤 Épico 1 — Gestão de Identidade e Perfil

Responsável pelo gerenciamento de autenticação, perfis acadêmicos e cadastro de competências dos usuários.

---

## RF01 — Cadastro Institucional

### US01 — Cadastro com e-mail institucional

**Como** aluno da Universidade de Brasília  
**Quero** criar uma conta utilizando meu e-mail institucional  
**Para** acessar a plataforma de forma segura e validar meu vínculo acadêmico.

#### Critérios de Aceitação
- O sistema deve aceitar apenas e-mails `@aluno.unb.br` e `@unb.br`
- O sistema deve impedir cadastros duplicados
- O usuário deve cadastrar nome, e-mail e senha
- O sistema deve validar as credenciais informadas

---

## RF02 — Perfil de Habilidades

### US02 — Cadastro de competências

**Como** usuário  
**Quero** cadastrar minhas competências técnicas e teóricas  
**Para** disponibilizar minhas habilidades para outros estudantes.

#### Critérios de Aceitação
- O usuário deve poder adicionar múltiplas habilidades
- As habilidades devem possuir categoria
- O sistema deve permitir edição posterior

---

### US03 — Edição de perfil acadêmico

**Como** usuário  
**Quero** editar minhas informações e habilidades  
**Para** manter meu perfil atualizado dentro da plataforma.

#### Critérios de Aceitação
- O sistema deve permitir atualização das informações
- As alterações devem ser salvas imediatamente

---

## RF03 — Gestão de Demandas

### US04 — Cadastro de necessidades acadêmicas

**Como** estudante  
**Quero** informar quais tipos de auxílio necessito  
**Para** encontrar usuários capazes de me ajudar.

#### Critérios de Aceitação
- O usuário deve poder cadastrar múltiplas demandas
- O sistema deve relacionar demandas às categorias disponíveis

---

# 📢 Épico 2 — Marketplace de Competências

Responsável pela publicação, organização e descoberta de ofertas de serviços.

---

## RF04 — Publicação de Ofertas

### US05 — Criação de oferta de serviço

**Como** usuário  
**Quero** publicar uma oferta de serviço  
**Para** disponibilizar minhas habilidades para troca de créditos.

#### Critérios de Aceitação
- O serviço deve possuir título e descrição
- O sistema deve permitir seleção de categoria
- O usuário deve informar duração estimada do serviço

---

## RF05 — Busca e Filtros

### US06 — Busca de ofertas

**Como** estudante  
**Quero** pesquisar ofertas utilizando palavras-chave  
**Para** encontrar serviços relevantes para minha necessidade.

#### Critérios de Aceitação
- O sistema deve possuir campo de busca textual
- O sistema deve listar resultados relacionados

---

### US07 — Filtragem de categorias

**Como** usuário  
**Quero** filtrar ofertas por categoria  
**Para** localizar serviços específicos de maneira rápida.

#### Critérios de Aceitação
- O sistema deve permitir filtros por categoria
- O sistema deve atualizar os resultados dinamicamente

---

## RF06 — Mural Ativo

### US08 — Visualização do mural de ofertas

**Como** usuário  
**Quero** visualizar as ofertas disponíveis na plataforma  
**Para** encontrar oportunidades de troca de serviços.

#### Critérios de Aceitação
- O sistema deve listar ofertas ativas
- Cada oferta deve exibir título, categoria e usuário responsável

---

# 🔁 Épico 3 — Ciclo de Vida da Troca

Responsável pelo gerenciamento das solicitações e conclusão das trocas.

---

## RF07 — Solicitação de Serviço

### US09 — Solicitação de oferta

**Como** usuário  
**Quero** solicitar um serviço publicado por outro estudante  
**Para** iniciar uma troca de competências.

#### Critérios de Aceitação
- O sistema deve registrar a solicitação
- O prestador deve ser notificado
- O usuário deve possuir saldo suficiente para solicitar

---

## RF08 — Aceite de Proposta

### US10 — Aceite ou recusa de solicitação

**Como** prestador de serviço  
**Quero** aceitar ou recusar solicitações recebidas  
**Para** controlar minhas interações na plataforma.

#### Critérios de Aceitação
- O sistema deve atualizar o status da solicitação
- O solicitante deve ser notificado sobre a decisão

---

## RF09 — Confirmação de Entrega

### US11 — Finalização de serviço

**Como** participante da troca  
**Quero** confirmar a conclusão do serviço  
**Para** finalizar corretamente a transação.

#### Critérios de Aceitação
- Ambas as partes devem confirmar a entrega
- O sistema deve liberar os créditos após confirmação mútua

---

# 💰 Épico 4 — Economia do Tempo

Responsável pela lógica financeira baseada em créditos de tempo.

---

## RF10 — Gestão de Créditos

### US12 — Conversão automática de horas

**Como** usuário  
**Quero** que o sistema converta automaticamente horas em créditos  
**Para** garantir consistência nas trocas realizadas.

#### Critérios de Aceitação
- O sistema deve seguir a regra `1 hora = 1 crédito`
- Os créditos devem ser atualizados automaticamente

---

## RF11 — Time Wallet

### US13 — Visualização de saldo

**Como** usuário  
**Quero** visualizar meu saldo de créditos de tempo  
**Para** acompanhar minhas horas disponíveis.

#### Critérios de Aceitação
- O sistema deve exibir saldo atualizado
- O saldo deve ser representado em horas/créditos

---

## RF12 — Extrato de Interações

### US14 — Histórico de transações

**Como** usuário  
**Quero** consultar meu histórico de transações  
**Para** acompanhar serviços realizados e recebidos.

#### Critérios de Aceitação
- O sistema deve exibir data da transação
- O sistema deve exibir participantes envolvidos
- O sistema deve exibir quantidade de créditos movimentados

---

# ⭐⚖️ Épico 5 — Confiança e Governança

Responsável pelo sistema de reputação e moderação de conflitos.

---

## RF13 — Feedback Pós-Serviço

### US15 — Avaliação de usuários

**Como** usuário  
**Quero** avaliar um serviço recebido  
**Para** compartilhar minha experiência com a comunidade.

#### Critérios de Aceitação
- O sistema deve permitir avaliação por estrelas
- O sistema deve permitir comentários textuais
- Apenas participantes da troca podem avaliar

---

## RF14 — Sistema de Disputas

### US16 — Abertura de disputa

**Como** usuário  
**Quero** abrir uma disputa em caso de problema  
**Para** solicitar intervenção administrativa.

#### Critérios de Aceitação
- O usuário deve informar motivo da disputa
- O sistema deve registrar a solicitação para análise

---

## RF15 — Painel Administrativo

### US17 — Auditoria administrativa

**Como** administrador da plataforma  
**Quero** visualizar transações e disputas  
**Para** garantir integridade e confiança no sistema.

#### Critérios de Aceitação
- O administrador deve acessar o histórico das trocas
- O sistema deve permitir análise das disputas
- O sistema deve registrar ações administrativas

---

# 💬 Épico 6 — Colaboração Direta

Responsável pela comunicação entre os usuários da plataforma.

---

## RF16 — Chat de Negociação

### US18 — Comunicação entre usuários

**Como** usuário  
**Quero** conversar diretamente com outro participante  
**Para** alinhar escopo, horários e detalhes do serviço.

#### Critérios de Aceitação
- O sistema deve permitir troca de mensagens
- O histórico de mensagens deve ser armazenado

---

## RF17 — Notificações

### US19 — Recebimento de notificações

**Como** usuário  
**Quero** receber notificações sobre minhas interações  
**Para** acompanhar atualizações da plataforma.

#### Critérios de Aceitação
- O sistema deve notificar novas mensagens
- O sistema deve notificar alterações em solicitações
- O sistema deve notificar confirmações de serviços

---