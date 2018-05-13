# Vote-testnet
### vote portal : http://www.eosio.sg

### Join As BP
If you want to join vote testnet hosted by eosio.sg. Please follow steps:
1. create account using portal in http://www.eosio.sg  This account will be used as your producer account. Save the private key and public key.
2. update your keys, producer name and agent name in config.ini, the keys and producer name should use as account created above. you can search <changehere> in config.ini for quick replace.
3. start your node
4. register your bp using script
excute chmod 777 reg_prod.sh, and register your bp using script: ./reg_prod.sh <my-name> <public-key> <my-url>


```
for example:   
./reg_prod.sh eosiosg EOS6MRyAjQq8ud7hVNYcfnVPJqcVpscN5So8BhtHuGYqET5GDW5CV http://eosio.sg
```
