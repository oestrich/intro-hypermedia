!SLIDE
# REST
## REpresentational State Transfer

!SLIDE
# Relies heavily on HTTP

* Methods and URIs
* Media types
* Client Server

!SLIDE
# Relies heavily on HTTP (Cont)

* Stateless
* Caching
* Uniform Interface (HATEOAS)

!SLIDE
# Methods and URIs

!SLIDE
# Five Routes

    GET    /orders
    POST   /orders
    GET    /orders/:id
    PUT    /orders/:id
    DELETE /orders/:id

!SLIDE
# GET /orders

List a set of orders

!SLIDE
# POST /orders

Create an order

!SLIDE
# GET /orders/:id

View a single order

!SLIDE
# PUT /orders/:id

Replace or create an order

!SLIDE
# DELETE /orders/:id

Delete an order

!SLIDE
# A bit about HTTP Verbs

!SLIDE
# GET

* Retrieve a resource

.notes should never change a resource

!SLIDE
# POST

* Most generic verb
* Can use it for anything

.notes no semantic meaning

!SLIDE
# PUT

* Update or Create a resouce, "Put this resource at this url"
* Must be the entire resource, not partial

.notes rails does this wrong

!SLIDE
# DELETE

* Delete a resource

!SLIDE
# PATCH

* Update a resource partially
* Must be a diff

.notes no current standard diff format, https://secure.designinghypermediaapis.com/nodes/much-ado-about-patch

!SLIDE
# Media Types

!SLIDE
# Formats
* JSON
* XML
* XHTML

!SLIDE
# Setting the Media Type

* Accept Headers
* Rails way - .:format

!SLIDE
# Representation based

Models != Representations

.notes Models do not necessarily equal end representations
