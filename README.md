# [Backend] Be The Hero
## Omnistack Week 11
##### Start
```
$git clone [repository]
$cd be-the-hero
$npm install
$npm start
```

#### How to use Knex
##### Creating migrations
```npx knex migrate:latest```
##### Rollback migrations
```npx knex migrate:rollback```

#### Dependencies
    "cors": "^2.8.5",
    "express": "^4.17.1",
    "knex": "^0.20.13",
    "sqlite3": "^4.1.1"
    
#### Structure
```
app
├── src
│  ├──
│  │  controllers
│  │     ├── IncidentController.js
│  │     ├── OngController.js
│  │     ├── ProfileController.js
│  │     └── SessionController.js
│  │  database
│  │     ├─── migrations
│  │     │    └─
│  │     ├─── connection.js
│  │     └─── db.sqlite
│  ├── index.js
│  └── routes.js
└── knexfile.js
```
