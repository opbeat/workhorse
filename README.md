# workhorse

## Project Goals

Celery replacement with the following key points

* Simple to use and reason about
* Minimal feature set, minimal magic
* Only supports rabbitmq as broker
* Default settings are geared toward safe task execution (at least once semantics)

## Stretch goals

* `not_before` functionality: Schedule a task to run no sooner than a specific time.

