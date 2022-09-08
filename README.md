# For GitLab Pipeline

## Artifactory
Create repos with [jfrog-tools](https://github.com/tsuyo/jfrog-tools)
```
$ jf-quick-setup -k gitlab -t maven
```
## GitLab
Set the following variables (Settings -> CI/CD -> Variables)
- ARTIFACTORY_URL
- ARTIFACTORY_USER
- ARTIFACTORY_PASSWORD
- REPO_NAME (if you follow the above, the name should be "gitlab-maven")
- BUILD_NAME