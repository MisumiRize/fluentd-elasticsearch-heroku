fluentd-elasticsearch-heroku
============================

Bootstrapping fluentd and elasticsearch on Heroku

[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)

You can simply deploy a copy of this set to Heroku via Heroku Button.

## Try

```bash
# Dump to Heroku log
$ curl "http://my-fluentd-on-heroku.herokuapp.com/debug.sample?json=%7B%22json%22%3A%22message%22%7D"
$ heroku logs

# Pass to elasticsearch
$ curl "http://my-fluentd-on-heroku.herokuapp.com/es.sample?json=%7B%22json%22%3A%22message%22%7D"
```
