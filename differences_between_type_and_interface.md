The core differences between type aliases and interface in TypeScript

We can define custom types on TypeScript in Type Alliases and Interface. Both descrive data structure, improve code read avility and maintain type safe. Besically both are usefull in TypeScript. But they do have some difference both are given below:

For Custom name keyword we use type alliase. It worked on objects, primitive type, uniun type, tuples and intersections. But Interface is used on OOP. Where it define the interface keyword on structure of an object. Also interface do not work on union types and type alliase can't extends but type alliases can combine using the & sign.

When Should You Use Them?

When I need to use extend on class we have to use interface which would be easy to add more sub classes. And when I use objects, primitive type, uniun type, tuples and intersections I would use type alliases.
