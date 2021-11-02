# C Programming Lab
Implementation using C in programming lab class when being Teacher Assistant.  
The problems are [here](http://134.208.3.66/problems?keyword=PR&page=1)  
  
## Problems and Description
* [Week2](Week2)
    * [week2-1](Week2/week2-1.c)
        * Description: A man walks X km in Y hours  in the same direction. What is the man's velocity in km/h for the journey?
        * Input: Input contain two number in a line and separate by a single space, first number stand for distance in km, second number stand for time in hour.
        * Output: A number stand for velocity in km/h, please rounded to six decimal places.
    * [week2-2](Week2/week2-2.c)
        * Description: Read a 4 digit number, reverse it and display it.
        * Input: A 4 digit number, first digit is not 0.
        * Output: A 4 digit number after reverse.
    * [week2-3](Week2/week2-3.c)
        * Description: Read in a number, round it down to an integer and display on screen.
        * Input: A number.
        * Output: Display the integer after round down.
    * [week2-4](Week2/week2-4.c)
        * Description: Please write a program allow user input two integer and print out the result of addition subtraction multiplication  division and modulo of two integer.
        * Input: Two integer separate by a single space.
        * Output: See sample output.
    * [week2-5](Week2/week2-5.c)
        * Description: Please write a program allow user input two floating point number and print out the result of addition, subtraction, multiplicationanddivision of two number.
        * Input: Two floating point number separate by a single space
        * Output: See sample output
    * [week2-6](Week2/week2-6.c)
        * Description: Gave you a number n, please find the maximum even number less than or equal to n.
        * Input: An positive integer n.
        * Output: An largest even number less than or equal to n.
* [Week3](Week3)
    * [week3-1](Week3/week3-1.c)
        * Description: Please input an integer, determine if the integer is odd or even.
        * Input: Just an integer.
        * Output: output "odd" if the integer is odd, "even" if the integer is even.
    * [week3-2](Week3/week3-2.c)
        * Description: Read in two integer m and n, determine if m is multiple of n.
        * Input: Input will be two integer m and n separate by a single space.
        * Output: Please reference the sample out
    * [week3-3](Week3/week3-3.c)
        * Description: We use two points to present a segment in one dimensional coordinates. Give you two segment, your job is to determine two segment are overlay or not.
        * Input: Input consist 4 integer, first two present segment 1, and follow two present segment 2.
        * Output: Print "overlay" if two segment overlay, "no overlay" if not.
    * [week3-4](Week3/week3-4.c)
        * Description: Three segment length a, b, c, c has maximum length, if a + b > c than these three segment can construct a triangle. If a * a + b * b = c * c it will be a "right triangle", if a * a + b * b > c * c it will be a "acute triangle", if a * a + b * b < c * c it will be a "obtuse triangle". Write a program to determine what kind of triangle it will be.
        * Input: Input consist three integer a, b, c, c will be the maximum value.
        * Output: 如果三個線段可以構成一個三角形，就輸出他是哪種三角形，如果是銳角三角形就輸出 "acute triangle" ，如果是鈍角三角形就輸出 "obtuse triangle" ，如果是直角三角形就輸出 "right triangle"。如果三個線段無法構成一個三角形則輸出 "can not construct"
* [Week4](Week4)
    * [week4-1](Week4/week4-1.c)
        * Description: Please write a program that can keep read in integer until 0, sum up all integer and print out the result.
        * Input: Input consist several integer until 0.
        * Output: sum of all integer.
    * [week4-2](Week4/week4-2.c)
        * Description: Please write a program read in an integer and print out all its factor.
        * Input: Input consist an positive integer.
        * Output: Print out all factors incremental ordering.
    * [week4-3](Week4/week4-3.c)
        * Description: Please write a program to determine if a number is prime or not.
        * Input: Input consist several test case. Every test case is just a integer. Input ended with 0.
        * Output: For every test case output "prime" if the input is a prime number, output "not a prime" if not.
    * [week4-4](Week4/week4-4.c)
        * Description: Please write a program, input a positive integer to represent the number of regular triangle layers, and print this triangle.
        * Input: A[1, 30] positive integer.
        * Output: Print this regular triangle.
    * [week4-5](Week4/week4-5.c)
        * Description: Please write a program for prime factorization.
        * Input: Input consist several test case. Every test case is just a integer. Input ended with 0.
        * Output: Please reference the sample output.
    * [week4-6](Week4/week4-6.c)
        * Description: Morse code is a character encoding scheme used in telecommunication that encodes text characters as standardized sequences of two different signal durations called dots and dashes or dits and dahs. Morse code is named for Samuel F. B. Morse, an inventor of the telegraph. Write a program allow user input a number and print out corresponding Morse code.
        * Input: Input is an integer number.
        * Output: Print out the corresponding Morse code.
    * [week4-7](Week4/week4-7.c)
        * Description: Given the square root of a positive integer N is between 0 and N, let the square root of N be x, a=0 is the lower bound, and b=N is the upper bound. Then there is the inequality a<=x<=b, square the inequality to get a*a<=x*x=N<=b*b, and let c = (a+b)/2 according to the root approximation through bisection, when square of c is greater than or equal to N, we update the upper bound and get a new inequality a<=x<=c, otherwise, we update the lower bound and get a new inequality c<=x<=b. The difference between the upper and lower bounds is called the error. Please design a program in which the user enters a positive integer and calculates the square root of the positive integer. Please be accurate to four decimal places.
        * Input: An integer n.
        * Output: Output the root of naccurate to four decimal places.
* [Week5](Week5)
    * [week5-1](Week5/week5-1.c)
        * Description: Please write a program to find the maximum and minimum number.
        * Input: Input consist multiple integer separate by a space.
        * Output: Output maximum number first and than minimum, separate them using a single space.
    * [week5-2](Week5/week5-2.c)
        * Description: Please write a program to find the greatest common divisor of  three number.
        * Input: Input consist several test case, each test case a line. For every test case there are three non-negative integer in it and separate by a space.
        * Output: For each test case output the result in one line.
    * [week5-3](Week5/week5-3.c)
        * Description: A mathmatician Goldbach's conjecture: any even number(larger than 2) can divide into two prime number’s sum.But some even numbers can divide into many pairs of two prime numbers’ sum. Example:10 =3+7, 10=5+5, 10 can divide into two pairs of two prime number.
        * Input: Input consist a positive even number n(4<=n<=32766).
        * Output: Print the value of how many pairs are this even number can be divided into.
    * [week5-4](Week5/week5-4.c)
        * Description: There is snail climbing on the wall from bottom, wall is 10 meter height. every day the snail climb up 4 meter, and slide down 3 meter at the night. In day 7 the snail climb up to the top of the wall. Please write a program, read in height of the wall, how many meter the snail climb up a day, how many meter the snail slide down at night, give the answer of which day the snail climb up to the top of the wall.
        * Input: Input consist three integer, first is height of the wall, second is meter of snail climb up a day, third is meter the snail slide down at night.
        * Output: Out a number represent in which day the snail will climb to top of the wall. Output -1 if the snail can never climb up the top.

## License
None License
