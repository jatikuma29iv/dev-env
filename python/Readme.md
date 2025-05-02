# Python 3.13

This `Dockerfile` creates environment to run python:3.13 inside docker

## Quickstart
Change dir to your project folder and run command:

### Run `App.py`
```bash
docker build -f https://raw.githubusercontent.com/jatikuma29iv/dev-env/refs/heads/main/python/Dockerfile -t pdev .
docker run --rm --name pdev -d pdev
```

this will launch `App.py`

### Only load requirements
```bash
docker build -f https://raw.githubusercontent.com/jatikuma29iv/dev-env/refs/heads/main/python/Dockerfile -t pdev .
docker run --rm -v $(pwd):/app --name pdev --entrypoint sleep -d pdev infinity
```

then enter shell by running
```
docker exec -it pdev bash
```
