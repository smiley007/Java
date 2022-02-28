# Arrays

## Functions

### Declare Array
Use **type[] arrayName = new type[size]** for declaring an array with specified size.
Array is initialized with a default value for below types:-
- For references (anything that holds an object) that is null.
- For int/short/byte/long that is a 0.
- For float/double that is a 0.0
- For booleans that is a false.
```
int[] arr = new int[26]; // arr is initialized with zero values
```
------------------------------------------------------------------------------------

### Initialize Array with default value
Use **Arrays.fill(arrName, value)** method to fill the already declared array with default value.
```
Arrays.fill(arr, 0);
```
------------------------------------------------------------------------------------
### Length of the array
Array has **length** property to get the length of array.
This is property and not a method as it is not an array.
```
int length = arr.length
```
------------------------------------------------------------------------------------
