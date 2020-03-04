# README

from https://www.autovice.jp/articles/43

# How to create this

``` shell

$ mkdir leatn_react-rails
$ mv leatn_react-rails learn_react-rails
$ cd learn_react-rails
$ bundle init
$ bundle install --path vendor/bundle
$ be rails new ./
$ be rails webpacker:install:react

$ bundle install # Add 'react-rails'
$ be rails g react:install
$ be rails g react:component HelloWorld greeting:string
$ be rails g controller Sample index
$ # a265fa83b6dfa543730c895b62167cf18a05b20c

$ bundle exec rails webpacker:install:typescript
$ mv ./app/javascript/packs/hello_react.jsx ./app/javascript/packs/hello_react.tsx
$ # a6539c46670d94bc536db552236590e2d27e110d
```

