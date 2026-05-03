# ⏳ Tempus — Banco de Tempo

## 🧩 Problema

Alunos da Universidade de Brasília (UnB) possuem diversas habilidades úteis — como escrita, programação, tradução, ensino, entre outras — mas geralmente não possuem recursos financeiros para contratar serviços.

Assim, esses alunos também precisam de ajuda em áreas que não dominam.

Isso cria um cenário onde:
- Existe oferta de habilidades
- Existe demanda por serviços
- Mas não há um meio eficiente de troca sem dinheiro

---

## 🎯 Escopo

O **Tempus** propõe um sistema de troca baseado em tempo.

- A moeda do sistema é **hora**
- Cada hora de serviço prestado gera **1 crédito**
- Créditos podem ser usados para solicitar serviços de outros usuários

O sistema será uma aplicação web com:
- Frontend interativo
- Backend para regras de negócio
- Banco de dados para persistência

---

## ⚙️ Requisitos Funcionais

1. **Cadastro de Perfil e Skills**
   - Usuário define:
     - O que sabe fazer (oferta)
     - O que deseja aprender/receber (demanda)

2. **Mural de Ofertas/Serviços**
   - Listagem de serviços disponíveis
   - Filtro por categorias:
     - Acadêmico
     - Técnico
     - Consultoria
     - Manutenção

3. **Sistema de Agendamento/Solicitação**
   - Usuário pode solicitar um serviço
   - Confirmação entre ambas as partes

4. **Carteira de Créditos (Time Wallet)**
   - Visualização do saldo de horas
   - Débito e crédito automático por transação

5. **Histórico de Transações**
   - Registro de:
     - Quem ajudou quem
     - Duração do serviço

6. **Sistema de Avaliação e Feedback**
   - Avaliações por estrelas
   - Comentários
   - Reputação do usuário

7. **Chat Interno**
   - Comunicação entre usuários
   - Negociação de detalhes do serviço

8. **Painel de Disputas/Moderação**
   - Abertura de chamados
   - Revisão de créditos em caso de problema

---

## 🧠 Detalhes do Produto

### 🔄 Modelo de Troca
- 1 hora = 1 crédito
- Não há variação de preço por skill (modelo igualitário)

### 🔐 Segurança
- Sistema de avaliação para evitar abuso
- Moderação em disputas

### 📊 Possíveis Extensões
- Ranking de usuários
- Gamificação (badges, níveis)
- Sistema de recomendação de serviços

### 🧱 Arquitetura
- Frontend: React + Tailwind
- Backend: Java (Spring)
- Banco: postgreSQL
- Deploy: Docker + serviço gratuito
- Arquitetura MVC

---

## 🚀 Épicos do Projeto

### 1. 👤 Gestão de Usuários
- Cadastro e login
- Edição de perfil
- Definição de skills

### 2. 📢 Marketplace de Serviços
- Criação de ofertas
- Listagem e busca
- Filtros por categoria

### 3. 🔁 Sistema de Trocas
- Solicitação de serviço
- Aceite/rejeição
- Finalização da troca

### 4. 💰 Carteira de Tempo
- Controle de créditos
- Atualização automática
- Histórico financeiro

### 5. ⭐ Reputação e Feedback
- Avaliação de usuários
- Sistema de estrelas
- Comentários

### 6. 💬 Comunicação
- Chat entre usuários
- Notificações

### 7. ⚖️ Moderação
- Abertura de disputas
- Painel administrativo
- Ajuste de créditos

---

## 👨‍💻 Autores

Carlos Cauã - 231034304
Thomas Jefferson - 202033561
Gabriel Bismarck - 170103323 
Bruno Gabriel - 241022460 
Gabriel Alexandre - 241038942 

