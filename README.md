# Freshbey

## http://freshbey.com

An online ecommerce grocery platform

## Usage

### ES Modules in Node

We use ECMAScript Modules in the backend in this project. Be sure to have at least Node v14.6+ or you will need to add the "--experimental-modules" flag.

Also, when importing a file (not a package), be sure to add .js at the end or you will get a "module not found" error

<!-- You can also install and setup Babel if you would like -->

### Env Variables

Create a .env file in then root and add the following

```
NODE_ENV = production
PORT = 5000
MONGODB_URI = mongodb+srv://admin:test@groceryecommercestore.p2u97.mongodb.net/groceryshop?retryWrites=true&w=majority
JWT_SECRET = roopeshthemass123@
EMAIL_USERNAME = 2ebcd460696ef8
EMAIL_PASSWORD = cb7e54cd13fa8b
EMAIL_HOST = smtp.mailtrap.io
EMAIL_PORT = 2525
```

### Install Dependencies (frontend & backend)

```
npm install
cd frontend
npm install
```

### Run

```
# Run frontend (:3000) & backend (:5000)
npm run dev

# Run backend only
npm run server
```

## Build & Deploy

Project is deployed on Heroku

### Seed Database

You can use the following commands to seed the database with some sample users and products as well as destroy all data

```
# Import data
npm run data:import

# Destroy data
npm run data:destroy
```
