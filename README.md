# mergeObjects
Write a function mergeObjects that takes multiple objects as arguments. The function should merge all the objects into a single object using the spread operator and return the merged object.
mergeObjects({ a: 1, b: 2 }, { c: 3 }, { d: 4, e: 5 });
Output: { a: 1, b: 2, c: 3, d: 4, e: 5 }
•	The function should handle any number of objects as input.
•	If there are properties with the same name in different objects, the value from the later object should overwrite the value from the earlier one.
