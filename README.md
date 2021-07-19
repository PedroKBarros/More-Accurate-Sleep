# More-Accurate-Sleep
A set of functions in Python and C++ with the aim of making the operating systems sleep function more accurate.

## Motivation
I'm developing, entirely in Python, the [LE3B software](https://github.com/PedroKBarros/LE3B), which simulates the reading of comments from the open-source software BigBlueButton. It turns out that it is necessary to use the sleep function to perform the time count.
The problem is that such a function presents an undesirable accuracy for the referred context, but it can be improved through alternative algorithms.

## References
All algorithms and knowledge presented in this repository were based on and/or taken from the article ["Making an accurate Sleep() function"](https://blat-blatnik.github.io/computerBear/making-accurate-sleep-function/).