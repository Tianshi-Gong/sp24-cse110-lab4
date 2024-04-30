1. At line 12, the code will print '3' because i is accessible in the function scope, and this is the value i holds when the loop exits.

2. At line 13, the code will print '150' because discountedPrice is var variable and it will leave the loop as the last element in prices / (1 - discount).

3. At line 14, the code will output '150', which is the last computed finalPrice in the loop for the price of 300 discounted by 50%.

4. This function is called with the parameters ([100, 200, 300], 0.5), it will return [50, 100, 150].