# Close Token Accounts
### Without the 15% <a href="https://sol-incinerator.com/">Sol Incinerator</a> Fee (0 fee with the program)

This program creates a transaction that closes 14 token accounts at once <u>in one transaction</u>.


14 is the highest number of token accounts to burn while ensuring the transaction has >90% success rate


To prevent accidental loss, this program only closes token accounts with 0 tokens in them.


To run:
Create a .env file with these contents
```dotenv
RPC_URL=... #your rpc url to use
WALLET=[...] #wallet whose token accounts to close, *uint8 bytes array format*
```
Then execute
`npm run start`

The program will respond with `14 token accounts successfully closed` if the transaction succeeded.


If the program doesn't respond in 60 seconds, your transaction failed. Restart the program.


Restart the program to keep closing token accounts for massive SOL gains.