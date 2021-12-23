## We have discontinued the publicly hosted version of RequestBin due to ongoing abuse that made it very difficult to keep the site up reliably. Please see instructions below for setting up your own self-hosted instance.

Originally Created by [Jeff Lindsay](http://progrium.com)

License
-------
MIT

Looking to self-host?
=====================

## Deploy your own instance using Docker

On the server/machine you want to host this, you'll first need a machine with
docker and docker-compose installed, then grab the RequestBin source using git:

`$ git clone https://github.com/l4rm4nd/Requestbin`

- You may modify the ``docker-compose.yml`` to specify your docker networks
- You may modify the ``requestbin/config.py`` to specify a new SESSION_SECRET_KEY

Go into the project directory and build + start the containers!

```
$ sudo docker-compose build
$ sudo docker-compose up -d
```

Your own private RequestBin will be running on port 0.0.0.0:8000.
