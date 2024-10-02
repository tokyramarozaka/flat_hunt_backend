# Flat hunt backend using Json-server

This is a low-code Rest API about apartments, using the json-server library. 

## How to run ? 

Install all dependencies first. And then run either of the following commands : 

```bash
npm run start
```

```bash
npx json-server -p 4000 api.json
```

This will cause the backend server to be active. And... you know what is left to do. 

## What endponts are available 

### 1. **GET /apartments**
Retrieve a list of all available apartments.

### 2. **GET /apartments/:id**
Retrieve a given apatement using its id

### 3. **GET /apartements?price_lte=...**
GET /apartments?price_lte=1500 will get all apartments whose price is less than or equal to 1500.

### 4. **GET /apartements?price_gte=...**
GET /apartments?price_gte=1500 will get all apartments whose price is greater than or equal to 1500

### 5. **GET /apartements?field_like=...**
GET /apartments?description_like=cozy will retrieve all items whose descrption contains the given request parameter.
