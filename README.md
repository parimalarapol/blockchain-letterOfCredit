# blockchain-letterOfCredit

This repository is for my academic project. Enhanced a **Trading and Letter of Credit** with **Hyperledger Composer and Hyperledger Fabric**. The	scenario is a	simple	transaction - sale	of	goods from	one	party	to	another.	This	transaction	is	complicated	by	the	fact	that	the buyer	and	the	seller have	no	common	trusted intermediary to	ensure	that	the	exporter	gets	the	money	he was	promised	and	the importer	gets	the	goods

The	transactions are	as	follows:  
1. Importer	requests	goods	from	the	exporter	in	exchange	of	money  
2. Exporter	accepts	the	trade	deal  
3. Importer	asks	its	bank	for	an	L/C	in	favor	of	the	exporter  
4. The	importer's	bank	supplies	an	L/C	in	favor	of	the	exporter,	and	payable	to the	latter's	bank  
5. The	exporter's	bank	accepts	the	L/C	on	behalf	of	the	exporter  
6. Exporter	applies	for	an	E/L	from	the	regulatory	authority  
7. Regulatory	authority	supplies	an	E/L	to	the	exporter  
8. Exporter	prepares	a	shipment	and	hands	it	off	to	the	carrier  
9. The	carrier	accepts	the	goods	after	validating	the	E/L,	and	then	supplies	a B/L	to	the	exporter  
10. The	exporter's	bank	claims	half	the	payment	from	the	importer's	bank  
11. The	importer's	bank	transfers	half	the	amount	to	the	exporter's	bank  
12. The	carrier	ships	the	goods	to	the	destination  
13. The	importer's	bank	pays	the	remaining	amount	to	the	exporter's	bank  


## Flow Diagram
![Alt text](https://github.com/parimalarapol/blockchain-letterOfCredit/blob/master/assets/flowDiagram_loc.PNG)

### Virtual Connect to Ubuntu-Xenial
![Alt text](https://github.com/parimalarapol/blockchain-letterOfCredit/blob/master/assets/ubuntu-xenial.JPG)

### Hyperledger Composer GUI Running
![Alt text](https://github.com/parimalarapol/blockchain-letterOfCredit/blob/master/assets/composer.JPG)

### Letter of Credit
![Alt text](https://github.com/parimalarapol/blockchain-letterOfCredit/blob/master/assets/loc-details.JPG)

### Transfer of Funds
![Alt text](https://github.com/parimalarapol/blockchain-letterOfCredit/blob/master/assets/funds-transfer.JPG)

## Lab 1
- Install Docker Compose
- Install Business Network Pre-Reqs
- Install GO Language
- Forking and Cloning the trade-finance-logistics repository
- Generate Network Cryptographic Material
- Launch the Sample Trade Network
- Verifying your Business Network

## Lab 2
- Launch the sample trade network in dev mode
- Install and run the chaincode on the channel
- Test the Chaincode

## Lab 3
- Building an application: Installing Tools and dependencies
- Configuring the network and application
- Install, run and invoke the chaincode
- Run the blockchain client application

## Lab 4
- Install the Letter of Credit sample application
- Run the Letter of Credit application
