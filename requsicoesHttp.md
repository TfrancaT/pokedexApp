# Requisições HTTP & Consumir APIs

- API ⇒ é um servidor que está ‘servindo’ dados/informações para serem utilizados em páginas web;
    - ela funciona entorno do protocolo HTTP;

## ************************REQUISIÇÕES:************************

- o protocolo HTTP funciona como uma interação entre o cliente (usuário final) e servidor (local onde estão armazenados informações das páginas web);

## **********MONTANDO REQUISIÇÕES HTTP:**********

- URL ⇒ Path ⇒ endereço do recurso que queremos********;********
    - ou pode se entender como o ********link******** de um site, por exemplo;
- Ex ⇒ URL: [https://pokeapi.co/api/v2/pokemon](https://pokeapi.co/api/v2/pokemon)
- na URL também, podemos identificar exatamente o que queremos do servidor
    - Ex² ⇒ na URL acima /api/v2/pokemon ⇒ está buscando a api, na versão dois, buscando a lista de pokemons;
- As requisições tem seus tipos: **********************************************************************GET / POST / PUT  / DELETE;**********************************************************************

- **************GET ⇒************** método de busca para trazer informações de um dado servidor;
    - para realizar essas buscas, é necessário passar alguns atributos daquelas informações que queremos
    - esses atributos podem ser solicitados diretamente no path (******URL******) ou utilizando argumentos do tipo **************************QUERY STRING;**************************
- ******************************QUERY STRING ⇒****************************** descrição de busca;
    - é localizada após um ponto de interrogação no path
    - Ex ⇒ [https://pokeapi.co/api/v2/pokemon](https://pokeapi.co/api/v2/pokemon)?type=grass&name=i ⇒ ?type=grass&name=i (identificado a query string);
    - a query string faz mais sentido ser utilizada para o método ******GET,****** porém é possível utilizá-la nos outros metodos;
- ****************HEADERS ⇒**************** área de dados onde é possível transmitir e receber dados do servidor;
    - são especificações para descrever nossas requisições ou complementá-las;
    - **************************REQUEST HEADERS ⇒************************** Configurações para as requisições, na hora de receber os dados, definir o que você quer/precisa;
    - ******RESPONSE HEADERS ⇒****** Configurações sobre como as respostas das requisições serão apresentadas; normalmente é controlada pelo cliente (próprio Browser).
- **************************************BODY & STATUS CODE ⇒************************************** o **********body********** é o corpo da requisição;