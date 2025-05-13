# universal-artifact-cli
A universal artifact CLI for managing artifacts to Artifactory, Nexus and other artifact repository managers.

The purpose of this utlity is to enable CI/CD pipelines to upload, download, delete and performa other actions on artifacts by using a single CLI tool.

# Features:
* Enables migratinf from current artifact repository manager to another without rewriting your CI/CD pipelines to use the new repository manager API.
* Set artifact metadata such as build job name, build number, Git commit hash, etc.
* Support multiple artifact repository managers backends for different types of artifacts, for exmaple Python artifacts and Docker images.
* Ability to search artifacts.


# JFrog Artifactory support
Artifactory support requires the jf-cli installed as uartifact-cli is using it to communicate with Artifactory's API.

# Future repository backends support
* Sonatype Nexus
* Harbor
* PyPI compatible backend
* AWS CodeDeploy
* GCP Artifact Registry
* Azure Artifacts

# Code Contributions
You are welcome to contribute backends to the project.
