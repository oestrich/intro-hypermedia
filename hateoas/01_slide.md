!SLIDE
# Uniform Interface

.notes the part most people don't get right

!SLIDE
# Uniform Interface

* Identification of resources
* Manipulation of resources via representations
* Self descriptive messages
* Hypermedia as the engine of application state

!SLIDE
# Identification of resources

.notes This is what a user looks like

!SLIDE
# Manipulation of resources via representations

.notes JSON, XML

!SLIDE
# Self descriptive messages
Statelessness

.notes Built into HTTP

!SLIDE
# Hypermedia as the engine of application state

HATEOAS

.notes The Rest of REST [Jon Moore Oredev 2010]

!SLIDE
# Clients should not know how to build routes

.notes most important thing about hateoas

!SLIDE
# Enter HAL

JSON cannot describe a link

!SLIDE
# HAL is a media type for defining links in JSON

application/hal+json

.notes +json is actually doesn't mean "if you can't load application/hal treat me as json" it exapnds to "application/json"

!SLIDE
# The Goal

GET /

.notes GET / and walk the entire API
