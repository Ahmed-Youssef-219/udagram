## pipeline diagram
![Image](../udagram/images/pipeline.jpeg)
<br/>

### Explanation of the pipeline
- When the developer changes the project code and commits and adds the code to github.
- circleci executes the project code as specified in the config.yml
- as shown in [config.yml](../.circleci/config.yml) of circleci the steps of the process is as following :-

1. circleci will execute build jobs which is consisted of some command which is 
`npm run frontend:install`
`npm run api:install`
`npm run frontend:lint`
`npm run frontend:build`
`npm run api:build`
2. This job requires approval before the workflow can       continue running.
2. then circleci will execute deploy jobs which is consisted of some command which is 
`npm run api:deploy`
`npm run frontend:deploy`

<br/>

## Environment variables

- the environment variables is stored in circleci as shown
    - ![Image](../udagram/circleci/Environment%20variables%20in%20circleci.png)
- when circleci execute the deploy commands for api it pass the environment variables to elasticbeanstalk 



## Pipeline Process

![Image](../udagram/circleci/pipeline%20process%20in%20circle%20ci.png)
![Image](../udagram/circleci/build%20process.png)
![Image](../udagram/circleci/deploy%20process.png)
![Image](../udagram/circleci/sucess%20process.png)