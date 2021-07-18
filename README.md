# web3js
Private Git repository for web3js practice.

1.  Access web3js web IDE, Remix IDE and write a hello-world Smart Contract in Solidity.
https://www.geeksforgeeks.org/hello-world-smart-contract-in-remix-ide/

2.  install TestRPC and Web3js
https://www.geeksforgeeks.org/interacting-with-ethereum-smart-contract-using-web3js/
NOTE: This website misspells ethereum.  On Step 2, it says to run "npm install -g etherumjs-testrpc".  This should be "npm install -g ethereumjs-testrpc".  Then on Linux I had to run "npm init" to create the package.json file.  I then ran "npm install ganache-cli", which is what the prompt on this screen instructed me to do.  Run "npm install -d".

The testrpc command still would not run.  I Googled it and found "npm install web3" on the official documentation site @ https://web3js.readthedocs.io/en/v1.3.4/getting-started.html.  In Linux, modules are installed to ~/node_modules.  The testrpc program is now ~/node_modules/ganache-cli/cli.js.  Success, when the ganache-cli server runs, it lists 10 private keys for use in a Wallet and shows the test server, 127.0.0.1:8545.  Each wallet has 100 ETH in it to test with.

NOTE: Step 3 on https://www.geeksforgeeks.org/interacting-with-ethereum-smart-contract-using-web3js/ says to run "npm install ethereum/web3.js0.20.0 –save".  This command failed for me.  I just had to run "npm install web3".
