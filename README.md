# paper-secrets
Store secrets securely on paper, using Shamir Secret Sharing and QR codes

# Project Goal
The goal of this project is provide a library, and perhaps UI that allows users to back up a file onto a piece of paper, in a secure manner.
A secret is not much of a secret if it is stored in plaintext on the paper. As people are prone to forgetting good passwords, especially when long periods of time elapse, or if unfortunate things happen to them, password protecting content on piece of paper requires that a password is stored somewhere securely, thereby not solving the problem.

This project splits the secret into fragments using Shamir Secret Sharing, allowing a secret file to be stored in a distributed and (more) secure manner than a piece of paper with a password.

Recovery can be done by scanning or photographing the required number of fragments to restore the secret, and by using this project to recreate the secret file.

The store file can be test or binary, and may be e.g. a password, text file with a will, pgp or ssh key or any other small secret.

# Dependencies

#https://github.com/shea256/secret-sharing
python-reportlab
python-qrcode
python-qrtools
