# MedSync
O projeto aporta a ideia de desenvolver um projeto web de agendamento de consultas em uma clínica pediátrica. O modelo web prioriza 
uma interface clara e objetiva, na qual o usuário tem acesso a agenda dos médicos. Considerando a seguinte aplicação, o usuário tem 
a liberdade de escolher o melhor dia e horário que esteja vago para ser atendido pelo médico escolhido.

Com uma interface intuitiva, o MedSync permitirá:
  - Agendar consultas rapidamente;
  - Gerenciar horários de forma eficiente;
  - Acesso seguro com autenticação;
  - Experiência simplificada para médicos e pacientes.

O projeto explora as seguintes tecnologias 
  - Protótipo: Figma | https://www.figma.com/design/dXYr0pZcivGla5FqEZlu7M/MedSync?node-id=0-1&t=xuBF85ODqzFKkprE-1
  - FrontEnd: React, JavaScript visando uma interface dinâmica e responsiva; 
  - Backend: Node.js, CRUD, leve e eficiente para o nosso desenvolvimento; 
  - Banco de dados: MySQL, adequado para o armazenamento de dados estruturado; 
  - Monolítica: Formato ideal para o nosso projeto, priorizando a simplicidade do desenvolvimento.
  - Autenticação: JWT (JSON Web Tokens) para segurança, recomendado para autenticação em aplicações web 
  - Deploy:

Operações CRUD 
  - Create: Criar agendamento na clínica, permitindo a seleção por doutor/especialidade;
  - Read: Visualização do agendamento realizado;
  - Update: Alteração do horário agendado, não permitindo alteração de especialidade;
  - Delete: Deletar o agendamento.

Requisitos Funcionais:  
  - Login e registro de pacientes, para autenticação dos usuários; 
  - Visualização da agenda dos médicos, por parte do paciente; 
  - Seleção de horários disponíveis; 
  - Confirmação de agendamento (redirecionamento para WhatsApp);
  - Cancelamento de consultas agendadas (redirecionamento para WhatsApp);
  - Acesso às informações do médico: agenda, especialização, CRM. 

Requisitos não funcionais  
  - Proteção de dados sensíveis (LGPD compliance);
  - Tempo de resposta rápido para agendamentos e consultas;
  - Suporte a múltiplos usuários simultaneamente;
  - Capacidade de adicionar novos médicos e pacientes sem impactar o desempenho. 

Ferramenta para controle de atividades:
- https://statics.teams.cdn.office.net/evergreen-assets/safelinks/1/atp-safelinks.html

Frontend: 
  - Desenvolvimento das telas de login, registro, agendamento e perfil.
  - Integração com a API do backend.

Backend: 
  - Criação das APIs para autenticação, agendamento e gerenciamento de perfis.
  - Integração com o banco de dados.

Banco de Dados: 
  - Modelagem do banco de dados (tabelas de usuários, médicos, consultas).
  - Configuração e deploy do banco. 

Testes: 
  - Testes unitários e de integração.
  - Correção de bugs. 

Documentação: 
  - Documentação do código e do projeto.
  - Atualização do repositório no GitHub. 

  - Ajustes sugeridos - primeira interação 24/02
Não foram feitas alterações significativas em relação ao projeto inicial apresentado pela equipe. O projeto foi aceito pelo Professor
orientador com entusiasmo, levando em consideração o protótipo do Figma apresentado.

  - Ajustes sugeridos - segunda interação 10/03
