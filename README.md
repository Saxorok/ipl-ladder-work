# This is ladder work of IU6-32 BMSTU

## To start up run
```
  git clone https://github.com/TwoBroWin/ipl-ladder-work.git
  cd ipl-ladder-work
  bundle install
```

## To Start a server in development mode
```
  rails db:migrate
  rails s
```
### Get ```localhost:3000``` in your browser

## To Run tests
```
  rails db:migrate RAILS_ENV=test
  rails test
```

## To Run Selenium tests
### Download geckodriver from here! https://github.com/mozilla/geckodriver/releases
```
  ruby test/selenium/selenium_test.rb
```
