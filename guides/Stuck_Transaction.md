# How to Fix a Stuck Pending Transaction on WanSwap

_In this guide, we will show you how to get rid of a stuck pending transaction using WanMask._

### Before you start

Before following this guide please check if your transaction is really stuck on [this](https://wanchain-txpool.vercel.app/) page. If you don’t see your address there the transaction has not been sent to the chain. If this is the case, please close your browser and start it again or clear your browser cache. This also works for stuck approvals or signatures.

If you have problems with transactions not showing on the Ledger HW wallet, please make sure that contract data is allowed on the Ledger Wanchain app.

When you have a stuck pending transaction you can follow these steps to cancel it

### Enabling Advanced Settings for Gas and Nonce

- Open your WanMask wallet extension, then click on the icon in the top-right and click on Settings. Go to advanced, and enable Advanced gas controls.  

![](../_media/Stucktrans1.png)

- After that enable 'Customize transaction nonce'.  
    
![](../_media/Stucktrans2.png)

- Now scroll all the way down and click 'Save'.

### Finding out transaction nonce

Now we need the pending transaction nonce, you can find all stuck transactions on [this](https://wanchain-txpool.vercel.app/) page. Check for your transaction and note the nonce number.

### Submitting an empty transaction

- Open the WanMask extension  

- Copy your address by clicking on your account name  

![](../_media/Stucktrans3.png)

- Click send  

- Paste your address  

![](../_media/Stucktrans4.png)

- Make sure the amount is on 0 and click next

- Edit the gas fee

![](../_media/Stucktrans5.png)  

- Choose the 'Fast' option and save (make sure you use slightly more gas than on the stuck pending transaction)

- Enter the nonce number in the custom nonce field

![](../_media/Stucktrans6.png)  

- Click confirm

If everything was done correctly the stuck transaction should now be gone.
