## OpenJDK:Alpine-SSH

Adds uppon [openjdk:alpine](https://hub.docker.com/_/openjdk/) a ssh-agent.
- install `openssh-client`.
- create `/root/.ssh` folder.

## Tags
**latest** : openjdk11

### Create ssh key
- Pull: `docker pull tinmegali/openjdk-alpine-ssh`
- Run bash: `docker run -it -vm tinmegali/openjdk-alpine-ssh sh`
- Create key: `ssh-keygen`
- Entender credentials
- Print publick key: `cat ~/.ssh/id_rsa.pub`
