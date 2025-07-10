
# Octra Wallet generation Guide

📌 CodeSpace - https://github.com/codespaces

## Quick Start

1. **Clone the repository:**
   ```bash
   git clone https://github.com/octra-labs/wallet-gen.git
   cd wallet-gen
   ```

2. **Run the wallet generator webserver:**
   
   **Linux/macOS:**
   ```bash
   chmod +x ./start.sh
   ./start.sh
   ```
   
   **Windows:**
   ```bash
   start.bat
   ```
---

** Done Now  Back up private key**

Faucet  https://faucet.octra.network/
---

Discord - https://discord.gg/b6DGzdd3ph

---


#  TASK 1 : TOKEN TRANSFER

###  Open in Codespace

 Go to 👉 [https://github.com/octra-labs/octra_pre_client](https://github.com/octra-labs/octra_pre_client)

---

###   Install dependencies

In the Codespace terminal, run:

```bash
pip install -r requirements.txt
````

---

###  Create and edit wallet.json

Create the wallet file:

```bash
cp wallet.json.example wallet.json
```

Then open the file: wallet.json

Paste your test wallet details [That you generate Early ] 



```
{
  "priv": "private key here",
  "addr": "octxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx",
  "rpc": "https://octra.network"
}
```

---

###  Send a test transaction

```bash
python cli.py send --to oct5ziFzQJkiJFPfcQeuAmp4vhfQgjwb8gyx2W2TZdGhzJm --amount 0.01
```

Send tokens to other Check  explorer: https://octrascan.io/

