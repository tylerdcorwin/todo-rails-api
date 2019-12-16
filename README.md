# README

- Rails Todo API,

  - configured to create/update/delete todo's

- Ruby version

  - 2.6.3

- System dependencies

  - Rails 6.0.1

- Configuration

- Database creation
  rails db:create
  rails db:migrate

- How to run the test suite

  - bundle exec rspec

- Postman testing
  - GET /todos
    - localhost:3000/todos
  - POST /todos
    - localhost:3000/todos
    - params:
      - title = Mozart
      - created_by = 1
  - PUT /todos/:id
    - localhost:3000/todos/1
    - params:
      - title = Beethoven
  - DELETE /todos/:id
    - localhost:3000/todos/1
