# WordPress Docker

This project is a docker-compose file written to get wordPress and MySQL spinning in seconds in your production server or local machine.

### Advantages:

- Have WordPress ready in a single command
- Installations are Isolated to the Docker Containers
- No Compatibility issues
- Prodution Ready.

### Requirements:

- Docker
- Docker Compose

### Platforms:

- Linux
- Windows
- Mac OS

### Accessing:

The wordPress container's port has been mapped to port 8080 of the localhost. This means that once all the containers are spinning, you have to go to your browser and navigate to the url `http://localhost:8080`

### Run:

Navigate using **Terminal** or **Command Prompt** to the project root directory in order to be able to execute the commands below.

Run container in Detached mode

```sh
docker-compose up -d
```

Run container in interactive mode

```sh
docker-compose up
```

### Shutdown:

```sh
docker-compose down
```
