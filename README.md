# UltraNote-Blockchain-Explorer
Block explorer for UltraNote CryptoNote based cryptocurrency.

#### Installation

1) It takes data from daemon ultranoted. It should be accessible from the Internet. Run ultranoted with open port as follows:
```bash
./ultranoted --rpc-bind-ip=127.0.0.1 --rpc-bind-port=31000
```
2) Just upload to your website and change 'api' variable in config.js to point to your daemon. You will also need to go through the API pages and update the links to point to your daemon IP as well. The API pages are located in the "q/" directory, the index.php file must point to your daemon IP. You must change all 4 of them "hashrate" "reward" "supply" "height"
