# The-Essence-Of-Karate
The decryption of an encrypted message using Python.

the encrypted message will be decrypted using Frequency Analysis. The frequency table that was used for this decryption project have alphabetical letters from A to Z showing their frequency. 

I declared the encrypted message by using a variable called, “encrypted_sentences =” and making the encrypted message as a string.

In order to decrypt the message, I used a dictionary because it stores variables, different data, numbers, etc. I called in “stored_characters = {}.” The reason why I used this variable with the curly brackets was because it helped count the frequencies each letter had in the string below. 

A “for” loop was implemented under the “stored_characters = {}.” It consisted of a temporary variable called “char” and the other variable “encrypted_sentences”  that was created for the string.

Below the “for” loop, an if/else statement was written using “if char in encrypted_sentences: if char not in stored_characters: stored_characters = 1. This simple code means if the letters that are in the sentences are not in the stored_characters, then make the letters be part of the stored characters. “else: stored_characters += 1” means if the letters that are in the sentences are in the stored_characters, then its going to make the character go up by one.

When determining the letters frequency in the string, I inputted an print statement with the variable stored_characters between the parenthesis. 

Started to decrypt the message by declaring a new variable called “attempt =” with the variable that was declared earlier in the code “encrypted_sentences” and using the “.replace” method. I used the “.replace” method because replacing one character at a time determines what the actual letter is on the alphabet combining it with the frequency. I noticed as I was implementing each letter onto the “.replace”, letters r, b and m were frequently seen within the message. As I compiled those three letters, An output of E, T, A were given. This is significant because these letters that were shown in the output are the most common in a sentence and or word. As I completed the rest of the code, I noticed that letter ‘g’ in the encrypted message is the less frequent letter seen. The reason why was because compiling the letter ‘g’, it came out as letter ‘Z.’ Overall, when the most common letter in the alphabet has a high frequency number it means that it’s been used the most. If the letter in the alphabet has a low frequency number it means that it’s not used as much. I coded in a print statement as the final step.

