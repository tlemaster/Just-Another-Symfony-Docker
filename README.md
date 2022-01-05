
# Just Another Symfony Docker

A Docker Compose Symfony 5 environment made for local development which includes 3 containers: Mysql8.0, php8.0-fpm, and nginx.
## Installation

Git pull or download files.  
Modify the .env file located in the docker folder with your desired db credentials.  
Install Symfony in the app directory.  
Navigate to the docker directory using a cli then run

```bash
  docker-compose up --build
```

Url endpoint that becomes available - http://localhost:8080 

## Support

Feel free to use this tool at your own risk as currently there are no plans for it to be actively supported by its author.
## Credits
Created by Todd LeMaster. Thanks for stopping by!