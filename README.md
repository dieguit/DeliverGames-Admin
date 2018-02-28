# DeliverGames-admin
Administration tool for Deliver Games. It will provide an environment for the API server and dashboard app.

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

For further information check the README files for each submodule.

- Diego
