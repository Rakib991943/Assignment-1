1. Differences between Interfaces and Types in TypeScript

Interface is mainly for describing the structure of an object.

Type can describe objects too, but also unions, intersections, and more advanced shapes.

Interfaces can be extended multiple times.

Types are more flexible for combining different types.

2. Use of keyof in TypeScript

keyof gives you all the keys (property names) of a type as a new type. It is useful when you want to work with object keys safely.

3. Difference between any, unknown, and never

any → No type checking, you can do anything with it.

unknown → Safer than any, you must check the type before using it.

never → Represents something that never happens, like a function that never returns.

4. Use of Enums in TypeScript

Enums are used to define a set of named constants. They make code more readable and easier to manage. There are two main types:

Numeric Enums → Values are numbers.

String Enums → Values are strings.

5. What is Type Inference?

Type inference means TypeScript automatically understands the type of a variable without you writing it. It helps reduce extra code and still keeps type safety.
