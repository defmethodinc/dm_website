## Study Group Expanded

*Every week I run the [Ruby on Rails Study Group](https://generalassemb.ly/education/ruby-on-rails-study-group/new-york-city/10792) for General Assembly. The sessions themselves are restricted to GA alumni, but I like to share what we learn with everyone!*

Here's what happened at the last Ruby Study Group:

- We watched a Ruby Tapas episode on [Immutable Enumerators](http://www.rubytapas.com/episodes/263-Immutable-Enumerators-with-Tom-Stuart) (video is not free). This led us to a discussion of immutability, concurrency, and why these concepts matter. The episode was authored by Tom Stuart, who wrote a really interesting blog post called [Programming with Nothing](http://codon.com/programming-with-nothing).
- We discussed the [differences between symbols and strings](http://www.reactive.io/tips/2009/01/11/the-difference-between-ruby-symbols-and-strings/) in Ruby.
- We talked about the [Google Sheets gem](https://github.com/gimite/google-spreadsheet-ruby) and, more generally, the right way to [implement OAuth].
- Finally, we discussed [executing raw SQL](http://guides.rubyonrails.org/v3.2.19/active_record_querying.html#using-a-string-sql-fragment) with ActiveRecord. Ultimately, we decided that this practice is safe so long as we programmers know what we're doing. Executing raw SQL sounds nefarious, but only the execution of arbitrary SQL poses a [security threat](http://www.cisco.com/web/about/security/intelligence/sql_injection.html) to your application. Knowing how to craft SQL by hand will prove very helpful as you continue in your programming career.

Happy hacking!

