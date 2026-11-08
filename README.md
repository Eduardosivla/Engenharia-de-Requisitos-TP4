## Documentação do Software: Sistema de Controle de uso de Sala de Aula da Universidade

<br>

<div align="justify">
  
## 1. Introdução
### 1.1 Descrição geral do Software

O Sistema é uma aplicação web e mobile que controla de uso de Salas de Aula de Universidades Públicas. O foco do sistemas é eliminar a maneira de distruibuições e disponibilização das salas de aula que, geralmente, são gerenciadas por planilhas ou avisos de informações, o que pode ocasionar em 'choques' e dificuldades em encontrar salas livreas para atividades acadêmicas. O sistema mantém e apresenta uma grade fixa a cada semestre, permitindo reservas eventuais, detecta conflitos de horários, mostra ocupações em tempo real e gera relatórios

---

### 1.2 Descrição dos usuários

O Sistema é direcionado à sociedade acadêmica como: discentes, docentes, coordenadores e secretários.


|Usuário|Descrição|
|-------|---------|
|Discentes|Esses usuários são alunos de Universidade Pública que desejam consultar salas de aulas e solicitam as mesmas para atividades acadêmicas, como estudos em grupo ou ensaios de apresentações|
|Alunos|Esses usuários são professores de Universidade Pública que consultam a grande, disponibilizada pelo sistema, e solicitam salas para reposições, aulas extras, defesas e eventos|
|Administrador (Coordenação/secretária)| responsável por cadastrar salas, montar a grade fixa, aprovar ou recusar reservas e consultar relatórios. (Perfil acrescentado para viabilizar as funções de gestão)|
</p>

<br>

### 2. Requisitos Gerais do Software
---
#### 2.1 Requisitos Funcionais
| ID | Nome | Descrição | Prioridade |
| :--- | :--- | :--- | :--- |
| RF-01 | Realizar Login | O sistema deve permitir que o usuário acesse com e-mail e senha. | Essencial |
| RF-02 | Cadastrar Usuário | O sistema deve permitir o cadastro do usuário informando e-mail, senha e categoria (aluno ou docente). | Essencial |
| RF-03 | Encerrar Sessão | O sistema deve permitir que o usuário encerre sua sessão com segurança. | Essencial |
| RF-04 | Gerenciar Salas | O administrador deve poder cadastrar, editar e desativar salas, informando bloco, sala. | Essencial |
| RF-05 | Montar grade fixa | O administrador deve poder alocar turmas em salas e horários para o semestre. | Essencial |
| RF-06 | Consultar ocupação | O administrador deve poder alocar turmas em salas e horários para o semestre. | Essencial |
| RF-07 | Detectar conflitos | O sistema deve impedir ou alertar sobre duas alocações na mesma sala e horário, ou do mesmo docente em salas diferentes no mesmo horário. | Essencial |
| RF-08 | Solicitar reserva eventual | Docentes e alunos devem poder solicitar uma sala livre informando data, horário, finalidade e número de participantes. | Importante |
| RF-09 | Cancelar reserva | O usuário deve poder cancelar reservas eventuais próprias. | Importante |
| RF-10 | Aprovar/recusar reserva | O administrador deve poder aprovar ou recusar solicitações pendentes. | Importante |
| RF-11 | Notificar usuário | O sistema deve notificar por e-mail mudanças de sala, aprovações e recusas. | Desejável |
| RF-12 | Emitir relatório de ocupação | O sistema deve gerar relatório de uso das salas por período, com taxa de ocupação. | Desejável |

---
#### 2.2. Requisitos Não Funcionais

| ID | Categoria | Descrição |
| :--- | :--- | :--- |
| RNF-01 | Desempenho | A autenticação deve ser concluída em até 2 segundos. |
| RNF-02 | Desempenho | A consulta de ocupação de um dia deve ser exibida em até 3 segundos. |
| RNF-03 | Segurança | Senhas devem ser armazenadas com hash e a comunicação deve usar HTTPS. |
| RNF-04 | Usabilidade | Um docente novo deve conseguir localizar uma sala livre e reservá-la em até 3 minutos sem treinamento. |
| RNF-05 | Disponibilidade | O sistema deve estar disponível pelo menos 95% do tempo no horário letivo. |
| RNF-06 | Compatibilidade | Deve funcionar nas versões atuais de Chrome, Firefox e Edge. |
| RNF-07 | Privacidade | O tratamento de dados pessoais deve seguir a LGPD. |

---
#### 2.3. Regras de Negócio

| ID | Nome | Descrição | Prioridade |
| :--- | :--- | :--- | :--- |
| RF01 | Realizar login | O sistema deve permitir que o usuário acesse com e-mail e senha. | Essencial |
| RF02 | Cadastrar usuário | O sistema deve permitir o cadastro de usuário informando e-mail, senha e categoria. | Essencial |
| RF03 | Encerrar sessão | O sistema deve permitir que o usuário encerre sua sessão com segurança. | Essencial |
| RF04 | Gerenciar salas | O administrador deve poder cadastrar, editar e desativar salas, informando bloco, capacidade e recursos (projetor, ar-condicionado, computadores). | Essencial |
| RF05 | Montar grade fixa | O administrador deve poder alocar turmas em salas e horários para o semestre. | Essencial|

<br>

### 3. Diagramas UML
---
#### 3.1 Diagramas de Casos de Uso
[Caso de Uso - Usuário](https://github.com/user-attachments/assets/a8eb2aad-ea12-40a2-85ea-b9c3f6295853)

[Caso de Uso - Docente](https://github.com/user-attachments/assets/a9ffe9ce-812d-4502-bc78-423c9b819132)

[Caso de Uso - Discente](https://github.com/user-attachments/assets/0d1b3e22-750e-45ff-bb99-53e581ea0ddb)

[Caso de Uso - Coordenador](https://github.com/user-attachments/assets/b72d1dd3-ab66-471f-a4a4-61c84040cdb4)

---
#### 3.1 Diagrama de Sequência
[Diagrama de Sequência - Cadastro](github.com/user-attachments/assets/dca0174b-bf71-408e-ab77-3e447a8d623c)

---
#### 3.2 Diagrama de Atividade
[Diagrama de Atividade - Escolher Sala](github.com/user-attachments/assets/5dc42de8-7691-4356-80a5-636f039aa6c0)

</div>







