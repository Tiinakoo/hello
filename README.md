# Hello

A tiny static web page served by nginx in a Docker container for a university project.

## Build locally

```bash
docker build -t hello .
docker run -p 8080:80 hello
```

Then open http://localhost:8080 and press the button. You should see "Success!".
