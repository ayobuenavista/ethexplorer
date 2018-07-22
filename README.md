# ETH Block Explorer based off github.com/etherparty/explorer

![ETH Block Explorer Screenshot](https://i.imgur.com/8dPnAct.jpg)

## License

The code in this branch is licensed under GPLv3 (see LICENSE file)
Feel free to modify or reuse the code here.

## Installation

```
git clone https://github.com/ayobuenavista/ethexplorer
npm install
npm start
```

Run ganache-cli
```
 ganache-cli --accounts 5 --db ganache-db --mnemonic 'gesture rather obey video awake genuine patient base soon parrot upset lounge' --networkId 5777 --debug
```

Then visit http://localhost:8000 in your browser of choice after you start the explorer

## Updates since original etherpaty/explorer base:

- Regular Expressions completed for Addresses, Block #s, and Transacions IDs (aka Search works great)
- The theme is based off Bootstrap V3 for responsive design.
- You can easily change from a cosmo or light theme utilizing https://bootswatch.com
- There is a basic API implemented now as well as well as a Ethereum Blockchain Information page
- Realtime ETH/USD Price Ticker
- Realtime Ethereum Hashrate
- Address Pages are integrated with Shapeshift to easily send a payment to an address.
- Responsive design
- Fontawesome Icons
- Block Time Averages
- Gas Prices/Limits
- Total/Current Difficulty
- Realtime latest blocks and recent transactions
- Other random blockchain info stats were added

_If you want to disable auto refresh/auto new block show, just comment line no 13-22 at: [app/scripts/controllers/mainController.js](https://github.com/sthnaqvi/explorer/blob/3a08032fc8550a863ae49acf0bdd45bfe2d961d1/app/scripts/controllers/mainController.js#L13-L22)_
