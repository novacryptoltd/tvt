# tvt
**Transaction Validator Tool for EOSBEES**

**Powered by NovaCrypto**

![image](https://github.com/novacryptoltd/tvt/assets/40249338/ef6b6aaa-d96f-4398-b20f-4d60fb57442e)


**The validator tool (TVT) uses RPC get_actions method by Hyperion History Solution V2**

**To know if a transfer has been made (transfer.from) via the eosio.evmin (bridge transfer.to) to eosevm from an account (a Bee) with a token (transfer.symbol) for a particular date (after or before)**
https://eos.hyperion.eosrio.io/v2/history/get_actions?transfer.from=wesleymouch2&transfer.to=eosio.evmin&transfer.symbol=USDT&after=2024-02-26T00:00:00.000Z

**To know if an action has been executed by a smart contract(account) for an action (act.name) and by an account (from) for a particular date (after or before)**
https://eos.hyperion.eosrio.io/v2/history/get_actions?account=nova3mindweb&act.name=addsolution&from=detroitfunds&after=2024-02-26T00:00:00.000Z

**To know if a transfer has been made (transfer.from) to defibox (swap.defi transfer.to) from an account (a Bee) with a token (transfer.symbol) for a particular date (after or before)**
https://eos.hyperion.eosrio.io/v2/history/get_actions?transfer.to=swap.defi&transfer.from=arbys.gm&transfer.symbol=USDT&before=2023-06-28T00:00:00.000Z

**CURL2PHP to convert those commands in PHP Code**

Input his a CSV file with one column made of rows containing the EOS Account of a Bee  <-- the eos account is verified if exists

Output is a CSV file with the parameters of the UI as shown on the above image

