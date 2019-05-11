# Devops-Dock

Docker DevOps development environment

## USING

```
$ cp .env-example .env
$ docker-compose build
$ docker-compose up 
```

### JENKINS

* Get jenkins initial password for setup

```
$ docker cp jenkins:/var/jenkins_home/secrets/initialAdminPassword ./
```

### NEXUS

* Artefacts repositoy

* Default credentials are: admin / admin123

### SONARQUBE

* Code Quality

* Default credentials are: admin / admin
