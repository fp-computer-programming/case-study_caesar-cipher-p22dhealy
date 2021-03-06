<h1 align="center">
    Fairfield College Preparatory School<br>
    Computer Programming - Mrs. Kinskey-Lebeda<br>
    Case Study - Caesar Cipher
</h1>

<h2 align="center">Due before 8:30 AM on 3/5 (20 pts.)</h2>

### Python Reviews
---
Read all instructions carefully. Answer the following question by adding to the code in the provided `caesar_cipher.py` file. In your heading, put your name and the date you began working on the file. Try to make your program as simple and as general as possible.

---
One of the most basic forms of encryption is known as a Caesar cipher, named for Julius Caesar and his use of the cipher to encrypt messages between legions of the Roman army. This encryption method involves shifting a letter by a certain number of places in the alphabet, wrapping around to the beginning if necessary. Shifts can be positive or negative integers. For example, 'B' shifted 5 places would be 'G' and 'A' shifted -3 places would be 'X'. 

Write a program that prompts the user for 2 values: the number of spaces that they would like to shift in the alphabet, and the name of an input file. 

The program should contain 3 functions.

The first function, called `cipher_key` has been written for you. This function takes the shift integer as an argument and returns a dictionary of the Caesar cipher. The keys in the dictionary are the original letters of the alphabet, and the values of the dictionary are their shifted counterparts.

The second function, called `shift_line` will take a line and the dictionary generated by `cipher_key` as arguments and return the shifted version of the line. You must fill in the rest of this function.

The final function called `encrypt_message` will take the input file name and the dictionary generated by `cipher_key` and create a new file called `encrypted_filename` where `filename` is the original name of the file the user input. The encrypted file should contain an shifted version of the contents from the original file. Be sure to maintain the same line structure in your "encrypted" file. You must also fill in the rest of this function.

The program should display to the console the cipher dictionary. Nothing else should be printed to the console.

Use the `alma_mater.txt` file in the repository to test your program. Using a shift value of 3, the `encrypted_test.txt` should look like this:

```
Idluilhog Suhs ixoo ulfk lq ehdxwb,
Ulvlqj iurp wkh vhd,
Prwkhu ri gholjkw dqg gxwb,
Khdu rxu sohgjh wr wkhh!
Ghhshu wkdq wkh Vrxqg'v eoxh zdwhu,
Vwurqjhu wkdq wkh jdoh,
Lv rxu oryh iru Dopd Pdwhu,
Idluilhog Suhs, doo kdlo!
```

<p align="center">Be sure to commit your code before the end of class. Only the latest commit will be graded.</p>
