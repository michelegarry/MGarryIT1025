# Executive Summary
The goal for this lab is to get a better idea of the elements of encrypting data and see how much cyber security matters and how it is put into place. Also, this lab introduces cryptography and how messages can be hidden. An insight is also given into what brute-force actually entails.  

# Cybersecurity and Encryption

* Imagine you are part of the Amazon.com online chat. Explain how each component of the security triad would impact your job
  * Confidentiality - Not sharing the person's information you are assisting
  * Integrity - Handling the issue at hand properly and in an honest manner
  * Availability - Having support be available to customers 24/7
* Identify three daily tasks that require authentication. Explain how each one could be converted to multi-factor authentication
  * Accessing e-mail, logging onto your bank account, and logging into the computer. E-mail can become multi-factor and send the phone number on file a confirmation number to enter. Logging into your bank account, you can also have your phone or e-mail connected that sends you a one-time code to enter in to be able to log on, or even use a finger print to gain access. A computer requires a pin or passcode, and some can also confirm with facial recognition.
* Explain ACL and RBAC. What are the advantages and disadvantages of each?
  * ACL - Access Control List
    * Advantages: Access is easier to go over to see who has acccess to what
    * Disadvantages: May be harder to remove access
  * RBAC - Role-Based Access Control
    * Advantages: Naming scheme is clear and concise, security is more on point with each users permissions
    * Disadvantages: The set-up is large amount of work, sometimes it is hard to assign permissions individually instead of as a whole
* Explain the interaction of ciphertext, a public key and a private key
  * The publlic key is used to encrypt the data present, which turns that darta into cipher text. The private key is used to read this cipher text.
* Explain why we need public key cryptography.
  * We need public key cryptography because this allows us to have the ability to decrypt and encrypt important data so it does not get intercepted. 

## Cryptography
* Type a message in the "Caesar Cipher Exploration box and turn the wheel to encrypt your message.
Then explain the encryption here:
  * Sunflower = yatlruckx (translated 6 letters from the original letter)

* Type a message in the "Frequency Fingerprint Exploration" box and a) Explain the result.
b) Would it be different for different languages?
  * a) "Have a good day" matches somewhat with the frequency exploration. It says the most frequent vowel is e usually, which a was actually most used.
  * b) It would be different for different languages because we don't all use the same letters/characters in the same word, so it would be different depending on the language.

* What is a "Polyalphabetic cipher?"
Type a message in the "Polyalphabetic Exploration" box as well as a shift word.
Explain the result.
  * Juniper tree = ddanjne ylnr (shift word = time)
  * The shift word moved the letters that it was made up of in the messgae to make it have a lesser chance to have the frequency detected.

## Brute Force
* What is Brute-Force and how does it relate to Kerckhoffs's principle?
  * Brute-force can be described as an attack that tries every decryption key possible to crack the code. Kerckhoffs's principle related to this because it mentions that even if someone can get their hands on the correct key, it should still be secure.

# Conclusion
This lab was useful for the introduction to cryptography, and cybersecurity. I really didn't think about how they sent messages in the past like that, I found that very interesting that systems like that came out to make sure secret messages were not read by someone other than the people involved. It is also fascinating to see how much in our everyday lives cybersecurity is actually apart of.

