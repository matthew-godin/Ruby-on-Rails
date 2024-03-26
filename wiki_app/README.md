# Setup

Start the server

```bash
rails s
```

Setup

```bash
rails g controller welcome index
rails g scaffold WikiPost
rails db:migrate
rails g migration AddTitleToWikiPost tilte:string
rake db:migrate
```

Access Rails console

```bash
rails c
```

Rails console

```bash
post = WikiPost.create!(title: 'My first post!')
```
