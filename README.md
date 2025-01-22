# T3RN BRIDGE BOT

![t3rn](assets/img1.png)

A bot designed to automate transactions and bridge assets on the t3rn network, making the process seamless and efficient. Now supports both Optimism Sepolia and Arbitrum Sepolia testnets.

**Register : [T3rn Airdrop](https://bridge.t1rn.io/)**

## BOT FEATURE

- Multi Account Support
- Auto Swap Betwen OP > ARB OR ARB > OP

## PREREQUISITE

- Git
- Node JS
- OP Sepolia ETH BALANCE / ARB Sepolia ETH BALANCE Depends on Config.

## SETUP & CONFIGURE BOT

### LINUX & MAC OS

- Install Prerequites:
  ```
  curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.40.0/install.sh | bash
  echo 'export NVM_DIR="$HOME/.nvm"' >> $HOME/.bash_profile
  echo '[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh"  # This loads nvm' >> $HOME/.bash_profile
  echo '[ -s "$NVM_DIR/bash_completion" ] && \. "$NVM_DIR/bash_completion"  # This loads nvm bash_completion' >> $HOME/.bash_profile
  source $HOME/.bash_profile
  nvm install --lts
  node -v
  npm -v
  sudo apt-get update
  sudo apt-get upgrade
  ```

1. Clone project repository
   ```
   git clone https://github.com/hokireceh/t3rn.git && cd t3rn
   ```
2. Install dependencies
   ```
   npm install
   ```
3. Copy all folder
   ```
   cp accounts/accounts_tmp.js accounts/accounts.js && cp config/config_tmp.js config/config.js
   ```
4. Configure the accounts
   ```
   nano accounts/accounts.js
   ```
   Setup your accounts using PK or Seed
5. Configure the config
   ```
   nano config/config.js
   ```
   Setup your config using OP / ARB
6. To start the app run 
   ```
   npm run start
   ```
   

## UPDATE BOT

To update bot follow this step :
1. Run
   ```
   git pull
   ```
   or 
   ```
   git pull rebase
   ```
   If error run
   ```
   git stash && git pull
   ```
2. Run
   ```
   npm update
   ```

3. Start the bot.

## NOTE

**You can configure:**
- Amount to Bridge
- Network
- Bridge Contract
- Raw Data
On Config File

If you did'nt get BRN Point, change the config OP or ARB RAW DATA with yours. Where to get it ? do manual TX from ARB to OP or OP to ARB, and go to explorer and copy the Input Data as HEX. Or you can just copy paste from wallet confirmation approval on input / data section.

## ☕️ Traktir kopinya & Thanks for Supporting us:

- [https://sociabuzz.com/silviaroyshieta/tribe](https://sociabuzz.com/silviaroyshieta/tribe)
- **EVM : `0x5ded4a50c40cfd9c040dff3c7f4aa2252136c4f2`**
- **SOLANA : `6iRWskAPXvrwiEiJe87qjtCyDJ5uq8YWUGZiKZhHY8K3`**

## LICENSE

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
