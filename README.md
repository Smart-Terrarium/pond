# pound
A repository created specifically for storing Infrastructure as Code (IaC) for projects:
* [toad]([https://linktodocumentation](https://github.com/MateuszMiekicki/toad))
* [frog]([https://linktodocumentation](https://github.com/MateuszMiekicki/frog))

## Usage
The following command runs two tasks. The first task builds and deploys the database from the init step. The second task builds the API image according to the `Dockerfile` in the docker dir.
The API is available at 8080
```bash
docker-compose up -d
```