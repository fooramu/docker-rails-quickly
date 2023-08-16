
<div align="center">
  <img width="586" alt="スクリーンショット 2023-08-18 10 47 04" src="https://github.com/fooramu/docker-rails-quickly/assets/434513/94cd06e1-27d7-4b4a-9941-f392e730f966">
</div>

# docker-rails-quickly

### You can check Rails7 very quickly.

- We don't have to occurred any more errors to check for Rails behavior.
- We don't have to Initial setup after git clone.
- We don't have to read long README.
- We don't have to start up mysterious containers.

### Containers

Name | Description | ※
--- | --- | ---
db | MySQL 8 | Health check available (linked to `web`)
web | ruby 3.2.2, Rails 7.0.7 | `rails new --force --no-deps --database=mysql --minimal`

We will continue to update to the latest version whenever possible.

## How it works

```bash
git clone git@github.com:fooramu/docker-rails-quickly.git
cd docker-rails-quickly
docker compose build
docker compose up -d
docker compose exec web rails db:create
```

## Goal

<img width="500" alt="スクリーンショット 2023-08-18 16 34 26" src="https://github.com/fooramu/docker-rails-quickly/assets/434513/8f5bedde-e384-42af-8eeb-04808389ee2a">

## How to contribute

If you have a more shortly construct ideas, please `fork`.
Thank you for all Rails engineer's.

1. Fork the repo
2. Create a new branch
3. Make your changes
4. Submit a pull request

## License

This project is licensed under the MIT open source license.
