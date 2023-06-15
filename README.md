Double-Loop.jmproj.R
johnm
2023-04-13
# Mindanao State University
# General Santos City
# Mathematics Department
# April 4, 2023
#
# Basic Programming in R
# Submitted by: John Michael H. Macawili
# Submitted to: Prof. Carlito Daarol
# Example1: Count number of iterations
count = 0
for (i in 1:5){
for (j in 4:9){
count = count +1
}
}
paste0("The count variable was updated for " , count, " times. ")
## [1] "The count variable was updated for 30 times. "
# Example 2: Double for loop Count number of iterations
count = 0
for (i in 20:26){
for (j in 15:30){
count = count +1
print(paste0(count, ": i= ",i, " | j= ", j , " | hello babes"))
}
}
## [1] "1: i= 20 | j= 15 | hello babes"
## [1] "2: i= 20 | j= 16 | hello babes"
## [1] "3: i= 20 | j= 17 | hello babes"
## [1] "4: i= 20 | j= 18 | hello babes"
## [1] "5: i= 20 | j= 19 | hello babes"
## [1] "6: i= 20 | j= 20 | hello babes"
## [1] "7: i= 20 | j= 21 | hello babes"
## [1] "8: i= 20 | j= 22 | hello babes"
## [1] "9: i= 20 | j= 23 | hello babes"
## [1] "10: i= 20 | j= 24 | hello babes"
## [1] "11: i= 20 | j= 25 | hello babes"
## [1] "12: i= 20 | j= 26 | hello babes"
## [1] "13: i= 20 | j= 27 | hello babes"
## [1] "14: i= 20 | j= 28 | hello babes"
## [1] "15: i= 20 | j= 29 | hello babes"
## [1] "16: i= 20 | j= 30 | hello babes"
## [1] "17: i= 21 | j= 15 | hello babes"
## [1] "18: i= 21 | j= 16 | hello babes"
## [1] "19: i= 21 | j= 17 | hello babes"
## [1] "20: i= 21 | j= 18 | hello babes"
## [1] "21: i= 21 | j= 19 | hello babes"
## [1] "22: i= 21 | j= 20 | hello babes"
## [1] "23: i= 21 | j= 21 | hello babes"
## [1] "24: i= 21 | j= 22 | hello babes"
## [1] "25: i= 21 | j= 23 | hello babes"
## [1] "26: i= 21 | j= 24 | hello babes"
## [1] "27: i= 21 | j= 25 | hello babes"
## [1] "28: i= 21 | j= 26 | hello babes"
## [1] "29: i= 21 | j= 27 | hello babes"
## [1] "30: i= 21 | j= 28 | hello babes"
## [1] "31: i= 21 | j= 29 | hello babes"
## [1] "32: i= 21 | j= 30 | hello babes"
## [1] "33: i= 22 | j= 15 | hello babes"
## [1] "34: i= 22 | j= 16 | hello babes"
## [1] "35: i= 22 | j= 17 | hello babes"
## [1] "36: i= 22 | j= 18 | hello babes"
## [1] "37: i= 22 | j= 19 | hello babes"
## [1] "38: i= 22 | j= 20 | hello babes"
## [1] "39: i= 22 | j= 21 | hello babes"
## [1] "40: i= 22 | j= 22 | hello babes"
## [1] "41: i= 22 | j= 23 | hello babes"
## [1] "42: i= 22 | j= 24 | hello babes"
## [1] "43: i= 22 | j= 25 | hello babes"
## [1] "44: i= 22 | j= 26 | hello babes"
## [1] "45: i= 22 | j= 27 | hello babes"
## [1] "46: i= 22 | j= 28 | hello babes"
## [1] "47: i= 22 | j= 29 | hello babes"
## [1] "48: i= 22 | j= 30 | hello babes"
## [1] "49: i= 23 | j= 15 | hello babes"
## [1] "50: i= 23 | j= 16 | hello babes"
## [1] "51: i= 23 | j= 17 | hello babes"
## [1] "52: i= 23 | j= 18 | hello babes"
## [1] "53: i= 23 | j= 19 | hello babes"
## [1] "54: i= 23 | j= 20 | hello babes"
## [1] "55: i= 23 | j= 21 | hello babes"
## [1] "56: i= 23 | j= 22 | hello babes"
## [1] "57: i= 23 | j= 23 | hello babes"
## [1] "58: i= 23 | j= 24 | hello babes"
## [1] "59: i= 23 | j= 25 | hello babes"
## [1] "60: i= 23 | j= 26 | hello babes"
## [1] "61: i= 23 | j= 27 | hello babes"
## [1] "62: i= 23 | j= 28 | hello babes"
## [1] "63: i= 23 | j= 29 | hello babes"
## [1] "64: i= 23 | j= 30 | hello babes"
## [1] "65: i= 24 | j= 15 | hello babes"
## [1] "66: i= 24 | j= 16 | hello babes"
## [1] "67: i= 24 | j= 17 | hello babes"
## [1] "68: i= 24 | j= 18 | hello babes"
## [1] "69: i= 24 | j= 19 | hello babes"
## [1] "70: i= 24 | j= 20 | hello babes"
## [1] "71: i= 24 | j= 21 | hello babes"
## [1] "72: i= 24 | j= 22 | hello babes"
## [1] "73: i= 24 | j= 23 | hello babes"
## [1] "74: i= 24 | j= 24 | hello babes"
## [1] "75: i= 24 | j= 25 | hello babes"
## [1] "76: i= 24 | j= 26 | hello babes"
## [1] "77: i= 24 | j= 27 | hello babes"
## [1] "78: i= 24 | j= 28 | hello babes"
## [1] "79: i= 24 | j= 29 | hello babes"
## [1] "80: i= 24 | j= 30 | hello babes"
## [1] "81: i= 25 | j= 15 | hello babes"
## [1] "82: i= 25 | j= 16 | hello babes"
## [1] "83: i= 25 | j= 17 | hello babes"
## [1] "84: i= 25 | j= 18 | hello babes"
## [1] "85: i= 25 | j= 19 | hello babes"
## [1] "86: i= 25 | j= 20 | hello babes"
## [1] "87: i= 25 | j= 21 | hello babes"
## [1] "88: i= 25 | j= 22 | hello babes"
## [1] "89: i= 25 | j= 23 | hello babes"
## [1] "90: i= 25 | j= 24 | hello babes"
## [1] "91: i= 25 | j= 25 | hello babes"
## [1] "92: i= 25 | j= 26 | hello babes"
## [1] "93: i= 25 | j= 27 | hello babes"
## [1] "94: i= 25 | j= 28 | hello babes"
## [1] "95: i= 25 | j= 29 | hello babes"
## [1] "96: i= 25 | j= 30 | hello babes"
## [1] "97: i= 26 | j= 15 | hello babes"
## [1] "98: i= 26 | j= 16 | hello babes"
## [1] "99: i= 26 | j= 17 | hello babes"
## [1] "100: i= 26 | j= 18 | hello babes"
## [1] "101: i= 26 | j= 19 | hello babes"
## [1] "102: i= 26 | j= 20 | hello babes"
## [1] "103: i= 26 | j= 21 | hello babes"
## [1] "104: i= 26 | j= 22 | hello babes"
## [1] "105: i= 26 | j= 23 | hello babes"
## [1] "106: i= 26 | j= 24 | hello babes"
## [1] "107: i= 26 | j= 25 | hello babes"
## [1] "108: i= 26 | j= 26 | hello babes"
## [1] "109: i= 26 | j= 27 | hello babes"
## [1] "110: i= 26 | j= 28 | hello babes"
## [1] "111: i= 26 | j= 29 | hello babes"
## [1] "112: i= 26 | j= 30 | hello babes"
paste0("The double loop displayed " , count, " lines of hello babes. ")
## [1] "The double loop displayed 112 lines of hello babes. "
# Example3: Double for loop Count number of iterations
count = 0
for (i in 20:26){
for (j in 15:30){
count = count +1
if (count < 10) {
print(paste0(count, ": i= ",i, " | j= ", j , " | hello babes"))
} else if (count < 100) {
print(paste0(count, ": i= ",i, " | j= ", j , " | hello babes"))
} else {
print(paste0(count, ": i= ",i, " | j= ", j , " | hello babes"))
}
}
}
## [1] "1: i= 20 | j= 15 | hello babes"
## [1] "2: i= 20 | j= 16 | hello babes"
## [1] "3: i= 20 | j= 17 | hello babes"
## [1] "4: i= 20 | j= 18 | hello babes"
## [1] "5: i= 20 | j= 19 | hello babes"
## [1] "6: i= 20 | j= 20 | hello babes"
## [1] "7: i= 20 | j= 21 | hello babes"
## [1] "8: i= 20 | j= 22 | hello babes"
## [1] "9: i= 20 | j= 23 | hello babes"
## [1] "10: i= 20 | j= 24 | hello babes"
## [1] "11: i= 20 | j= 25 | hello babes"
## [1] "12: i= 20 | j= 26 | hello babes"
## [1] "13: i= 20 | j= 27 | hello babes"
## [1] "14: i= 20 | j= 28 | hello babes"
## [1] "15: i= 20 | j= 29 | hello babes"
## [1] "16: i= 20 | j= 30 | hello babes"
## [1] "17: i= 21 | j= 15 | hello babes"
## [1] "18: i= 21 | j= 16 | hello babes"
## [1] "19: i= 21 | j= 17 | hello babes"
## [1] "20: i= 21 | j= 18 | hello babes"
## [1] "21: i= 21 | j= 19 | hello babes"
## [1] "22: i= 21 | j= 20 | hello babes"
## [1] "23: i= 21 | j= 21 | hello babes"
## [1] "24: i= 21 | j= 22 | hello babes"
## [1] "25: i= 21 | j= 23 | hello babes"
## [1] "26: i= 21 | j= 24 | hello babes"
## [1] "27: i= 21 | j= 25 | hello babes"
## [1] "28: i= 21 | j= 26 | hello babes"
## [1] "29: i= 21 | j= 27 | hello babes"
## [1] "30: i= 21 | j= 28 | hello babes"
## [1] "31: i= 21 | j= 29 | hello babes"
## [1] "32: i= 21 | j= 30 | hello babes"
## [1] "33: i= 22 | j= 15 | hello babes"
## [1] "34: i= 22 | j= 16 | hello babes"
## [1] "35: i= 22 | j= 17 | hello babes"
## [1] "36: i= 22 | j= 18 | hello babes"
## [1] "37: i= 22 | j= 19 | hello babes"
## [1] "38: i= 22 | j= 20 | hello babes"
## [1] "39: i= 22 | j= 21 | hello babes"
## [1] "40: i= 22 | j= 22 | hello babes"
## [1] "41: i= 22 | j= 23 | hello babes"
## [1] "42: i= 22 | j= 24 | hello babes"
## [1] "43: i= 22 | j= 25 | hello babes"
## [1] "44: i= 22 | j= 26 | hello babes"
## [1] "45: i= 22 | j= 27 | hello babes"
## [1] "46: i= 22 | j= 28 | hello babes"
## [1] "47: i= 22 | j= 29 | hello babes"
## [1] "48: i= 22 | j= 30 | hello babes"
## [1] "49: i= 23 | j= 15 | hello babes"
## [1] "50: i= 23 | j= 16 | hello babes"
## [1] "51: i= 23 | j= 17 | hello babes"
## [1] "52: i= 23 | j= 18 | hello babes"
## [1] "53: i= 23 | j= 19 | hello babes"
## [1] "54: i= 23 | j= 20 | hello babes"
## [1] "55: i= 23 | j= 21 | hello babes"
## [1] "56: i= 23 | j= 22 | hello babes"
## [1] "57: i= 23 | j= 23 | hello babes"
## [1] "58: i= 23 | j= 24 | hello babes"
## [1] "59: i= 23 | j= 25 | hello babes"
## [1] "60: i= 23 | j= 26 | hello babes"
## [1] "61: i= 23 | j= 27 | hello babes"
## [1] "62: i= 23 | j= 28 | hello babes"
## [1] "63: i= 23 | j= 29 | hello babes"
## [1] "64: i= 23 | j= 30 | hello babes"
## [1] "65: i= 24 | j= 15 | hello babes"
## [1] "66: i= 24 | j= 16 | hello babes"
## [1] "67: i= 24 | j= 17 | hello babes"
## [1] "68: i= 24 | j= 18 | hello babes"
## [1] "69: i= 24 | j= 19 | hello babes"
## [1] "70: i= 24 | j= 20 | hello babes"
## [1] "71: i= 24 | j= 21 | hello babes"
## [1] "72: i= 24 | j= 22 | hello babes"
## [1] "73: i= 24 | j= 23 | hello babes"
## [1] "74: i= 24 | j= 24 | hello babes"
## [1] "75: i= 24 | j= 25 | hello babes"
## [1] "76: i= 24 | j= 26 | hello babes"
## [1] "77: i= 24 | j= 27 | hello babes"
## [1] "78: i= 24 | j= 28 | hello babes"
## [1] "79: i= 24 | j= 29 | hello babes"
## [1] "80: i= 24 | j= 30 | hello babes"
## [1] "81: i= 25 | j= 15 | hello babes"
## [1] "82: i= 25 | j= 16 | hello babes"
## [1] "83: i= 25 | j= 17 | hello babes"
## [1] "84: i= 25 | j= 18 | hello babes"
## [1] "85: i= 25 | j= 19 | hello babes"
## [1] "86: i= 25 | j= 20 | hello babes"
## [1] "87: i= 25 | j= 21 | hello babes"
## [1] "88: i= 25 | j= 22 | hello babes"
## [1] "89: i= 25 | j= 23 | hello babes"
## [1] "90: i= 25 | j= 24 | hello babes"
## [1] "91: i= 25 | j= 25 | hello babes"
## [1] "92: i= 25 | j= 26 | hello babes"
## [1] "93: i= 25 | j= 27 | hello babes"
## [1] "94: i= 25 | j= 28 | hello babes"
## [1] "95: i= 25 | j= 29 | hello babes"
## [1] "96: i= 25 | j= 30 | hello babes"
## [1] "97: i= 26 | j= 15 | hello babes"
## [1] "98: i= 26 | j= 16 | hello babes"
## [1] "99: i= 26 | j= 17 | hello babes"
## [1] "100: i= 26 | j= 18 | hello babes"
## [1] "101: i= 26 | j= 19 | hello babes"
## [1] "102: i= 26 | j= 20 | hello babes"
## [1] "103: i= 26 | j= 21 | hello babes"
## [1] "104: i= 26 | j= 22 | hello babes"
## [1] "105: i= 26 | j= 23 | hello babes"
## [1] "106: i= 26 | j= 24 | hello babes"
## [1] "107: i= 26 | j= 25 | hello babes"
## [1] "108: i= 26 | j= 26 | hello babes"
## [1] "109: i= 26 | j= 27 | hello babes"
## [1] "110: i= 26 | j= 28 | hello babes"
## [1] "111: i= 26 | j= 29 | hello babes"
## [1] "112: i= 26 | j= 30 | hello babes"
paste0("The double loop displayed " , count, " lines of hello babes. ")
## [1] "The double loop displayed 112 lines of hello babes. "
# Example 4: Back to the problem mentioned in the limitation of single for loops.
# what is the sum of the first N integers? 1 + 2 + 3 + ... + N + ...
# What is the sum of terms 1/2 + 1/4 + 1/8 + 1/16 + 1/32 +....
# what is the sum of terms 1/2 + 1/3 + 1/4 + 1/5 + 1/6 + ...
# N is a numeric array
# N = 10000, 20000, 30000, 40000, 50000, 60000, 70000, 80000, 90000, 100000, 30000
0,600000, 1000000, 2000000
# Solution
N <- c(10000, 20000, 30000, 40000, 50000, 60000, 70000, 80000, 90000, 100000,
300000, 600000, 1000000, 2000000)
# declare empty arrays as container of the sum of terms
sum1r <- NULL
sum2r <- NULL
sum3r <- NULL
for (j in 1:length(N)){
# initialize sum accumulators
sum1 = 0
sum2 = 0
sum3 = 0
for (i in 1:N[j]){
sum1 = sum1 + i # this will handle question number 1
sum2 = sum2 + (1/2)^i # this will handle question number 2
sum3 = sum3 + 1/i # this will handle question number 3
}
# fill up the summation containers
sum1r[j] <- sum1
sum2r[j] <- sum2
sum3r[j] <- sum3
}
# display results
options("scipen"=100)
result <- data.frame(cbind(sum1r,sum2r,sum3r))
rownames(result) <- paste0("at N = ",N)
# change column headers to more informative one
colnames(result) <- c("Sum of 1+2+3+...+N", "Sumof 1/2+1/4+1/8+...", "Sum of
1+1/2+1/3+...")
result
## Sum of 1+2+3+...+N Sumof 1/2+1/4+1/8+... Sum of \n1+1/2+1/3+...
## at N = 10000 50005000 1 9.787606
## at N = 20000 200010000 1 10.480728
## at N = 30000 450015000 1 10.886185
## at N = 40000 800020000 1 11.173863
## at N = 50000 1250025000 1 11.397004
## at N = 60000 1800030000 1 11.579324
## at N = 70000 2450035000 1 11.733473
## at N = 80000 3200040000 1 11.867004
## at N = 90000 4050045000 1 11.984786
## at N = 100000 5000050000 1 12.090146
## at N = 300000 45000150000 1 13.188755
## at N = 600000 180000300000 1 13.881901
## at N = 1000000 500000500000 1 14.392727
## at N = 2000000 2000001000000 1 15.085874
# interpretation
# at increasing number of terms
# the sum of the first series of terms increases very fast
# the sum of the second series of terms always equal to 1, regardless of the value
of N
# the sum of the third series of terms increases slowly. The sum increases as N in
creases
# Conclusion
# the first series is an example of a divergent series as N --> infinity
# the second series is an example of a convergent series as N --> infinity since t
he sum is always the same
# the third series is an example of a divergent series as N --> infinity (though s
lowly)
# New Topic: Vector Operations versus Loops in R
# Example 1: Computation of the correlation coefficient between two variables usin
g vector operations
datax <-
c(0.9913345,1.0027839,0.9968691,1.0161024,1.0065136,1.0297600,0.9659482,1.018586
2,
1.0097508,1.0202250,1.0238810,0.9801332,1.0099076,0.9817378,0.9963364,1.021932
8,
1.0059981,0.9722559,0.9926882,1.0267477,0.9945208,1.0177237,0.9808133,1.014341
5,
1.0074551,1.0002456,0.9937849,1.0453198,0.9826864,1.0082201)
datay <-
c(0.9964580,1.0181583,0.9895960,1.0176893,1.0009406,1.0226642,0.9558703,1.011187
3,
1.0158226,1.0187873,
1.0230155,0.9670798,1.0056325,0.9734213,1.0020038,1.0126897,1.0032060,0.978340
6,
0.9948068,1.0246172,
0.9939589,1.0168364,0.9806948,1.0168963,1.0137382,0.9938570,0.9844847,1.048781
8,
0.9784052,1.0037628 )
xlen <- length(datax)
# the following results can be obtained directly
(sumx = sum(datax))
## [1] 30.1146
(sumy = sum(datay))
## [1] 30.0634
(sumxy = sum(datax%*%datay))
## [1] 30.18842
(sumxsquare = sum(datax^2))
## [1] 30.2394
(sumysquare = sum(datay^2))
## [1] 30.13869
(squaresumx = sumx^2)
## [1] 906.8893
(squaresumy = sumy^2)
## [1] 903.8082
# solve the numerator
nume <- xlen * sumxy - sumx * sumy
# solve the denominator
num2a <- xlen * sumxsquare - squaresumx
num2b <- xlen * sumysquare - squaresumy
deno <- sqrt(num2a*num2b)
Pearsonr <- nume/deno
Pearsonr
## [1] 0.9501044
# Question: What is the point of using for loops?
# Answer: There are situations where vector operation is not applicable
# Example 2: Finding limit of a function Using 2 Sided Limits
# what is the limit of the function f(x) = 2(x^2-x)/(x-1) as x approaches 1 from t
he right?
# What is the limit of the function f(x) = 2(x^-x)/(x-1) as x approaches 1 from th
e left?
# Note: The existence of a limit of a function exists provided we can measure the
value
# of the function at several points and measure how small is the difference
# The critical point here is x = 1 since at that value, f(x) becomes undefined bec
ause the denominator becomes 0
# We will investigate the behavior of the function at values closer to 1 from both
the
# left and right side of 1
#STEP1: we assume values of x from 3 to 1.001 at an increment of -0.001
x_fromright <- seq(from = 3, to = 1.0001,by = -0.0001)
# then we compute the corresponding value of the function f(x)
fx_atxfromright = 2*(x_fromright^2 - x_fromright)/(x_fromright-1)
#STEP2: we assume values of x from -1 to 0.99 at an increment of 0.001
x_fromleft <- seq(from = -1, to = 0.9999, by = 0.0001)
# then we compute the corresponding value of the function f(x)
fx_atxfromleft = 2*(x_fromleft^2-x_fromleft)/(x_fromleft-1)
# to compare results, we must arrange the values using a dataframe (table)
result <- data.frame(cbind(x_fromleft," ",fx_atxfromleft,x_fromright," ",
fx_atxfromright))
colnames(result) <- c("x approaces 1 from left "," ", " Value of f", " x
approaches 1 from right", " "," Value of f at x right")
# extract last 10 rows and evaluate the pattern
x<- nrow(result)-10
y <- nrow(result)
(last15rows <- result[x:y,])
## x approaces 1 from left Value of f x \napproaches 1 from right
## 19990 0.9989 1.99780000000005 1.0011
## 19991 0.999 1.99799999999994 1.001
## 19992 0.9991 1.99820000000008 1.0009
## 19993 0.9992 1.99840000000001 1.0008
## 19994 0.9993 1.99859999999994 1.0007
## 19995 0.9994 1.99879999999989 1.0006
## 19996 0.9995 1.99899999999986 1.0005
## 19997 0.9996 1.99919999999987 1.0004
## 19998 0.9997 1.99939999999995 1.0003
## 19999 0.9998 1.99960000000021 1.0002
## 20000 0.9999 1.999799999999 1.0001
## Value of f at x right
## 19990 2.00219999999995
## 19991 2.00199999999984
## 19992 2.00179999999992
## 19993 2.00160000000027
## 19994 2.00139999999974
## 19995 2.00120000000011
## 19996 2.00100000000014
## 19997 2.00079999999958
## 19998 2.00059999999931
## 19999 2.00039999999979
## 20000 2.00019999999878
# at the bottom of the dataframe you will see that as x approaches 1 from the lef
t, f(x) approaches 1.99979999
# and as x approaches 1 from the right, f(x) approaches 2.00019999
# and we can therefore conclude that the limit f(x) as x approaches 1 is equal to
2.
# since the two sided limits are the same
# Example 3: Finding limit of another function
# what is the limit of the function f(x) = |2(x^2-x)|/(x-1) as x approaches 1 from
the right?
# What is the limit of the function f(x) = |2(x^-x)|/(x-1) as x approaches 1 from
the left?
# Note: The existence of a limit of a function exists provided we can measure the
value
# of the function at several points and measure how small is the difference
# The critical point here is x = 1 since at that value, f(x) becomes undefined sin
ce the denominator becomes 0
# We will investigate the behavior of the function at values closer to 1 from both
the
# left and right side of 1
#STEP1: we assume values of x from 3 to 1.001 at an increment of -0.001
x_fromright <- seq(from = 3, to = 1.0001,by = -0.0001)
# then we compute the corresponding value of the function f(x)
fx_atxfromright = abs(2*(x_fromright^2 - x_fromright))/(x_fromright-1)
#STEP2: we assume values of x from -1 to 0.99 at an increment of 0.001
x_fromleft <- seq(from = -1, to = 0.9999, by = 0.0001)
# then we compute the corresponding value of the function f(x)
fx_atxfromleft = abs(2*(x_fromleft^2-x_fromleft))/(x_fromleft-1)
# to compare results, we must arrange the values using a dataframe (table)
result <- data.frame(cbind(x_fromleft," ",fx_atxfromleft,x_fromright," ",
fx_atxfromright))
colnames(result) <- c("x approaces 1 from left "," ", " Value of f", " x
approaches 1 from right", " "," Value of f at x right")
# extract last 10 rows
x<- nrow(result)-10
y <- nrow(result)
(last15rows <- result[x:y,])
## x approaces 1 from left Value of f x \napproaches 1 from right
## 19990 0.9989 -1.99780000000005 1.0011
## 19991 0.999 -1.99799999999994 1.001
## 19992 0.9991 -1.99820000000008 1.0009
## 19993 0.9992 -1.99840000000001 1.0008
## 19994 0.9993 -1.99859999999994 1.0007
## 19995 0.9994 -1.99879999999989 1.0006
## 19996 0.9995 -1.99899999999986 1.0005
## 19997 0.9996 -1.99919999999987 1.0004
## 19998 0.9997 -1.99939999999995 1.0003
## 19999 0.9998 -1.99960000000021 1.0002
## 20000 0.9999 -1.999799999999 1.0001
## Value of f at x right
## 19990 2.00219999999995
## 19991 2.00199999999984
## 19992 2.00179999999992
## 19993 2.00160000000027
## 19994 2.00139999999974
## 19995 2.00120000000011
## 19996 2.00100000000014
## 19997 2.00079999999958
## 19998 2.00059999999931
## 19999 2.00039999999979
## 20000 2.00019999999878
# at the bottom of the dataframe you will that as x approaches 1 from the left, f
(x) approaches -1.99979999
# and as x approaches 1 from the right, f(x) approaches 2.00019999
# and we can therefore conclude that the limit f(x) as x approaches 1 does not exi
st
# as the two sided limits are not the same.
# Example 4: Back to computing correlations again
# load the dataset and get some informations
head(mtcars)
## mpg cyl disp hp drat wt qsec vs am gear carb
## Mazda RX4 21.0 6 160 110 3.90 2.620 16.46 0 1 4 4
## Mazda RX4 Wag 21.0 6 160 110 3.90 2.875 17.02 0 1 4 4
## Datsun 710 22.8 4 108 93 3.85 2.320 18.61 1 1 4 1
## Hornet 4 Drive 21.4 6 258 110 3.08 3.215 19.44 1 0 3 1
## Hornet Sportabout 18.7 8 360 175 3.15 3.440 17.02 0 0 3 2
## Valiant 18.1 6 225 105 2.76 3.460 20.22 1 0 3 1
# display first 6 rows
dim(mtcars)
## [1] 32 11
dim(mtcars)
## [1] 32 11
names(mtcars)
## [1] "mpg" "cyl" "disp" "hp" "drat" "wt" "qsec" "vs" "am" "gear"
## [11] "carb"
summary(mtcars)
## mpg cyl disp hp
## Min. :10.40 Min. :4.000 Min. : 71.1 Min. : 52.0
## 1st Qu.:15.43 1st Qu.:4.000 1st Qu.:120.8 1st Qu.: 96.5
## Median :19.20 Median :6.000 Median :196.3 Median :123.0
## Mean :20.09 Mean :6.188 Mean :230.7 Mean :146.7
## 3rd Qu.:22.80 3rd Qu.:8.000 3rd Qu.:326.0 3rd Qu.:180.0
## Max. :33.90 Max. :8.000 Max. :472.0 Max. :335.0
## drat wt qsec vs
## Min. :2.760 Min. :1.513 Min. :14.50 Min. :0.0000
## 1st Qu.:3.080 1st Qu.:2.581 1st Qu.:16.89 1st Qu.:0.0000
## Median :3.695 Median :3.325 Median :17.71 Median :0.0000
## Mean :3.597 Mean :3.217 Mean :17.85 Mean :0.4375
## 3rd Qu.:3.920 3rd Qu.:3.610 3rd Qu.:18.90 3rd Qu.:1.0000
## Max. :4.930 Max. :5.424 Max. :22.90 Max. :1.0000
## am gear carb
## Min. :0.0000 Min. :3.000 Min. :1.000
## 1st Qu.:0.0000 1st Qu.:3.000 1st Qu.:2.000
## Median :0.0000 Median :4.000 Median :2.000
## Mean :0.4062 Mean :3.688 Mean :2.812
## 3rd Qu.:1.0000 3rd Qu.:4.000 3rd Qu.:4.000
## Max. :1.0000 Max. :5.000 Max. :8.000
str(mtcars)
## 'data.frame': 32 obs. of 11 variables:
## $ mpg : num 21 21 22.8 21.4 18.7 18.1 14.3 24.4 22.8 19.2 ...
## $ cyl : num 6 6 4 6 8 6 8 4 4 6 ...
## $ disp: num 160 160 108 258 360 ...
## $ hp : num 110 110 93 110 175 105 245 62 95 123 ...
## $ drat: num 3.9 3.9 3.85 3.08 3.15 2.76 3.21 3.69 3.92 3.92 ...
## $ wt : num 2.62 2.88 2.32 3.21 3.44 ...
## $ qsec: num 16.5 17 18.6 19.4 17 ...
## $ vs : num 0 0 1 1 0 1 0 1 1 1 ...
## $ am : num 1 1 1 0 0 0 0 0 0 0 ...
## $ gear: num 4 4 4 3 3 3 3 4 4 4 ...
## $ carb: num 4 4 1 1 2 1 4 2 2 4 ...
# all variables are numeric
# define subsets
Set1 <- mtcars[,1:5]
Set2 <- mtcars[,6:10]
cor(Set1,Set2)
## wt qsec vs am gear
## mpg -0.8676594 0.41868403 0.6640389 0.5998324 0.4802848
## cyl 0.7824958 -0.59124207 -0.8108118 -0.5226070 -0.4926866
## disp 0.8879799 -0.43369788 -0.7104159 -0.5912270 -0.5555692
## hp 0.6587479 -0.70822339 -0.7230967 -0.2432043 -0.1257043
## drat -0.7124406 0.09120476 0.4402785 0.7127111 0.6996101
pairwiseCor <- function(depvar,indepvar){
# establish counter to count how many pairs are possible
counter =0
for(i in 1:length(depvar)){
for (j in 1:length(indepvar)){
counter = counter +1
}
}
# define holder of correlation results
df <- data.frame(VarX =rep(0,counter), VarY=rep(0,counter),
AbsCor=rep(0,counter), Cor=rep(0,counter), PValue=rep(0,counte
r),
Assessment=rep(0,counter))
# fill in the dataframe with details
k=0
for(i in 1:length(depvar)){
for (j in 1:length(indepvar)){
k=k+1
df[k,1] <- names(depvar)[i]
df[k,2] <- names(indepvar)[j]
df[k,3] <- round(abs(cor(depvar[,i],indepvar[,j])),2)
df[k,4] <- round(cor(depvar[,i],indepvar[,j]),2)
tt <- cor.test(depvar[,i],indepvar[,j],method="spearman")
df[k,5] <- round(tt$p.value,2)
df[k,6] <- ifelse((df[k,5] < 0.05), "<0.05 (sig)", "> 0.05 (not sig")
}
}
return(df)
}
pairwiseCor(Set1,Set2)
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## VarX VarY AbsCor Cor PValue Assessment
## 1 mpg wt 0.87 -0.87 0.00 <0.05 (sig)
## 2 mpg qsec 0.42 0.42 0.01 <0.05 (sig)
## 3 mpg vs 0.66 0.66 0.00 <0.05 (sig)
## 4 mpg am 0.60 0.60 0.00 <0.05 (sig)
## 5 mpg gear 0.48 0.48 0.00 <0.05 (sig)
## 6 cyl wt 0.78 0.78 0.00 <0.05 (sig)
## 7 cyl qsec 0.59 -0.59 0.00 <0.05 (sig)
## 8 cyl vs 0.81 -0.81 0.00 <0.05 (sig)
## 9 cyl am 0.52 -0.52 0.00 <0.05 (sig)
## 10 cyl gear 0.49 -0.49 0.00 <0.05 (sig)
## 11 disp wt 0.89 0.89 0.00 <0.05 (sig)
## 12 disp qsec 0.43 -0.43 0.01 <0.05 (sig)
## 13 disp vs 0.71 -0.71 0.00 <0.05 (sig)
## 14 disp am 0.59 -0.59 0.00 <0.05 (sig)
## 15 disp gear 0.56 -0.56 0.00 <0.05 (sig)
## 16 hp wt 0.66 0.66 0.00 <0.05 (sig)
## 17 hp qsec 0.71 -0.71 0.00 <0.05 (sig)
## 18 hp vs 0.72 -0.72 0.00 <0.05 (sig)
## 19 hp am 0.24 -0.24 0.04 <0.05 (sig)
## 20 hp gear 0.13 -0.13 0.06 > 0.05 (not sig
## 21 drat wt 0.71 -0.71 0.00 <0.05 (sig)
## 22 drat qsec 0.09 0.09 0.62 > 0.05 (not sig
## 23 drat vs 0.44 0.44 0.01 <0.05 (sig)
## 24 drat am 0.71 0.71 0.00 <0.05 (sig)
## 25 drat gear 0.70 0.70 0.00 <0.05 (sig)
# we can also process pairwise correlation for the following
Set1 = mtcars
Set2 = mtcars
pairwiseCor(Set1,Set2)
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## Warning in cor.test.default(depvar[, i], indepvar[, j], method = "spearman"):
## Cannot compute exact p-value with ties
## VarX VarY AbsCor Cor PValue Assessment
## 1 mpg mpg 1.00 1.00 0.00 <0.05 (sig)
## 2 mpg cyl 0.85 -0.85 0.00 <0.05 (sig)
## 3 mpg disp 0.85 -0.85 0.00 <0.05 (sig)
## 4 mpg hp 0.78 -0.78 0.00 <0.05 (sig)
## 5 mpg drat 0.68 0.68 0.00 <0.05 (sig)
## 6 mpg wt 0.87 -0.87 0.00 <0.05 (sig)
## 7 mpg qsec 0.42 0.42 0.01 <0.05 (sig)
## 8 mpg vs 0.66 0.66 0.00 <0.05 (sig)
## 9 mpg am 0.60 0.60 0.00 <0.05 (sig)
## 10 mpg gear 0.48 0.48 0.00 <0.05 (sig)
## 11 mpg carb 0.55 -0.55 0.00 <0.05 (sig)
## 12 cyl mpg 0.85 -0.85 0.00 <0.05 (sig)
## 13 cyl cyl 1.00 1.00 0.00 <0.05 (sig)
## 14 cyl disp 0.90 0.90 0.00 <0.05 (sig)
## 15 cyl hp 0.83 0.83 0.00 <0.05 (sig)
## 16 cyl drat 0.70 -0.70 0.00 <0.05 (sig)
## 17 cyl wt 0.78 0.78 0.00 <0.05 (sig)
## 18 cyl qsec 0.59 -0.59 0.00 <0.05 (sig)
## 19 cyl vs 0.81 -0.81 0.00 <0.05 (sig)
## 20 cyl am 0.52 -0.52 0.00 <0.05 (sig)
## 21 cyl gear 0.49 -0.49 0.00 <0.05 (sig)
## 22 cyl carb 0.53 0.53 0.00 <0.05 (sig)
## 23 disp mpg 0.85 -0.85 0.00 <0.05 (sig)
## 24 disp cyl 0.90 0.90 0.00 <0.05 (sig)
## 25 disp disp 1.00 1.00 0.00 <0.05 (sig)
## 26 disp hp 0.79 0.79 0.00 <0.05 (sig)
## 27 disp drat 0.71 -0.71 0.00 <0.05 (sig)
## 28 disp wt 0.89 0.89 0.00 <0.05 (sig)
## 29 disp qsec 0.43 -0.43 0.01 <0.05 (sig)
## 30 disp vs 0.71 -0.71 0.00 <0.05 (sig)
## 31 disp am 0.59 -0.59 0.00 <0.05 (sig)
## 32 disp gear 0.56 -0.56 0.00 <0.05 (sig)
## 33 disp carb 0.39 0.39 0.00 <0.05 (sig)
## 34 hp mpg 0.78 -0.78 0.00 <0.05 (sig)
## 35 hp cyl 0.83 0.83 0.00 <0.05 (sig)
## 36 hp disp 0.79 0.79 0.00 <0.05 (sig)
## 37 hp hp 1.00 1.00 0.00 <0.05 (sig)
## 38 hp drat 0.45 -0.45 0.00 <0.05 (sig)
## 39 hp wt 0.66 0.66 0.00 <0.05 (sig)
## 40 hp qsec 0.71 -0.71 0.00 <0.05 (sig)
## 41 hp vs 0.72 -0.72 0.00 <0.05 (sig)
## 42 hp am 0.24 -0.24 0.04 <0.05 (sig)
## 43 hp gear 0.13 -0.13 0.06 > 0.05 (not sig
## 44 hp carb 0.75 0.75 0.00 <0.05 (sig)
## 45 drat mpg 0.68 0.68 0.00 <0.05 (sig)
## 46 drat cyl 0.70 -0.70 0.00 <0.05 (sig)
## 47 drat disp 0.71 -0.71 0.00 <0.05 (sig)
## 48 drat hp 0.45 -0.45 0.00 <0.05 (sig)
## 49 drat drat 1.00 1.00 0.00 <0.05 (sig)
## 50 drat wt 0.71 -0.71 0.00 <0.05 (sig)
## 51 drat qsec 0.09 0.09 0.62 > 0.05 (not sig
## 52 drat vs 0.44 0.44 0.01 <0.05 (sig)
## 53 drat am 0.71 0.71 0.00 <0.05 (sig)
## 54 drat gear 0.70 0.70 0.00 <0.05 (sig)
## 55 drat carb 0.09 -0.09 0.49 > 0.05 (not sig
## 56 wt mpg 0.87 -0.87 0.00 <0.05 (sig)
## 57 wt cyl 0.78 0.78 0.00 <0.05 (sig)
## 58 wt disp 0.89 0.89 0.00 <0.05 (sig)
## 59 wt hp 0.66 0.66 0.00 <0.05 (sig)
## 60 wt drat 0.71 -0.71 0.00 <0.05 (sig)
## 61 wt wt 1.00 1.00 0.00 <0.05 (sig)
## 62 wt qsec 0.17 -0.17 0.21 > 0.05 (not sig
## 63 wt vs 0.55 -0.55 0.00 <0.05 (sig)
## 64 wt am 0.69 -0.69 0.00 <0.05 (sig)
## 65 wt gear 0.58 -0.58 0.00 <0.05 (sig)
## 66 wt carb 0.43 0.43 0.00 <0.05 (sig)
## 67 qsec mpg 0.42 0.42 0.01 <0.05 (sig)
## 68 qsec cyl 0.59 -0.59 0.00 <0.05 (sig)
## 69 qsec disp 0.43 -0.43 0.01 <0.05 (sig)
## 70 qsec hp 0.71 -0.71 0.00 <0.05 (sig)
## 71 qsec drat 0.09 0.09 0.62 > 0.05 (not sig
## 72 qsec wt 0.17 -0.17 0.21 > 0.05 (not sig
## 73 qsec qsec 1.00 1.00 0.00 <0.05 (sig)
## 74 qsec vs 0.74 0.74 0.00 <0.05 (sig)
## 75 qsec am 0.23 -0.23 0.26 > 0.05 (not sig
## 76 qsec gear 0.21 -0.21 0.42 > 0.05 (not sig
## 77 qsec carb 0.66 -0.66 0.00 <0.05 (sig)
## 78 vs mpg 0.66 0.66 0.00 <0.05 (sig)
## 79 vs cyl 0.81 -0.81 0.00 <0.05 (sig)
## 80 vs disp 0.71 -0.71 0.00 <0.05 (sig)
## 81 vs hp 0.72 -0.72 0.00 <0.05 (sig)
## 82 vs drat 0.44 0.44 0.01 <0.05 (sig)
## 83 vs wt 0.55 -0.55 0.00 <0.05 (sig)
## 84 vs qsec 0.74 0.74 0.00 <0.05 (sig)
## 85 vs vs 1.00 1.00 0.00 <0.05 (sig)
## 86 vs am 0.17 0.17 0.36 > 0.05 (not sig
## 87 vs gear 0.21 0.21 0.12 > 0.05 (not sig
## 88 vs carb 0.57 -0.57 0.00 <0.05 (sig)
## 89 am mpg 0.60 0.60 0.00 <0.05 (sig)
## 90 am cyl 0.52 -0.52 0.00 <0.05 (sig)
## 91 am disp 0.59 -0.59 0.00 <0.05 (sig)
## 92 am hp 0.24 -0.24 0.04 <0.05 (sig)
## 93 am drat 0.71 0.71 0.00 <0.05 (sig)
## 94 am wt 0.69 -0.69 0.00 <0.05 (sig)
## 95 am qsec 0.23 -0.23 0.26 > 0.05 (not sig
## 96 am vs 0.17 0.17 0.36 > 0.05 (not sig
## 97 am am 1.00 1.00 0.00 <0.05 (sig)
## 98 am gear 0.79 0.79 0.00 <0.05 (sig)
## 99 am carb 0.06 0.06 0.73 > 0.05 (not sig
## 100 gear mpg 0.48 0.48 0.00 <0.05 (sig)
## 101 gear cyl 0.49 -0.49 0.00 <0.05 (sig)
## 102 gear disp 0.56 -0.56 0.00 <0.05 (sig)
## 103 gear hp 0.13 -0.13 0.06 > 0.05 (not sig
## 104 gear drat 0.70 0.70 0.00 <0.05 (sig)
## 105 gear wt 0.58 -0.58 0.00 <0.05 (sig)
## 106 gear qsec 0.21 -0.21 0.42 > 0.05 (not sig
## 107 gear vs 0.21 0.21 0.12 > 0.05 (not sig
## 108 gear am 0.79 0.79 0.00 <0.05 (sig)
## 109 gear gear 1.00 1.00 0.00 <0.05 (sig)
## 110 gear carb 0.27 0.27 0.53 > 0.05 (not sig
## 111 carb mpg 0.55 -0.55 0.00 <0.05 (sig)
## 112 carb cyl 0.53 0.53 0.00 <0.05 (sig)
## 113 carb disp 0.39 0.39 0.00 <0.05 (sig)
## 114 carb hp 0.75 0.75 0.00 <0.05 (sig)
## 115 carb drat 0.09 -0.09 0.49 > 0.05 (not sig
## 116 carb wt 0.43 0.43 0.00 <0.05 (sig)
## 117 carb qsec 0.66 -0.66 0.00 <0.05 (sig)
## 118 carb vs 0.57 -0.57 0.00 <0.05 (sig)
## 119 carb am 0.06 0.06 0.73 > 0.05 (not sig
## 120 carb gear 0.27 0.27 0.53 > 0.05 (not sig
## 121 carb carb 1.00 1.00 0.00 <0.05 (sig)
summary(mtcars)
## mpg cyl disp hp
## Min. :10.40 Min. :4.000 Min. : 71.1 Min. : 52.0
## 1st Qu.:15.43 1st Qu.:4.000 1st Qu.:120.8 1st Qu.: 96.5
## Median :19.20 Median :6.000 Median :196.3 Median :123.0
## Mean :20.09 Mean :6.188 Mean :230.7 Mean :146.7
## 3rd Qu.:22.80 3rd Qu.:8.000 3rd Qu.:326.0 3rd Qu.:180.0
## Max. :33.90 Max. :8.000 Max. :472.0 Max. :335.0
## drat wt qsec vs
## Min. :2.760 Min. :1.513 Min. :14.50 Min. :0.0000
## 1st Qu.:3.080 1st Qu.:2.581 1st Qu.:16.89 1st Qu.:0.0000
## Median :3.695 Median :3.325 Median :17.71 Median :0.0000
## Mean :3.597 Mean :3.217 Mean :17.85 Mean :0.4375
## 3rd Qu.:3.920 3rd Qu.:3.610 3rd Qu.:18.90 3rd Qu.:1.0000
## Max. :4.930 Max. :5.424 Max. :22.90 Max. :1.0000
## am gear carb
## Min. :0.0000 Min. :3.000 Min. :1.000
## 1st Qu.:0.0000 1st Qu.:3.000 1st Qu.:2.000
## Median :0.0000 Median :4.000 Median :2.000
## Mean :0.4062 Mean :3.688 Mean :2.812
## 3rd Qu.:1.0000 3rd Qu.:4.000 3rd Qu.:4.000
## Max. :1.0000 Max. :5.000 Max. :8.000
