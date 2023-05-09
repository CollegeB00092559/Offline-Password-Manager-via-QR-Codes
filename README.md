# Offline-Password-Manager-via-QR-Codes

This contains two files:
1. Python Code that uses AES-256 and asks for a user input for the Password to be encrypted and for a password to use for the encryption.  This is then output to a QR Code.  It also creates a " masked message" by prefixing the encrypted output, before the QR Code is generated, with an error message
2. An android application that scans the QR Code and you can input a password.  If the password is the same used to encrypt (point 1) it will display the Password
