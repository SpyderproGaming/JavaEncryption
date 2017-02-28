# JavaEncryption

This program is currently insanely secure. From release 3.3 deciphering a 10 pass encrypted message without viewing the source code to this project or using the program itself is impossible. If access is given to the program or the source code though, the encryption is only as strong as your password. No matter what I do to make the encryption strong, if your key is 123, and you can decrypt something by typing 123, then so can a computer doing a brute force attack. You MUST use strong passwords if you intend to evade any serious opposition like governments. Maximum effective encryption key length is 24 but you can enter longer ones, they just get cut due to limitations in the framework of the software. Login passwords can be as long as you want though and don't get cut. I would highly recommend that if you intend to do any real encryption that you use a randomly generated 24 character password from this site: https://lastpass.com/generatepassword.php

If you use a password that consists of words and no symbols any real threat can easily crack your password with a brute force or dictionary attack. Random passwords of length 24 allow for 93^24 (1.7522286e47) combinations that a computer has to try in order to decrypt your message. (93 is derived from all typable characters, ASCII 33-126)

TL:DR

These messages are uncrackable unless your password is weak and the opposition has access to this software along with the skills needed.
