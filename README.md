# `CrossChain ERC-721 Step by Step Guide`

> Effortlessly transfer ERC-721 tokens from one chain to another. Made using Router Cross-Talk.

This project is built with [Router CrossTalk](https://dev.routerprotocol.com/crosstalk-library/overview/introduction)

Router Protocol is a solution introduced to address the issues hindering the usability of cross-chain liquidity migration in the DeFi ecosystem. It acts as a bridge connecting various layer 1 and layer 2 blockchains, allowing for the flow of contract-level data across them. The Router Protocol can either transfer tokens between chains or initiate operations on one chain and execute them on another.

Please check the [official documentation of Router Protocol](https://www.routerprotocol.com/) 


# ⭐️ `Star us`

If this repository helps you build cross-chain dapps faster and easier - please star this project, every star makes us very happy!

# 🤝 `Need help?`

If you need help or have other some questions - don't hesitate to write in our discord channel and we will check asap. [Discord link](https://discord.com/invite/xnb3nNYC). The best thing about this is the super active community ready to help at any time! We help each other.

# ✌️`Let's Begin 🚀`

Step 1) Log in to your preferred Solidity development platform, such as Remix or Truffle , etc

Step 2) Create a new workspace by selecting the "New Workspace" option. You may need to specify a name for the workspace and choose a template to use. For example, you could select the "Solidity" template.

Step 3) Create a new file in the workspace by selecting the "New File" option. Give the file a name and save it with the ".sol" extension. For example, you could name the file "NFT" and save it as "NFT.sol".

Step 4) Open the "NFT.sol" file, which contains the code you want to use for your new file. Copy the entire code from the "coin.sol" file.

Step 5) Go back to the editing area for your new file in the workspace. Paste the code you copied from "NFT.sol" into this new file.

<img width="600" alt="image" height="300" height="300" height="300" height="300" height="300" src="https://user-images.githubusercontent.com/124175970/222487874-7f661c6c-7ad1-4cd0-8364-216376b5eb8d.png">




<img width="600" alt="image" height="300" height="300" height="300" height="300" height="300" src="https://user-images.githubusercontent.com/124175970/222489012-d0697c9a-c7db-41d8-9591-8b3455862d0a.png">



<img width="600" alt="image" height="300" height="300" height="300" height="300" height="300" src="https://user-images.githubusercontent.com/124175970/222489772-ceecb651-0554-4c0a-8185-3684fae93b7a.png">

Step 1) Open your preferred web browser.

Step 2) Go to https://metamask.io/download/ and install the Metamask extension for your browser.

Step 3) Open the Metamask extension by clicking on its icon in your browser toolbar.

Step 4) Click on the "Create Wallet" button to create a new wallet.

Step 5) Set a password for your wallet in the provided field. Make sure to remember this password, as it will be needed to access your wallet in the future.

Step 6) Choose either the "Secure my wallet with a seed phrase" or "No thanks, maybe later" option. We recommend choosing the first option to secure your wallet with a backup seed phrase.

Step 7) Connect to the Mumbai network:

Go to https://mumbai.polygonscan.com/
Scroll down to the bottom of the page and click on the "Add Mumbai Network" button to add Mumbai Network to Metamask Wallet

Step 8) Connect to the Fuji network:

Go to https://testnet.snowtrace.io/
Scroll down to the bottom of the page and click on the "Add C-Chain ( Fuji ) Network" button to add Fuji Network to Metamask Wallet




Step 11) Go back to your Remix IDE.

Step 12) In the left-hand sidebar, click on the "Solidity Compiler" option.

Step 13) Click on the "Compile NFT.sol" button to compile the code for your contract.

Step 14) If the compilation is successful, you should see a green checkmark next to the "NFT.sol" file in the left-hand sidebar.

Step 15) If there are any errors in your code, you will see them listed in the right-hand panel under the "Errors" tab. Click on each error to see a more detailed description of the problem and how to fix it.

Step 16) Alternatively, you can use the shortcut command, "Ctrl + S" on your keyboard to compile the code

Step 12) Select Inject Provider from Environments in Deployments section<br/>



<img width="600" alt="image" height="500"  src="https://user-images.githubusercontent.com/124175970/221346226-e0e851b9-8212-481f-9901-26793e19fa1a.png">

Step 13) Switch to Binance Chain and copy your wallet address

<img width="600" alt="image" height="500" src="https://user-images.githubusercontent.com/124175970/222494290-26e66b6d-62e7-498b-ae3a-7b2f8395fc37.png">

Or 

Step 13) Switch to Fuji Network and copy your wallet address  



<img width="600" alt="image" height="500" src="https://user-images.githubusercontent.com/124175970/222494290-26e66b6d-62e7-498b-ae3a-7b2f8395fc37.png">


Step 14) A faucet is a service that allows you to receive free cryptocurrency to use for testing purposes. 

To add faucet to your Fuji account, visit https://faucet.avax.network/ and follow these steps:

Paste your wallet address in the provided field.
Click on the "REQUEST 2 AVAX" button to receive free AVAX tokens to your wallet address.

To add faucet to your account on the Mumbai network, visit https://faucet.polygon.technology/ and follow these steps:

Paste your wallet address in the provided field.
Click on the "Submit" button to receive free MATIC tokens to your wallet address.



<img width="600" alt="image" height="300" height="300" height="300" height="300" height="300" src="https://user-images.githubusercontent.com/124175970/221346290-f0183c5a-217b-4ba3-8860-e866f6265372.png">



Step 17) To switch to the Fuji/Binance Network from your Metamask extension, click on the Metamask icon in your browser toolbar, and select "Fuji/Binance" from the network dropdown menu.

Step 18) To deploy the contract, go back to Remix and click on the "Deploy & Run Transactions" button and select the correct contract from the dropdown menu.

Next, click on the "Environment" dropdown menu and select "Injected Web3" to ensure Remix can connect to your Metamask wallet enter the "Gateway address" for Fuji/Binance (which can be found at https://devnet.lcd.routerprotocol.com/router-protocol/router-chain/multichain/chain_config), and set the "DestGasLimit" to 500000.

Step 19) To deploy the contract on the Mumbai Network, switch back to the Metamask extension and select "Mumbai" from the network dropdown menu. Then, return to Remix and repeat the previous steps, but this time, select enter the corresponding "Gateway address" for Mumbai from the same website (https://devnet.lcd.routerprotocol.com/router-protocol/router-chain/multichain/chain_config). Set the "DestGasLimit" to 500000.

Note: A "faucet" is a tool that allows you to receive test tokens or cryptocurrency for free, which can be used to test out transactions and contracts on a blockchain network. By adding the faucet to your wallet address, you can receive these test tokens for free, which can be used to deploy and test your smart contract.

Step 20) Switch to the Fuji/Binance Network by clicking on the Metamask extension in your browser and selecting "Fuji/Binance" from the dropdown menu. Once you are on the correct network, select the contract you deployed on Fuji from the "Contract" section of Remix.

Then, click on the "setContractOnChain" function in the "Contract" section and pass in the following parameters:

_chainId: 0
_destChainId: 80001
_contract: The address of the Mumbai contract that you just deployed
Click on the "transact" button to execute the function.

Step 21) Switch to the Mumbai Network by clicking on the Metamask extension in your browser and selecting "Mumbai" from the dropdown menu. Once you are on the correct network, select the contract you deployed on Mumbai from the "Contract" section of Remix.

Then, click on the "setContractOnChain" function in the "Contract" section and pass in the following parameters:

_chainId: 0
_destChainId: 43113
_contract: The address of the Fuji/Binance contract that you just deployed
Click on the "transact" button to execute the function.

Step 22) Switch to Fuji/Binance Network and mint some ERC20 Tokens through mint function of the Fuji/Binance contract deployed<br/>



<img width="600" alt="image" height="300"  src="https://user-images.githubusercontent.com/124175970/221346368-d761fb5c-4596-44c8-973d-0c97e800c267.png">



Step 23) Copy the Fuji contract address that you just deployed in the previous steps, then visit https://devnet-faucet.routerprotocol.com/ in your web browser. Paste the Fuji contract address into the provided field and click on the "Get Route" button to receive some Route tokens in the Fuji contract.CrossTalk works on a prepaid fee model. Upon receiving the CrossTalk Request, the Router chain will calculate the estimated fee for executing the transaction on the destination chain in terms of ROUTE tokens and deduct the fee plus incentive from the feePayer address upfront.Fee and relayer incentive for any cross-chain request on Router have to be paid in ROUTE tokens only





<img width="600" alt="image" height="500" src="https://user-images.githubusercontent.com/124175970/221346388-5dbdaa27-58aa-4633-b6cd-05eb9ebc39da.png">



Step 24) Come back to Remix ,and Call TransferCrossChain function of the Fuji/Binance contract deployed , passing in 0, 80001 ,30000000000 ,recipient address and amount as parameters<br/>



<img width="600" alt="image" height="300" height="300" height="300" height="300" height="300" src="https://user-images.githubusercontent.com/124175970/221346412-bce85fb1-139f-42ed-ade6-e916b09b5fdd.png">



Step 25) You can see the CrossTalk transactions here https://devnet-explorer.routerprotocol.com/crosstalks 

Step 26) When all 4 green checks are there, come back to Remix again and switch to Mumbai Network

Step 27) Call the function , totalSupply of the Mumbai contract deployed to see the ERC20 tokens transferred

Step 28) Earn your NFT Certificate . Fill the below form.

https://docs.google.com/forms/d/e/1FAIpQLSd8Xuiuw32kOqGsWmT5s7GLjLVZ_rHXw9bAJbdbr0XzrVG6RA/viewform?embedded=true
	

