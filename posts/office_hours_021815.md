## Study Group Expanded: 12 February 2015

*Every week I run the [Ruby on Rails Study Group](https://generalassemb.ly/education/ruby-on-rails-study-group/new-york-city/10792) for General Assembly. The sessions themselves are restricted to GA alumni, but I like to share what we learn with everyone!*

Here's what happened at the last Ruby Study Group:

- We looked at some [new methods](http://www.sitepoint.com/new-methods-ruby-2-2/) in Ruby 2.2.0. We spent some figuring out why anyone would use the new `itself` method. One use case is covered here by Aaron Lasseigne. You can also view this [Ruby Tapas video](http://www.rubytapas.com/episodes/280-Itself) on the topic, though it is not free.

- I gave a public service announcement regarding [Puma](http://puma.io/), Heroku's new [web server of choice](https://devcenter.heroku.com/changelog-items/594). The PSA is to read Heroku's [steps to deploying with the Puma web server](https://devcenter.heroku.com/articles/deploying-rails-applications-with-the-puma-web-server) very closely. Pay particular attention to the [Thread Safety](https://devcenter.heroku.com/articles/deploying-rails-applications-with-the-puma-web-server#thread-safety) section and follow the instructions there. If you're wondering whether or not your application is thread-safe, it probably isn't.

- This led us into the topic of concurrency, one too large to cover in any single session. However, if you're interested in concurrency here's how you can get started:

  1. Read about what programming concurrency is and how it's typically implemented. Any intro will do - Wikipedia, various college lecture notes, etc...
  2. Have a look at Practicing Ruby's [Gentle Introduction to Actor-based Concurrency](https://practicingruby.com/articles/gentle-intro-to-actor-based-concurrency). The Dining Philosopher's problem, a quintessential concurrency puzzle, is broken down here.
  3. Check out [Celluloid](https://celluloid.io/) and [concurrent-ruby](https://github.com/ruby-concurrency/concurrent-ruby) to see how Rubyists are solving the problem of concurrency in everyday programming.
  4. Don't be afraid of looking at new languages that are built to solve this problem. I recommend [Golang](http://www.golang-book.com/10/index.htm) and [Elixir](http://www.infoq.com/interviews/valim-elixir) (links are to the languages' respective concurrency topics).

Happy Hacking!

