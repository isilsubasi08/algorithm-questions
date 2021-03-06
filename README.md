# Algorithm Questions

In this repo, we will be dealing with digits of integers and solving algorithmic questions.
We will create a class called <b>Digits</b>. We will write static methods for the Digits class.

1. Write a method named <b>digitZero</b> that gets an integer parameter n and returns its least significant digit. For example, if the parameter is 5786, the method should return 6.

2. Write a method named <b>digitFirst</b> that gets an integer parameter n and returns its first digit. For example, if the parameter is 5786, the method should return 5. 

3. Write a method named <b>digitAt</b> that gets two integers n and i as parameters (in this order). The method should return the ith digit of n. For example, if the parameters are 89745 and 2, the method should return 7. Note that the zeroth digit is 5, the first digit is 4 and the second digit is 7. 

4. Write a method named <b>digitSumLargerThan</b> that gets two integers n and limit as parameters (in this order) and returns the sum of the digits that are larger than the limit. For example, if the parameters are 889745 and 7, the method will return the sum of the digits that are larger than 7, that is 8+8+9 = 25. 

5. Write a method named <b>digitCount</b> that gets two integers n and digit as parameters (in this order). The method counts the number of digits in n that are equal to digit. For example, if the parameters are 4574172 and 7, the method should return 2. Note that 7 occurs 2 times in 4574172. 

6. Write a method named <b>digitRemoveAt</b> that gets two integers n and i as parameters (in this order). The method returns the integer obtained from n by the removal of its i-th digit. For example, if the parameters are 61748 and 3, the method should return 6748. Note that the third digit is removed from 61748. 

7. Write a method named <b>digitRemoveAll</b> that gets two integers n and digit as pa- rameters (in this order). The method should return the integer obtained from n by the removal of all digits with value equal to the parameter digit. For example, if the parameters are 647544 and 4, it should return 675. Note that all occurrences of 4 in 647544 are removed. 

8. Write a method named <b>randomNumber</b> that gets an integer parameter k. The method should return a k-digit integer with no digits repeated. For example, if the parameter is 4, the method may produce 9276. However, it may not return 9296, since it repeats the digit 9, It may also not return 926 since it is not a 4-digit number.

9. Write a method named <b>reverse</b> that gets an integer parameter n and returns the integer obtained by the reversal of its digits. For example, if the parameter is 89745, the method should return 54798.

10. Write a method named <b>charDigitSum</b> that gets a String parameter str and returns the sum of the integer equivalents (ASCII CODES) of the individual characters in the string. For example, if the parameter is “hello”, the method will return the sum of characters that is 104 (for h) + 101 (for e) + 108 (for l) + 108 (for l) + 111 (for o) = 532.

