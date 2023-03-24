# Voting-System-using-Blockchain
Idea: A blockchain-based voting system that preserves voter privacy and increases accessibility, while keeping the voting system transparent, secure, and cost-effective. The system implements a voting framework that utilizes ethereum’s blockchain and smart contracts to achieve voter administration and auditable voting records. The implementation was deployed on ethereum’s test network to demonstrate usability, scalability, and efficiency.

Pre requisites:

Node JS
Ganache
Metamask extension in the browser, preferably chrome.
Implement:

Open ganache and select quick start ethereum.

Open your browser and configure metamask. Create a wallet and store yourSecret Recovery Phrase in a safe place.

Connecting metamask and ganache:

In metamask, go to settings > networks > add network. You can also get to this by clicking the metamask extension pinned on your browser > clicking the profile picture > settings > networks > add network
Give your network any name of choice.
For New RPC URL go to ganache where you'll copy the RPC server url and paste in Metamask.
Chain ID for ganache is 1337.
You can name currency symbol as "ETH" and save.
Importing an account from ganache to metamask:

Open ganache and select show keys on any account. The show keys button is the key icon.
Copy the private key and click done.
Open the metamask menu which can be accessed by clicking the profile picture and select import account.
Paste the private key copied from ganache and click import.
Cloning the project
git clone link

cd blockchain-voting-system

npm i

npm install -g truffle

truffle compile

truffle migrateortruffle migrate --reset for subsequent runs

npm start

-- The project will open in the browser and metamask will ask you to select an account. Select the account we had imported earlier.


