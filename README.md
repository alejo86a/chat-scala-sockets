# chat-scala-sockets

A minimal **Play Framework (Scala)** web application scaffold, generated from the default Play/Activator template (`my-play-chat`).

## What this is

This is essentially the default Play Framework starter project with its demo controllers left mostly intact. Despite the repo name, there is no actual chat or WebSocket feature implemented — it looks like the starting point of a chat application built with Scala and sockets that was never completed, or a personal practice exercise exploring the Play framework.

## Tech stack

- Scala 2.11
- Play Framework (PlayScala plugin)
- sbt / Activator build tool
- ScalaTest + Play test support

## Structure

- `app/controllers/HomeController.scala` — basic HTTP request handling
- `app/controllers/AsyncController.scala` — example of asynchronous request handling
- `app/controllers/CountController.scala` — example of dependency injection
- `app/services/Counter.scala`, `app/services/ApplicationTimer.scala` — example stateful/lifecycle components
- `app/Module.scala` — Guice bindings
- `app/Filters.scala` — HTTP filters
- `conf/routes` — route definitions
- `test/` — basic Play test specs

## How to run

```bash
# Using sbt (recommended if installed)
sbt run

# Or using the bundled Activator launcher
./bin/activator run
```

Then open http://localhost:9000.

## Context

Personal practice project exploring the Play Framework in Scala; appears to be an unfinished/early-stage experiment rather than a production application.
