Para execução via NodeJS

1- Instalar o Newman: "npm install -g newman";
2- Execução: "newman run Trello.postman_collection.json --verbose -r cli,json"

OBS.: No CLI será gerado um relatório macro e um relatório de evidência será gerado em formato JSON detalhando a execução na pasta do projeto.