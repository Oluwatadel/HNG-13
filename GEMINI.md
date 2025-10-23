## Project Overview

This project contains two stages, `stage0` and `stage1`. 

`stage0` is a FastAPI application that provides a `/me` endpoint. This endpoint returns the user's name, email, backend stack, current UTC timestamp, and a random cat fact.

## Building and Running (for stage0)

To build the Docker image for `stage0`:

```bash
docker build -t hng13-stage0 ./stage0
```

To run the Docker container for `stage0`:

```bash
docker run -p 8000:8000 hng13-stage0
```

The application will then be accessible at `http://localhost:8000/me`.
