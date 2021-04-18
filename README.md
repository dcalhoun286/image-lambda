# Lab: AWS - S3 and Lambda

For this lab assignment, I utilized AWS Lambda to process images when they're uploaded to an S3 Bucket.

## Author: Dar-Ci Calhoun

## Feature Tasks

- A user should be able to upload an image at any size, and have both the original size and a thumbnail size
- When an image is uploaded to your S3 bucket, it should trigger a Lambda function which must:
  - Create a 50x50 pixel thumbnail version of that image
  - Save it to another S3 bucket
  - It should do so with a predictable naming convention, so that your server and/or frontend know where that thumbnail image will be

## Links

- Pull Request: [https://github.com/dcalhoun286/image-lambda/pull/1](https://github.com/dcalhoun286/image-lambda/pull/1)

## Resources and Collaborators

- [YouTube: Using a Lambda trigger to resize an uploaded image](https://www.youtube.com/watch?v=M4iEeXlw_qU)
- [Medium: Resize Images On-the-Fly With S3, Lambda, and API Gateway](https://medium.com/frontend-at-scale/resize-images-on-the-fly-with-s3-lambda-and-api-gateway-36032f44857b)
- [GitHub: nodejs-aws-lambda-image-resizer](https://github.com/MuhammadReda/nodejs-aws-lambda-image-resizer/)
- [GitHub: sample JavaScript code for resizing pictures on AWS Lambda](https://gist.github.com/dkarchmer/d68e20f6de36827d6c2f0f640bf151e1)
- [Stack Overflow: resizing the image in S3 bucket from lambda trigger using NodeJS](https://stackoverflow.com/questions/44434372/resizing-the-image-in-s3-bucket-from-lambda-trigger-using-nodejs)
- [npmjs.com: lambda-resize-image](https://www.npmjs.com/package/lambda-resize-image#usage-image-restrictions-resize)
