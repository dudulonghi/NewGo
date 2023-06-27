# Respostas  

## Questão 1

**Quais são os contras de utilizar se herança entre classes? Quais alternativas você adotaria caso quisesse deixar de usar herança em um relacionamento específico? Dê um exemplo.**

R: Acho que uma desvantagem de se utilizar herança entre classe é justamente a junção rígida das classes, tanto classe filho tanto pai.
Uma vez que, se eu quiser fazer alguma atualização na classe pai, a classe filha pode sofrer para ser modificada ou atualizada. E para melhorar 
eu utilizaria "Agregação", uma vez que ela vai reutilizar os códigos, mas sem acoplar inteiramente (é como se fosse uma referência). Por exemplo, eu tenho time de futebol
e jogadores, eu como time de futebol, posso atualizar o jogador,, mas cada jogador é independente, ele possui seus proprios metódos.


## Questão 2

**Suponha que você tem uma classe final, da qual você não tem o código-fonte, e que você deseja adicioná-la a uma estrutura de polimorfismo, mas cuja interface pública é**
**ligeiramente diferente da classe. Que padrão de projeto você poderia utilizar para aSproveitar o código desta classe, mas fazendo com que ela atenda à interface da**
**esperada na estrutura de polimorfismo?**

R: Um padrão de projeto que caberia no enunciado é o Adapter, porque ele permite que as classes com interfaces incompatíveis trabalhem em conjunto.

## Questão 3

**Em que cenários você poderia usar um proxy? Dê um exemplo real**

R: Quando você controlar o acesso a um objeto. Ele é muito utilizado para fazer autenticação de usuário.

## Questão 4

**Você prefere utilizar domínios anêmicos ou ricos? Como avalia os prós e contras de cada?**

R: Depende muito, mas no geral prefiro utilizar o rico, uma vez que ele visa conter tanto os métodos tanto as classes.
**Pros Anêmicos:** Simples e Fácil dividir cada seção do projeto 
**Contras Anêmicos:** Faltar informações para concluir uma determinada funcionalidade

**Pros Ricos:** Possui mais informações, o que ccolabora para ter um domínio de negocio melhor 
**Contras Ricos:** Mais difícil.

## Questão 5

**Dê um exemplo do bom uso do princípio OCP, da sigla SOLID.**

R: Sendo sincero essa eu não faço ideia, não aprendi na faculdade e nem por fora. Mas vou dar uma pesquisada e colocar o que entendi. 
Pelo o que eu entendi, você consegue melhorar a qualidade do código basicamente com abstração.

## Questão 6

**Qual é a diferença entre requisitos funcionais, não-funcionais e regras de negócio. Dê um exemplo de cada.**

R: Tenho um sistema de calculo de IMC para um nutricionista

   requisitos funcionais: São as funcionalidades do sistema, o que foi pedido e o que ele vai fazer.(O calculo em si do IMC)
   requisitos não-funcionais: é mas a parte de usabilidade do sistema, como se fossem os atributos do sistema. (O tempo que meu sistema vai demorar para executar o calculo)
   regras de negócio: Vai ser toda a documentação do projeto que está sendo desenvolvido. (Diagramas por exemplo)

## Questão 7

**Quais estratégias de diagramação você utiliza em seus projetos? Quais diagramas e por quê?**

R: Em projetos da faculdade e em paralelo a ela. Normalmente começo com o diagrama de Casos de Uso para identificar as ações e qual ator está envolvido. Depois passo 
para o de Classe, que vou fazer as relações entre elas e identificar quais são as principais. E depois o de sequencia, que mostra o fluxo de informações e os caminhos a serem seguidos. Nos projetos que eu fiz, foram basicamentem esses.

## Questão 8

**Você está utilizando GitFlow e precisa fazer uma alteração na versão em desenvolvimento de um projeto. Quais etapas você teria que realizar?**

R: Dentro do Git, nós temos varias formas de organização. No GitFlow a gente tem a main, developer e release pelo o que eu me lembro. Então primeiramente eu iria desenvolver na branch developer e fazendo os commit, e quando eu for entregar eu subo na branch master, que no caso é a branch main.

## Questão 9

**O que você deve ter feito para que uma funcionalidade que você pegou para implementar seja considerada como 'done'?**

R: Para ser considerado um done, temos primeiramente que ter entendido os requisitos do sistema, após isso ter uma ideia de como vai ser feitos o projeto. Após as fases primárias, devemos fazer testes, correção do que der errado e  após isso ele está pronto para ser um concluido, e sempre fazer a documentação, para que pessoas após você, saiba sobre o que se trata.

## Questão 10

**Quais são as cerimônias do SCRUM e como você avalia a importância de cada?**

R: O Scrum hoje em dia é uma metodologia utilizada em várias empresas e lugares. Eu utilizei o scrum na faculdade em algumas aulas e tem algumas coisas importântes dele, como por exemplo o planejamento antes de tudo, as reuniões diárias que duram em torno de 15 minutos, para conversar  sobre o que foi feito no dia passado e o que vai ser feito hoje e a revisão. Todas são muito importânte, sem planejamento não tem como trabalhar, as reuniões são boas para todo mundo se situar onde está e não ter desavença de desenvolvimento e a revisão é importânte para entregar o melhor projeto para o cliente.

## Questão 11

**Você conhece e utiliza Docker nos seus projetos? Se sim, para que?**

R: Eu não conheço Docker e nunca utilizei, porém não tenho medo de aprender, estou buscando uma oportunidade justamente para aprender coisas novas e agregar algum valor se possível.
