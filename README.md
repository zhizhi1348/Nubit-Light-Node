# Run A Nubit Light Node
![Just Pics](https://github.com/zhizhi1348/Nubit-Light-Node/blob/main/Screenshot%202024-06-09%20220055.png)

[zhizhi twitter](https://x.com/zhiyarrr1) 

[Nubit Doscord](https://discord.gg/nubit)

## Nubit Incentivized Alpha Testnet
A native Bitcoin DA layer has announced that its Alpha testnet incentive program is now live. The Alpha testnet event is divided into three phases: community assembly, light node missions, and testnet adventures, with incentives offered at each stage.

Phase 1 is active

Join Testnet Dashboard

Remember to get faucet here

You'd better first to run a light node then use your node wallet to connect to the dashboard

***Light Node is a phase 2 task but better you run it now***

## System Requirements

RAM : 500MB	

CPU : Signle Core	

Disk : +30GB SSD

### Install Dependecies

```ruby
sudo apt-get update && sudo apt-get upgrade -y 
sudo apt-get install curl screen git-all build-essential glibc-source pkg-config libssl-dev clang git-lfs -y
```

### Install & Run

```ruby
# Open a screen
screen -S nubit

# Install and Run
curl -sL1 https://nubit.sh | bash
```
**You can minimze the screen with Ctrl+A+D**

### Save Mnemonic (12 Words)
```ruby
sudo cat $HOME/nubit-node/mnemonic.txt
```

### Cheatshits
```ruby
# Check logs
screen -r nubit

# minimze again
CTRL + A + D

# Restart Node if Needed
cd $HOME && cd nubit-node
./start.sh

## Delete Node if Needed
rm -rf $HOME/nubit-node $HOME/.nubit-light-nubit-alphatestnet-1
```
