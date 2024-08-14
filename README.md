
# DockerComposeActivity

We deployed two applications behind a reverse proxy, routing traffic based on URL paths. The proxy listened on port 80, directing requests to the first app on port 8000 and the second on port 8001, enabling seamless access to both apps from the same domain.


## Instructions
1. Clone this repository
2. Initialize the project with the next command

```bash
  docker-compose up --build
```

## Visit the site
 - Landing Page: [http://localhost:80](http://localhost:80)


## Authors

- [@CristhianAC](https://github.com/CristhianAC)
- [@MateoGE01](https://github.com/MateoGE01)

