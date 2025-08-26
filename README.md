# Decrypting-Encrypted-Messages-with-Linux
This project demonstrates how to use Linux command-line tools and cryptographic techniques to uncover hidden messages in encrypted files. The activity simulates a real-world scenario where files in a user’s home directory have been encrypted, and you must recover them by identifying and breaking a Caesar cipher, then decrypting with OpenSSL.


This project demonstrates how to use Linux command-line tools and cryptographic techniques to uncover hidden messages in encrypted files. 
The activity simulates a real-world scenario where files in a user’s home directory have been encrypted, and recovery is done by identifying and breaking a Caesar cipher, then decrypting with OpenSSL.


⚙️ Tasks Completed
# Task 1: Read the contents of a file

Used ls to list files in /home/analyst

Read the instructions inside README.txt with cat

# Task 2: Find and decrypt a hidden file

Navigated to the caesar subdirectory

Discovered hidden file .leftShift3 using ls -a

Decrypted the Caesar cipher using tr command

# Task 3: Decrypt a file

Used OpenSSL to decrypt Q1.encrypted with the revealed password

Successfully recovered the file Q1.recovered

Viewed the decrypted hidden message with cat

<img width="835" height="265" alt="image" src="https://github.com/user-attachments/assets/ecbc72dc-ffa7-4427-9084-889516fc8255" />




# 🧰 Tools & Commands Used

ls, ls -a → list files (including hidden ones)

cat → display file contents

cd → navigate directories

tr → decrypt Caesar cipher by translating characters

openssl → decrypt AES-256-CBC encrypted data
