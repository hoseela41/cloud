# cloud
This project was created for users to upload files on [google cloud storage](https://www.elastic.co/partners/google-cloud). ElasticSearch (deployed to GCE) was used for users to search recent and list personal posts. User authentication was done via token-based flow with React Router v4 and JSON Web Token.

## How to run the project
1. Create a Virtual Machine on Google Compute Engine ([GCE](https://cloud.google.com/compute)).
3. Change the user name, external and internal ip in files.
4. Create a bucket on [Google Storage Cloud](https://cloud.google.com/storage)
5. Change the bucket name in files.
6. Under around folder run ```go run *.go```, the service should start immediately.
7. Utilze [Postman](https://www.postman.com/) to launch services of POST, GET with REST APIs.

