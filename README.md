oauth_sample
===

## setup

```bash
$ git clone
$ cd APP_DIR
$ bundle install
$ bundle exec rake app:init
$ rails s
$ curl http://localhost:3000
```

## DB reset

```bash
$ bundle exec rake db:drop app:init
```

## unit test

```bash
$ bundle exec guard
```
