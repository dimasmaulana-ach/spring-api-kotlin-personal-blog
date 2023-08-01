# API SPEC

## Roles

- Method: GET, POST, PUT, DELETE
- Content Type: Application/json
- Endpoint: ```/api/v1/role```
- Body:

```json
{
  "name": "string"
}
```

- Response :

```json
{
  "code" : 200,
  "message" : "OK",
  "data": {
    "id": "uuid",
    "name" : "string"
  }
}
```

## Users

- Method: GET, POST, PUT, DELETE
- Content Type: Application/json
- Endpoint: ```/api/v1/users```
- Body: 

```json
{
    "name" : "string",
    "username" : "string",
    "email" : "string",
    "password" : "string",
    "personal_token" : "string"
}
```

- Response :

```json
{
  "code" : 200,
  "message" : "OK",
  "data": {
    "id": "uuid",
    "name" : "string",
    "username" : "string",
    "email" : "string",
    "password" : "string",
    "personal_token" : "string"
  }
}
```


## Category

- Method: GET, POST, PUT, DELETE
- Content Type: Application/json
- Endpoint: ```/api/v1/category```
- Body:

```json
{
  "name": "string"
}
```

- Response :

```json
{
  "code" : 200,
  "message" : "OK",
  "data": {
    "id": "uuid",
    "name" : "string"
  }
}
```


## Blogs

- Method: GET, POST, PUT, DELETE
- Content Type: Application/json
- Endpoint: ```/api/v1/blogs```
- Body:

```json
{
  "title" : "string",
  "slug" : "string",
  "body" : "text",
  "category" : "uuid",
  "users" : "uuid"
}
```

- Response :

```json
{
  "code" : 200,
  "message" : "OK",
  "data": {
    "id": "uuid",
    "title" : "string",
    "slug" : "string",
    "body" : "text",
    "category" : "uuid",
    "users" : "uuid"
  }
}
```