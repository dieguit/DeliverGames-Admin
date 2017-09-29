# DeliverGames-admin
Administration tool for Deliver Games. It will provide an environment for the API (with database), server and dashboard app.

## To run / develop:
Check for docker and docker-compose
```{r, engine='bash', count_lines}
$ docker -v
$ docker-compose -v
```

Get the project
```{r, engine='bash', count_lines}
$ git clone git@github.com:dieguit/DeliverGames-admin.git && cd DeliverGames-admin
$ git submodule init && git submodule update
```
I am using submodules and microservices, so we can get them too with git's submodule init & submodule update.

Now we can start everything with docker-compose
```{r, engine='bash', count_lines}
$ docker-compose up -d
```
You should now have:
* Node server running on http://127.0.0.1:3000 

Upcoming next:
* Web server (probably nginx) to serve static files and an Angular4 / react / Vue.js app.
* DB server (probably mysql, mongo is in discussion.. graphql is starting to gain ground)
