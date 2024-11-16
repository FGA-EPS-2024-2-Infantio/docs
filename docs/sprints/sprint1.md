# Sprint 1

## Issues e responsáveis

| Atividade                                   | Responsável(is)                                                                               |
|---------------------------------------------|-----------------------------------------------------------------------------------------------|
| Criar e listar professor                    | Matheus Soares Arruda, Mateus Caltabiano Neves Frauzino, João Victor Correia de Oliveira      |
| Criar e listar alunos                       | Victor Eduardo Araújo Ribeiro, Pedro de Miranda Haick, Vitor Manoel Aquino de Brito           |
| Integração com SonarQube                    | Gabriel Ferreira da Silva, Pedro Helias Carlos, Caio Vitor Carneiro de Oliveira                                           |
| Integração com o Auth0                      | Guilherme Keyti Cabral Kishimoto, Matheus Calixto Vaz Pinheiro, Felipe Alef Pereira Rodrigues |
| Tela de preenchimento de matricula de aluno | Hugo Rocha de Moura, Henrique  Pucci da Silva Pinto                                           |
| CRUD de escolas                             | Lucas Lopes Frazão                                                                            |

## Reuniões de acompanhamento

### Dia 12/11/2024

| Atividade                                   | O que foi feito                                                                                                                               | O que falta fazer                        |
|---------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------|
| Criar e listar professor                    | Desenvolvimento concluído no backend                                                                                                          | Desenvolvimento do frontend              |
| Criar e listar alunos                       | Backend já está funcional com todas as rotas CRUD. Frontend está em estado inicial                                                            | Finalizar o frontend                     |
| Integração com SonarQube                    | Estudo e configuração do Sonarqube a nível local no backend e frontend, para coleta de testes, verificação de segurança e cobertura de código | Explicação de como rodar o Sonar Scanner |
| Integração com o Auth0                      | Login e logout com o auth0 estão configurados e redirecionando corretamente                                                                   | Tela de login e bug de logout            |
| Tela de preenchimento de matricula de aluno | Iriam iniciar a issue                                                                                                                                 | -                                        |
| CRUD de escolas                             | Foi finalizado o fluxo completo                                                                                                               | Testes                                   |


### Dia 14/11/2024

| Atividade                                   | O que foi feito                                                                                                                                                                                                                     | O que falta fazer                                                                                                                            |
|---------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------|
| Criar e listar professor                    | Finalização do frontend                                                                                                                                                                                                             | Correção do PR e merge                                                                                                                       |
| Criar e listar alunos                       | Evolução do frontend e ajustes de captura de erro no backend                                                                                                                                                                        | Teste do backend, e finalização do frontend (editar e excluir)                                                                               |
| Integração com SonarQube                    | SonarQube está integrado no backend e frontend. SonarScanner está rodando por fora, é necessário rodar ele no docker-compose para evitar a instalação local                                                                         | SonarScanner no docker e documentação de como rodar o SonarQube + SonarScanner e a esteira de CI/CD.                                         |
| Integração com o Auth0                      | O fluxo de login está funcionando. A proteção dos endpoints no backend já está implementada, mas por enquanto só em um endpoint de teste. A requisição para pegar o token no Postman com a API do Auth0 também já está configurada. | Implementar no front a requisição na API do Auth0 para pegar o token depois de logado;. A tela com o botão de login antes de acessar o site. |
| Tela de preenchimento de matricula de aluno | Finalizado                                                                                                                                                                                                                          | Correção do PR e merge                                                                                                                       |
| CRUD de escolas                             | Testes realizados                                                                                                                                                                                                                   | -                                                                                                                                            |

## Avaliação de pares

| Menção e pequeno relato          | Matheus Soares Arruda | Mateus Caltabiano Neves Frauzino | João Victor Correia de Oliveira |
|----------------------------------|-----------------------|----------------------------------|---------------------------------|
| Matheus Soares Arruda            |                       |                                  |                                 |
| Mateus Caltabiano Neves Frauzino |                       |                                  |                                 |
| João Victor Correia de Oliveira  |                       |                                  |                                 |


| Menção e pequeno relato       | Victor Eduardo Araújo Ribeiro | Pedro de Miranda Haick | Vitor Manoel Aquino de Brito |
|-------------------------------|-------------------------------|------------------------|------------------------------|
| Victor Eduardo Araújo Ribeiro |                               |                        |                              |
| Pedro de Miranda Haick        |                               |                        |                              |
| Vitor Manoel Aquino de Brito  |                               |                        |                              |

| Menção e pequeno relato         | Gabriel Ferreira da Silva | Pedro Helias Carlos | Caio Vitor Carneiro de Oliveira |
|---------------------------------|---------------------------|---------------------|---------------------------------|
| Gabriel Ferreira da Silva       |                           |                     |                                 |
| Pedro Helias Carlos             |                           |                     |                                 |
| Caio Vitor Carneiro de Oliveira |                           |                     |                                 |

| Menção e pequeno relato          | Guilherme Keyti Cabral Kishimoto | Matheus Calixto Vaz Pinheiro | Felipe Alef Pereira Rodrigues |
|----------------------------------|----------------------------------|------------------------------|-------------------------------|
| Guilherme Keyti Cabral Kishimoto |                                  |                              |                               |
| Matheus Calixto Vaz Pinheiro     |                                  |                              |                               |
| Felipe Alef Pereira Rodrigues    |                                  |                              |                               |

| Menção e pequeno relato       | Hugo Rocha de Moura | Henrique Pucci da Silva Pinto |
|-------------------------------|---------------------|-------------------------------|
| Hugo Rocha de Moura           |                     |                               |
| Henrique Pucci da Silva Pinto |                     |                               |

| Menção e pequeno relato          | Lucas Lopes Frazão | Líderes |
|----------------------------------|--------------------|---------|
| Matheus Soares Arruda            |                    |         |
| Gabriel Ferreira da Silva        |                    |         |
| Victor Eduardo Araújo Ribeiro    |                    |         |
| Guilherme Keyti Cabral Kishimoto |                    |         |
| Hugo Rocha de Moura              |                    |         |
| Lucas Lopes Frazão               |                    |         |

## Sprint review

| O que rolou de bom | O que rolou de ruim | Como melhorar |
|--------------------|---------------------|---------------|
|                    |                     |               |
|                    |                     |               |
|                    |                     |               |
|                    |                     |               |
|                    |                     |               |
|                    |                     |               |