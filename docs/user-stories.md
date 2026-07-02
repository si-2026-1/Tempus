# User Stories — Tempus

As User Stories representam as principais funcionalidades do Tempus sob a perspectiva do usuário. Elas estão organizadas por **Épicos**, que agrupam funcionalidades relacionadas do sistema.

---

# Épico 1 — Cadastro e Perfil

## US01 — Cadastro institucional

> Como aluno da UnB, quero criar uma conta utilizando meu e-mail institucional, para acessar a plataforma de forma segura e comprovar meu vínculo com a universidade.

**Regras de negócio**

* Apenas e-mails institucionais (`@aluno.unb.br` e `@unb.br`) são aceitos.
* Não é permitido cadastrar e-mails duplicados.

---

## US02 — Cadastro de habilidades

> Como usuário, quero cadastrar minhas habilidades e competências, para que outros estudantes possam encontrar e contratar meus serviços.

**Regras de negócio**

* O usuário pode cadastrar múltiplas habilidades.
* As habilidades podem ser editadas ou removidas posteriormente.

---

# Épico 2 — Marketplace de Serviços

## US03 — Publicação de ofertas

> Como usuário, quero publicar uma oferta de serviço, para disponibilizar minhas habilidades para outros estudantes.

**Regras de negócio**

* A oferta deve possuir título, descrição e categoria.
* Cada oferta pode informar a quantidade de créditos desejada.

---

## US04 — Busca de ofertas

> Como prestador de serviços, quero pesquisar ofertas disponíveis, para encontrar oportunidades compatíveis com minhas habilidades.

**Regras de negócio**

* Permitir pesquisa por palavra-chave.
* Permitir filtros por categoria.

---

# Épico 3 — Execução da Troca

## US05 — Solicitação de serviço

> Como usuário, quero solicitar um serviço anunciado, para iniciar uma troca de serviços com outro estudante.

**Regras de negócio**

* O sistema registra a solicitação.
* O prestador é notificado sobre o pedido.

---

## US06 — Gerenciamento de solicitações

> Como prestador, quero aceitar ou recusar solicitações recebidas, para controlar meus atendimentos.

**Regras de negócio**

* O status da solicitação deve ser atualizado automaticamente.
* O solicitante deve ser informado da decisão.

---

# Épico 4 — Créditos e Histórico

## US07 — Gerenciamento de créditos

> Como usuário, quero acompanhar meu saldo de créditos, para controlar minhas trocas realizadas na plataforma.

**Regras de negócio**

* O saldo deve refletir todas as transações realizadas.
* O histórico de movimentações deve permanecer disponível para consulta.

---

## US08 — Histórico de serviços

> Como usuário, quero consultar meu histórico de serviços, para acompanhar todas as trocas realizadas.

**Regras de negócio**

* Exibir serviços prestados e solicitados.
* Informar os créditos envolvidos em cada transação.

---

# Épico 5 — Avaliações e Comunicação

## US09 — Avaliação de serviços

> Como usuário, quero avaliar um serviço concluído, para compartilhar minha experiência e contribuir para a reputação dos participantes.

**Regras de negócio**

* Apenas participantes da troca podem realizar avaliações.
* A avaliação pode conter nota e comentário.

---

## US10 — Comunicação entre usuários

> Como usuário, quero trocar mensagens com outro participante, para combinar os detalhes da prestação do serviço.

**Regras de negócio**

* O histórico das mensagens deve permanecer disponível.
* Os usuários devem ser notificados sobre novas mensagens.

---

# Épico 6 — Administração

## US11 — Abertura de disputas

> Como usuário, quero abrir uma disputa quando ocorrer um problema na troca, para solicitar a mediação da administração.

**Regras de negócio**

* O usuário deve informar o motivo da disputa.
* A administração poderá acompanhar e analisar o caso.
