# Node.js Express & MongoDB: CRUD Rest APIs

CRUD API

## Project setup
```
npm install
```

### Run
```
node server.js / nodemon server.js
```

### Testing API Via Postman
```
localhost:8080/

Methods	Urls	Actions
GET =>	    api/tutorials	            get all Tutorials
GET	=>    api/tutorials/:id	        get Tutorial by id
POST =>	    api/tutorials	            add new Tutorial
PUT =>	    api/tutorials/:id	        update Tutorial by id
DELETE =>	    api/tutorials/:id	        remove Tutorial by id
DELETE =>	    api/tutorials	            remove all Tutorials
GET =>	    api/tutorials/published	    find all published Tutorials
GET =>	    api/tutorials?title=[kw]	find all Tutorials which title contains 'kw'

POST =>	/api/auth/signup	signup new account
POST =>	/api/auth/signin	login an account
GET =>	/api/test/all	retrieve public content
GET =>	/api/test/user	access User’s content
GET =>	/api/test/mod	access Moderator’s content
GET =>	/api/test/admin	access Admin’s content
```