# rocketseat-nodejs-01-fundamentals

### init projet
`` npm run dev ``


## REST

### POST user
#### request: http://localhost:3333/users
#### body: `` { "name": "...", "email": "..." } ``
#### response: `` 201 ``

### GET users
#### request: http://localhost:3333/users
#### response: `` [{ "name": "...", "email": "..." }] ``

### GET users search
#### request: http://localhost:3333/users?search=NAME_OR_EMAIL
#### response: `` [{ "name": "...", "email": "..." }] ``

### PUT user
#### request: http://localhost:3333/users/:ID
#### body: `` { "name": "...", "email": "..." } ``
#### response: `` 204 ``

### DELETE user
#### request: http://localhost:3333/users/:ID
#### response: `` 204 ``
