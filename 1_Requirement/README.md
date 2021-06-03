# Requirements 🎯

## ▶️ Introduction 💬
 This proposed model focuses to acess the use of blockchain as a service to implement electronic voting systems. The proposed model identifies the limitations,both technological and legal, of the current voting system and briefs how realizing such system with using blockchain can be benificial. Through the description of proposed architecture, the process of an election and implementing a blockchain-based system the paper explains how the security is improved and how the limitations can be overcome.

## ▶️ Research 📖
It has been a challenge from long time for an electronic voting system that proves to satisfy all the legal requirements of voting. Decentralised technologies has been compelling technological advancement in the information technology world. Blockchain technologies is based on distributed ledger system and offers innumerable applications with features like immutibility etc., benefiting sharing economies. 
## ▶️ Specific Requirements 💼
### ↪️ *External Interface Requirements*
* The user should be able to understand and use and a manual provided on the webpage regarding the process and should be interactive interface so that queries should be answered.
  ### ✅ *User Interface* 👨‍🦱
  * The UserInterface should be user friendly for the user to interact with.
  * It includes basic login by which user can verify his vote.
  * FAQ section being introduced for intraction of user with admin and others.

  ### ✅ *Hardware requirement ⛓️* 
  * Several systems working as different nodes.
  * Finger print sensor.

  
  ### ✅ *Software requirement 🖥️*
 
  * JS, HTML, CSS, bootstrap – Tools for designing for linking proposed model to ui.

### ↪️ *Functional requirements 🗃️*
* User can vote easily with the satisfaction that tampering cannot happen.
* One's vote goes to other nodes as well so if anything happens to a node vote is still saved on other systems on a real time basis. 
*	Login as well as registration is required for using controll center. .  

### ↪️ *Description :

  ### ✅ *Product Perspective*
  * To make the election easy, time efficient, cost efficient and transparent and reduce the man power.
  
  
   
  ### ✅ *Product Features:
  * Results can be announced as soon as election get over through iterating on blockchain, any tampering with vote data can be detected using blockchain property.
  * Easy to install and set-up.

## ▶️ Cost and Features :
### ↪️ *Cost*
The whole costs depends on the no. systems we use and on what scale voting is done.

### ↪️ *Features*
  * A smart contract includes identifying the roles that are 
involved in the agreement and the different transactions and 
components in the process.
  * Time efficient as well as cost efficient.
  * One cannot vote for other because of fingerprint verification.
  * Less Man force required.
  
### ↪️ *Software Model*
* Waterfall model was opted to make this project.
* It Made easy to first gather all the resources and plans required for this project.
* Then carrying out the proposed model in respective order.
* And finally implementing the software with testing and maintenance made it successfully


## ▶️ Defining the System
### The Block
    1	The block has the following fields
      (i)  Index: Index indicates the block number of the block. 
      (ii) Previous hash: The previous hash is the hash of the
           previous block.
     (iii) EVM-ID: It is the unique identification number for 
           EVMs.
     (iv)  Choice: The value in choice field represents a candidate 
           or a party.
      (v)  Choice: The value in choice field represents a candidate 
           or a party.
      (vi) Signature: It is the hash value used for validating ablock. 
      (vii)Fingerprint hash: It is the hash of the fingerprint of voter. 
      (viii)Time stamp: The date and time of creation of block.
   
 ### Block Creation
    A block is generated only after the hash of voters fingerprint is matched with all the blocks in the chain. 
    If hash matches with none of the blocks then a new block is generated with the data.


### Fingerprint Hash
    SHA 256 hash is generated from fingerprint collected. The hash so obtained is converted to SHA 128 hash. 
    This done to reduce the space and increase security. So double hashing is done.
### Consensus Mechanism
    This consensus is achieved using digital signatures. For authentication of blocks we propose RSA algorithm 
    for digital signature. The private key along with choice, fingerprint hash and EVM id are used to generate 
    to signature at the node where vote is casted.At all other EVMs using the public key along with fingerprint 
    hash,EVM id and choice the signature is verified. All authenticated blocks are deployed onto the blockchain.
    
## ▶️ SWOT ANALYSIS
![SWOT-Analysis](https://github.com/ashwinikumar1913/LTTS_SDLC/blob/main/1_Requirement/SWOT-ANALYSIS.png)

# ▶️ 4W&#39;s 

## ↪️ Who:

This proposed model will help government and the citizens.

## ↪️ What:

Making the whole voting procedure easy and transparent.

## ↪️ When:

When any election occurs. 

## ↪️ Where:

Anywhere. 



