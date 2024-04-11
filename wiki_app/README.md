# Setup

## Pre-setup

Install SQLite 3 and add it to the PATH.

```bash
rails new wiki_app
npm install --global yarn --force
```

## Start the Server

```bash
rails s
```

## Setup

```bash
rails g controller welcome index
rails g scaffold WikiPost
rails db:migrate
rails g migration AddTitleToWikiPost tilte:string
rake db:migrate
rails db:seed
rails g migration AddDescriptionToWikiPost description:string
rails g migration AddAuthorToWikiPost author:string
rails db:migrate
rails active_storage:install
rails db:migrate
rails turbo:install
rails importmaps:install
```

## Access Rails Console

```bash
rails c
```

## Rails Console

```bash
post = WikiPost.create!(title: 'My first post!')
```
