# User Stories — Tempus

As User Stories representam as principais funcionalidades do Tempus sob a perspectiva do usuário. Elas estão organizadas por **Épicos**, que agrupam funcionalidades relacionadas do sistema.

---

# Épico 1 — Cadastro e Perfil

## US01 — Cadastro institucional

> Como aluno da UnB, desejo cadastrar-me utilizando meu e-mail institucional para utilizar a plataforma com segurança.

**Regras de negócio**

* Apenas e-mails institucionais (`@aluno.unb.br` e `@unb.br`) são aceitos.
* Não é permitido cadastrar e-mails duplicados.

---

## US02 — Cadastro de habilidades

> Como usuário, desejo cadastrar minhas habilidades para que outros estudantes encontrem meus serviços.

**Regras de negócio**

* O usuário pode cadastrar múltiplas habilidades.
* As habilidades podem ser editadas ou removidas posteriormente.

---

# Épico 2 — Marketplace de Serviços

## US03 — Publicação de ofertas

> Como usuário, desejo publicar ofertas de serviços para disponibilizar minhas habilidades.

**Regras de negócio**

* A oferta deve possuir título, descrição e categoria.
* Cada oferta pode informar a quantidade de créditos desejada.

---

## US04 — Busca de ofertas

> Como prestador, desejo buscar e filtrar ofertas para encontrar oportunidades compatíveis.

**Regras de negócio**

* Permitir pesquisa por palavra-chave.
* Permitir filtros por categoria.

---

# Épico 3 — Execução da Troca

## US05 — Solicitação de serviço

> Como usuário, desejo solicitar um serviço para contratar outro estudante.

**Regras de negócio**

* O sistema registra a solicitação.
* O prestador é notificado sobre o pedido.

---

## US06 — Gerenciamento de solicitações

> Como prestador, desejo aceitar ou recusar solicitações para gerenciar meus atendimentos.

**Regras de negócio**

* O status da solicitação deve ser atualizado automaticamente.
* O solicitante deve ser informado da decisão.

---

# Épico 4 — Créditos e Histórico

## US07 — Gerenciamento de créditos

> Como usuário, desejo acompanhar meu saldo de créditos para controlar minhas trocas.

**Regras de negócio**

* O saldo deve refletir todas as transações realizadas.
* O histórico de movimentações deve permanecer disponível para consulta.

---

## US08 — Histórico de serviços

> Como usuário, desejo visualizar meu histórico para acompanhar serviços realizados.

**Regras de negócio**

* Exibir serviços prestados e solicitados.
* Informar os créditos envolvidos em cada transação.

---

# Épico 5 — Avaliações e Comunicação

## US09 — Avaliação de serviços

> Como usuário, desejo avaliar serviços concluídos para compartilhar minha experiência.

**Regras de negócio**

* Apenas participantes da troca podem realizar avaliações.
* A avaliação pode conter nota e comentário.

---

## US10 — Comunicação entre usuários

> Como usuário, desejo conversar com outros participantes para combinar os detalhes da troca.

**Regras de negócio**

* O histórico das mensagens deve permanecer disponível.
* Os usuários devem ser notificados sobre novas mensagens.

---

# Épico 6 — Administração

## US11 — Abertura de disputas

> Como usuário, desejo abrir disputas para que a administração resolva conflitos de forma justa.

**Regras de negócio**

* O usuário deve informar o motivo da disputa.
* A administração poderá acompanhar e analisar o caso.
