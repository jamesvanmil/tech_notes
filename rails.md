# Rails

## Curate

Run all of the specs: `bundle exec rake spec`
Run some of the specs: `BUNDLE_GEMFILE=spec/internal/Gemfile bundle exec rspec path/to/spec.rb:LINE`

## Resque

* Start redis: `redis-server`
* Start workers:
    * New: `bin/resque work`
    * Old: 
        * Foreground: `RAILS_ENV=development QUEUE=* VERBOSE=1 rake resque:work`
        * Background: `RAILS_ENV=development QUEUE=* VERBOSE=1 rake -s resque:work > /dev/null 2>1&`
