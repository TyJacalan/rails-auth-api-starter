# RAILS STARTER

A starter template for a rails api only application with authentication for users already setup.

### Main dependencies:

* Cors

* Devise

* JWT

### How to use:
1. Clone the repository to your local machine
```git clone https://github.com/TyJacalan/rails-auth-api-starter.git```
2. Run
```bundle install```
3. Run
```EDITOR="code --wait" rails credentials:edit```
4. Do a global find and replace for `rails_auth_api_starter` with `your_project_name`
5. Run
```bin/rails db:create db:migrate```
6. Start your api server on port 4000
```bin/rails s```
