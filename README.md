Sidekiq: Uses Redis to queue background jobs. Redis is an in-memory data store so it’s very fast. Sidekiq adds complexity to infrastructure because Redis needs to be added.

By Default, Sidekiq checks enqueued jobs every 5 seconds. 

To enqueue first job:
1) launch Rails Console in Terminal with 'Rails c' command
2) Once in Rails Console, enter 'FakeJob.perform_later'

