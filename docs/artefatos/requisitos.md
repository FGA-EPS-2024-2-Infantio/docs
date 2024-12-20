# **Requisitos**

## **Introdução**

Os **requisitos** definem as funcionalidades e características que o sistema deve possuir para atender às necessidades dos usuários e objetivos da instituição. Eles servem como base para o desenvolvimento, garantindo que todas as partes interessadas tenham uma compreensão clara do que será implementado.

## **Objetivo**

Este artefato tem como objetivo reunir todos os **Requisitos Funcionais** e **Requisitos Não Funcionais** necessários para o desenvolvimento do sistema Infantio. Os requisitos funcionais detalham as funcionalidades específicas que o sistema deve oferecer, enquanto os requisitos não funcionais asseguram que o sistema seja eficiente, seguro, escalável e de fácil utilização.


## **Requisitos Funcionais**

**Requisitos Funcionais** descrevem as funcionalidades específicas que o sistema deve executar. Eles detalham o comportamento do sistema em resposta a entradas específicas, ações dos usuários ou condições do ambiente.

| **Identificação** | **Descrição** | **Épico** |
|-------------------|---------------|-----------|
| **RF01** | Permitir que administradores criem novas escolas na plataforma. | E01 |
| **RF02** | Permitir que administradores editem informações das escolas existentes. | E01 |
| **RF03** | Organizar as informações das escolas cadastradas de maneira eficiente. | E01 |
| **RF04** | Permitir que diretores cadastrem novos alunos na plataforma. | E02 |
| **RF05** | Permitir que diretores e professores visualizem as informações dos alunos cadastrados. | E02 |
| **RF06** | Permitir que diretores atualizem os dados dos alunos existentes. | E02 |
| **RF07** | Permitir que diretores excluam alunos da plataforma. | E02 |
| **RF08** | Permitir que diretores cadastrem novos professores na plataforma. | E03 |
| **RF09** | Permitir que diretores editem informações dos professores existentes. | E03 |
| **RF10** | Permitir que diretores excluam professores da plataforma. | E03 |
| **RF11** | Permitir que diretores consultem os dados relacionados aos professores. | E03 |
| **RF12** | Fornecer uma visão organizada das turmas e disciplinas associadas a cada professor. | E03 |
| **RF13** | Permitir que diretores criem novas turmas na plataforma. | E04 |
| **RF14** | Permitir que diretores atribuam professores às turmas. | E04 |
| **RF15** | Permitir que diretores atribuam alunos às turmas. | E04 |
| **RF16** | Permitir que diretores editem as informações das turmas existentes. | E04 |
| **RF17** | Permitir que diretores excluam turmas da plataforma. | E04 |
| **RF18** | Permitir que usuários façam login com credenciais únicas. | E05 |
| **RF19** | Validar as credenciais do usuário durante o processo de login. | E05 |
| **RF20** | Exibir apenas os dados correspondentes à escola vinculada ao perfil do usuário após o login. | E05 |
| **RF21** | Implementar diferentes níveis de acesso (roles) como administrador, diretor, professor e outros conforme necessário. | E05 |
| **RF22** | Garantir que apenas usuários autenticados possam acessar funcionalidades protegidas. | E05 |
| **RF23** | Permitir que administradores e diretores gerenciem (criem, editem, excluam) os roles e permissões dos usuários. | E05 |
| **RF24** | Permitir que diretores gerem um arquivo CSV contendo os dados das mensalidades dos alunos. | E07 |
| **RF25** | Permitir que diretores filtrem as mensalidades por período, escola ou turma antes de gerar o CSV. | E07 |
| **RF26** | Fornecer feedback ao usuário sobre o status da geração do CSV (e.g., sucesso, erro). | E07 |
| **RF27** | Permitir que diretores e professores gerem um relatório em PDF das presenças dos alunos. | E06 |
| **RF28** | Permitir a seleção de períodos específicos e turmas ao gerar o relatório em PDF. | E06 |
| **RF29** | Permitir que diretores enviem mensagens ou solicitações diretamente para o administrador. | E08 |
| **RF30** | Registrar todas as comunicações entre diretores e administradores para fins de auditoria. | E08 |
| **RF31** | Notificar administradores sobre novas mensagens ou solicitações recebidas dos diretores. | E08 |
| **RF32** | Categorizar as mensagens por tipo (e.g., suporte técnico, solicitações financeiras, feedback). | E08 |
| **RF33** | Permitir a anexação de documentos ou arquivos nas comunicações. | E08 |
| **RF34** | Permitir que diretores enviem mensagens para pais/mães de alunos via WhatsApp. | E09 |
| **RF35** | Permitir a personalização das mensagens enviadas aos pais/mães. | E09 |
| **RF36** | Notificar diretores sobre respostas recebidas dos pais/mães. | E09 |
| **RF37** | Permitir o envio de notificações automáticas para eventos importantes (e.g., reuniões, avisos de ausência). | E09 |
| **RF38** | Categorizar as mensagens por tipo (e.g., avisos, convites, feedback). | E09 |
| **RF39** | Permitir a anexação de documentos ou arquivos nas mensagens via WhatsApp. | E09 |
| **RF40** | Permitir que professores realizem chamadas de presença diretamente na tela. | E10 |
| **RF41** | Permitir que professores consultem informações relevantes sobre os alunos de suas turmas. | E10 |
| **RF42** | Permitir que professores e diretores registrem ocorrências relacionadas aos alunos, como advertências e suspensões. | E11 |
| **RF43** | Permitir que usuários visualizem o histórico de ocorrências de cada aluno. | E11 |
| **RF44** | Permitir que usuários registrem e acompanhem as notas dos alunos. | E11 |
| **RF45** | Integrar funcionalidades de busca e filtro para facilitar a localização de ocorrências específicas. | E11 |

## **Requisitos Não Funcionais Gerais**

**Requisitos Não Funcionais** descrevem as características e atributos do sistema que não estão diretamente relacionados a funcionalidades específicas, mas são essenciais para a qualidade e o desempenho do sistema como um todo.

| **Identificação** | **Descrição** |
|-------------------|---------------|
| **RNF01** | **Desempenho:** O tempo de carregamento das páginas não deve exceder 3 segundos. |
| **RNF02** | **Segurança:** Todos os dados sensíveis devem ser armazenados de forma segura, limitando o acesso apenas a pessoas autorizadas. |
| **RNF03** | **Escalabilidade:** Deve suportar a adição de novas funcionalidades sem impactar o desempenho existente. |
| **RNF04** | **Usabilidade:** A interface do usuário deve ser intuitiva e fácil de navegar. |
| **RNF05** | **Compatibilidade:** O sistema deve ser compatível com os principais navegadores (Chrome, Firefox, Edge, Safari). |
| **RNF06** | **Confiabilidade:** O sistema deve garantir a integridade dos dados, evitando perdas ou corrupções. |
| **RNF07** | **Manutenibilidade:** O código-fonte deve ser modular e bem documentado para facilitar futuras manutenções e atualizações. |
