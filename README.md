# DeliverGames-Admin
Administration tool for Deliver Games

# To run:
Check for docker and docker-compose
```{r, engine='bash', count_lines}
$ docker -v
$ docker-compose -v
```

Get the project
```{r, engine='bash', count_lines}
$ git clone git@github.com:dieguit/DeliverGames-Admin.git && cd DeliverGames-Admin
$ git submodule init && git submodule update
```
I am using submodules and microservices, so we can get them too with git's submodule init & submodule update.

Now we can start everything with docker-compose
```{r, engine='bash', count_lines}
$ docker-compose up -d
```
You should now have a node server running on http://127.0.0.1:3000 
