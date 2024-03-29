# Kata: FizzBuzz
Imagine the scene. You are eleven years old, and in the five
minutes before the end of the lesson, your Maths teacher
decides he should make his class more “fun” by introducing
a “game”. 

He explains that he is going to point at each pupil
in turn and ask them to say the next number in sequence,
starting from one. The “fun” part is that if the number is
divisible by three, you instead say “Fizz” and if it is divisible
by five you say “Buzz”. 
So now your maths teacher is pointing
at all of your classmatesin turn, and they happily shout“one!”,
“two!”, “Fizz!”, “four!”, “Buzz!”… until he very deliberately
points at you, fixing you with a steely gaze… time stands
still, your mouth dries up, your palms become sweatier and
sweatier until you finally manage to croak “Fizz!”. Doom is
avoided, and the pointing finger moves on.

So of course in order to avoid embarrassment in front of your
whole class, you have to get the full list printed out so you
know what to say. Your class has about 33 pupils and he might
go round three times before the bell rings for breaktime. Next
maths lesson is on Thursday. Get coding!

Write a program that prints the numbers from 1 to 100. But
for multiples of three print “Fizz” instead of the number and
for the multiples of five print “Buzz”. For numbers which are
multiples of both three and five print “FizzBuzz”.

Sample output:
Kata: FizzBuzz 124

1

2

Fizz

4

Buzz

Fizz

7

8

Fizz

Buzz

11

Fizz

13

14

FizzBuzz

16

17

Fizz

19

Buzz

… etc up to 100

##Additional discussion points for the
Retrospective
• Is the code you have written clean? Are there any
smells?
• Did you refactor throughout or do it all at the end?
• What if a new requirement came along that multiples
of seven were “Whizz”? Could you add that without
editing the existing code? (Cue discussion of the OpenClosed Principle)
Kata: FizzBuzz 125
Ideas for after the Dojo
• When you’ve got it all working for “Fizz” and “Buzz”,
add “Whizz” for multiples of seven
• Then add “Fizz” also for all numbers containing a 3 (eg
23, 53)

## Contexts to use this Kata
I find this an excellent kata for introducing beginners to TDD.
It’s pretty straightforward to choose the order of test cases,
work in small steps, and complete the whole exercise still
leaving time for a decent retrospective.
