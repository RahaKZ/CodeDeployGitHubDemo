This is sample experimentation of using CodeDeploy.
I am just following [this page by bogotobogo](https://www.bogotobogo.com/DevOps/AWS/aws-CodeDeploy-Deploy-an-Application-from-GitHub.php)

But this is the actual tutorial, which I should have followed: [official one](https://docs.aws.amazon.com/codedeploy/latest/userguide/tutorials-github-create-github-repository.html). Official one contains also cleanup step.

The resources created for this tutorial:
1. My own AWS account
1. DeployDemoAppFromGithub - AWS CodePipeline - helps to automate the release of my application. It automates the build and the deployment for this tutorial.
1. CodeDeployGitHubDemo-App - AWS CodeDeploy - automates my application deployments to Amazon EC2.
1. ProjectForCodeDeployGitHubDemo - AWS CodeBuild - compiles my appliaction and produces packages that are ready to deploy.
1. specific user, roles and policies for above resources.
