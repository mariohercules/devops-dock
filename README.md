# Devops-Dock

Docker DevOps development environment

## USING

Clone devops-dock inside your project:

```
$ git clone https://github.com/mariohercules/devops-dock.git
```

Enter the devops-dock folder and rename env-example to .env.

```
$ cp .env-example .env
```

Run your containers:

```
$ docker-compose up -d gitlab jenkins grafana
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

### GRAFANA

* Analytics and monitoring

Default credentials are: admin/ admin 
