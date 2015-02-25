## Study Group Expanded

*Every week I run the [Ruby on Rails Study Group](https://generalassemb.ly/education/ruby-on-rails-study-group/new-york-city/10792) for General Assembly. The sessions themselves are restricted to GA alumni, but I like to share what we learn with everyone!*

Here's what happened at the last Ruby Study Group:

- First, I'm very proud to announce that a couple of your Office Hours attendees have deployed a really fun social application called [ohhey.me](http://ohhey.me/). Check out the site and show them some love!

- We spoke once again about thread safety. I observed that most Rails applications are not thread safe, despite Rails itself being thread-safe. That's a hard one to explain, so I found someone on the Internet who did a [pretty nice job of it](http://stackoverflow.com/questions/15184338/how-to-know-what-is-not-thread-safe-in-ruby/15184752#15184752). This is a concern, but not a major one. Plenty of scalable web applications are built without thread safety. They can still perform exceptionally well. Thread safety is an advanced topic. Explore it at your leisure but keep your focus on the fundamentals - object oriented design, testing, and hosting considerations, among others.

- We didn't get to this in class but I want to share it anyway. This tutorial details the [Life of an HTTP Request in Rails](https://www.omniref.com/ruby/gems/railties/4.2.0/symbols/Rails::Application#annotation=4084035&line=161). I like this tutorial because it starts in the Rails core classes and works it's way to your controller. This one taught me a couple of things.

- We discussed the problem of Heroku dynos "going to sleep" when they're not idle. The easiest and recommended approach to avoid this is to bump up the number of dynos you're using. However, there are more cost-effective methods out there such as [Uptime Robot](https://uptimerobot.com/) and even [configuring the New Relic add-on](https://coderwall.com/p/u0x3nw/avoid-heroku-idling-with-new-relic-pings).

Happy Hacking!

