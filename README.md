# Catalyst Explorer
Block explorer for Catalyst CryptoNote based cryptocurrency.

#### Installation

1) It takes data from daemon `catalystd`. It should be accessible from the Internet. Run `catalystd` with open port as follows:
```bash
./catalystd --enable-cors="*" --enable_blockexplorer --rpc-bind-ip=0.0.0.0 
```
2) Just upload to your website and change 'api' variable in config.js to point to your daemon.

### Development
Devs: @taegus @katz @devopsralf @n8tb1t

### Note
A lot of this code is from the great Karbovanets/Karbowanec-Blockchain-Explorer
