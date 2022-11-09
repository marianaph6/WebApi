# dotnet-6-crud-api-users

.NET 6.0 - CRUD API 

## Get All  --> GET
    http://localhost:4000/users 

## Get One --> GET
    http://localhost:4000/users/1
 
## Create --> POST
    http://localhost:4000/users 

    {
        "title": "Mr",
        "firstName": "George",
        "lastName": "Costanza",
        "role": "User",
        "email": "george@costanza.com",
        "password": "george-likes-spicy-chicken",
        "confirmPassword": "george-likes-spicy-chicken"
    }

## Update --> PUT
    http://localhost:4000/users/1

    {
        "firstName": "Art",
        "lastName": "Vandelay"
    }

## Delete --> Deete
    http://localhost:4000/users/1