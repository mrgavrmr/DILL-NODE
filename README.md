# DILL-NODE
# Guide to Participating in the Dill.xyz Project and Launching a Node

>  Hello everyone! Today I'll show you how to set up a reward-earning node for the Dill project – backed by undisclosed investment from Santiago R. Santos and several small funds, plus officially incubated by Binance with confirmed airdrops.

**Dill.xyz is a scalable decentralized Data Availability Network fully aligned with Danksharding’s roadmap. With funding from Binance Labs and other VCs, the project offers participants a unique chance to become early network validators.**
**[CryptoRank](https://cryptorank.io/ico/dill#funding-rounds "CryptoRank")**

## TO LAUNCH THE NODE YOU MUST GET TOKENS. For now we are getting tokens, I will add the installation instructions a bit later

## There is no point in just farming tokens, you must launch the node. At least that is what the moderators say in the offline discord

**Now anyone can launch a node and/or earn dill coins.**

## There are 2 nodes from the project

**- Light Validator
3600 DILL tokens required
Server system requirements 2CPU\2RAM\20GB**

**- Full Validator
36000 DILL tokens required
Server system requirements 4CPU\8RAM\256GB**

**Action algorithm:**
1. Earn tokens ([Galxe company](https://app.galxe.com/quest/Dill/GCgJAtvF1h?referral_code=GRFr2Jksp6m_3iKpJtyMo-YgzWGP73MgGqyi5HsRX40aLZM "Galxe company") and communication in [discord](https://discord.com/invite/3RcBhF7n "discord")).
2. Wait for a snapshot (every Thursday).
3. Request your tokens to your wallet in the **#alps** channel.
4. If you want, proceed to installing light node. If not, wait for news.

## How to earn points and get the right to run a node?

> Here are the criteria for the level for which you can get tokens

[![](https://img1.teletype.in/files/8c/23/8c23d558-a448-4596-9f3b-72c25546a00c.png)](https://img1.teletype.in/files/8c/23/8c23d558-a448-4596-9f3b-72c25546a00c.png)

## **Method 1**
**Take part in the [Galxe campaign](https://app.galxe.com/quest/Dill/GCgJAtvF1h?referral_code=GRFr2Jksp6m_3iKpJtyMo-YgzWGP73MgGqyi5HsRX40aLZM "Galxe campaign"), be sure to use my referral link. This way you can thank me and speed up the writing of the guide =). In any case, the first task is a must. It will make life easier in the future, and they often started giving rewards for such tasks.**

## **Method 2**
**Go to discord and just start chatting. Ask stupid and smart questions. You can chat off-topic. To complete this task, you will need about 150 messages. It is done quickly and easily.**

## How to check your level?
Go to the discord channel and enter !rank or /rank (No CD 2 hours)

[![](https://img2.teletype.in/files/58/29/5829fd5f-8516-4109-8109-91bf01d37437.png)](https://img2.teletype.in/files/58/29/5829fd5f-8516-4109-8109-91bf01d37437.png)

## How to get dill tokens to your wallet?

Go to the **#alps channel**, enter **$request** and your **evm wallet**.

If you just **enter $request**, you will see how many tokens are available to you.

[![](https://img4.teletype.in/files/3d/60/3d600134-f8e0-4462-9a64-5b89cfcb2458.png)](https://img4.teletype.in/files/3d/60/3d600134-f8e0-4462-9a64-5b89cfcb2458.png)

## Installing and configuring node

[![](https://img2.teletype.in/files/9f/17/9f17490c-99fb-4ed5-bc30-03862ccb3904.png)](https://img2.teletype.in/files/9f/17/9f17490c-99fb-4ed5-bc30-03862ccb3904.png)

**Add Dill network to wallet manually**
RPC URL: https://rpc-alps.dill.xyz 

Chain ID: 102125 

Currency Symbol: DILL 

Explorer: https://alps.dill.xyz

**Start a new Dill node**

**Update the system and install the required dependencies**

`sudo apt update && sudo apt upgrade -y`

`sudo apt install curl -y`

`curl -s https://raw.githubusercontent.com/odanoder/scripts/refs/heads/main/base/base_packages.sh | bash`

**Launch**

`curl -sO https://raw.githubusercontent.com/DillLabs/launch-dill-node/main/dill.sh  && chmod +x dill.sh && ./dill.sh`

**Wait for the file to download. During testing, the download speed may be slow**

**If such an error occurs, press any key and continue the installation.**

[![](https://img3.teletype.in/files/e7/45/e745fd05-3850-4e32-b23d-33d6da87179a.png)](https://img3.teletype.in/files/e7/45/e745fd05-3850-4e32-b23d-33d6da87179a.png)

**As soon as you see the message "Step 1 completed" press "Enter".**

[![](https://img4.teletype.in/files/f8/90/f8909cd0-f340-4e5a-bd0f-332b0f8725e4.png)](https://img4.teletype.in/files/f8/90/f8909cd0-f340-4e5a-bd0f-332b0f8725e4.png)

**Press any key.**

Select a new or existing mnemonic:
1 - Create a new mnemonic. If you are installing it for the first time.
2 - If there is an existing mnemonic.
[![](https://img4.teletype.in/files/7c/66/7c661723-0290-49e2-b618-0524886eb300.png)](https://img4.teletype.in/files/7c/66/7c661723-0290-49e2-b618-0524886eb300.png)

In our case, we select, press 1 and click the ENTER key - new installation

**SAVE THE PASSWORD and press the ENTER key**
[![](https://img2.teletype.in/files/90/49/9049673a-339f-4fba-9d42-e78ffe753fc7.png)](https://img2.teletype.in/files/90/49/9049673a-339f-4fba-9d42-e78ffe753fc7.png)

**Choose 1 or 2**
1) If you have only 3600 tokens
2) If you have 36,000 tokens.
[![](https://img4.teletype.in/files/b7/d1/b7d12ae7-90eb-46f9-a6b5-386966c54d80.png)](https://img4.teletype.in/files/b7/d1/b7d12ae7-90eb-46f9-a6b5-386966c54d80.png)

validator mnemonic and wallet mnemonic to which we requested tokens, these are 2 different wallets.

Next, we enter the address to which we requested tokens in Discord twice.

A window like this will appear, press ENTER
[![](https://img2.teletype.in/files/d8/3a/d83ab1b2-f771-4465-aa01-d99d26e67c12.png)](https://img2.teletype.in/files/d8/3a/d83ab1b2-f771-4465-aa01-d99d26e67c12.png)

**We complete the installation. The long underlined line is the address of our node.**

[![](https://img2.teletype.in/files/59/58/5958fd27-1cdb-4a91-ab43-483f6ec7ce26.png)](https://img2.teletype.in/files/59/58/5958fd27-1cdb-4a91-ab43-483f6ec7ce26.png)

**To check the node's functionality, enter the command**

`bash $HOME/dill/health_check.sh`
There should be a line like this. 2025-03-25 15:45:33 UTC > Node health check passed - this means that the node is working properly.

Go to the directory and copy all the files from the folder to your computer
`cd /root/dill/validator_keys`

Then go to the browser and open the link https://staking.dill.xyz/.
[![](https://img2.teletype.in/files/1a/b2/1ab24776-6fa4-4612-beff-23850aec8722.png)](https://img2.teletype.in/files/1a/b2/1ab24776-6fa4-4612-beff-23850aec8722.png)

**Next we will be asked to connect our wallet and add the Alps network to it.**
[![](https://img2.teletype.in/files/dd/cb/ddcb961f-ad21-4be5-8619-3d21ef6350cf.png)](https://img2.teletype.in/files/dd/cb/ddcb961f-ad21-4be5-8619-3d21ef6350cf.png)

**After successful connection you will see the following:**
[![](https://img4.teletype.in/files/b1/7e/b17e49be-02a5-4f74-b19e-4e4c4c1c7df5.png)](https://img4.teletype.in/files/b1/7e/b17e49be-02a5-4f74-b19e-4e4c4c1c7df5.png)

**Make sure you have connected your wallet, which you requested tokens to in Discord and which you entered when installing the node. If everything is OK, check the box and click continue. Or connect another wallet.**

[![](https://img1.teletype.in/files/c7/83/c7833bed-fb8f-4105-b1c6-bc6e6cc3482b.png)](https://img1.teletype.in/files/c7/83/c7833bed-fb8f-4105-b1c6-bc6e6cc3482b.png)

**Next, we click the Confirm deposit button to send 3600 tokens from the wallet to our validator's address. And then we wait for the status to change to this:**

[![](https://img1.teletype.in/files/42/c3/42c34375-38c7-4f9c-9ec8-98637053695c.png)](https://img1.teletype.in/files/42/c3/42c34375-38c7-4f9c-9ec8-98637053695c.png)

**Go to the explorer and enjoy.**

When we enter the node address [in the explorer](https://alps.dill.xyz/validators "in the explorer"), we need to add `0x` before the node address

Before your validator appears in the list, you will have to wait about 12 - 15 hours.

`/show_pubkey.sh` the command must be executed from the dill folder (cd dill to go to the folder)

## Useful commands:
Check the node status (if we see Node health check passed, then everything is fine)
**Start the node**
`bash $HOME/dill/start_dill_node.sh`

**Stop the node**
`bash $HOME/dill/stop_dill_node.sh`

**View the node synchronization status and the node status**
`bash $HOME/dill/health_check.sh -v`

**Node health check passed - the node is working fine.**
Synchronization done, current slot is 1405136 - synchronization is complete.

## How to add more validators to the installed node?
**Adding new validators**
After you have staked 3600 tokens on the first validator, you can create additional validators if you have 3600+ tokens for each of them.

**Instructions:**
Run the script:
Go to the **dill** folder and run the command:
`bash $HOME/dill/2_add_validator.sh`

**Create a new wallet:**
1 **Select option 1 (create a new wallet).**
Save your secret phrase (you will need it for recovery).
 Press Enter.
 Enter the wallet address you received your tokens to twice in Discord.
2 **Stake tokens:**
 After creating the second validator, you need to stake 3600 tokens to it.
 Adding the following validators:
3 **Repeat steps 1-3 for each new validator.**

⚠️**Important:**

The maximum number of validators per node is 10.
Each validator requires 3600 tokens. If you do not have enough funds, creating new validators is useless.

**X profile https://x.com/MrGavrMr**
