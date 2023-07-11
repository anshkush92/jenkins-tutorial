Trying to understand how the jenkins is applied when the user has commited

GithubSCM --> Works whenever there is a github event --> we can specify on which event we want to run the jenkins job

![Serving the localhost:8080 on the internet using the ngrok](./images/1.png)

Whenever we push any commit to the reposirtory, it runs the jobs - The job we want to run

The output when we push something on the branch
![Output of the Job when we push on the branch --> /feature-github-webhook](./images/2.png)

To avoid this permission denied, we can use the **chmod** command

<hr/>
