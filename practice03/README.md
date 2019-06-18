## One to Multi

Build a function that sorts an array into a multidimensional array grouped by data type

- Write a function that takes one parameter 
	- Parameter 1 - An array of anything
- The function should output a multidimensional array grouped by data type
- Example: 
	- `var myArray = ['hello', 34, true, false, 'goodbye', 56, 12, '25', true];`
	- `groupArray(myArray);`
	- Output - `[['hello, 'goodbye', '25'], [34, 56, 12], [true, false, true]]`

	pseudo: 
	-take in a list
	-create a new empty list, to be returned later
	-go through inputted list one by one
	-check using typeof to see what type of value that index holds
	-create 3 separate arrays for different types.
		-string, boolean, number
	-push to specific array
	-push array to multi array,
	-return multi array
	

