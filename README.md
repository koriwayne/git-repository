# git-repository

To bring up the entire docker compose file 

`docker compose up -d`

## To bring up individual containers there names are

`docker compose up -d revers-proxy` will bring up the traefik reverse-proxy 

`docker compose up -d whoami` will bring up a traefix/whoami program to test the reverse-proxy

`docker compose up -d prometheus` will bring up the prometheus server

`docker compose up -d grafana` will bring up the grafana server

`docker compose up -d plex` will bring up the plex media server

`docker compose up -d minecraft` will bring up the minecraft server

 ### To Do:

ArgoCD

SonarQube

Trivy

Terraform

ARC Action Runners

```

- Choose a Dockerfile Linter
    - Trivy
    - Handolint
    - Dockle
        - git clone https://github.com/goodwithtech/dockle.git
        - cd dockle
        - docker build -t dockle:local .

- Add Dockerfile lint job to the Security Policy Repo
- Scan results uploaded to the Vulnerability Dashboard

```
