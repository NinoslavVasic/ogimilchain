<h1>Proof of Auth in local blockchain</h1>

<h1> OgimilChain<h1>



<h2>Local blockchain: step by step</h2>


1.  <p>Using <code>GETH</code> create 2 virtual nodes</p>

![](https://github.com/NinoslavVasic/ogimilchain/blob/master/screenshots/01-gen_acc.PNG)


2.  <p>Create local network and Genesis Block using <code>puppeth</code></p>


![](https://github.com/NinoslavVasic/ogimilchain/blob/master/screenshots/02-puppeth_og.PNG)


3. <p> New genesis configuration export json files into specific folder. </p>


![](https://github.com/NinoslavVasic/ogimilchain/blob/master/screenshots/03-add_acc_exp_gen.PNG)


4. <p> Initialize nodes1 and node2. <p>
   <p> NOTE: only ogimil.json is needed in further development</p>


![](https://github.com/NinoslavVasic/ogimilchain/blob/master/screenshots/04-init_nodes.PNG)


5. <p> Open separate GitBash to start 'ogimilchain' mining node1 <p>

   <p> NOTE: IT IS IMPORTANT TO CONNECT NODES  by entering enode of the node1 when running node2 mining </p>


![](https://github.com/NinoslavVasic/ogimilchain/blob/master/screenshots/05-node1.PNG)

7. <p> Open separate GitBash to start up mining full thread on 'ogimichain' - mining node2 </p>

   <p> NOTE: IT IS IMPORTANT TO CONNECT NODES  by entering enode of the node1 when running node2 mining</p>

![](https://github.com/NinoslavVasic/ogimilchain/blob/master/screenshots/06-node2.PNG

   <p> For purpose of connecting local blockchain to a digital wallet one have to create it. In this exercise, I used MyCrypto, protected with the mnemonic phrase. It is important to keep the wallet keys in a safe place in order to protect the funds in your wallet.</p>

8. <p>  Chose Kovan network and login to your wallet </p>
   <p> Make sure that Kovan  network is chosen and then login with Mnemonic phrase. </p>


![](https://github.com/NinoslavVasic/RocketChain/blob/master/Screenshots1/9_mycrypto.png)

9. <p> Chose wallet to pre-fund </p>

   <p> Unlock the wallet. </p>

![](https://github.com/NinoslavVasic/RocketChain/blob/master/Screenshots1/10_mn_login.png)

10. <p> Wallet info - private key </p>
    <p> After login to your wallet chose wallet info from dropdown menu, copy private key and store it in safe file.  </p>

![](https://github.com/NinoslavVasic/RocketChain/blob/master/Screenshots1/11_wallet_priv_key.png)

11. <p> Set Up Your Custom Node </p>

    <p> Open up MyCrypto, then click Change Network at the bottom left. Click "Add Custom Node", then add the custom network information that you set in the genesis.</p>

    <p>Make sure that you scroll down to choose Custom in the "Network" column to reveal more options like Chain ID.</p>


![](https://github.com/NinoslavVasic/ogimilchain/blob/master/screenshots/08-set_node.PNG)

12. <p> OgimilChain Network </p>

    <p> On the left bottom side of the screen, click on the "change network" and scroll down to the newly created ogimil network.  </p>

![](https://github.com/NinoslavVasic/ogimilchain/blob/master/screenshots/09-keystore_login.PNG)

   
   <p> Chose ogimil network and login with keystore file which you have previously stored in a safe file.  </p>

![](https://github.com/NinoslavVasic/ogimilchain/blob/master/screenshots/10-login2.PNG)



13. <p> Transaction Initiation </p>


![](https://github.com/NinoslavVasic/ogimilchain/blob/master/screenshots/11-initiate_tx.PNG)

14. <p> Confirm if everyting is valid before executing transaction and click on the button. </p>

![](https://github.com/NinoslavVasic/ogimilchain/blob/master/screenshots/12-conf_tx.PNG)


15. <h3> VOILA!!!: Succesfully Executed Transaction <h3>

![](https://github.com/NinoslavVasic/ogimilchain/blob/master/screenshots/13-status_tx.PNG)



<footer>
    
Copyright 2020 Columbia Engineering - FinTech Bootcamp NVasic
    
    
</footer>




