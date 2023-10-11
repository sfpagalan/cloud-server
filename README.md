# cloud-server
Deploy a simple Node.js server to EC2, using Elastic Beanstalk

# Node.js Server Deployment to AWS Elastic Beanstalk

This repository contains a simple Node.js server deployed to AWS Elastic Beanstalk. The server responds with a "Hello, AWS Elastic Beanstalk!" message.

## Deploying Using AWS Elastic Beanstalk

### Task 1: Deploy from the AWS Control Panel (GUI)

1. Log in to the AWS Management Console.
2. Navigate to Elastic Beanstalk.
3. Click "Create Application."
4. Choose a name and platform (Node.js).
5. Create an environment and select "Web server environment."
6. In the Application code section, upload your application code (ZIP file).
7. Review and create the environment.
8. Once the environment is created, your server will be deployed. You can access it at [Link to GUI Deployed Server](http://animae.us-west-2.elasticbeanstalk.com/).

### Task 2: Deploy Using AWS Elastic Beanstalk CLI

1. Open your terminal.
2. Navigate to your project directory.
3. Initialize Elastic Beanstalk using the following command:
`eb init -p nodejs-14.17 cloud-server`
4. Create an Elastic Beanstalk environment using the following command:
`eb create Cloud-server-env`
5. Deploy your application to the environment using:
`eb deploy`
6. Once the deployment is complete, you can access your server at [Link to CLI Deployed Server](<CLI Deployed Server URL>).

## Troubleshooting and Notes

If you encounter any issues during deployment, refer to the [AWS Elastic Beanstalk documentation](https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/eb3-deployment.html) for troubleshooting guidance.

Remember to keep your AWS access credentials secure and follow best practices for AWS security.

## About the Server

This Node.js server responds with a simple "`Hello, AWS Elastic Beanstalk!`" message.

### Server Code

You can find the server code in the [app.js](app.js) file.

### Package Information

The server's package.json file includes the project dependencies.

## Author

Sydney Mae Pagalan

## License

This project is licensed under the [License Name] License - see the [LICENSE.md](LICENSE.md) file for details.
