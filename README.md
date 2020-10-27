To run using `docker-compose` use the following command

```bash
docker-compose up --build web db
```

The option `--build web db` allows to rebuild the image used by the `web` service used in `docker-compose.yml` (required for any code changes to take effect)

# Todo
- Edit page for product
- Errors handling
- Logins/sessions
