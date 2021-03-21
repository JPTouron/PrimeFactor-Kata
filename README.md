## Source:

http://butunclebob.com/ArticleS.UncleBob.ThePrimeFactorsKata

## Bob Martin's problem statement

Although quite short, this kata is fascinating in the way it shows how ‘if’ statements
become ‘while’ statements as the number of test cases increase.  It’s also a
wonderful example of how algorithms sometimes become simpler as they become
more general.

I stumbled upon this little kata one evening when my son was in 7th grade.  He
had just discovered that all numbers can be broken down into a product of primes
and was interested in exploring this further.  So I wrote a little ruby program, test-
first, and was stunned by how the algorithm evolved.

I have done this particular kata in Java 5.0.  This should give you a feel for the 
power and convenience of some of the new features.

## The Requirements
Write a class named “PrimeFactors” that has one static method: generate.
The generate method takes an integer argument and returns a List<Integer>.  That list contains the prime factors in numerical sequence.

## The PPT file
The ppt has the problem statement and requirements as well as the solutions posed by uncle Bob