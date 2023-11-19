docker run -it --network some-network --rm redis redis-cli -h some-redis

brew install redis
redis-server
brew services start redis
brew services info redis
brew services stop redis
redis-cli
ping
