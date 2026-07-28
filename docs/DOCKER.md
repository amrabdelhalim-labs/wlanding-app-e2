# Docker preview

This image serves the repository's static landing page with NGINX and has no
runtime dependencies.

```sh
docker pull ghcr.io/amrabdelhalim-labs/wlanding-app-e2:v1.0.1
docker run --rm -p 8080:80 ghcr.io/amrabdelhalim-labs/wlanding-app-e2:v1.0.1
```

Open `http://localhost:8080`.


For automatic port selection and browser launch, see [the zero-config launcher guide](./LAUNCHER.md).
