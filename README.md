# 🎯 Go CRUD API

<img src="https://github.com/Muhammederendemir/go-crud-api/blob/main/image/go-crud-api.jpg">

## 📌 Case

I have a Movie Struct and I will create, read, update, delete operation in Movie list.

## 📌 Run

```yaml
go build
```

```yaml
go run main.go
```

## 📌 Get Movies Service

* http://localhost:8080/movies  GET
f
## 📌 Get Movie Service

* http://localhost:8080/movies/{id} GET

## 📌 Create Movie Service

* http://localhost:8080/movies/  POST

## 📌 Update Movie Service

* http://localhost:8080/movies/{id} UPDATE

## 📌 Delete Movie Service

* http://localhost:8080/movies/{id} DELETE

## 📌 Request Body

{
    "isbn": "164",
    "title": "Inception",
    "director": {
        "firstname": "Christopher",
        "lastname": "Nolan"
    }
}

## 📌 Packages

- encoding/json
- math/rand  
- net/http
- strconv
- github.com/gorilla/mux

## 📌 Reources
* https://www.youtube.com/watch?v=jFfo23yIWac&ab_channel=freeCodeCamp.org

