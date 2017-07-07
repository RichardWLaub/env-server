# env-server

A simple go server that prints environment variables.

## Usage

To test, set any environment variables you'd like:

```
vim variables.env
```

Then deploy with:

```
docker-compose up -d
```

Once the server is running check the variables by going to `localhost` in your browser or with:

```
curl localhost
```

Fork this repo and experiment!
