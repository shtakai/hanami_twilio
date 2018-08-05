# Twilio Message

[![GuardRails badge](https://badges.production.guardrails.io/shtakai/hanami_twilio.svg)](https://www.guardrails.io)

Twilio Message Webhook W/Hanami

## Environment

ruby: 2.4.2

```
at least

gem 'hanami',       '~> 1.1'
gem 'hanami-model', '~> 1.1'
```

## Setup

How to run tests:

```
% bundle exec rake test
```

How to run the development console:

```
% bundle exec hanami console
```

How to run the development server:

```
% bundle exec hanami server
```

How to prepare (create and migrate) DB for `development` and `test` environments:

```
% bundle exec hanami db prepare

% HANAMI_ENV=test bundle exec hanami db prepare
```

Explore Hanami [guides](http://hanamirb.org/guides/), [API docs](http://hanamirb.org/docs/1.0.0/), or jump in [chat](http://chat.hanamirb.org) for help. Enjoy! 🌸
