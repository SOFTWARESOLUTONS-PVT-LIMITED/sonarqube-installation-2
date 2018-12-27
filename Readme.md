# Sonarqube
SonarQube is an open-source platform developed by SonarSource for continuous inspection of code quality to perform automatic reviews with static analysis of code to detect bugs, code smells, and security vulnerabilities on 20+ programming languages

## Requirement/Preinstall:
1. docker
2. docker-compose
## Starting Sonarqube
command `docker-compose -f sonarqube.yml up -d` <br />
-d => detached process from current session and run it in background<br />
-f => Specify an alternate compose file default is docker-compose.yml

## Accessing Sonarqube
open sonarqube in http://localhost:8183<br>
default username: admin<br>
default password: admin<br>
## Stopping sonarqube
command `docker-compose -f sonarqube.yml down`


