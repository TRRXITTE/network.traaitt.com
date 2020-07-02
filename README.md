***Note:*** This repository is currently unmaintained. If you want to take over the maintenance and support of this project, let us know!

# traaitt-Blockchain-Explorer
Block explorer for traaitt CryptoNote based cryptocurrency.

#### Installation

1) It takes data from daemon traaittnetwork. It should be accessible from the Internet. Run traaittnetwork with open port as follows:
```bash
./traaittnetwork --enable-cors="*" --enable-blockexplorer --rpc-bind-ip=0.0.0.0 --rpc-bind-port=11898
```
2) Just upload to your website and change 'api' variable in config.js to point to your daemon.


### Development
Devs:
TRRXITTE inc.

### Note

A lot of this code is from the great Karbovanets/Karbowanec-Blockchain-Explorer
