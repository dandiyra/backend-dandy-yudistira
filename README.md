
**Server:** Node, Express

**DataBase:** postgres, typeorm


## Run Locally


Install dependencies

```bash
  npm install
```

Start the tsc

```bash
  npm run watch
```

Start the server

```bash
  npm run dev
```


## Environment Variables

To run this project, you will need to add the following environment variables to your .env file

`PORT`

`TOKEN_SECRET`

`REFRESH_TOKEN_SECRET`





## API Reference

#### Create user

```http
  POST /user/create
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `firstName`      | `string` | **Required**. Your API key |
| `lastName`      | `string` | **Required**. Your API key |
| `email`      | `string` | **Required**. Your API key |
| `password`      | `string` | **Required**. Your API key |
| `phoneNumber`      | `number` | **Required**. Your API key |

#### login user

```http
  POST /user/login
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `phoneNumber`      | `number` | **Required**. Your API key |
| `password`      | `string` | **Required**. Your API key |


#### Get all users

```http
  GET /user/list
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `id` | `uuid` | **Required**. Your API key |
| `firstName` | `string` | **Required**. Your API key |
| `lastName` | `string` | **Required**. Your API key |
| `email` | `string` | **Required**. Your API key |
| `password` | `string` | **Required**. Your API key |
| `profileImage` | `string` | **Required**. Your API key |
| `isActive` | `boolean` | **Required**. Your API key |
| `phoneNumber` | `number` | **Required**. Your API key |
| `tocken` | `string` | **Required**. Your API key |
| `refreshToken` | `string` | **Required**. Your API key |

A postman collection has been added for better understanding.

