##Todo API
**************
Task:
Write a simple API interface with your preferred language/framework for a todo application.
the API must export the main HTTP verbs to add/edit/remove/list todos items 

Every todo item must contain two entries (title, done)


##How to run
1. Install docker & docker-compose
2. Run containers `docker-compose up -d`
3. Enter to app container `docker-compose exec app bash`
4. Run tests `vendor/bin/phpunit`

Internal nginx container binded to localhost:80 on host-machine
