HANDS ON
• OBJETIVOS:

• Criação de um docker-compose.yml para funcionar com wordpress

• Precisamos ter um container para cada serviço um para o wordpresse outro para o
MySQL

----------------PASSO A PASSO DA ATIVIDADE-----------------------
• Crie um novo diretório local para organizar os arquivos do projeto Docker

• Crie um arquivo docker-compose.yml e crie dois services
    para db
    para wordpress
• Utilize as imagens oficiais do Wordpres e do MySQL
    latform: linux/amd64
    wordpress image: wordpress:latest
    mysql image: mysql:5.7
• Configure o docker-compose para iniciar todos os containers juntos
    docker-compose up  -d
• Verifique logs do compose e pare em seguida
    docker-compose logs && docker-compose down
