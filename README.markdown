# Capistrano Slack

Push deployment messages to Slack


```ruby

require 'capistrano/slack'
set :slack_token, "webhook_token" # comes from inbound webhook integration
set :slack_room, "#general"
set :slack_subdomain, "kohactive" # if your subdomain is kohactive.slack.com
```