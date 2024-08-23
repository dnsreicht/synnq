# SYNNQ DEVNET API Overview

**Base URL:** `https://rest.synnq.io`

---

## Wallet Management

- **Create Wallet**
  - **Method:** `POST`
  - **Endpoint:** `/create_wallet`
  - **Description:** Create a new wallet with a specified prefix.

- **Retrieve Wallet**
  - **Method:** `POST`
  - **Endpoint:** `/get_wallet`
  - **Description:** Retrieve a wallet by its address.

- **Query Balance**
  - **Method:** `POST`
  - **Endpoint:** `/query_balance`
  - **Description:** Check the balance of a specific wallet.

- **Retrieve Wallet from Mnemonic**
  - **Method:** `POST`
  - **Endpoint:** `/retrieve_wallet_from_mnemonic`
  - **Description:** Recover a wallet using a mnemonic phrase.

- **Update Wallet Permissions**
  - **Method:** `POST`
  - **Endpoint:** `/update_wallet_permissions`
  - **Description:** Modify the permissions of a wallet.

- **Update Wallet Role**
  - **Method:** `POST`
  - **Endpoint:** `/update_wallet_role`
  - **Description:** Change the role associated with a wallet.

- **Authenticate Wallet**
  - **Method:** `POST`
  - **Endpoint:** `/authenticate`
  - **Description:** Authenticate a wallet using SSO.

- **Verify Auth Token**
  - **Method:** `POST`
  - **Endpoint:** `/verify_auth_token`
  - **Description:** Validate an authentication token.

- **Get Wallets Count**
  - **Method:** `GET`
  - **Endpoint:** `/get_wallets_count`
  - **Description:** Retrieve the total number of wallets.

- **Get Wallets Holding Coin**
  - **Method:** `POST`
  - **Endpoint:** `/get_wallets_holding_coin`
  - **Description:** Get wallets holding a specific coin.

---

## Transactions

- **Submit Transaction**
  - **Method:** `POST`
  - **Endpoint:** `/transaction`
  - **Description:** Process a transaction request.

- **Retrieve Transaction**
  - **Method:** `GET`
  - **Endpoint:** `/get_transaction`
  - **Description:** Fetch transaction details by hash.

---

## Blockchain & Governance

- **Get Block Height**
  - **Method:** `GET`
  - **Endpoint:** `/block_height`
  - **Description:** Retrieve the current block height.

- **Fetch DAG State**
  - **Method:** `GET`
  - **Endpoint:** `/fetch_dag_state`
  - **Description:** Get the state of the Directed Acyclic Graph (DAG) with optional pagination.

- **Submit Governance Proposal**
  - **Method:** `POST`
  - **Endpoint:** `/submit_proposal`
  - **Description:** Propose changes in the governance system.

- **Vote on Proposal**
  - **Method:** `POST`
  - **Endpoint:** `/vote_on_proposal`
  - **Description:** Vote on a submitted governance proposal.

- **Retrieve Proposal**
  - **Method:** `GET`
  - **Endpoint:** `/get_proposal`
  - **Description:** Retrieve a governance proposal by ID.

- **Retrieve All Proposals**
  - **Method:** `GET`
  - **Endpoint:** `/get_proposals`
  - **Description:** Fetch all proposal IDs.

- **Submit General Proposal**
  - **Method:** `POST`
  - **Endpoint:** `/submit_general_proposal`
  - **Description:** Submit a general non-governance proposal.

- **Vote on General Proposal**
  - **Method:** `POST`
  - **Endpoint:** `/vote_on_general_proposal`
  - **Description:** Vote on a general proposal.

- **Retrieve General Proposal**
  - **Method:** `GET`
  - **Endpoint:** `/get_general_proposal`
  - **Description:** Fetch a general proposal by ID.

---

## Token & Coin Management

- **Create Bearer Token**
  - **Method:** `POST`
  - **Endpoint:** `/create_token`
  - **Description:** Generate a new bearer token.

- **Create Coin**
  - **Method:** `POST`
  - **Endpoint:** `/create_coin`
  - **Description:** Issue a new coin with specified attributes.

- **Mint Token**
  - **Method:** `POST`
  - **Endpoint:** `/mint_token`
  - **Description:** Mint new tokens for a given symbol.

---

## Smart Contracts

- **Execute Smart Contract**
  - **Method:** `POST`
  - **Endpoint:** `/execute_contract`
  - **Description:** Execute a method within a smart contract.

- **Deploy Smart Contract**
  - **Method:** `POST`
  - **Endpoint:** `/deploy_contract`
  - **Description:** Deploy a new smart contract.

---

## Machine Learning

- **Predict**
  - **Method:** `POST`
  - **Endpoint:** `/predict`
  - **Description:** Make predictions using a neural network model.

- **Forecast**
  - **Method:** `POST`
  - **Endpoint:** `/forecast`
  - **Description:** Generate forecasts using a neural network model.
