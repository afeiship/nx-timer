# nx-timer
> Timer for nx.

## installation
```rb
# from gem
gem 'nx-timer'
# from git
gem 'nx-timer', git: 'git@github.com:afeiship/nx-timer.git'
```

## usage
```rb
Nx::interval(3) do
    puts "hello nx-timer"
end

# hello nx-timer
# hello nx-timer
# ...
```

## build/publish
```shell
# build
gem build nx-timer.gemspec

# publish
gem push nx-timer-0.1.0.gem
```

## resources
- https://stackoverflow.com/questions/19416443/setinterval-equivalent-for-ruby/19416686
- https://mlog.club/article/1276189