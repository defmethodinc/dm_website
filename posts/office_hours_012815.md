## Study Group Expanded

*Every week I run the [Ruby on Rails Study Group](https://generalassemb.ly/education/ruby-on-rails-study-group/new-york-city/10792) for General Assembly. The sessions themselves are restricted to GA alumni, but I like to share what we learn with everyone!*

Here's what happened at the last Ruby Study Group:

- We went into detail about Infrastructure as a Service (IAAS) vs. Platform as a Service (PAAS). [Digital Ocean](http://digitalocean.com/) is an example of IAAS and Heroku is an example of PAAS. The differences are many, including:
  - PAAS is opinionated about servers and databases. On Heroku, you'll use Puma and Postgres and you will like it! IAAS allows more flexibility.
  - PAAS allows easy scaling of infrastructure. With IAAS you will have to build your own strategy for increasing web instances, making more room for your database, etc...
  - PAAS does a number of things you may not be aware of - aggregating, compressing, and rotating logs; managing your deployment and rollback processes; ensuring your web and database servers never go down.
  - IAAS gives you the opportunity to learn about everything that goes into managing a web application. Every serious developer should learn to do this. However, when you're on the job or starting your own business, PAAS will save you headaches that far exceed the increase in cost over IAAS.

- We had a few different discussions that all boiled down to how AJAX works and how we can manipulate DOM elements. I didn't do as good a job as I'd like explaining this. It's a very broad topic, so I recommend starting with the basic [Rails Guides information](http://guides.rubyonrails.org/working_with_javascript_in_rails.html). Ryan Bates also has a [great RailsCast](http://railscasts.com/episodes/136-jquery-ajax-revised) that details AJAX and JQuery. Please keep bringing your questions and we'll try to work through them together.

- For those interested in learning TDD/BDD: I linked to a [free video course](https://www.udemy.com/learn-test-driven-development-in-ruby/?couponCode=meu). I don't know the instructor or the course, but it's free and seems worth a shot!

- Sticking with testing, we had a discussion about a [recent post](http://david.heinemeierhansson.com/2014/tdd-is-dead-long-live-testing.html) from Rails inventor David Heinemeier Hansson. The main takeaways were:
  - People - even very smart, talented, and influential engineers - have been bashing testing since testing was invented. This is not new.
  - It's exceedingly possible that, since he invented the framework and all, that David has less use for TDD than the average Rails developer.
  - Trying new things is important. If you've never really learned TDD/BDD, then choosing not to learn it will hamstring you as an engineer. If you're already an expert and you never do anything **without** TDD, maybe it's time to challenge that practice for a little while.

Happy Hacking!

