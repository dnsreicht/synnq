API calls overview

SYNNQ DEVNET API
Base URL: https://rest.synnq.io


Wallet Management:

Create Wallet: 
POST /create_wallet
Create a new wallet with a specified prefix.

Retrieve Wallet: 
POST /get_wallet
Retrieve a wallet by its address.

Query Balance: 
POST /query_balance
Check the balance of a specific wallet.

Retrieve Wallet from Mnemonic: 
POST /retrieve_wallet_from_mnemonic
Recover a wallet using a mnemonic phrase.

Update Wallet Permissions: 
POST /update_wallet_permissions
Modify the permissions of a wallet.

Update Wallet Role: 
POST /update_wallet_role
Change the role associated with a wallet.

Authenticate Wallet: 
POST /authenticate
Authenticate a wallet using SSO.

Verify Auth Token: 
POST /verify_auth_token
Validate an authentication token.

Get Wallets Count: 
GET /get_wallets_count
Retrieve the total number of wallets.

Get Wallets Holding Coin: 
POST /get_wallets_holding_coin
Get wallets holding a specific coin.

Transactions:

Submit Transaction: 
POST /transaction
Process a transaction request.

Retrieve Transaction: 
GET /get_transaction
Fetch transaction details by hash.

Blockchain & Governance:

Get Block Height: 
GET /block_height
Retrieve the current block height.

Fetch DAG State: 
GET /fetch_dag_state
Get the state of the Directed Acyclic Graph (DAG) with optional pagination.

Submit Governance Proposal: 
POST /submit_proposal
Propose changes in the governance system.

Vote on Proposal: 
POST /vote_on_proposal
Vote on a submitted governance proposal.

Retrieve Proposal: 
GET /get_proposal
Retrieve a governance proposal by ID.

Retrieve All Proposals: 
GET /get_proposals
Fetch all proposal IDs.

Submit General Proposal: 
POST /submit_general_proposal
Submit a general non-governance proposal.

Vote on General Proposal: 
POST /vote_on_general_proposal
Vote on a general proposal.

Retrieve General Proposal: 
GET /get_general_proposal
Fetch a general proposal by ID.

Token & Coin Management:

Create Bearer Token: 
POST /create_token
Generate a new bearer token.

Create Coin: 
POST /create_coin
Issue a new coin with specified attributes.

Mint Token: 
POST /mint_token
Mint new tokens for a given symbol.

Smart Contracts:

Execute Smart Contract: 
POST /execute_contract
Execute a method within a smart contract.

Deploy Smart Contract: 
POST /deploy_contract
Deploy a new smart contract.

Machine Learning:

Predict: 
POST /predict
Make predictions using a neural network model.

Forecast: POST /forecast
Generate forecasts using a neural network model.
