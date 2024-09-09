
<div align="center">
  <img width="586" alt="スクリーンショット 2023-08-18 10 47 04" src="https://github.com/fooramu/docker-rails-quickly/assets/434513/94cd06e1-27d7-4b4a-9941-f392e730f966">
</div>

# docker-rails-quickly

### You can check and run Rails7 very quickly.

Let's use to learn to your “Rails" !

### Containers

Name | Description | ※
--- | --- | ---
db | MySQL 8 | Health check available (linked to `web`)
web | ruby 3.2.5, Rails 7.2.1 | `rails new --force --no-deps --database=mysql --minimal`

### Update history

- <a href="https://github.com/fooramu/docker-rails-quickly/commit/2808c6f2c4d4c6d0c5f2a53df64a9add2d46057f">7.2.1 - 2024.08.28</a>
- <a href="https://github.com/fooramu/docker-rails-quickly/commit/9122719f30aff81233962ad9c331bce06c1102bf">7.1.3 - 2024.01.17</a>
- <a href="https://github.com/fooramu/docker-rails-quickly/commit/1fbd12381ed9ca66f016fa51bb9ab09094cfa9f4">7.0.8 - 2023.09.19</a>

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

<img width="500" alt="image" src="https://github.com/fooramu/docker-rails-quickly/assets/434513/4e258ba4-4970-4ac1-93c7-9bc4fee563e8">

## How to contribute

If you have a more shortly construct ideas, please `fork`.
Thank you for all Rails engineer's.

1. Fork the repo
2. Create a new branch
3. Make your changes
4. Submit a pull request

## License

This project is licensed under the MIT open source license.
