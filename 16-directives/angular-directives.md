# Custom Angular Directives

With services we have seen one way to reuse certain code throughout our
application. Services are a way for us to re-use javascript code, but what about
visual components in our application (i.e html)? Directives are provided to us
by angular so that we can re-use ui components throughout our application.

Now, this isn't limited to html, directives can wrap up javascript, html, css,
and other angular directives into nice reusable components that we can use in
any controller.

### Syntax for writing custom directives

Like we have seen with controllers and services, there is more than one way to
write them. With directives we will follow a particular pattern that makes them
more reusable

##### isolated scope

We will always define our own scope. Once we do that, then we pass in the
variable data we want to use when we add the directive in our views

##### link function

Don't worry about the nuances too much, but think of the link function as the
controller - here we can add functions and values to the scope the directive
will have



