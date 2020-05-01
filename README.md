# I Decided to Learn Rails

I chose to learn Ruby and Rails, largely because it seemed an approachable object-oriented language with a supportive and welcoming community. I was excited that the course highlighted both functional programming and test-driven development.

Aside from a full-on technical skills dump, one of my biggest takeaways from the course was increased confidence in my ability to use "technical sophistication" to solve problems even without deep knowledge of the associated technology. I had fun making this app and using Rails. Can't wait to use it again!


# Ruby on Rails Tutorial sample application

This is the sample application for
[*Ruby on Rails Tutorial:
Learn Web Development with Rails*](https://www.railstutorial.org/)
(6th Edition)
by [Michael Hartl](https://www.michaelhartl.com/).

## License

All source code in the [Ruby on Rails Tutorial](https://www.railstutorial.org/)
is available jointly under the MIT License and the Beerware License. See
[LICENSE.md](LICENSE.md) for details.

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

For more information, see the
[*Ruby on Rails Tutorial* book](https://www.railstutorial.org/book).
