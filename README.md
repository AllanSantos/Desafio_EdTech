# Desafio_EdTech:rocket:

## Tecnologias utilizadas:

- **Express**  
- **TypeScript**
- **Cors**
- **Axios**
- **Banco Postgress**
- **Docker**
- **uuidv4**
- **JWT**
- **bcryptjs**
- **TypeORM**
- **Material-UI**
- **react-bootstrap**

## Comandos Projeto
- Rodar comando yarn(tanto no front quanto no back)
  > Para baixar as dependecias.
- Rodando servidor yarn dev
  > Para iniciar o servidor NodeJS.
  
- Rodando servidor yarn start
  > Para iniciar o servidor React.js.
## Ajustes
- Ajustar o arquivo ormconfig.json com as configurações do Docker
- Ajustar Secret e ExpireIn em src\config\auth.js

  ~~~JSON
  "type": "postgres",
  "host": "localhost",
  "port": 5432,
  "username": "user",
  "password": "password",
  "database": "database_name",
  jwt: {
    secret: 'SECRET',
    expiresIn: 'EXPIRES_IN'
  }
  ~~~
