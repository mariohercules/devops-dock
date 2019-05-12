# Devops-Dock

Docker DevOps development environment

## USING

```
$ cp .env-example .env
$ docker-compose build
$ docker-compose up gitlab jenkins grafana
```

### JENKINS

* Get jenkins initial password for setup

```
$ docker cp jenkins:/var/jenkins_home/secrets/initialAdminPassword ./
```

### NEXUS

* Artefacts repository

Default credentials are: admin / admin123

### SONARQUBE

* Code Quality

Default credentials are: admin / admin

### GITLAB

* Code repository / build management and continuous integration server

Default credential is: root 

### TEAMCITY

* Code repository / build management and continuous integration server

Default credential is: root 
