![Image](../udagram/images/aws%20infrastructure%20diagram.jpeg)

### Explanation of the process
When the user makes a request from the frontend, which is stored on S3 bucket.
The frontend sends the request to the API which is stored on EB and then the API sends the request to the database which is stored on RDS and then sends it back to the user again

## Link to frontend [go to frontend](http://udagram-frontend-219.s3-website-us-east-1.amazonaws.com/home)
`http://udagram-frontend-219.s3-website-us-east-1.amazonaws.com/home`

## More Details


## RDS
![Image](https://github.com/Ahmed-Youssef-219/udagram/blob/main/udagram/images/RDS/1-%20dashboard.png?raw=true)
![Image](https://github.com/Ahmed-Youssef-219/udagram/blob/main/udagram/images/RDS/2-%20create_database_EngineOptions.png?raw=true)
![Image](https://github.com/Ahmed-Youssef-219/udagram/blob/main/udagram/images/RDS/3-%20create_database_Templates.png?raw=true)
![Image](https://github.com/Ahmed-Youssef-219/udagram/blob/main/udagram/images/RDS/4-%20create_database_Settings.png?raw=true)
![Image](https://github.com/Ahmed-Youssef-219/udagram/blob/main/udagram/images/RDS/5-%20create_database_InstanceConfiguration.png?raw=true)
![Image](https://github.com/Ahmed-Youssef-219/udagram/blob/main/udagram/images/RDS/5-%20create_database_publicAccsess.png)
![Image](https://github.com/Ahmed-Youssef-219/udagram/blob/main/udagram/images/RDS/7-%20created%20db.png?raw=true)
![Image](https://github.com/Ahmed-Youssef-219/udagram/blob/main/udagram/images/RDS/8_db_endpoint&port.png?raw=true)


## EB
![Image](https://github.com/Ahmed-Youssef-219/udagram/blob/main/udagram/images/EB/1-create%20EB.png?raw=true)
![Image](https://github.com/Ahmed-Youssef-219/udagram/blob/main/udagram/images/EB/2_EB_envTier.png?raw=true)
![Image](https://github.com/Ahmed-Youssef-219/udagram/blob/main/udagram/images/EB/3_EB_App%20Info.png?raw=true)
![Image](https://github.com/Ahmed-Youssef-219/udagram/blob/main/udagram/images/EB/4_EB_Platform.png?raw=true)
![Image]https://github.com/Ahmed-Youssef-219/udagram/blob/main/udagram/images/EB/5_EB_sourceCodeOrigin.png?raw=true)


## S3
![Image](https://github.com/Ahmed-Youssef-219/udagram/blob/main/udagram/images/S3/1_S3_createBucket.png?raw=true)
![Image](https://github.com/Ahmed-Youssef-219/udagram/blob/main/udagram/images/S3/2_S3_generalConfiguration.png?raw=true)
![Image](https://github.com/Ahmed-Youssef-219/udagram/blob/main/udagram/images/S3/3_S3_public%20access.png?raw=true)
![Image](https://github.com/Ahmed-Youssef-219/udagram/blob/main/udagram/images/S3/4_S3_generalOption.png?raw=true)
![Image](https://github.com/Ahmed-Youssef-219/udagram/blob/main/udagram/images/S3/5_S3_staticWebsiteHosting.png?raw=true)
![Image](https://github.com/Ahmed-Youssef-219/udagram/blob/main/udagram/images/S3/6_S3_bucketPolicy.png?raw=true)
![Image](https://github.com/Ahmed-Youssef-219/udagram/blob/main/udagram/images/S3/7_S3_uploadedFiles2.png?raw=true)



## Iam key
![Image](https://github.com/Ahmed-Youssef-219/udagram/blob/main/udagram/images/Iam/create%20iam%20user.png?raw=true)
![Image](https://github.com/Ahmed-Youssef-219/udagram/blob/main/udagram/images/Iam/user%20details.png?raw=true)
![Image](https://github.com/Ahmed-Youssef-219/udagram/blob/main/udagram/images/Iam/set%20permissions.png?raw=true)