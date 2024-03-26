# Setup

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
```

## Access Rails Console

```bash
rails c
```

## Rails Console

```bash
post = WikiPost.create!(title: 'My first post!')
```
