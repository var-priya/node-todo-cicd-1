Complete Jenkins CI/CD Project:

1. Login into jenkins dashboard and create a job with the name "jenkins-projects"

2. Enter code URl in source code management section

3 Enabled GitHub hook trigger for GITScm polling.

4. Go to github --settings--webhooks

5. Saved the webhook.

Running the Application:

Add the jenkins user to the docker group:

In the Execute shell run the application using Docker compose.

Do some changes in the project and commit changes.

The pipeline is automatically triggered.

Your project is ready.
