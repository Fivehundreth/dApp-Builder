# dApp-Builder

This is a dApp-browser and Ethereum wallet, stored on a mobile device, and allows you to make transactions when working with Ethereum dApps on your iOS or Android device.

The principle is to add additional html and js to the web page of dApp frontend: the library [Web3.js](https://github.com/ethereum/web3.js), the script that creates the Web3 object that interacts with dApp Builder Ethereum node, and additional scripts to work with the user's wallet and signing transactions. The Ethereum wallet stored on a mobile device is implemented using [Go Ethereum Account management](https://github.com/ethereum/go-ethereum/wiki/Mobile:-Account-management).

This solution is made as a widget for iBuildApp mobile app creation platform. You can try how it works on Android [here](http://ibuildapp.com/dapps.php).