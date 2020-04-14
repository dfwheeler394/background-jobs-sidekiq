Sidekiq: Uses Redis to queue background jobs. Redis is an in-memory data store so it’s very fast. Sidekiq adds complexity to infrastructure because Redis needs to be added.

By Default, Sidekiq checks enqueued jobs every 5 seconds. 
