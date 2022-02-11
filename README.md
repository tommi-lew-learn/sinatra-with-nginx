# Sinatra with Nginx
This was created as part of a Terraform / AWS ECS / Golang learning project. This Sinatra app was built as a initial app placeholder and was meant to be replaced with a Golang app.
## Ruby Sinatra app (app)

Simple Ruby web application built using the Sinatra web framework. Sinatra is a much lighter web framework compared to Rails.

## Nginx (web)

Nginx is used as a reverse proxy when deploying the web app to a cloud provider. The `nginx.conf` alongside the `Dockerfile` is found in the `app` directory.

## Local development environment

You can use the `docker-compose.yml` file to spin up both the Sinatra application and Nginx web servers. But you could probably keep it simple with `ruby app.rb` instead.
