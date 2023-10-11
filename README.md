# cloud-server

Deploy a simple Node.js server to EC2, using Elastic Beanstalk

## Deploying Using AWS Elastic Beanstalk

### Task 1: Deploy from the AWS Control Panel (GUI)

1. Create a new environment, using Elastic Beanstalk from the AWS Control Panel (GUI)
2. Manually deploy your application to this environment by uploading a .zip file

### Task 2: Deploy Using AWS Elastic Beanstalk CLI

1. Using the same server, create a new environment using Elastic Beanstalk from your terminal
2. Manually deploy your application to this environment by using eb deploy

## About the Server

This Node.js server responds with a simple "`Hello, AWS Elastic Beanstalk!`" message.

### Server Code

[app.js](app.js) file.

## Installation

- Clone repository:

   ```bash
   git clone https://github.com/yourusername/cloud-server.git
   cd caps

    `npm install`

## Usage

- Create env: `eb create insert-env-name`
- Deploy server: `eb deploy`
- Start/Open server: `eb open`

## Deployed Links

[Link to GUI Deployed Server](http://animae.us-west-2.elasticbeanstalk.com/)

[Link to CLI Deployed Server](http://cloud-server-env.eba-pxmvkxjr.us-west-2.elasticbeanstalk.com/)

## Author

Sydney Mae Pagalan

## License

This project is licensed under the [License Name] License - see the [LICENSE.md](LICENSE.md) file for details.
