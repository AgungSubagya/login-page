# login-page

- username: admin
- password: admin

### Docker Container
1. Install [Docker](https://www.docker.com)
2. Run `docker pull agngsbgya/login-page-app`
3. Run `docker run -d --name login-page -p 8080:80 agngsbgya/login-page-app`
4. Browse to <http://localhost:8080> (on macOS and Windows browse to
   <http://192.168.0.109:8080> if you are using docker-machine instead of the native docker installation)