# HW_18_Blockchain
 
 Welcome ZBank Team!

Today we will walk through the blockchain we will be using for this bank.

(The Blockchain folder needed is already on your systems. Needed later.)

We will start with two downloads. GitBash and MyCrypto wallet. Please start with the GitBash download and we will go from there.

Thank You. Now we will open GitBash by the start menu on your own system. Type “GitBash”. Open and let’s begin.

 

SCREENSHOT: Configure_genesis.png

On GitBash, you will be starting in your Desktop folder and we will practice a “ls” command. Please type “ls” and then type “cd Blockchain_Tools” and then ENTER.

Then in the current state enter “cd geth then TAB, then ENTER.

This is now the /geth-alltools folder.

Now still looking and the Configure_genesis.png, we will enter: . /puppeth

We will now enter our proud name of “jpnet” as our network name.

 

SCREENSHOT: No_Fund.png

We will now enter 2 as the choice to “Configure new genesis”

Next question, we will enter 1 for “Create new genesis from scatch”

Here at ZBank, we are using choice number 2 for “proof-of-authority”

Our blocks are going to be set at 15 seconds for default. Please enter 15 then press ENTER.

At this point we will fund accounts. Enter two account numbers and press ENTER.

Next, ENTER “no” because we will not fund any at this point.

 

SCREENSHOT: Ctrl+C.png

On this screenshot, we will create our own chain/network ID.

Please enter 888 and press ENTER.

Now we will, enter Ctrl+C to exit this stage.

 

 

SCREENSHOT: Node1 mine.png

Now we will get our Nodes running. In the /geth-alltools folder again, we will enter:  

. /geth –datadir node1 –mine

Then press ENTER and we should see Starting of the Ethereum mainnet…

At the bottom of this screenshot please notice an enode. Copy that entire enode and save it.

You will need from “enode://…all the way to…30303 --ipcdisable”

 

SCREENSHOT: Node 2 boot.png

Again, please make sure you “cd” to the geth-alltools folder. Now enter:

./geth –datadir node2 –port 30304 –bootnodes “paste enode next” and then ENTER

Node 2 is now running.

 

SCREENSHOT: MyCrypto Wallet.png (735)

Let’s now open MyCrypto Wallet now. Start menu on your systems and enter MyCrypto and open the wallet.

Here we will “Create New Wallet”

Walk through the steps and REMEMBER TO SAVE YOUR MNIMONIC PHRASE!

“Select an Address” screen will be reached and pick an address and then “Unlock”

 

SCREENSHOT: Private Key.png

At this point, I have highlighted the address I was using, and the Private Key is covered. Press the “eye” button to show your key to copy and paste it safely.

 

SCREENSHOT: Custom Node.png

Please enter all info that is shown in this screenshot.

Then “Save & Use Custom Node”

 

 
SCREENSHOT: View & Send.png

On this screenshot, we will see our address or enter it if you don’t see it. Addresses should start with “Ox” and more to follow.

Now, enter an amount we want to send. Set a fee and “Send Transaction”

 

SCREENSHOT: Confirm Transaction.png  

Here is our confirmation of our transaction and we will review and hit “Send”

 

 

SCREENSHOT: Pending.png

Here we will see our “Pending” transaction.

 

SCREENSHOT: Recent Transactions.png

In this screenshot, the “Recent Transactions” are shown and our network is set-up!

Thank You all for your attention and lets keep ZBank moving!

 

 

 
