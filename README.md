ID: 11298535
s# js-for-react-native-11298535
js-for-react-native-11298535project
ID: 11298535
NAME: AMAKYE JACOB HAGAN
FOR TASK 1 
The argument for the processArray function is an array of numbers.
The function transforms each element of the input array using the map technique to produce a new array.
A number is squared (num * num) if it is even, that is, num % 2 === 0.

A number gets tripled (num * 3) if it is unusual.
The outcome is the transformed array that is given back.
This function can be tested by including the arrayManipulation.js file in an HTML file and executing it in a browser console, or by running the file in a JavaScript environment like Node.js. The final example usage logs the result to the console and shows how to utilize the processArray method.
TASK 2
processArray function:

This function processes an array of numbers, squaring even numbers and tripling odd numbers.
formatArrayStrings function:

This function takes two arrays as arguments: an array of strings and an array of numbers (already processed by processArray).
It maps through the string array and modifies each string based on its corresponding number from the number array.
If the corresponding number is even, the string is converted to uppercase using toUpperCase().
If the corresponding number is odd, the string is converted to lowercase using toLowerCase().
Example usage:

The example demonstrates how to use both processArray and formatArrayStrings.
It first processes a sample number array and then formats a sample string array based on the processed numbers.
The output is logged to the console for verification.

TASK 3
The function createUserProfiles:

Two arrays are passed into this function: one containing the original names and the other containing the updated names.
It builds a new array of objects by utilizing the map technique.
Every item has:
id: an automatically increasing number that begins at 1.
originalName: The initial name found in the array of originalNames.
modifiedName: The matching changed name from the array of modifiedNames.
Use as an example:

Using sample data, the example shows how to use the createUserProfiles function.
Initially, arrays with the original and updated names are defined.
After that, it uses these arrays to call createUserProfiles, logging the generated user profiles to the console.
