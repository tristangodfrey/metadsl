# MetaDSL

A simple markdown-based language that allows business people/product owners
to maintain the base layer of a DSL.

## Example

```markdown
# Shopping Cart

A shopping cart contains one or more items

# Shopping Cart Item

A shopping cart item has a product and a quantity

# Product

An item that can be purchased by a customer in the webstore

```

## Features

- A plugin system allows for code generation based on inferred domain structure/relationships
- Automatic (POJO) class generation for each of the terms defined in the DSL
- Testing tool to verify that the code reflects the domain

