
### Dependencies

```
- Node v14.15.1 (LTS) or more recent. While older versions can work it is advisable to keep node to latest LTS version

- npm 6.14.8 (LTS) or more recent, Yarn can work but was not tested for this project

- AWS CLI v2, v1 can work but was not tested for this project

- A RDS database running Postgres.

- A S3 bucket for hosting uploaded pictures.

```



### AWS architecture

```
- RDS - Host: database-1.czwztuxqlyhd.us-east-1.rds.amazonaws.com
- RDS -  Port: 5432
- RDS -  Name: udagram

- S3 Endpoint : http://mohamedemad1.s3-website-us-east-1.amazonaws.com/

- Elastic Beanstalk URL : http://mohamedemad-api-dev.eba-wxgub8xc.us-east-1.elasticbeanstalk.com/

```




### pipeline process

```
- install frontend dependencies.
- build frontend.
- deploy the project to S3.
- install backend dependencies.
- change the main entry point in the package.json from `src/server.js` to `server.js`.
- transpile the Typescript/Backend.
- Install AWS-EB.
- deploy the project to eb.

```





