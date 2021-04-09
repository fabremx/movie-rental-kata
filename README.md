# Movie Rental

This source code follows Martin Fowler's book "Refactoring, Improving the Design of Existing Code".

## Context

Actualy the `statement` method prints out a simple text output of a rental statement

```
Rental Record for martin
  Ran 3.5
  Trois Couleurs: Bleu 2
Amount owed is 5.5
You earned 2 frequent renter points
```

## Instructions

Refactor first the code then write an HTML version of the statement method :

```
<h1>Rental Record for <em>martin</em></h1>
<table>
  <tr><td>Ran</td><td>3.5</td></tr>
  <tr><td>Trois Couleurs: Bleu</td><td>2</td></tr>
</table>
<p>Amount owed is <em>5.5</em></p>
<p>You earned <em>2</em> frequent renter points</p>
```

## Testing

Unit tests can be run using npm:

    $ npm test

Coverage tests can be run using npm:

    $ npm run cover
