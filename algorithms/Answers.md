##Exercise 1

#A
O(n)

#B
O(log n)

#C
O(sqrt(n))

#D
O(n log n)

#E
O(n^4)

#F
O(n)

#G
O(n)

##Exercise 2

#A
Given an array  A of n numbers, design a linear running time algorithm to find the maximum value of a[j] - a[i], where j >= i.

function maxDiff(a) {
  let high = Math.max(a[0], a[1]);
  let low  = Math.min(a[0], a[1]);
  let highestDiff = high - low;

  for (let i = 2; i < a.length; i++) {
    high = Math.max(high, a[i]);
    low  = Math.min(low, a[i]);
  }
  
  return high - low;
}

#B

#C

##Exercise 3

#A
O(n):


#B

