# Metacrafters Creating a Token
Creating a token with Solidity for Metacrafters Solidity course final assessment.

## Description
This project serves as an exercis to hone fluency of Solidity language.
Solidity is a language which EVM runs to to create transaction blocks.
This is the gist of how proof of stake works in decentralized transaction or mining. 

## Getting Started
### Installing
* The assessment file is public and free to download.
* Highly advise to install Remix (Solidity IDE) as well.

Remix Link: https://remix-project.org/

Remix Online IDE web based version: https://remix.ethereum.org/
### Executing program
* With Remix, ensure that the version imported to the file is the version
of Remix currently installed on your device:

``` pragma solidity 0.8.22; ```

or

``` pragma solidity version; ```

or 

``` pragma solidity ^0.8.22; ```
* After successfully importing the right version, simply compile the code
by navigating the Solidity Compiler on the right navigator.
* Click ```Compile L9_FinalAssessment.sol``` under the Advanced Configurations.
* Under Solidity Compiler, click Deploy & run transactions.
* Under CONTRACT, click ```Deploy```.
* Scroll all the way down and you will see the deployed token. Click the arrow.
* Click ```Token_Abbrv``` and ```Token_Name``` and it will display the token name and abbreviation.
* Scroll all the way up and copy ACCOUNT address.
* Scroll all the way down again and paste the address in ```balances```, ```burn```, and ```mint```.
* Under ```mint```, input a value. Click ```transact```.
* Under ```burn```, input a value to deduct from the mint value. Click ```transact```.
* Lastly, click ```Total_Supply```

Inputting a value in burn that is greater than the mint value or the ```Total_Supply``` will not return any value to the ```Total_Supply```.

## Help
There are no known issues so far. If you ever find one, email me at: 

p.tecson.rizal@gmail.com

as for Metacrafters, email me at:

423004024@ntc.edu.ph 

## Authors
Marco Tecson
@Mordical62645

## License
This project is not licensed but is under the name of Metacrafters and The National Teachers College.
