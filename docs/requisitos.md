# Requisitos

## Requisitos Não Funcionais

1. **RNF1 (Segurança e Autenticação):** O sistema deve garantir que apenas usuários com e-mail institucional válido da Universidade de Brasília (@aluno.unb.br ou @unb.br) possam se cadastrar.
2. **RNF2 (Usabilidade):** O sistema deve possuir interface simples e intuitiva, permitindo que os usuários encontrem, ofereçam e solicitem serviços com facilidade.
3. **RNF3 (Responsividade):** O sistema deve possuir interface adaptável a diferentes tamanhos de tela, como computadores, tablets e celulares.
4. **RNF4 (Desempenho):** O sistema deve carregar páginas e informações essenciais em tempo adequado para não prejudicar a experiência do usuário.
5. **RNF5 (Auditabilidade):** O sistema deve manter registros das transações de créditos de tempo para permitir consulta, conferência e resolução de disputas.
6. **RNF6 (Disponibilidade):** O sistema deve estar disponível para acesso dos usuários durante os períodos de uso acadêmico.
   
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
