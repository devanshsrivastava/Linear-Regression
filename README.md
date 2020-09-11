# Linear-Regression
We will use Linear Regression to predict price for house of certain area

How to check which linear line is the best solution

## Cost Function

* In mathematics, the character that looks like weird E is called summation (Greek sigma). It is the sum of a sequence of numbers, from i=1 to n. Let’s imagine this like an array of points, where we go through all the points, from the first (i=1) to the last (i=n)

* For each point, we take the y-coordinate of the point, and the y’-coordinate. The y-coordinate is our purple dot. The y’ point sits on the line we created. We subtract the y-coordinate value from the y’-coordinate value, and calculate the square of the result

* The third part is to take the sum of all the (y-y’)² values, and divide it by n, which will give the mean

### Our goal is to minimize this mean, which will provide us with the best line that goes through all the points


