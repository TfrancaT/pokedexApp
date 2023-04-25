* Requisições HTTP;

    - Toda requisição tem um método.
    - é composta por uma URL, por um método de requisção, por headers[request/response], e pelo corpo da requisição;

URL -> é o IP e Porta do servidor;
        ${Endereço}/${path = caminho de identificação do recurso}
    
    Os servidores DNS fazem a conversão do IP para Domain Name;
    
* Request Method: GET --> "BUSCAR"; POST --> "INSERIR"; PUT --> "ATUALIZAR"; DELETE --> "DELETAR";

    Sempre que se faze uma requisição para o servidor, ela tem um tipo;
    Query$tring = descrição de busca;
                  Como utilizar: após o ponto de [?], identifica-se a query string;
                  A grande maioria das vezes, faz mais sentido utilizar a qs para o method GET[Busca]

    Lembrete: para passar parametros na query string, pode ser diretamente no path, ou utilizando o get[busca]

    Headers: descrevem/complementam as requisições;

        Request Headers
            - Configuração da API;

        Response Headers
            - Configuração da API;

    Response Body: é o corpo da requisição;