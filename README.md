[![forthebadge](http://forthebadge.com/images/badges/made-with-ruby.svg)](http://forthebadge.com) [![forthebadge](http://forthebadge.com/images/badges/uses-git.svg)](http://forthebadge.com)

# TDD and pair programming over Fizzbuzz - Part 2

The goal of Fizzbuzz is to introduce you to Test Driven Development (TDD) and Pair Programming.
Fizzbuzz is normally of the first programs one writes when trying a new language. Today we also practiced Pair programming with each person "driving" for 5 mins and the other two persons "navigating".


## Specifications of Fizzbuzz
- The program can be passed a number.
- When passed a number that is a multiple of 3, the program returns the message 'Fizz'.
- When passed a number that is a multiple of 5, the program returns the message 'Buzz'.
- When passed a number that is a multiple of both 3 and 5, the program ignores the previous 2 rules and returns the message 'Fizzbuzz'.
- In all other cases, the program simply returns the given number.


## How to Play
First clone the directory to your local drive & navigate to the folder that contains the game.

In order to play the game you will need to use interactive Ruby (IRB). If you do not have Ruby and IRB installed on your computer, please click [here](https://www.ruby-lang.org/en/documentation/quickstart/) for instruction.

After you have installed Ruby and IRB, open your favourite Command Line Terminal and start IRB by giving the following command:

```
fizzbuzz_directory$ irb
```

Then you can start playing the game by using the following command:

```
fizzbuzz(desired_number)
```

Below you can see a sample of a game:

```
2.4.2 :001 > require_relative  "lib/fizzbuzz.rb"
 => true
2.4.2 :002 > fizzbuzz(5)
 => "buzz"
2.4.2 :003 > fizzbuzz(3)
 => "fizz"
2.4.2 :004 > fizzbuzz(30)
 => "fizzbuzz"
2.4.2 :005 > fizzbuzz(4)
 => 4
```

### Contributors:
- Lars Finlay
- Xin Wang
- Nikolaos Sakellarios
