# kata-fizzbuzz
Code repo for the fizzbuzz code kata using gradle and java

This is a TDD code kata using the fizzbuzz programming practice etude.

---

## Introduction
Solving the classic FizzBuzz programming exercise using Test Driven Development.

Generate a single line string with the numbers (integers) from 0 to 100 (inclusive) where numbers divisible by 3 are replaced with the word "fizz" and numbers that are divisible by 5 are replaced by "buzz". Numbers that are evenly divisible by 3 and 5 are replaced by the word fizzbuzz.

### Scope
This is a practice for IDE, gradle, java, and testing skills.
The end output should be equal to the following string exactly.
`"0, 1, 2, fizz, 4, buzz, fizz, 7, 8, fizz, buzz, 11, fizz, 13, 14, fizzbuzz, 16, 17, fizz, 19, buzz, fizz, 22, 23, fizz, buzz, 26, fizz, 28, 29, fizzbuzz, 31, 32, fizz, 34, buzz, fizz, 37, 38, fizz, buzz, 41, fizz, 43, 44, fizzbuzz, 46, 47, fizz, 49, buzz, fizz, 52, 53, fizz, buzz, 56, fizz, 58, 59, fizzbuzz, 61, 62, fizz, 64, buzz, fizz, 67, 68, fizz, buzz, 71, fizz, 73, 74, fizzbuzz, 76, 77, fizz, 79, buzz, fizz, 82, 83, fizz, buzz, 86, fizz, 88, 89, fizzbuzz, 91, 92, fizz, 94, buzz, fizz, 97, 98, fizz, buzz"`

In the first attempt, analyse the issue, break down the task into small, quickly achievable and easily testable sub-units.
Write them down as a series of todos then follow the list.
In subsequent attempts where the problem is understood, try to get quicker by using keyboard short-cuts, efficiently using the IDE,  and improving on the coding idioms used.

Steps

1. Create a FizzBuzzImpl class that extends the FizzBuzz interface
2. Create a new test method in the FizzBuzzTest class.
3. Proceed with the TDD work cycle

### TDD Work Cycle
- Create a test that fails because you haven't implemented the required functionality
- Implement the required functionality (Make the test green)
- Refactor (important!)
- rerun the test (keep it green)
Repeat until finished

### TDD refactoring hints
- Move code to where it logically belongs
- Remove duplication
- Make names self-documenting.
