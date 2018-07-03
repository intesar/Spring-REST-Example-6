<figure>
  <a href="https://fxlabs.io">
    <img src="https://fxlabs.io/wp-content/uploads/2018/02/FX-Logo-100x100.png" alt="FX Labs" />
  </a>
</figure>



# Automated API Testing & Security for the Spring REST Hotels App Example

### Supported REST APIs

| Method | Endpoint | Parameters | Response Messages |  
| :---         | :---           | :---          | :---         | 
| GET   | /example/v1/hotels    | page, size      |  401 (Unauthorized), 403 (Forbidden), 404 (Not Found)     | 
| POST     | /example/v1/hotels      |   hotel      | 201 (Created), 401 (Unauthorized), 403 (Forbidden), 404 (Not Found)      | 
| DELETE   | /example/v1/hotels/{id}    | id    | 204 (No Content), 401 (Unauthorized), 403 (Forbidden)    | 
| GET    | /example/v1/hotels/{id}      | id     | 401 (Unauthorized), 403 (Forbidden), 404 (Not Found)      | 
| PUT   | /example/v1/hotels/{id}     | id, hotel    | 201 (Created), 204 (No Content), 401 (Unauthorized), 403 (Forbidden), 404 (Not Found)    |  
