## Project 1 : BookAPP:

    1. Learn request method of HTTP
    2. Data Validation
        - pydantics(Post、Put)
        - Path and Query parameter(Get、Delete)
            - gt=0 # >0 greater than
            - ge=0 # >=0 greater than or equal
            - le=0 # <=0 less than
            - lt=0 # <0 less than or equal
    3. Exception handling
    4. Status code
        - 1xx : Information Response(Request Processing)
        - 2xx : Success(Request Successfully complete)
            - 200:OK( Get)
            - 201:Created(POST)
            - 204:No Content(PUT)
        - 3xx : Redirection(Further action must be complete)
        - 4xx : Client Error(An error was caused by the client)
            - 400:Bad Request(Invalid Request method)
            - 401:Unauthorized(Client deos not have valid authentication)
            - 404:Not Found(The clients requested resource can not bo found)
            - 422:Unprocessable Entity(Semantic Error in Client Request)
        - 5xx : Server Errors : An error occurred on the server
            - 500:Internal Server error(Generic Error)
    5. Swagger Configuration
    6. Python request objects

## Project 2 : TodoApp:

    1. SQL Database
        - SQLite
        - Postgresql
        - Mysql
    2. JWT(Json Web Token)
        - Authentication
        - Authorization(admin、User)
    3. Hashing Passwords
    4. Pytest(unit test、integration test)
    5. Frontend with jinja template
