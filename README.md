# Monad_Testnet

Deploy Smart Contract and Auto-send Token


1. Deploy Smart Contract
To deploy the smart contract, run the following commands:

```bash
wget -O DM.sh https://raw.githubusercontent.com/choir94/Airdropguide/refs/heads/main/DM.sh && chmod +x DM.sh && ./DM.sh
```
This command downloads the script, gives it execute permissions, and runs it to deploy the smart contract.



2. Clone the Repository
Clone the Monad Testnet repository using Git:

```bash
git clone https://github.com/yndra04/MonadTestnetDeploy.git
cd Monad-Testnet
```
This will clone the repository and navigate into the project directory.



3. Install Dependencies

To install the necessary dependencies, run the following commands:
```
sudo apt install python3 python3-pip -y
```

```bash
pip3 install -r requirements.txt
```

4. Run the Bot Using Screen

Now, run the bot in a screen session. This will keep the bot running even if you disconnect from the terminal.

```bash
screen -S MonadTestnetDeploy
```
After that, you can run the bot:

For a 60-second delay mode:
```bash
python3 bot.py
```

For a fast mode using Bot2.py:

```bash
python3 bot2.py
```
Once you’ve followed these steps, the deployment and auto-send bot should be running, ready to send tokens automatically.

-- Done!

