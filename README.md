# oauth2-app

OAuth2 source code for Ruby and Rails project extracted with Devise and [oauth-plugin]

RUBY 2.7
### The provider

First, `cd` the `oauth2-provider` folder and run:

```
bundle install
```

Then, start the server by running the `rails server` command.

Your provider app will be available at http://localhost:3000/.

### The consumer
In a different command line tab/window, `cd` the `oauth2-consumer` folder and run:

```
bundle install
```

Then, run the client app by issuing the following command:

```
ruby app.rb
```

You app will be available at http://localhost:4567/.