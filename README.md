# addBoringcoinTransaction.py

**Description of the Python Code**

This Python script is designed to add a new transaction to a Google Sheet using the `ezsheets` library. The script requires three command-line arguments:

1.  **Sender**: The entity sending the transaction.
2.  **Recipient**: The entity receiving the transaction.
3.  **Amount**: The value of the transaction.

Here's a step-by-step breakdown of what the code does:

1.  The script first checks if the required command-line arguments are provided. If not, it displays the usage instructions and exits.
2.  It then extracts the sender, recipient, and amount from the command-line arguments using `sys.argv`.
3.  The script connects to a Google Sheet using the `ezsheets` library and the specified URL. The sheet is assumed to be located at `https://autbor.com/boringcoin`. Please note that you should replace this URL with the actual URL of your Google Sheet to avoid any permission errors.
4.