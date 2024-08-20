# Ruby on Rails Tutorial (by Michael Hartl) sample application

## License

All source code is available jointly under the MIT License and the Beerware License.

## Getting started

To get started with the app, clone the repo and then install the needed gems:

```
$ gem install bundler -v 2.3.14
$ bundle _2.3.14_ config set --local without 'production'
$ bundle _2.3.14_ install
```

Next, migrate the database:

```
$ rails db:migrate
```

Finally, run the test suite to verify that everything is working correctly:

```
$ rails text
```

If the test suite passes, you'll be ready to run the app in local server:

```
$ rails server
```

Be HAPPY!!!!
