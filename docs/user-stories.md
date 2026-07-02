# User Stories — Tempus

As User Stories representam as principais funcionalidades do Tempus sob a perspectiva do usuário. Elas estão organizadas por **Épicos**, que agrupam funcionalidades relacionadas do sistema.

---

# Épico 1 — Cadastro e Perfil

## US01 — Cadastro institucional

> Como aluno da UnB, quero criar uma conta utilizando meu e-mail institucional, para acessar a plataforma de forma segura e comprovar meu vínculo com a universidade.

**Regras de negócio**

* Apenas e-mails institucionais (`@aluno.unb.br` e `@unb.br`) são aceitos.
* Não é permitido cadastrar e-mails duplicados.

**Critérios de aceitação**
* Dado um e-mail institucional válido, o sistema deve permitir o cadastro.
* Dado um e-mail fora dos domínios permitidos, o sistema deve impedir o cadastro e informar o motivo.
* Caso o e-mail já esteja cadastrado, o sistema deve exibir uma mensagem de erro.

---

## US02 — Cadastro de habilidades

> Como usuário, quero cadastrar minhas habilidades e competências, para que outros estudantes possam encontrar e contratar meus serviços.

**Regras de negócio**

* O usuário pode cadastrar múltiplas habilidades.
* As habilidades podem ser editadas ou removidas posteriormente.

**Critérios de aceitação**
* O sistema deve permitir adicionar novas habilidades.
* O sistema deve permitir editar uma habilidade existente.
* O sistema deve permitir excluir uma habilidade.
* As alterações devem ser refletidas imediatamente no perfil.

---

# Épico 2 — Marketplace de Serviços

## US03 — Publicação de ofertas

> Como usuário, quero publicar uma oferta de serviço, para disponibilizar minhas habilidades para outros estudantes.

**Regras de negócio**

* A oferta deve possuir título, descrição e categoria.
* Cada oferta pode informar a quantidade de créditos desejada.

**Critérios de aceitação**
* O sistema não deve permitir publicar ofertas incompletas.
* Após publicada, a oferta deve ficar disponível nas pesquisas.
* O usuário pode editar ou remover a oferta.

---

## US04 — Busca de ofertas

> Como prestador de serviços, quero pesquisar ofertas disponíveis, para encontrar oportunidades compatíveis com minhas habilidades.

**Regras de negócio**

* Permitir pesquisa por palavra-chave.
* Permitir filtros por categoria.

**Critérios de aceitação**
* O sistema deve retornar resultados compatíveis com o termo pesquisado.
* Os filtros devem reduzir os resultados corretamente.
* Caso não existam ofertas, o sistema deve informar ao usuário.

---

# Épico 3 — Execução da Troca

## US05 — Solicitação de serviço

> Como usuário, quero solicitar um serviço anunciado, para iniciar uma troca de serviços com outro estudante.

**Regras de negócio**

* O sistema registra a solicitação.
* O prestador é notificado sobre o pedido.

**Critérios de aceitação**
* O sistema deve registrar a solicitação.
* O prestador deve ser notificado.
* O status inicial deve ser "Pendente".

---

## US06 — Gerenciamento de solicitações

> Como prestador, quero aceitar ou recusar solicitações recebidas, para controlar meus atendimentos.

**Regras de negócio**

* O status da solicitação deve ser atualizado automaticamente.
* O solicitante deve ser informado da decisão.

**Critérios de aceitação**
* Ao aceitar, a solicitação muda para "Aceita".
* Ao recusar, muda para "Recusada".
* O solicitante recebe a atualização.

---

# Épico 4 — Créditos e Histórico

## US07 — Gerenciamento de créditos

> Como usuário, quero acompanhar meu saldo de créditos, para controlar minhas trocas realizadas na plataforma.

**Regras de negócio**

* O saldo deve refletir todas as transações realizadas.
* O histórico de movimentações deve permanecer disponível para consulta.

**Critérios de aceitação**
* O saldo deve refletir todas as transações.
* O histórico deve permanecer disponível para consulta.

---

## US08 — Histórico de serviços

> Como usuário, quero consultar meu histórico de serviços, para acompanhar todas as trocas realizadas.

**Regras de negócio**

* Exibir serviços prestados e solicitados.
* Informar os créditos envolvidos em cada transação.

**Critérios de aceitação**
* O histórico deve listar todas as trocas concluídas.
* O usuário pode visualizar os detalhes de cada serviço.

---

# Épico 5 — Avaliações e Comunicação

## US09 — Avaliação de serviços

> Como usuário, quero avaliar um serviço concluído, para compartilhar minha experiência e contribuir para a reputação dos participantes.

**Regras de negócio**

* Apenas participantes da troca podem realizar avaliações.
* A avaliação pode conter nota e comentário.

**Critérios de aceitação**
* O sistema impede avaliações duplicadas.
* A nota deve estar dentro da escala definida (por exemplo, de 1 a 5).
* A avaliação passa a ser exibida no perfil do usuário avaliado.

---

## US10 — Comunicação entre usuários

> Como usuário, quero trocar mensagens com outro participante, para combinar os detalhes da prestação do serviço.

**Regras de negócio**

* O histórico das mensagens deve permanecer disponível.
* Os usuários devem ser notificados sobre novas mensagens.

**Critérios de aceitação**
* As mensagens devem aparecer em ordem cronológica.
* O histórico deve permanecer disponível após a conclusão do serviço.

---

# Épico 6 — Administração

## US11 — Abertura de disputas

> Como usuário, quero abrir uma disputa quando ocorrer um problema na troca, para solicitar a mediação da administração.

**Regras de negócio**

* O usuário deve informar o motivo da disputa.
* A administração poderá acompanhar e analisar o caso.

**Critérios de aceitação**

* O sistema deve registrar a disputa.
* O administrador deve visualizar todas as disputas abertas.
