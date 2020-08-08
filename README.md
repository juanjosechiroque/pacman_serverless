# Send pacmandata to AWS Lambda

## this simple html browser UI is served from server.js by / default route. 

Clicking on pacman image sends x location data to web server and web server sends on to AWS API Gateway. 

Gateway then sends to Lambda function and that sends data to DynamoDB database. 

The Web Server setup is covered in https://www.youtube.com/watch?v=gpjdu8pgORg&t=5s . 

The AWS API Gateway, Lambda Functions, DynamoDB is covered in https://youtu.be/fkM2GRYvtLI . 

(Note that the BadBank stores more complex data than PacMan but the API and Lambdas are exactly the same)