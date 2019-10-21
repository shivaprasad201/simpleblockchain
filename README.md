# Simple Application to demonstrate Blockchains.
## Demonstrates the track of transactions on blocks. 
## Uses sha256 Algorithm to encrypt the transaction blocks.

## Pre-requisites:

* Needs GO to build the package. <a href ="https://golang.org/dl/">Install Go from here</a>

## Setup:
1. Clone the repository.
2. Build the package `go build`
3. Run the package `./simpleblockchain`

## Usage:
* Run the server as mentioned above. [Setup:3]
* Hit localhost:[port] on your browser/postman or even curl to get json data of the genesis block.

    ![Alt text](assets/img1.jpg?raw=true "Genesis")

* Add some transactions. For this you can use postman or send a post request using curl.

    ![Alt text](assets/img2.jpg?raw=true "Add-transaction")

* Now get all the transactions.

    ![Alt text](assets/img3.jpg?raw=true "Get-transactions")
    
    ![Alt text](assets/img4.jpg?raw=true "Get-transactions2")

* Note that the blocks are created for each transaction and contains the hashed data of the previous blocks. 

* Enjoy!