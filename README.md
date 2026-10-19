# My First Docker Image

Assalam-o-Alaikum! This is my first Docker image. It contains a small web page served by the Nginx web server.

**Created by:** Ariba Irfan

## Files

| File | Purpose |
|------|---------|
| `index.html` | Page structure and text |
| `style.css` | Page colors and design |
| `script.js` | Shows a message when the button is clicked |
| `Dockerfile` | Instructions for building the Docker image |

## How to run

Start Docker Desktop, then open a terminal in this folder and run:

```
docker build -t meri-pehli-image .
docker run -d -p 8080:80 meri-pehli-image
```

Then open this address in your browser: http://localhost:8080
