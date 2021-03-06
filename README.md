# Generate Readable OTP

`Generate Human-Readable One-Time Passwords`

**WARNING** Passwords generated by this library are *not* secure or strong and should *not* be relied upon.

Generated passwords are meant to be easily verbally communicated: (and non-offensive).

* All lower-case with no spaces.
* Word combinations shouldn't be offensive.
* No punctuation or symbols.
* Word-banks contain English words from 4th-grade (or earlier) spelling lists.

# Return Values

All methods return an array of strings.

Example: `ShortPhrase()` returns `["dogs", "like", "art"]`

This is done so that a presentation-layer can easily format the output to aid readability. At first glance the above example "dogslikeart" takes a little effort to read - but alternating the color of each word woud make it easy to read.

# Methods

## Hexadecimal()

Generate a random hexadecimal value.

## ShortPhrase()

Generate a short phrase using words from English 4th grade spelling lists.

## ShortPhraseNumber()

Generates a short pharse with a random number 2-digit number either appended or prepended

## WordNumber()

Generates a random word with a trailing 2-digit number
