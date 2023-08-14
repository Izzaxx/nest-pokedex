<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

# Execute in develoment

1. Clone repository

2. Execute
```
npm install
```

3. Have NestJS installed
```
npm i -g @nestjs/cli
```

4. Run database in docker
```
docker-compose up -d
```

5. Clone file __.env.template__ and rename copy to __.env__

6. Fill enviroment variables in __.env__

7. Run project in develoment
```
npm run start:dev
```

8. Regenerate datas in database with the seed
```
http://localhost:3000/api/v2/seed
```

## Stack used
* MongoDB
* Nest
