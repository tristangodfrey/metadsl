# Requirements

## MVP

An absolute must is to avoid pitfalls such as overtokenizing
the input; this is a tradeoff between developer UX and domain
expert UX, and poor domain expert UX tends to be more harmful
as it occurs upstream of the development team and thus may
lead to a great number of issues.

In order to achieve this goal we should only tokenize things which
a domain expert would already annotate themselves if they were to
be writing a text document, which basically boils down to just
headings.

This is already a fine foundation as the heading itself is enough to
generate an empty class, and the content associated with the heading
allows us to generate the behavioural documentation for that class.
(developers may of course choose to supplement it with technical details
where necessary)

## Possible expansion

It cannot be expected of domain experts to be able/willing to wrap their heads
around non-trivial syntax details necessary for more complex behaviour, therefore
the only way to accomplish this would be by means of introducing a GUI that complements
the text format, and allows users to define specific relationships between objects.

## Problems Solved

- No need for developers to document class behaviour
- Consistent naming of domain objects


## Way in the future

Instead of using a simple parser to generate a moderate amount of code, train a neural net
to produce diagrams based on text input, and optionally have the diagram validated by a
developer upon generation
