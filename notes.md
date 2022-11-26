## Interface: 
An interface is actually an example of a value type. 
 
## Value types: 
Value types are types that are reused and shared across multiple subgraphs. 
Value type schema definitions can differ across subgraphs, in Federation 2.

These types can be
* Object Types, 
* enums, 
* unions, or 
* interfaces

## The @shareable directive:
Applying the @shareable directive enables multiple subgraphs to resolve a particular object field (or set of object fields). This allows the field(s) to which the directive is applied to exist in more than one subgraph.