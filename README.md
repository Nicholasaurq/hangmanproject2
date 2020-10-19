# hangmanproject3
Project 3 - Nicholas Urquhart

https://github.com/Nicholasaurq/hangmanproject3

User guesses an encrypted word in a game of hangman, user has 10 misses to guess the world entirely.
a word list is used and a random number chooses which word in the list to use.
program has an interface to show you which letters you have guessed correctly and where they are in the word.
Also checks to make sure the user doesn't guess the same letter more than once.
After guessing the word correctly, the word begins to be decrypted.
Since the encryption used an index to determine how the ascii values of the word were changed, the decrypt function simply reverses this.
