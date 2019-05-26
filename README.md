# MakersBnB

## Context
Four days group project for the sixth week Makers Academy Course.
Team size: Four software developers.

## Development Environment
Language : Javascript (Backend and frontend)
Frame: node.js, Express.js
Database: PostgreSQL (ORM:Sequelize)

## Test Environment
Jasmine + Nightwatch.js

## How to Run
Git clone the application and navigate (cd) into myapp repository

Installation required:
* node.js
* PostgreSQL
* Sequelize

Run following command to setup database:
```
$ createdb makers_bnb
```

```
$ sequelize db:migrate
```

Run the server (Node):

```
$ npm start
```

Open the app in a browser by insert url:
```
http://localhost:3000/
```

### User Stories
```
User story 1
As a General User
So I can maintain settings / properties
I want to be able to log in to makers bnb

User story 2
As a Listing User
So I can offer my property for rent
I want to be able to list my property on makers bnb

User story 3
As a Listing user
So I can offer all my properties for rent
I want to be able to list multiple properties on makers bnb

User story 4
As a Listing User
So I can have a unique listing
I want to be able to add a name, description and price to each space

```

### Extra
Security vulnerability from installation of nightwatch

Remediation
Upgrade growl to version 1.10.0 or later. For example:

"dependencies": {
  "growl": ">=1.10.0"
}
or…
"devDependencies": {
  "growl": ">=1.10.0"
}
