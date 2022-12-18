# Necessary steps

In terminal, type this command to edit the hosts' file configuration:

```
sudo vim /etc/hosts
```

Add these lines:

```
127.0.0.1       blue.labs.com.br
127.0.0.1       green.labs.com.br
127.0.0.1       labs.com.br
```

These changes will set your domains to be available in your machine.

Obs: The name can be anything, since you change the nginx.conf file to get these domains.

After that, just run the docker compose to launch the necessary containers:

```
docker compose up -d
```

## References

https://www.youtube.com/watch?v=bFZurhL14LA
https://docs.nginx.com/nginx/admin-guide/web-server/reverse-proxy/
https://blog.logrocket.com/how-to-run-a-node-js-server-with-nginx/
