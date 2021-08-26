# Rails GraphQL
This repository shows how to use GraphQL in Rails. master branch contains the REST apis for the project, and graphql branch contains REST apis along with the GraphQL ones.
## Installation
#### Clone the repo:
```sh
   $ git clone https://github.com/anshulg8/rg_demo.git
```
- Change into the `rg_demo` directory:
```sh
   $ cd rg_demo
```
#### Setup the database:
```sh
   $ rails db:create
   $ rails db:migrate
   $ rails db:seed
```
#### Install all dependencies:
```sh
   $ bundle install
```
##### Start the development server:
```sh
   $ rails server
```
- You're set to consume any endpoint at `http://localhost:3000/graphql`.
