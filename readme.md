# Crud para ser utilizado em conjunto com a AWS Gateway, Lambda e DynamoDB

Utilizar este guia para utilizar esta página: https://docs.aws.amazon.com/pt_br/apigateway/latest/developerguide/http-api-dynamo-db.html

Após isso altere as linhas no final do arquivo index.html
    {
        awsUrl: 'https://SUA_API_GATEWAY.execute-api.us-east-1.amazonaws.com/items', <- Altere para a url do seu api gateway
        loading: false,
        ...

O arquivo index.html pode ser executado localmente ou hospedado em um S3 standard por exemplo.

Dúvidas fiquem a vontade em abrir uma issue.
https://github.com/tiagoiwamoto/aws-crud/issues/new

Obrigado