# Reading list

## Clean code
[Clean your Rails routes: grouping](https://medium.com/rubycademy/how-to-keep-your-routes-clean-in-ruby-on-rails-f7cf348ec13b): a simple solution when routes start to get messy

[Ruby modules: Extend vs Include vs Prepend](https://gist.github.com/max-las/288df80f6c14bec7b96a6b2df566ae51): different ways to include modules

## Performance
[Wrangling slow reports, large file exports, and long-running tasks in Rails with Active Job](https://boringrails.com/articles/large-exports-and-slow-reports-with-activejob/): writing good background jobs

[Performance Impact of Using Ruby on Rails View Partials](https://scoutapm.com/blog/performance-impact-of-using-ruby-on-rails-view-partials): using partials does have an impact on performance

## Database
[Never Query the Same Thing More Than Once](https://johnnunemaker.com/never-query-the-same-thing-more-than-once/): advanced ActiveRecord techniques (probably not for every day)

[Store structured data in database](https://api.rubyonrails.org/classes/ActiveRecord/Store.html): storing hashes in a single column

[Chapter 10: Multiple Table Inheritance - Enterprise Rails](https://danchak99.wordpress.com/enterprise-rails/chapter-10-multiple-table-inheritance/): looking into STI (single table inheritance), MTI (multiple table inheritance) and polymorphism in Rails. The rest of the book is also great, even if its quite old (2008) and some parts may not be relevant to current versions of Rails.

## Javascript
[Writing better StimulusJS controllers](https://boringrails.com/articles/better-stimulus-controllers/): building reusable StimulusJS controllers

[Evil Front Part 1: Modern Frontend in Rails](https://evilmartians.com/chronicles/evil-front-part-1): applying a component architecture to Rails, and looking into a lot of webpacker configuration

[Event namespaces](https://medium.com/@giraldezjorge/jquery-event-namespaces-25df89bd89dd): using namespaces to bind and/or unbind events

## Testing
[Setting Up Cypress, Rails, and CircleCI](https://gilesbowkett.com/blog/2020/10/09/cypress-rails-circle/): digging into an Cypress, an interesting alternative to Capybara coming from the Javascript world

## Devops
[How many Heroku dynos do you need, and which size — an opinionated guide](https://railsautoscale.com/how-many-dynos/): great article explaining all you need to know about Heroku dyno and concurrency configuration

[Heroku Database Connection Calculator](https://railsautoscale.com/heroku-postgresql-connection-calculator/): a tool to calculate how many db connections are necessary on Heroku (and avoid `PG::ConnectionBad` errors

## Design patterns
[Rails design patterns - The big picture](https://longliveruby.com/articles/rails-design-patterns-the-big-picture) : simple explanations of the most common design patterns

[Form Objects - Rails Casts](http://railscasts.com/episodes/416-form-objects?view=asciicast): in this episode you will learn a couple of techniques to extract form-behavior out into its own class.

[Form Object Techniques & Patterns](https://medium.com/@jaryl/disciplined-rails-form-object-techniques-patterns-part-1-23cfffcaf429): explanation of the form object pattern with examples

## Data
[Pipelining without pipes](https://thoughtbot.com/blog/pipelining-without-pipes-in-ruby): building a basic data pipeline in ruby using functional programming

## Project management
[Building large features: my process for branches, requests and reviews](https://remimercier.com/building-large-features-process/): some interesting ideas on how to organize the developement of large features

## Emailing
[Your Guide to Bulletproof Email Buttons that Work](https://www.litmus.com/blog/a-guide-to-bulletproof-buttons-in-email-design/): different techniques to build buttons that also work in MS Outlook
