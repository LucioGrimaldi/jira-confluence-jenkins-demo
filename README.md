JIRA-CONFLUENCE-JENKINS DOCKER COMPOSE DEMO


1. docker-compose file with 3 docker containers with basic setting
    1. Jira
    2. Confluence
    3. Jenkins

2. nginx reverse proxy as additional docker to proxy each system.
Example:
Access Jira with https://somedomain.com/jira on local system.


3. Python script that pulls data from Jira and Jenkins APIs, and then writes it to a Confluence page using the Confluence API.
Example:
Pull a list of projects and jobs from Jira and Jenkins and who the Project Lead and Creators are.


4. The script is into a Jenkins job and set it to run daily.