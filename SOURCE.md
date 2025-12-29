# engelsystem-image-builder

Automatischer Docker-Image-Builder für `engelsystem/engelsystem`, published nach GHCR:  
`ghcr.io/mschabhuettl/engelsystem`

## What it does
- Pollt das Upstream-Repo regelmäßig (Cron)
- Baut daraus ein Docker-Image
- Pusht Tags:
  - `latest`
  - `<upstream-sha12>`

## Usage
Pull:
```bash
docker pull ghcr.io/mschabhuettl/engelsystem:latest
