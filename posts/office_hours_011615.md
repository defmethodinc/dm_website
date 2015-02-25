## Study Group Expanded: 15 January 2015

*Every week I run the [Ruby on Rails Study Group](https://generalassemb.ly/education/ruby-on-rails-study-group/new-york-city/10792) for General Assembly. The sessions themselves are restricted to GA alumni, but I like to share what we learn with everyone!*

Here's what happened at the last Ruby Study Group:

- We looked at the simple and secure way to lock part of an application down with HTTP Basic Authentication. This is [easier to implement](http://api.rubyonrails.org/classes/ActionController/HttpAuthentication/Basic.html) than it is to [explain](http://en.wikipedia.org/wiki/Basic_access_authentication). One use case for HTTP Basic Auth: when you don't want to create separate user roles, or when you don't want to have the concept of a "user" at all. If you have an application that's open to the public and does not necessitate the creation of users, you can use HTTP Basic Auth to restrict access to those parts of your site that you want to control.

- Free Books! I came across [this list](https://github.com/vhf/free-programming-books/blob/master/free-programming-books.md) of free programming books on the Twitters. It's legit - there are hundreds of books on any language you can think of and even some language-agnostic computer science books.

- We discussed [acts_as_voteable](https://github.com/ryanto/acts_as_votable) and looked for alternatives. [make_voteable](https://github.com/medihack/make_voteable) and [thumbs_up](https://github.com/bouchard/thumbs_up) will both give you the same functionality. If you want to "roll your own," have a look at this [RailsBridge article](http://docs.railsbridge.org/intro-to-rails/allow_people_to_vote).

- Taking a quick dive into the world of Twitterbots, we discussed using an "observer pattern" versus polling for updates in one's Twitter feed. I came across [this GitHub repo](https://github.com/jsuder/rails-retweeter-bot), which actually has both implementations. It's not a gem and probably won't work for most use cases "out of the box." But you can use it to inspect the code and learn how to build your own.

- I mentioned this but we did not get a chance to cover it: [Five Ruby Methods You Should Be Using](https://blog.engineyard.com/2015/five-ruby-methods-you-should-be-using?utm_source=rubyweekly&utm_medium=email). From personal experience, I can tell you that many programmers are gravitating toward the `Object#tap` and `Enumerable#flat_map` methods. The spaceship operator is an oldie but a goodie!

- We talked about building our own APIs with the wonderful [grape gem](https://github.com/intridea/grape). By the way, if you're looking to contribute to open source you should give this gem a look.

- Finally, a message from one of our members to anyone who needs a private wiki solution:

```
Google sites still works, kind of.
-- Dan Keezer.
```

Thanks for the ringing endorsement, Dan!

Happy Hacking!

