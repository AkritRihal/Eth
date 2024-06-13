
# Simple Token Contract

Welcome to my GitHub repository where I’ve crafted a Simple Token Contract! This project is a testament to my journey through the world of Solidity, designed to encapsulate the essence of creating a cryptocurrency token on the Ethereum blockchain. It’s a personal endeavor to solidify my understanding of blockchain technology and to share my learning experience with you.




## Description

In my contract, aptly named SimpleToken, I’ve incorporated several features that are fundamental to the workings of a cryptocurrency:

    Public Variables: I’ve declared public variables to store the vital details of my token, such as:
    tokenName: The official name of my token.
    tokenAbbreviation: The shorthand symbol representing my token.
    totalSupply: The aggregate count of tokens available in the market.
 1. Address to Balance Mapping: I’ve used a mapping to link Ethereum addresses with their respective token balances, which acts like a ledger to keep track of who owns how many tokens.
 2. Mint Function: My mint function is a mechanism to create new tokens. It takes an address and a value, and it responsibly increases the totalSupply along with the balance of the specified address by the stated amount.
 3. Burn Function: In contrast, my burn function is designed to reduce the token supply. It accepts an address and a value, similar to the mint function, but it decreases the totalSupply and the address’s balance, effectively annihilating the tokens.
 4. Conditional Checks: To maintain transactional integrity, I’ve included conditional statements in the burn function to ensure that the address has enough tokens for the burn operation to be executed.
## Learning Path

This contract is the culmination of my educational path, integrating various concepts I’ve learned:

    1. Introduction to Data Types: Grasping Solidity’s data types was essential for me to define the variables and structure my contract.
    2. Mapping in Solidity: Learning about mappings was crucial as it allowed me to associate addresses with token balances.
    3. Functions Demonstration: The mint and burn functions are practical applications of how to manipulate state variables and engage with the blockchain.
    4. Conditional Statements: Implementing conditionals in the burn function was a great way to learn how to enforce logic within my contract.

    
## Get Started
If you’re interested in interacting with my contract, feel free to clone this repository and import the contract into your preferred Solidity development environment. 

Code Structure:

To begin, navigate to the Remix IDE  Ensure that the “Compiler” option is set to “0.8.18” to match the pragma specified in the contract code. Once set, click on the “Compile MyToken.sol” button to compile the contract.

After successful compilation, proceed to the “Deploy & Run Transactions” tab, also found in the left-hand sidebar. From the dropdown menu, select the MyToken contract. Click on the “Deploy” button to deploy the contract onto the Ethereum blockchain.

This contract includes a mint function to increase the token supply and credit an account, and a burn function to decrease the token supply and debit an account, with checks to ensure the account has sufficient balance for burning tokens.

Please note, this contract is primarily for educational purposes. It’s not intended for real-world deployment without further development and security considerations.

Happy exploring, and I’m thrilled to have reached this significant milestone in my Solidity journey!
## Authors

- [@AkritRihal](https://github.com/AkritRihal)

