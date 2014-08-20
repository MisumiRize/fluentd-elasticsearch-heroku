web: bundle exec fluentd -c td-agent.conf -i "<source>\n type http\n port $PORT\n</source>\n<match es.**>\n type elasticsearch\n hosts $SEARCHBOX_URL\n</match>"
