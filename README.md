# sequelize-express-api

Taken from

https://arjunphp.com/build-restful-api-using-node-express-sequelize/

and

https://github.com/sequelize/express-example

```
sequelize model:create --name Todo --attributes title:string,description:string
```

## Create a TODO

```
curl -X POST -H "Content-Type: application/json" -d '{"title":"create a rest client","description":"create it with node js"}' "http://localhost:8080/todos"
```

## List TODO's

```
curl http://localhost:8080/todos/
```
