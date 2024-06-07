# tvt
**Transaction Validator Tool**

**Powered by NovaCrypto**

![image](https://github.com/novacryptoltd/tvt/assets/40249338/c1819596-94ae-40a3-8420-b8e3556c4b4e)

![image](https://github.com/novacryptoltd/tvt/assets/40249338/4887a6f5-2ea5-4d41-a346-6cc0cd04606d)


**The validator tool (TVT) uses RPC get_actions method by Hyperion History Solution V2**

**To know if a transfer has been made (transfer.from) via the eosio.evmin (bridge transfer.to) to eosevm from an account with a token (transfer.symbol) for a particular date (after or before)**
https://eos.hyperion.eosrio.io/v2/history/get_actions?transfer.from=wesleymouch2&transfer.to=eosio.evmin&transfer.symbol=USDT&after=2024-02-26T00:00:00.000Z

**To know if an action has been executed by a smart contract(account) for an action (act.name) and by an account (from) for a particular date (after or before)**
https://eos.hyperion.eosrio.io/v2/history/get_actions?account=nova3mindweb&act.name=addsolution&from=detroitfunds&after=2024-02-26T00:00:00.000Z

**To know if a transfer has been made (transfer.from) to defibox (swap.defi transfer.to) from an account with a token (transfer.symbol) for a particular date (after or before)**
https://eos.hyperion.eosrio.io/v2/history/get_actions?transfer.to=swap.defi&transfer.from=arbys.gm&transfer.symbol=USDT&before=2023-06-28T00:00:00.000Z

**CURL2PHP to convert those commands in PHP Code**

Input is a CSV file with one column made of rows containing the EOS Account  <-- the eos account is verified if exists

Output is a CSV file with the parameters of the UI as shown on the above image

