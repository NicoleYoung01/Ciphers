## How does the cipher work?
### This cipher works by encrypting pairs of letters. 

![foursquare md](https://user-images.githubusercontent.com/94389191/142347788-165e1f61-64a5-4c7f-8896-25f04a4e31dd.jpeg)

* Four 5 by 5 matrices are arranged in a square. 
* Each of the 5 by 5 matrices contains the letters of the alphabet, usually omitting Q. The upper-left and lower-right matrices contain the standard alphabet, while the upper-right and lower-left squares are the "ciphertext squares" and contain a mixed alphabetic sequence. 
* The ciphertext squares you add your keyword then fill the rest of the square with the alphabet, dopping any repeated letters. 
* To encrypt a message you need to separate your word or words into pairs of letters. 
* Then you take your first letter and find it in the upper left square.
* Then take your second letter and find it in the lower right square. 
* In the upper right square where the row of your first letter and the column of second letter meet is your first letter of the encrypted digraph. 
* Then in the lower left square where the column of your first letter and the row of your second letter meet is the second letter of the encrypted digraph. 
* Do this for the rest of the letters in your word or words and you have your encryption. 

## Is it symmetric?
### Yes the cipher is symmetric. To decrypt you would do the same thing as you would to encrypt just in reverse.  
