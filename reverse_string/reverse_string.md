# Reverse String 

## Introduction

Reversing strings (reading them from right to left, rather than from left to right) is a surprisingly common task in programming.

For example, in bioinformatics, reversing the sequence of DNA or RNA strings is often important for various analyses, such as finding complementary strands or identifying palindromic sequences that have biological significance.

## Instructions

Your task is to reverse a given string.

Some examples:

    Turn "stressed" into "desserts".
    Turn "strops" into "sports".
    Turn "racecar" into "racecar".

## Bonus

Test your function on this string: `uüu` and see what happens. Try to write a function that properly reverses this string. Hint: grapheme clusters

To get the bonus test to run, remove the ignore flag (#[ignore]) from the last test, and execute the tests with:
```
cargo test --features grapheme
```
You will need to use external libraries (a `crate` in rust lingo) for the bonus task. A good place to look for those is `crates.io`, the official repository of crates. Please remember that only a limited set of crates is supported by our test runner. The full list is in `this file` under the section [dependencies].

Check the [documentation](https://doc.rust-lang.org/cargo/guide/dependencies.html) for instructions on how to use external crates in your projects.

## Source
[Introductory challenge to reverse an input string](https://www.freecodecamp.org/news/how-to-reverse-a-string-in-javascript-in-3-different-ways-75e4763c68cb)