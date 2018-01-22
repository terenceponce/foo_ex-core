# Foo Ex

## Overview

- This is an attempt at creating a cryptocurrency exchange

## Quick Start

```
git clone https://github.com/terenceponce/foo_ex-core # or clone your fork
cd foo_ex-core
bundle install
cp .env.example .env
bundle exec rake db:create db:migrate db:seed
bundle exec rails server
```

Open a REST client and go to [localhost:3000](http://localhost:3000)
