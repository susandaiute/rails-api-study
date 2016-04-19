# Rails as an API Study

Use your favorite search engine and the provided readings to research and answer
the following questions (no prior knowledge is expected).

In your answers, be sure to cite any relevant sources you consulted in your
search. We ask you to write answers in your own words in order to see how you
process what you've read. Please do not answer with direct quotes from source
material. Instead, digest what you've read and repeat it in your own voice.

Please note:

-   Many of the readings will mention the "view" layer. We won't be covering the
    view layer in this program.
-   We'll use our [rails-api-template](/ga-wdi-boston/rails-api-template)
    repository as the basis for our rails applications.
    This template excludes the "view" layer.

## Required Readings

-   [Starting Ruby on Rails: What I Wish I Knew | BetterExplained](http://betterexplained.com/articles/starting-ruby-on-rails-what-i-wish-i-knew/)
-   [Intermediate Rails: Understanding Models, Views and Controllers | BetterExplained](http://betterexplained.com/articles/intermediate-rails-understanding-models-views-and-controllers/)
-   [Getting Started with Rails — Ruby on Rails Guides](http://guides.rubyonrails.org/getting_started.html)
-   [The Rails Command Line — Ruby on Rails Guides](http://guides.rubyonrails.org/command_line.html)
-   [Rails Routing from the Outside In — Ruby on Rails Guides](http://guides.rubyonrails.org/routing.html)
-   [Action Controller Overview — Ruby on Rails Guides](http://guides.rubyonrails.org/action_controller_overview.html)

## Define Model Responsiblities

In your own words, define what the responsibilities of the model layer are in
Rails.

```md
The model stores data that is either fetched or passed to it by the controller.
```

## Define Controller Responsiblities

In your own words, define what the responsibilities of the controller layer are
in Rails.

```md
The controller interacts with the model to get, update, or submit information
that the model will then store.  It will take fetched data and then pass it
to the view so that it will be displayed in a readable fashion.
```

## Define Router Responsiblities

In your own words, define what the router does in Rails.

```md
Based on the request by the client, the router chooses which controller is
most appropriate to fulill the request.
```

## The Request-Response Cycle in Rails

Starting with a client making a GET request to a particular URL, describe how
the parts of Rails interact to produce and send a response.

```md
The server gets the GET request from a client which is then routed to the
appropriate action controller.  The controller then gets the requested data from
the model which it will pass to the view.  The view takes this info and and
packages it so that the client can then display it.
```
