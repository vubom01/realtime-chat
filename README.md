# Demo Realtime Chat

This is a simple real-time chat application built with Ruby on Rails, using Turbo and Redis to support real-time message transmission.

## Technologies

```
$ Ruby version: 3.1.0
$ Rails version: 7.2
$ Database: sqlite3 3.43.2
$ Redis: Used as pub/sub to transmit messages instantly
$ Turbo Streams: Supports real-time UI updates
```

## Running

```
$ docker-compose up -d
$ bundle install
$ rails db:migrate
$ rails g devise:install
$ rails s       
```

## Usage
```
$ Open a browser and navigate to http://localhost:3000
$ Sign in or create a new account
$ Join a chat room and send messages in real-time    
```

![2025-02-28 09-51-51.gif](public/2025-02-28%2009-51-51.gif)
