# Password Hash Cracker

This Python script attempts to crack hashed passwords using a dictionary attack. It reads a list of common passwords from a file, hashes each password, and compares it with a list of hashed passwords to find matches.

Modules Used

    hashlib: Used for hashing passwords using SHA-256 algorithm.

Usage

    Prepare Hashed Passwords:
        Create a file named hashed.txt containing the usernames and their hashed passwords in the format          <username>:<hashed_password>.

    Prepare Common Passwords:
        Create a file named passwords.txt containing a list of common passwords, each on a new line.

    Run the Script:
    python password_cracker.py

Output:

    The script will print any found matches in the format <username> : <password>.

Example Output:

    yaml

    HASH FOUND
    Joe : welcome1

