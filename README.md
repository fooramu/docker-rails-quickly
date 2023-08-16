# light-docker-rails

### You can check Rails7 very quickly.

- We don't have to occurred any more errors to check for Rails behavior...
- We don't have to modify some codes after git clone...
- We don't have to read long README.md
- We don't have to start up mysterious container.

... Only the welcome page is needed.

Thank you for all Rails engineer's.

# Step

```bash
git clone git@github.com:fooramu/light-docker-rails.git
cd light-docker-rails
docker-compose build
docker-compose up -d
docker-compose exec web rails db:create
```

# Contribute

If you have a more shortly construct ideas, please contribution.



