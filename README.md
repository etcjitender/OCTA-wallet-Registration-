
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


# 🪙 TASK 1 : TOKEN TRANSFER

### 🔹 STEP 1: Open in Codespace

1. Go to 👉 [https://github.com/octra-labs/octra_pre_client](https://github.com/octra-labs/octra_pre_client)
2. Click the green `Code` button  
3. Select → `Open with Codespaces` → `+ New codespace`
4. Wait for the environment to fully load

---

### 🔹 STEP 2: Install dependencies

In the Codespace terminal, run:

```bash
pip install -r requirements.txt
````

---

### 🔹 STEP 3: Create and edit wallet.json

Create the wallet file:

```bash
cp wallet.json.example wallet.json
```

Then open the file: wallet.json

Paste your test wallet details (⚠️ never use your real wallet):
![Wallet Generation](IMG_20250630_110429.png)


```
{
  "priv": "private key here",
  "addr": "octxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx",
  "rpc": "https://octra.network"
}
```

---

### 🔹 STEP 4: Send a test transaction

```bash
python cli.py send --to oct5ziFzQJkiJFPfcQeuAmp4vhfQgjwb8gyx2W2TZdGhzJm --amount 0.01
```

🟢 That’s it! You can now access the wallet UI and make transactions to addresses found on the explorer: https://octrascan.io/

---





Discord - https://discord.gg/b6DGzdd3ph

---
