## Note: this currently runs on the Morden Testnet.
This app is a view-only version of DPet.  To actually write and scan microchips, use https://github.com/phillyfan1138/DPetEmbedded.
## Production (mist): 

Download mist from https://github.com/ethereum/mist/releases.  Add accounts as necessary.  Then navigate to https://phillyfan1138.github.io/DPet/.  This will only run in the Mist browser.

## Development:

Download and install geth and add it to your path.  Add at least one account.  This process is described here: https://github.com/ethereum/go-ethereum/wiki/geth.  Also requires nodejs https://nodejs.org/en/.  

In cmd/terminal, go to the directory containt index.js.  Type "npm install".  Wait for the downloads.  Then type "node index.js".  It will prompt for the password used in creating the account created for ethereum above.  Then it will start up the Geth server.  Once done, the browser for the dapp will open.  

## Use:

To actually submit records, you have to pay ether (currently a .1 ether.  This runs on morden testnet, so its not real).  To simply test whether this works, search "123" to retrieve results. This does not require any ether.



