# Programming Basics: Loops Using Arrays

1. **sumOfNumbers.** Create a program that adds up the numbers in an array (of at least 3 numbers). **Bonus**: Print to screen both the sum and the product of these numbers.

2. **Hello Frien.** Create an array filled with your friends' and family's names. Loop over the array and greet each friend. **Bonus**: Print the indexes of each item in the array. Examples:

* [Maria, Mike, Paul, Doven] ➞ expected output: "Hello Maria! Hello Mike! Hello Paul! Hello Doven!" 

* **Bonus** [Susan, Rezvane, Hadi] ➞ expected bonus output: "Susan is at index 0 of my friends and family array, Rezvane is at index 1 of my friends and family array, Hadi is at index 2 of my friends and family array". 

3. **City Names.** Create an array of city names. Loop through the array and add the city names to a string. Examples:

* [Berlin, Paris, Prague, Rome] ➞ expected output: "Berlin, Paris, Prague, Rome". 

4. **Odds and Evens.** Create a program that changes a given array by adding 1 to each odd integer and subtracting 1 from each even integer. Examples:
* [3, 5, 2, 4] ➞ expected output: [4, 6, 1, 3]
* [6, 9, 10, 20] ➞ expected output: [5, 10, 9, 19]

5. **Capitalize.** Create a program that capitalizes the first letter of each element in an array of names. Examples:
* ["matt", "sara", "lara"] ➞ ["Matt", "Sara", "Lara"]
* ["samuel", "MARIA", "luke", "mary"] ➞ ["Samuel", "Maria", "Luke", "Mary"]
* ["Cynthia", "Karen", "Jane", "Carrie"] ➞ ["Cynthia", "Karen", "Jane", "Carrie"]

* **Note:** Keep names in the same order and make sure that only the first letter of the name is capitalised (See "Maria" in the second above example). 
	
6. **No Duplicates!** A set is a collection of unique items. A set can be formed from an array by removing all duplicate items. Create a program which transforms an array into a set of unique values. See the examples below. Example:
* [1, 4, 4, 7, 7, 7] ➞ [1, 4, 7]

* [1, 6, 6, 9, 9] ➞ [1, 6, 9]
* [2, 2, 2, 2, 2, 2] ➞ [2]
* [5, 10, 15, 20, 25] ➞ [5, 10, 15, 20, 25]

7. **Repeat it.** Create a program with two variables: "item" and "times". Create a program that repeats the "item" as many times as specified by "times". The first variable ("item") is the item that needs repeating while the second argument ("times") is the number of times the item is to be repeated. Print the result in an array. Examples:

* ("example", 3) ➞ ["example", "example", "example"]

8. **Factors.** A factor chain is an array where each previous element is a factor of the next consecutive element. The following is a factor chain:
[3, 6, 12, 36]

* // 3 is a factor of 6 (3 * 2 = 6)
* // 6 is a factor of 12 (6 * 2 = 12)
* // 12 is a factor of 36 (12 * 3 = 36)

Create a program that determines whether or not a given array is a factor chain. Examples:
* [1, 2, 4, 8, 16, 32] ➞ true
* [1, 1, 1, 1, 1, 1] ➞ true
* [2, 4, 6, 7, 12] ➞ false
* [10, 1] ➞ false

