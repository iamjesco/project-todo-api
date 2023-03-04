
# Basic ToDo API

A basic CRUD Api created with Java

### Api Developer: 
* Raylie Augustino Martina

# API endpoints

## Get all todos
**Response**  

![](https://img.shields.io/static/v1?label=GET&message=/api/todos/&color=005599)
```text
HTTP/1.1 200 OK
```
```json
{
    "pk": Integer,   //  Todo id
    "title": String,    //  Todo title
    "body": String,   //  Todo body text   
    "created": DateTime,    //  Todo created date
    "updated": DateTime,    //  Todo updated date
    "is_done": Boolean,    //  Todo is done status
}
```

## Create todo
**Request**

![](https://img.shields.io/static/v1?label=POST&message=/api/todos/&color=005599)
**Response**
```text
HTTP/1.1 201 OK
```
```json
{
    "title": String,
    "body": String,
    "is_done": Boolean    //  Default = False
}
```
## Get single todo
**Request**

![](https://img.shields.io/static/v1?label=GET&message=/api/todos/{int:pk}&color=005599)  

**Response**
```text
HTTP/1.1 200 OK
```
```json
{
    "pk": Integer,
    "title": String,
    "body": String,
    "created": DateTime,
    "updated": DateTime,
    "is_done": Boolean,
}
```
## Update todo
**Request**

![](https://img.shields.io/static/v1?label=PUT&message=/api/todos/{int:pk}&color=005599)

**Response**
```text
HTTP/1.1 200 OK
```
```json
{
    "title": String,
    "body": String,
    "is_done": Boolean,
}
```
## Delete todo
**Request**

![](https://img.shields.io/static/v1?label=DELETE&message=/api/todos/{int:pk}&color=005599)

```text
HTTP/1.1 204 OK
```

**Response**
```text
[]
```




















