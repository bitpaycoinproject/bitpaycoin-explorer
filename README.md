# BitpayCoin Blockchain Explorer
Block explorer for BitpayCoin CryptoNote based cryptocurrency.

#### Installation

1) It takes data from daemon Bitpaycoind. It should be accessible from the Internet. Run Bitpaycoind with open port as follows:
```bash
./Bitpaycoind --enable-cors="*" --enable-blockexplorer --rpc-bind-ip=0.0.0.0 --rpc-bind-port=11787
```
2) Just upload to your website and change 'api' variable in config.js to point to your daemon.

### Development
Donate: [BPAY] bPAYj5GbjoD6Y6G2we4j5HVMPco7KHb3g2qGLnZCqnDEFnPdLBh3PbRd7fUcRMEZTd8kwsEmiaSYeX9meRS6jXGUZzzVdrVidXd

### Note
A lot of this code is from the great Karbovanets/Karbowanec-Blockchain-Explorer
