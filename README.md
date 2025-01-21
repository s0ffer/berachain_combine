# Berachain Script:

This script provides an interface for interacting with Berachain, enabling users to manage tokens, perform swaps, and engage with staking mechanisms. Below is a guide to the functionalities and how to set up and run the script on your system.

![show](https://github.com/user-attachments/assets/6f9e0f4b-f7e6-437c-a467-79a552aeec0c)

---

## Features

### 1. `claim_faucet`
**Description:**
Requests funds from the Berachain faucet.
### 2. `get_bera_balance`
**Description:**
Fetches the balance of BERA tokens in your wallet.
### 3. `swap_bera_to_ibgt`
**Description:**
Swaps BERA tokens for iBGT tokens.
### 4. `deposit_ibgt_bera`
**Description:**
Deposits iBGT and BERA tokens into a specific pool.
### 5. `deposit_to_ibgt_wbera_station`
**Description:**
Deposits iBGT and wBERA into the station contract.
### 6. `get_bgt_reward`
**Description:**
Claims staking rewards in the form of BGT tokens.
### 7. `delegate_bgt_to_validator`
**Description:**
Delegates BGT tokens to a validator (You can add them by changing validators in Berachain class).
### 8. `confirm_delegation`
**Description:**
Confirms the delegation of BGT tokens to validators.

---

## User Interface

- **Menu Navigation:**
  - Use **arrow keys** to navigate through the menu.
  - Press **Enter** to select an option.
  - Use **Tab** to switch between buttons.

---

## Setup Instructions

### Step 1: Clone the Repository
```bash
git clone <repository-url>
cd <repository-folder>
```

### Step 2: Create a Virtual Environment
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### Step 3: Install Dependencies
```bash
pip install -r requirements.txt
```

### Step 4: Configure Environment Variables
Add API-Key of Capmonster in `api_key.txt`, private keys of wallets in `private_keys.txt`, proxies into `proxies.txt`

### Step 5: Run the Script
```bash
python app.py
```

---

## Requirements
- Python 3.11 or above
- Dependencies listed in `requirements.txt`

---

## Contributing
Feel free to fork this repository, create a new branch, and submit a pull request with your improvements or new features.

---

## License
This project is licensed under the MIT License. See the `LICENSE` file for more details.

