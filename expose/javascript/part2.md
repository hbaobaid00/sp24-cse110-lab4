# Answers for Part 2

1. Line 12 prints the value 3 because i is declared as a var which means that the variable can be accessed outside the block. Once the for loop is ran, i ends off with the value of 3 because the size of prices is 3.
2. Line 13 prints the value 150 because it will take the discount price of the last element in the array since "discountedPrice" is updated after each iteration. When you apply the discount to 300, it comes to 150.
3. Line 14 prints the value 150 because the last update to "finalPrice" would be 150 * 100 / 100 which is 150.
4. The function returns [50, 100, 150] because the loop takes the discount of each item in the list and pushes it to a new list which is what gets returned.
