# Metodologia

## Controle de Versão

A ferramenta de controle de versão adotada no projeto foi o [Git](https://git-scm.com/), sendo que o [Github](https://github.com) está sendo  utilizado para hospedagem do repositório.

O projeto segue a convenção do [Gitflow](https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow) para nomenclatura e fluxo de trabalho com branches, para isso, nós temos:

- `main`: versão estável já testada do software
- `develop`: versão de desenvolvimento do software
- `docs`: branch para modificações na documentação geral do projeto
- `feature/*`: branches utilizadas para desenvolvimento de uma nova funcionalidade, devem ser excluídas após o merge com `develop`
- `release/*`: branches de entrega do projeto de acordo com os marcos estabelecidos na disciplina

À nivel de desenvolvimento temos três principais eventos que trabalham com as branches:

- *Desenvolvimento de uma nova funcionalidade*: são utilizadas as branches de `feature/*` criadas a partir de `develop` e, ao finalizadas, devem ser integradas de volta com essa branch.
- *Melhorias na documentação*: a branch de documentação deve ser atualizada com a `main` ao iniciar o desenvolvimento e integrada de volta ao finalizar.
- *Entrega do projeto*: durante as entregas todo o código disponível em `develop` deve ser utilizado como base para criar uma nova branch `release/*` que posteriormente é integrada à `main`. Esse processo também deve gerar uma nova tag contendo a versão atual do projeto num modelo de [versionamento semântico](https://semver.org/).

## Gerenciamento de Projeto

### Divisão de Papéis

| [<img alt="Victor Henry" src="https://github.com/Victruviuz.png?size=115" width="115"><br><sub>Victor Henry</sub>](https://github.com/Victruviuz)<p>Dev</p> | [<img alt="João Sena" src="https://github.com/JoaoSena13.png?size=115" width="115"><br><sub>João Sena</sub>](https://github.com/JoaoSena13)<p>Dev</p>  | [<img alt="Roberto Eller" src="https://github.com/repaiva.png?size=115" width="115"><br><sub>Roberto Eller</sub>](https://github.com/repaiva)<p>Scrum Master</p>  | [<img alt="Lucas Arcanjo" src="https://github.com/lucassarcanjo.png?size=115" width="115"><br><sub>Lucas Arcanjo</sub>](https://github.com/LucasSArcanjo)<p>Product Owner</p>  | [<img alt="João Gustavo Medeiros" src="https://github.com/pontesj.png?size=115" width="115"><br><sub>João Gustavo Medeiros</sub>](https://github.com/pontesj)<p>Dev</p>  | [<img alt="Renato Haniel" src="https://github.com/RHanielGit.png?size=115" width="115"><br><sub>Renato Haniel</sub>](https://github.com/RHanielGit)<p>Dev</p>  |
| :---: |:---: |:---: |:---: |:---: |:---: |

- **Development Team (Dev)**: os desenvolvedores são responsáveis pela execução das tarefas de cada Sprint.
- **Product Owner**: cria e comunica os itens do backlog.
- **Scrum Master**: conduz e ajuda o time a entender a teoria e prática do Scrum, garantindo a eficácia do trabalho a partir do agilismo.

### Gerenciamento das tarefas

Para gerir as tarefas do projeto e acompanhar as atividades desenvolvidas por cada membro do time, foi criado um Trello 

Divisão do kanban:

- Backlog: banco de tarefas que precisam ser discutidas e refinadas
- Ready to start: história pronta para ser iniciada, já com os detalhes necessários para desenvolvimento
- Doing: história em desenvolvimento que deve estar atribuída à um desenvolvedor
- Tests: depois de finalizado o desenvolvimento, é hora de testar as implementações em dupla com outro membro desenvolvedor
- Done: quando o código da história é incorporado à branch `main` e as validações passam com sucesso, ela finalizou.

### Ferramentas

As ferramentas empregadas no projeto são:

- Visual Studio Code: editor de código extremamente versátil para desenvolvimento de aplicações web.
- WhatsApp: comunicação base do grupo por meio de um grupo para alinhamento
- Figma: ferramenta para prototipação de telas.
- Trello: controle e mapeamento das tarefas do projeto.
