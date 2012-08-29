!SLIDE
# Great, now I know what a Hypermedia API is. 

!SLIDE
# How do I make one?

!SLIDE
# Rails + Lots of Gems

Also monkey patching

!SLIDE
# Gems

* ActiveModel::Serializer
* RspecApiDocumentation
* Raddocs
* A few other handy ones

!SLIDE command
# $ rails new hypermedia_api --skip-test-unit

!SLIDE command
# $ vim Gemfile

    gem 'raddocs'
    gem 'active_model_serializers'

!SLIDE command
# $ vim Gemfile

    group :test, :development do
      gem 'rspec-rails'
      gem 'rspec_api_documentation'
    end

!SLIDE
# Get rspec set up

!SLIDE
# Create our first acceptance test

!SLIDE
# Generate models, index action, serializers

!SLIDE
# Show

!SLIDE
# Create

!SLIDE
# Update

!SLIDE
# Delete

!SLIDE
# Set up HAL

Let the monkey patching begin

!SLIDE
# We're missing something...

!SLIDE command
# $ curl http://localhost:300/
# ""

!SLIDE
# Root resource
