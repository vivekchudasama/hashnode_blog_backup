## Array [🤓] in Javascript👨🏻‍💻 | Everything you need to know about an array in JS!

### **Before we look into an array in JavaScript. We should know why we use an array and what an array is in programming languages, what is the benefit of using an array** 
**-----------------------------------------**
#  What is an array in programming?

>An array is **a data structure** that may **hold a fixed-size collection of the same data type components**. A collection of data is stored in an array, although it is generally more convenient to conceive of an array as a collection of variables of the same type.

# Why do we use an array?

>An array is a collection of bits or data kept in shared memory spaces, often known as database systems, in coding. An array's goal is to group several bits of data of the same type.

# What's the benefit of using an array?

>The array data structure has a clear advantage: It could hold various data formats with a common name. It allows object access at random. There is no memory deficit or overload since the array is fixed in size and stored in shared memory locations. It is useful to store any form of data that has a fixed size.

# Now get the main point: An Array in JavaScript.

> - Arrays are indeed a powerful and extensible Javascript feature. They are very easy to use and can do practically anything. However, arrays in Javascript and other common languages differ significantly.

> - There are only six data types in Javascript: datatypes (boolean, integer, text, null, undefined, undefined) and object. Arrays are not included in this list because they are also objects.

## Create an Array
> To create an array you can use various methods to create

**'' The const keyword is commonly used to declare arrays. ''**

1. First Method 
  > without breaking space
```
const cars = ["Saab", "Volvo", "BMW"];
``` 
2. Second Method
  > Space and Keyword break
```
const cars = [
  "Saab",
  "Volvo",
  "BMW"
];
```
3.  Third Method
  > with elements 
```
const cars = [];
cars[0]= "Saab";
cars[1]= "Volvo";
cars[2]= "BMW";
```

## Accessing Array Elements

> Arrays are accessed using their integer indexes. Since an array's indexing starts with 0 to the definition of an array.

1. Array Accessing with [index no]
```
const cars = ["Saab", "Volvo", "BMW"];
let car = cars[0];
```

##  Changing an Array Element

> Arrays are the form of index 0 to 'N' number, to change the 'N' number of value in an array we use array name and [No. of Index] = "New Value".

1. For Example
```
const cars = ["Saab", "Volvo", "BMW"];
cars[0] = "Opel";
```

## Access the Full Array Or print the full Array

> to print or access an array we use the array's name

1.
```
let num = [1, 2, 3, 4, 5];
for (let number of num) 
{
console.log(number);
}
```

#### Credit | Resources

>[w3schools](https://www.w3schools.com/js/js_arrays.asp)




