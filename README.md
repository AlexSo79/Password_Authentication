# Password Authentication

This is a simple Python program that demonstrates how to use the `getpass` module to authenticate users based on a predefined database of usernames and passwords.

## Requirements

- Python 3
- ipykernel

## Usage

- Run the code in a Jupyter notebook or any other Python IDE.
- Enter your username and password when prompted.
- If your username and password match the database, you will see a "Verified" message.
- If your username or password is incorrect, you will be asked to enter your password again.

## Database

The database is a dictionary that contains four pairs of usernames and passwords. You can modify the database as you wish, but make sure to use the same format.

```python
database = {
    "user1" : "123456",
    "User2" : "654321",
    "User3" : "67890",
    "User4" : "09876"
}
