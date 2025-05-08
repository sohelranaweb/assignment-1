# Assignment Blog

### 1. What is type inference in TypeScript? Why is it helpful?

=> Type inference in TypeScript is the feature where the complier automatically determines the type of a variable or function return value, even if I don't type it.

exmaple:
let name = 'Sohel';

Here, I didn't mention type of name, but TypeScript infers it as a string because the value assigned is 'Sohel'. That's why in TypeScript Type inference is a important thing.

### Why is it helpful?

=> In TypeScript there are some advantage like:

- Less code, more clarity: don't have to write types everywhere; TypeScript figures them out.
- Catches error early: Because of type inference, TypeScript can catch mistakes while writing code.
- Cleaner code: Code becomes easier to read and maintain.

### 2. What are some differences between interfaces and types in typeScript?

=> In TypeScript, bothe interface and type can be used to describe the shape of an object, but they have some key differences.

- Interfaces are best suited for defining object structres and are extendable through inheritance. One advantage of interface is declaration merging, which allows multiple declarations with the same name to combine into one - useful in librarises or third party integrations

- Types are more flexible. They can represent not just objects, but also unions, intersections, primitive, and tuples.

In general, i prefer using interface for object shapes and type when i need to work with complex combinations or non-object types.
