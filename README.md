# LMS (Learning Management System)
This project is divided into 3 different Node based web applications written in JavaScript, Bootstrap, CSS and HTML.

Admin and Instructor apps are based on the sails framework deployed as a container on AWS or Azure. Student web app is created and deployed as a serverless web application on AWS lambda.

While adding the students in the course on the Instructor web app, it initiates a 2-phase commit(2PC) and updates the available seats of that course on the Admin web app.

## Node Packages
- [express](https://www.npmjs.com/package/express)
- [mysql](https://www.npmjs.com/package/mysql)
- [csv-parser](https://www.npmjs.com/package/csv-parser)
- [request-promise](https://www.npmjs.com/package/request-promise)
- [serverless-http](https://www.npmjs.com/package/serverless-http)
