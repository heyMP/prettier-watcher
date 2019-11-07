# Prettier Watcher for Docker

Watches files for changes then runs a prettier formatting.

## Usage

```bash
docker run -v $(pwd):/work heymp/prettier-watcher **/*.html -- prettier --write {{changed}}
```