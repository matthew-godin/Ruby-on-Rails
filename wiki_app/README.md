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
```
