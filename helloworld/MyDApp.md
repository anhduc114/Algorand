Building a smartcontract on Algorand using Algokit

# What is Algorand?
- Blockchain platform and cryptocurrency
- Provides decentralized infrastructure for building various applications
- Applications include financial system and decentralized applications (dApps)

# What is a dApp?
- Stands for decentralized application
- Key principle of dApp: open and accessible to anyone who wants to create and use them.
# What is a smartcontract?
- 
# What is Algokit?
- A smartcontract development tool for Algorand's blockchain.
- Using Algokit to create dApps and interact with dApps on Algorand
- Open-source, support Window + MacOS

# How to create a smartcontract using Algokit?
- On MacOS
- Requirements: PipX, Homebrew, Python 3.10 or higher, Docker, VSCode

## Install AlgoKit
- brew install algorandfoundation/tap/algokit
- Restart terminal (to ensure Algokit in available on PATH)
- Verify: algokit --version (should be 1.6.0)

## Start LocalNet
- algokit localnet start

## Create smartcontract
- algokit init
 -> Choose project name
 -> Choose project template 
 -> Others option 
- Once finished, VS Code will automatically be opened with initialised project. The app used in the demo contain one smart contract (built using Beaker - smart contract development framework)
- (Explain helloworld.py and demo.py)
- right-click on demo.py and select Run Python File in Terminal to deploy HelloworldApp smart contract
- Contract deployed successfully!

# Dappflow
- A web-based user interface that lets you visualise accounts, transactions, apps on Algorand network
- Provides ability to deploy and call smart contracts.
- Launch:  algokit explore
