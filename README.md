# Ruby on Rails Tutorial sample applictaion

This is the sample application for the
[*Ruby on Rails Tutorial:
Learn Web Development with Rails*](https://railstutorial.org/)
by [Michael Hartl](https://www.michaelhartl.com)

## License

All source code in the [Ruby on Rails Tutorial](https://www.railstutorial.org/) is available jointly under the MIT License and the Beerware License, See [LICENSE.md](LICENSE.md) for details.

## Getting Started

To get started with the app, clone the repo and then install the needed gems:
```
$ gem install bundler -v 2.5.3
$ bundle install
```

Next, migrate the database:
```
$ rails db:migrate
```

Finally, run the test suite to verify that eerything is working correctly:
```
$ rails test
```

If the test suite passes, you'll be ready to run the app in a local server:
```
$ rails server
```
