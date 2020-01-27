# hlf-landRegistry
land registry system on hyperledger fabric in order to prevent land grabbers.

###### Background

The Land ownership in India is mainly established via the sale deeds(procured during
the property registration) and some other documents. However, all these documents
don’t guarantee the claim of ownership but rather establish duplication and also causes land grabbing.
Due to the poor maintenance and the lack of communication across the departments (Revenue departments and Department of Stamps And Registry), we very often find discrepancies, outdated and data being out of
sync in Land Records. These discrepancies are the root cause of ownership problem as one has to go back several years of records to verify the ownership claim. 

We know that the blockchains are immutable,distributed ledgers and the transactions that are once recorded cannot be modified. Also the distributed architecture of the blockchains helps in preventing unauthorized modification of data via any Traditional Cyber Attacks.
That is why I argue why I think blockchain is a good solution to the above Problem Statement.. Once, Traditional Land Records are moved to blockchain ledger, Thats it. Every transaction Regarding Lands will be Recorded and They will Live forever. Even When we and our Planet is no more..😘Kidding..
Blockchain Says 'I need Internet..💥😭'


##### Work-Flow 

>Simplified for Demonstration. After looking into information on the internet about land registration and Transfer, I found that almost all the states in India have more or less adopted the
same kind of the workflow.

1. User and Admin Registrations
2. Land Registration by User with Necessary Details and Documents Submission. (Digitization on Blockchain)
3. Land Approval by Admin(A Government Entity- Revenue Dept.)
4. Land Sale(Ownership Transfer) Registration by User.
5. Land Transfer Approval(Ownership Transfer Approval by Govt Entity.)


##### Terminologies Used in Chaincode

1. PLID: Permanent Land Id used as unique Identifier for land across application
2. Sale-deed: Sale Deed is a legal document describing the transfer of right, title and ownership of Property by a Seller to a Purchaser
3. PlotId: Traditional land Identifier as registered in Revenue Offices(Survey No.)
4. PoD: Proof of Documents Describing Ownership Claim for Land.
5. PODHash: hash of Uploaded encrypted documents in distributed web(e.g. IPFS)
6. plotCoords: Plot Location Global coordinates(latitude and Longitudes)


#### Quick-demo:

```
git clone https://github.com/Salmandabbakuti/hlf-landRegistry.git

cd hlf-landRegistry/client
chmod 777 start.sh && bash start.sh

Note: Some transactions might throw an error as they require you to replace hardcoded values (like registration Id, saledeedIds) in start.sh script.

```

##### User Interface:

##### User Registration:
![User Registration Demo](https://j.gifs.com/WLv6pE.gif)

##### Land Registration:
![Land Registration Demo](https://j.gifs.com/91BrOz.gif)

##### Land Sale:

![Land Sale Demo](https://j.gifs.com/YWxE0Y.gif)

Deployed to https://hlf-landregistry.netlify.com Check it out for Demonstration.

>Note: Un-authorized use and Reproduction Claim Not Allowed as it is Live on cloud.

##### Author   

##### :wave: [Salman Dabbakuti](https://salmandabbakuti.github.io)

<a href="https://www.buymeacoffee.com/Salmandabbakuti" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png" alt="Buy Me A Coffee" style="height: 41px !important;width: 174px !important;box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;-webkit-box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;" ></a>

©Salman Dabbakuti
