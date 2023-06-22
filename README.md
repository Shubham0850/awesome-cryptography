# awesome-cryptography

## Introduction to Cryptography

### Definition and purpose of cryptography
-----------------
Most of the time, people misunderstand the concept of cryptography or perceive it as a daunting and complex topic. 😕 However, the truth is that cryptography is not as intimidating as it may seem. In fact, it can be quite fascinating and easy to understand. 🤩 To demystify this intriguing field, let's delve into a story that illustrates the essence of cryptography in a simple and engaging manner. 📚🔐

Story: Sir Alex and the Magical Encryption 🛡️🔑

Once upon a time, in a land ruled by a powerful king, there was a brave knight named Sir Alex. Sir Alex was known for his extraordinary skills and courage. He was often sent on important missions by the king.

One day, the king called Sir Alex to his chamber and handed him a vital message to be delivered to the neighboring kingdom. The message contained confidential information about a possible attack on the king's realm. It was crucial that the message reached the neighboring kingdom's ruler safely and without falling into the wrong hands.

Knowing the risks involved, Sir Alex sought the help of a wise old wizard named Merlin, who was an expert in cryptography. Merlin explained to Sir Alex that cryptography could protect the message from prying eyes and make it unreadable to anyone except the intended recipient.

Merlin took the message and performed a magical process on it. He used a secret code, known only to him and Sir Alex, to transform the message into a jumble of seemingly random letters and numbers. This encrypted message looked like a puzzle that only the one with the right key could solve. 🧙✨

With the encrypted message in hand, Sir Alex embarked on his journey to the neighboring kingdom. Along the way, he encountered many challenges, including bandits and spies who were eager to seize the message. But thanks to the encryption, they couldn't understand the secret information hidden within the jumble of characters.

Finally, Sir Alex arrived safely at the neighboring kingdom's castle and handed the encrypted message to the ruler. The ruler, who possessed the key to decipher the code, decrypted the message and learned about the imminent attack. With this valuable information, the ruler was able to take measures to protect both kingdoms.

In this story, cryptography played a crucial role in securing the message and ensuring its confidentiality. It transformed the original message into an unreadable form, protecting it from unauthorized access. Only those who possessed the right key could decrypt the message and understand its true meaning.

This story serves as a testament to the power and significance of cryptography. By using encryption techniques, we can safeguard sensitive information, maintain privacy in our digital communications, and ensure the security of online transactions. So, let's embark on this journey of understanding cryptography and discover how it influences our everyday lives. 🚀🔒

In the real world, cryptography is used to secure sensitive information transmitted over networks, protect online transactions, safeguard personal data, and ensure the privacy of communication. It provides a way to keep our information safe from prying eyes and maintain trust in our digital interactions, just like Sir Alex's encrypted message helped protect the kingdoms in our story.


### Historical overview of cryptography
----------
Long, long ago, before the age of computers and smartphones, people had a burning desire to keep their messages secret. But how did they do it without fancy encryption algorithms? Well, they got creative!

Imagine you're living in ancient times, where people used to communicate through written letters. You write a letter to your friend, but you don't want others to understand its content if it falls into the wrong hands. What would you do?

One of the earliest techniques used by ancient civilizations was called "Caesar cipher." It's named after the famous Roman emperor Julius Caesar. He loved secrecy so much that he invented this simple way of encrypting his messages.

![Caesar's cipher](/assets/Caesars.png)
Caesar's cipher was as easy as shifting the letters of the alphabet by a fixed number. For example, if Caesar decided to shift each letter by three positions, the letter 'A' would become 'D,' 'B' would become 'E,' and so on. By applying this rule to each letter of the message, he created an encrypted version that only those who knew the secret shift value could decipher.

![cipher disks](/assets/cipher%20disks.png)
Fast forward to the Middle Ages, where kings, queens, and their courtiers were always sending secret messages. They came up with clever devices called "cipher disks" or "cipher wheels." These were circular disks or rotating cylinders that had the alphabet engraved around the edges. By aligning different letters on the disks, they could substitute one letter for another and create encoded messages.

![Giovan Battista Bellaso](/assets/Giovan%20Battista%20Bellaso.png)
But wait, there's more! In the 16th century, an Italian scholar named Giovan Battista Bellaso came up with a brilliant idea. He introduced the concept of a "key" to cryptography. With a key, both the sender and the receiver could agree on a secret code and use it to encrypt and decrypt their messages. This was a significant leap forward in the world of cryptography.

![Enigma machine](/assets/Enigma%20machine.png)
As time went on, more advanced techniques emerged. In the 20th century, the famous Enigma machine was developed. It was used by the Germans during World War II to encrypt their military communications. The Enigma machine had rotating wheels, wires, and plugs that created complex encryption patterns. Breaking the Enigma code became a crucial task for codebreakers like Alan Turing, who played a pivotal role in deciphering these encrypted messages.

And now, in the digital age, we have sophisticated algorithms and complex mathematical concepts behind modern cryptography. It's a fascinating journey from Caesar's simple letter shifting to the complex encryption methods we use today.

So, the next time you send a private message or make a secure online transaction, remember the long and exciting history of cryptography. It's a story of human ingenuity and the quest to protect our secrets throughout the ages.

### Goals and principles of cryptography
------
The main goal of cryptography is to keep information safe and secure. It does this by following a set of principles that ensure confidentiality, integrity, authenticity, and availability of the information.

**Confidentiality:**

 Imagine you have a secret diary where you write down your thoughts and feelings. You want to make sure that nobody else can read it. Cryptography helps by turning your diary into a secret code that only you can understand. It keeps your private thoughts hidden and confidential, protecting them from prying eyes.

**Integrity**: 

Let's say you have an important document that you need to send to someone. You want to make sure that the document arrives exactly as you sent it, without any changes or tampering. Cryptography ensures the integrity of the document by adding a special code or signature to it. When the recipient receives the document, they can verify the code to ensure that it hasn't been altered during transmission.

**Authenticity**:

 Imagine you're ordering a package online. You want to be sure that the package is coming from a genuine and trustworthy source. Cryptography can help establish authenticity by using digital signatures. The sender adds a unique signature to the package, which serves as proof of their identity. When you receive the package, you can check the signature to ensure that it indeed came from the authentic sender.

**Availability**:

 Let's say you have encrypted a sensitive file on your computer to protect it from unauthorized access. While it's important to keep it secure, you also need to be able to access and use the file when you need it. Cryptography ensures availability by allowing you, as the authorized user, to decrypt the file using a secret key and access the information whenever necessary.

**Key Management**:

 To keep information secure, cryptography relies on the use of keys. Keys are like secret codes that are used to encrypt and decrypt information. It's crucial to manage these keys properly. Just like you would keep a physical key to your house safe, cryptographic key management ensures that the keys are generated, stored, and shared securely so that only authorized individuals can access the encrypted information.

By following these goals and principles, cryptography helps protect sensitive information, secure digital communication, verify identities, and maintain trust in our online interactions. It ensures that our secrets remain secret, our data stays intact, and our transactions are safe from unauthorized access or manipulation.

## Basic Terminologies in Cryptography
- Plaintext and ciphertext
- Encryption and decryption
- Keys and key management
- Cryptanalysis and cryptosystems
- Attack types: brute force, ciphertext-only, known plaintext, chosen plaintext, chosen ciphertext

## Types of Cryptography
- Symmetric cryptography: principles and examples
- Asymmetric (public-key) cryptography: principles and examples
- Hash functions: principles and examples
- Digital signatures and certificates

## Key Cryptographic Algorithms
- Data Encryption Standard (DES)
- Advanced Encryption Standard (AES)
- Rivest-Shamir-Adleman (RSA) algorithm
- Secure Hash Algorithm (SHA) family

## Cryptography Applications
- Secure communication: SSL/TLS protocols
- File and disk encryption
- Password hashing and storage
- Digital rights management (DRM)
- Secure electronic transactions and online banking
- Virtual Private Networks (VPNs)

## Learning Resources
- [Book: "Cryptography Engineering" by Bruce Schneier](https://www.schneier.com/books/cryptography-engineering/)
- [Online Course: "Applied Cryptography" on Coursera](https://www.coursera.org/learn/applied-cryptography)
- [Article: "A Beginner's Guide to Cryptography" on Medium](https://medium.com/@adamgwalter/a-beginners-guide-to-cryptography-40c4632b8f97)
- [Video: "Introduction to Cryptography" by Khan Academy](https://www.khanacademy.org/computing/computer-science/cryptography)