# TodoAPI
First API using .NET Core
Project based on Microsoft website to learn about language and architecture

#### Using postman
- Before you should unable you ssl security in Visual Studio.

#### Get 
http://localhost:<PORT>/api/todo

Body
Empty


#### Get with ID
http://localhost:<PORT>/api/todo/1

Body
Empty


#### POST
http://localhost:<PORT>/api/todo

Body

{
    "name":"walk dog",
    "isComplete":true
}


#### PUT
http://localhost:<PORT>/api/todo/1

Body
    
{
    "ID":1,
    "name":"feed fish",
    "isComplete":true
}

#### DELETE
http://localhost:<PORT>/api/todo/1

Body
Empty

#### Referência:
https://docs.microsoft.com/pt-br/aspnet/core/tutorials/first-web-api?view=aspnetcore-2.2&tabs=visual-studio
