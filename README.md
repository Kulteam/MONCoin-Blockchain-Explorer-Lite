# MONCoin-Blockchain-Explorer-Lite
Block explorer for MONCoin CryptoNote based cryptocurrency.

#### Installation

1) It takes data from daemon MONCoind. It should be accessible from the Internet. Run MONCoind with open port as follows:
```bash
./MONCoind --enable-cors="*" --enable-blockexplorer --rpc-bind-ip=0.0.0.0 --rpc-bind-port=12898
```
2) Just upload to your website and change 'api' variable in config.js to point to your daemon.


### Made by
Devs:
    @Kulteam

### Note
Forked from Plenteum Blockchain Explorer
A lot of this code is from the great Karbovanets/Karbowanec-Blockchain-Explorer
