## Overview
The **template-wordpress-default** template adds to a stack the ability to provision the Wordpress development environment with a Docker container.

## Prerequisites
To use this template you need to use the `CLI` of `StackSpot` that you can download [**here**](https://stackspot.com/).

- Docker: ~20.10.8
- Docker Compose: ~3.8

## **How to Use**
### Input parameters
The inputs parameters needed to use the template are: 

| **Field**                     | **Value**         | **Description**   |
| :---                          | :---              | :---              |
| Project Name                  | ex.: project-name | Application name  |
| Wordpress Server Port         | ex.: 81           | Web Server port   |
| Wordpress Database Name       | ex.: wp_stackspot | Database Name     |
| Wordpress Database Port       | ex.: 3306         | Database Port     |
| Wordpress Database UserName   | ex.: wp_stackspot | Database User     |
| Wordpress Database Password   | ex.: wp_stackspot | Database Password |
| Wordpress Docker Image        | ex.: 6.0.1        | Docker image name |

 ## Creating the project from the template

 ```bash
stk create app project-name -S stack-wordpress/default
 ```

## Execution of the created project

After creating your project, to build and run the docker containers solution, run the command below in the root of where you find the **docker-compose.yml** file

```bash
docker-compose -f 'docker-compose.yml' up --build
```

Then open http://localhost:81 in your browser.