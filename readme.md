# DevOps CI/CD using Java Spring PetClinic Sample Application
[See latest build](http://spring-petclinic-devops-dev.us-east-1.elasticbeanstalk.com)

## A DevOps Approach
- A developer pushes code change to GitHub and triggers a new build
- Jenkins Master acts on trigger by delegating build to minion build servers
- Jenkins posts build status to dashboard
- Jenkins sends email notification and posts Slack message for development team
- Java Spring boot application is deployed into Docker container
- Docker container is deployed to the target environment where it is autoscaled
- Any failing container is replaced automatically by Docker cluster management

<img alt="devopspipeline" src="https://github4doug.github.io/img/devopspipeline.png">

# Contributing

The [issue tracker](https://github.com/spring-projects/spring-petclinic/issues) is the preferred channel for bug reports, features requests and submitting pull requests.

For pull requests, editor preferences are available in the [editor config](.editorconfig) for easy use in common text editors. Read more and download plugins at <http://editorconfig.org>. If you have not previously done so, please fill out and submit the https://cla.pivotal.io/sign/spring[Contributor License Agreement].

# License

The Spring PetClinic sample application is released under version 2.0 of the [Apache License](http://www.apache.org/licenses/LICENSE-2.0).

[spring-petclinic](https://github.com/spring-projects/spring-petclinic)
[spring-framework-petclinic](https://github.com/spring-petclinic/spring-framework-petclinic)
[spring-petclinic-angularjs]( https://github.com/spring-petclinic/spring-petclinic-angularjs)
[javaconfig branch]( https://github.com/spring-petclinic/spring-framework-petclinic/tree/javaconfig)
[spring-petclinic-angular]( https://github.com/spring-petclinic/spring-petclinic-angular)
[spring-petclinic-microservices]( https://github.com/spring-petclinic/spring-petclinic-microservices)
[spring-petclinic-reactjs]( https://github.com/spring-petclinic/spring-petclinic-reactjs)
[spring-petclinic-graphql]( https://github.com/spring-petclinic/spring-petclinic-graphql)
[spring-petclinic-kotlin]( https://github.com/spring-petclinic/spring-petclinic-kotlin)
[spring-petclinic-rest]( https://github.com/spring-petclinic/spring-petclinic-rest)
