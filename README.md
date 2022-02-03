# Challenge19
Blockchain Wallet

With fintech_finder.py, we created code that allows us to find fintech professionals and list them as candidates. We can then choose to hire these candidates based on their hourly rate and hours hired. However, what is unique about this code is that we pay the candidate with cryptocurrency and the transaction is automatically logged onto the blockchain. The cryptocurrency is paid directly to their blockchain account address.

## Technology

We use the functions from the file crypto_wallet.py. All the imported libraries used in this Challenge assignment is:

```
import os
import requests
from dotenv import load_dotenv
from bip44 import Wallet
from web3 import Account
from web3 import middleware
from web3.gas_strategies.time_based import medium_gas_price_strategy
import streamlit as st
from dataclasses import dataclass
from typing import Any, List
from web3 import Web3
```

## Usage

![Streamlit Transaction](/Images/Streamlit.JPG)
![Ganache Accounts](/Images/ganache.JPG)
![Ganache Transaction Details](/Images/transaction_details.JPG)