# Especificações do Projeto

O Fake Detector tem o intuito de auxiliar uma pessoa que quer saber de uma notícia é verdadeira ou falsa, por exemplo, uma pessoa recebeu uma notícia em alguma rede social e quer saber se essa notícia é verdadeira ou falsa, ai então entra o fake detector, a pessoa vai entrar em nosso site, colocar o link que recebeu e o site dará a resposta se a noticia é verdadeira ou falsa, o site vai buscar em diversas fontes na internet para dizer se a notícia é verdadeira ou falsa.

O Fake Detector utiliza as seguites tecnologias: HTML, CSS, JAVASRIPT, BOOTSTRAP


<!-- <span style="color:red">Pré-requisitos: <a href="1-Documentação de Contexto.md"> Documentação de Contexto</a></span>

Definição do problema e ideia de solução a partir da perspectiva do usuário. É composta pela definição do  diagrama de personas, histórias de usuários, requisitos funcionais e não funcionais além das restrições do projeto.

Apresente uma visão geral do que será abordado nesta parte do documento, enumerando as técnicas e/ou ferramentas utilizadas para realizar a especificações do projeto -->

## Personas

- José Roberto tem 37 anos, é administrador de sistemas, casado, tem 2 filhos, trabalha em uma empresa de Marketing em São Paulo. Com o alto número de Fake News, ele tem a necessidade de um atalho para verificar a veracidade das notícias, visando diminuir o tempo gasto na busca de informações verdadeiras.
- Ítalo possui 22 anos, graduando em ciências sociais pela PUC-Minas. Encontrou dificuldade em diferenciar as notícias falsas e fontes para o seu TCC, encontrando no Fake Detector a possibilidade de não somente agilizar o seu rendimento com o processo de discernimento, como também garantir a validade das informações. 
- Natália Dutra possui 45 anos, casada e é advogada e trabalha no tribunal de justiça de Belo Horizonte. Devido a sua profissão necessita ficar bem-informada das notícias, principalmente as ligadas a política. Entretanto, Natália possui pouco contato com aparelhos mobile, assim encontrando uma grande dificuldade na consulta de informações verídicas.


<!-- >> **Links Úteis**:
> - [Rock Content](https://rockcontent.com/blog/personas/)
> - [Hotmart](https://blog.hotmart.com/pt-br/como-criar-persona-negocio/)
> - [O que é persona?](https://resultadosdigitais.com.br/blog/persona-o-que-e/)
> - [Persona x Público-alvo](https://flammo.com.br/blog/persona-e-publico-alvo-qual-a-diferenca/)
> - [Mapa de Empatia](https://resultadosdigitais.com.br/blog/mapa-da-empatia/)
> - [Mapa de Stalkeholders](https://www.racecomunicacao.com.br/blog/como-fazer-o-mapeamento-de-stakeholders/)
> -->
Lembre-se que você deve ser enumerar e descrever precisamente e personalizada todos os clientes ideais que sua solução almeja.

## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|Administrador de sistemas | Gerenciar dados de usuário disponiveis | Manter o sitema funcionando de forma correta |
|Universitário | Verificar a veracidade das noticias | Utilizar informações corretas em pesquisas |
|Pessoa comum | Verificar a veracidade das noticias |Compartilhar notícias veradeiras |
|Profissional de direito | Verificar a veracidade das noticias |Poder utilizar notícias verdadeiras |
|Usuário Final | Verificar a veracidade das noticias | Se informar com noticias verdadeiras |

<!--Apresente aqui as histórias de usuário que são relevantes para o projeto de sua solução. As Histórias de Usuário consistem em uma ferramenta poderosa para a compreensão e elicitação dos requisitos funcionais e não funcionais da sua aplicação. Se possível, agrupe as histórias de usuário por contexto, para facilitar consultas recorrentes à essa parte do documento.

<!-- >> **Links Úteis**:
> - [Histórias de usuários com exemplos e template](https://www.atlassian.com/br/agile/project-management/user-stories)
> - [Como escrever boas histórias de usuário (User Stories)](https://medium.com/vertice/como-escrever-boas-users-stories-hist%C3%B3rias-de-usu%C3%A1rios-b29c75043fac)
> - [User Stories: requisitos que humanos entendem](https://www.luiztools.com.br/post/user-stories-descricao-de-requisitos-que-humanos-entendem/)
> - [Histórias de Usuários: mais exemplos](https://www.reqview.com/doc/user-stories-example.html)
> - [9 Common User Story Mistakes](https://airfocus.com/blog/user-story-mistakes/) -->

## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001| Permitir que o usuário verifique a veracidade de uma notícia | ALTA | 
|RF-002| Garantir um controle de usuários que utilizem a plataforma   | MÉDIA |
|RF-003| Exibir fontes confiáveis ao detectar fake news  | MÉDIA |


### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| O sistema deve ser responsivo para rodar em um dispositivos móveis | MÉDIA | 
|RNF-002| Deve processar requisições do usuário em no máximo 3s |  BAIXA | 
|RNF-002| Deve ser acessível para qualquer pessoa a partir de um link da internet |  BAIXA | 

## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O projeto deverá ser entregue até o final do semestre |
|02| Não pode ser desenvolvido um módulo de backend        |
