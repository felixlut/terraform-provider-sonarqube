# terraform-provider-sonarqube
Terraform provider for managing Sonarqube configuration

## Installation
Download the binary from the [Releases](https://github.com/jdamata/terraform-provider-sonarqube/releases/latest) page and place it in: ```~/.terraform.d/plugins``` or ```%APPDATA%\terraform.d\plugins```

## Usage
[example.tf](example.tf) contains a sample of how to use this provider.

Consult the docs below for more details.

## Docs
[Provider configuration](docs/provider.md)

Resources:
- [sonarqube_qualitygate](docs/sonarqube_qualitygate.md)
- [sonarqube_qualitygate_condition](docs/sonarqube_qualitygate_condition.md)

## Development
```bash
docker run -d --name sonarqube -p 9000:9000 sonarqube:latest
make run
```
