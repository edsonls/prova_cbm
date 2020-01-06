# Prova CBMSE 2020

Para concorrer a vaga o candidato terá que desenvolver uma aplicação web utilizando as tecnologias abaixo listadas, cujo o objetivo será realizar todas as operações de CRUD.


# Tecnologias
 - ReactJS
 - Bootstrap, Material ou qualquer framework de estilização
 - PHP >= 7 (livre para usar qualquer framework)
 - Postgress | MySQL

## Instruções da prova

 - O candidato deve fazer um **fork** desse repositório e criar sua estrutura de pastas sendo que no mesmo repositório tem que esta o **fron-end, back-end** e o sql contendo o **schema** do banco de dados.
 - Após o projeto pronto o candidato deve fazer o *commit e push* para o seu repositório **não sendo necessário** solicitar um **pull-request**
 

## Projeto

 - Existe uma API pública [(Link)](https://viacep.com.br/), que dado um determinado CEP, ela te retorna as informações do mesmo.  
 ![exemplo](https://www.imagemhost.com.br/images/2020/01/04/Screenshot_2020-01-04-ViaCEP---Webservice-CEP-e-IBGE-gratuito.png)
 - A partir das informações acima, desenvolva um sistema que consuma a API com cep válido seguindo modelo de tela/mockup de **referência** para aplicação ![](https://www.imagemhost.com.br/images/2020/01/04/Screenshot_2020-01-04-Prova-de-Selecao-Programador-Senior2727-pdf.png)
 - Crie uma estrutura de tabela na sua base de dados, para persistir as informações retornadas da API, de acordo com o protótipo de tela acima
 - Ao consultar um CEP verificar se já existe o CEP informado na base de dados local.
 - A partir da resposta recebidada API,salve em uma tabela de banco de dados as seguintes informações: *CEP, Logradouro, complemento, bairro, cidade, estado*
 - Crie a funcionalidade Editar, juntamente com o formulário, onde só será permitido alterar as informações *Logradouro, complemento, bairro, cidade, estado.*
 - Crie a Funcionalidade Deletar, onde dever ser perguntado ao Usuário antes de executar a ação: “Tem certeza que deseja Excluir o endereço?”.
 - Crie a Funcionalidade Visualizar do CEP.

 
## Oque será avaliado?
O desafio será avaliado através dos seguintes critérios.

 - Habilidade com framework de front-end e/ou back-end
 - Habilidade em estilização de pagina HTML
 - POO
 - API-REST
 - Arquitetura do projeto
 - Banco de Dados seguindo as melhores práticas

## Entrega

 - O código possui algum controle de dependências?
 - O resultado final está completo para ser executado?
 - O resultado final atende ao que se propõe fazer?
 - O resultado final atende totalmente aos requisitos propostos?

## Boas Práticas

 - O código está bem estruturado?
 - O código está fluente na linguagem?
 - O código faz o uso correto de Design Patterns?

## Documentação

 - O código foi entregue com um arquivo de README claro de como se guiar?
 - O código possui comentários pertinentes?
 - O código está em algum controle de versão?
 - Os commits são pequenos e consistentes?
 - As mensagens de commit são claras?

## Código Limpo

 - O código possibilita expansão para novas funcionalidades?
 - O código é Don't Repeat Yourself?
 - O código é fácil de compreender?
