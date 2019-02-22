crud-node

Run server.js file

1. User registration
POST http://localhost:8000/users/register
with body name, email, and password.

2. Get token
POST http://localhost:8000/users/authenticate
with body email and password which have been registered successfully

3. Insert movie
POST http://localhost:8000/movies
with body name and released_on (date) and header x-access-token (token from point 2)

4. List movies
GET http://localhost:8000/movies

5. Modify (PUT or DELETE) movies on http://localhost:8000/movies/{_id}
with header x-access-token (token from point 2)




Erma Ramadhani