# Modelagem de Dados (DER)

Abaixo está o Modelo Conceitual e Físico do sistema Tempus, construído a partir do Backlog de produto. Ele mapeia as entidades fortes (Usuário e Oferta) e o fluxo de entidades fracas geradas durante a prestação do serviço (Solicitação, Transação, Mensagem e Avaliação).

![Diagrama Entidade-Relacionamento](der-tempus.png)

```mermaid
erDiagram
    USUARIO ||--o{ USUARIO_SKILL : "possui (FK)"
    USUARIO ||--o{ OFERTA : "publica (FK)"
    USUARIO ||--o{ SOLICITACAO : "solicita (FK)"
    OFERTA ||--o{ SOLICITACAO : "recebe (FK)"
    SOLICITACAO ||--o| TRANSACAO : "gera (FK)"
    SOLICITACAO ||--o{ MENSAGEM : "contem (FK)"
    SOLICITACAO ||--o| AVALIACAO : "possui (FK)"

    USUARIO {
        VARCHAR(100) email PK
        VARCHAR(100) nome
        INTEGER saldo_horas
    }

    USUARIO_SKILL {
        VARCHAR(100) email_usuario PK, FK
        VARCHAR(50) skill PK
    }

    OFERTA {
        INTEGER cod_oferta PK
        VARCHAR(100) titulo
        VARCHAR(50) categoria
        VARCHAR(100) email_publicador FK
    }

    SOLICITACAO {
        INTEGER cod_solicitacao PK
        VARCHAR(20) status
        DATE data
        VARCHAR(100) email_solicitante FK
        INTEGER cod_oferta FK
    }

    TRANSACAO {
        INTEGER cod_transacao PK
        INTEGER horas_debitadas
        INTEGER cod_solicitacao FK
    }

    MENSAGEM {
        INTEGER cod_mensagem PK
        VARCHAR(255) texto
        TIMESTAMP data_hora
        INTEGER cod_solicitacao FK
    }

    AVALIACAO {
        INTEGER cod_avaliacao PK
        INTEGER estrelas
        VARCHAR(255) comentario
        INTEGER cod_solicitacao FK
    }
```
