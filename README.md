# UserManagerMVC
ASP.NET Core MVC

```mermaid
graph LR;
    DataBase-->Model-->Controller-->View;
```
```mermaid
classDiagram
    class User {
        -String Name
        -Int Age
        -String Email
        -Enum Gender
        +CreateUser(User user) : HTTP Status
        +ReadUser(int Id) : HTTP Status
        +UpdateUser(int Id) : HTTP Status
        +DeleteUser(int Id) : HTTP Status
        +ReadAllUsers() : HTTP Status
        +SearchByNameUsers() : HTTP Status
    }
```

| RM | Nome |
|--|--|
| 94170 | Felipe Breno Sugisawa Altran|
| 93187 | Gabriel João da Silva|
| 94266 | Vinicius Alves Torres|
| 92895 | Vinicius Yuji Nishioka|
