good work!

to check if we are receiving an empty array, we can do it this way and the function will also be protected against null values:

if (!array || !array.length) return null;
