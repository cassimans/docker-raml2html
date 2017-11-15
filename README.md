# Docker image for RAML build

## Compatibility
- GitLab-ci

## Usage 
```sh
raml-build:
  image: $CI_REGISTRY/docker-raml2html/liquibase-service:3.0.0
  tags:
    - dockerbuilds
  script:
    - raml2html -i Lampiris_Adm_Services.raml -o Lampiris_Adm_Services.html
```