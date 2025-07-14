# Week1-Task--Octra
Week1 Task -Octra
Quest1 - Send Tokens

Step 1
```bash
pip install -r requirements.txt
```
Step 2
```bash
cp wallet.json.example wallet.json
```
Step 3

Then open the file: wallet.json

Paste your test wallet details
```bash
{
  "priv": "private key here",
  "addr": "octxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx",
  "rpc": "https://octra.network"
}
```

Step 4 : Send a test transaction
```bash
python cli.py send --to octECeUEKyTeFMYBumubqnskCYo292LJaDi8pR7ETJB4NYz --amount 0.01
```

send to any address 

