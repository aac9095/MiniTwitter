# MiniTwitter

MiniTwitter is minimalist app emulating core features of Twitter website. The project focusses on building model associations (has-many through associations). A User can create multiple posts(each of which belong to one User) and a User can folow multiple Users (each of which can be followed by multiple Users).


## Getting started

To get started with the app, clone the repo and then install the needed gems:

```
$ bundle install --without production
```

Next, migrate the database:

```
$ rails db:migrate
```

Finally, run the test suite to verify that everything is working correctly:

```
$ rails test
```

If the test suite passes, you'll be ready to run the app in a local server:

```
$ rails server
```

