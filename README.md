# Digiplay Gaming SDK

A production-ready SDK to integrate DigiByte blockchain functionalities into games. The SDK provides modules for wallet management, transaction creation/signing/broadcasting, tokenization, and asynchronous blockchain event listening. It is designed to empower game developers with blockchain-powered features such as secure micropayments, in-game asset management, and real-time event handling.

## Features

- **Wallet Management:** Create new wallets, derive addresses, and securely manage keys.
- **Transaction Handling:** Build, sign, and broadcast transactions with retry logic.
- **Tokenization:** Issue and transfer tokens representing in-game assets.
- **Event Listening:** Asynchronously listen for blockchain events to update game state.
- **Modular Design:** Easy to extend and integrate with various game engines and platforms.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Repository Structure](#repository-structure)
- [Configuration](#configuration)
- [Contributing](#contributing)
- [License](#license)
- [Changelog](#changelog)

## Installation

### Prerequisites

- Python 3.7 or higher
- pip (Python package installer)

### Dependencies

- `aiohttp`  
  Install via pip:
  ```bash
  pip install aiohttp
