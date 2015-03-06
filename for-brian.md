# Webauth tests

`cd path/to/webauth`

`TRAVIS=1 RAILS_ENV=test rake db:migrate`

`rm .bundle/config`

`TRAVIS=1 bundle install`

`rm Guardfile`

`TRAVIS=1 RAILS_ENV=test guard init rspec`

`TRAVIS=1 RAILS_ENV=test guard`

Guard command line: `a` to run all tests
