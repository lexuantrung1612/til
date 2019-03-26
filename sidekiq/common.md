 - To Clearn out everything in sidekiq
 ```
 Sidekiq::Queue.all.each(&:clear)
 Sidekiq::RetrySet.new.clear
 Sidekiq::ScheduledSet.new.clear
 Sidekiq::DeadSet.new.clear
 ```
