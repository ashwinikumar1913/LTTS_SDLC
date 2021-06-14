# Blockchain EVM
This project focuses to asses the use of blockchain as a service to implement electronic voting systems. This consensus is achieved using digital signatures. For 
authentication of blocks we propose RSA algorithm for digital signature. The private key along with choice, fingerprint hash and EVM id are used to generate to signature at the node 
where vote is casted. At all other EVMs using the public key along with fingerprint hash, EVM id and choice the signature is verified. All authenticated blocks are deployed onto the 
blockchain.
## Folder Structure
Folder             | Description
-------------------| -----------------------------------------
`1_Requirements`   | Documents detailing requirements and research
`2_Design`         | Documents specifying design details
`3_Implementation` | All code and documentation
`4_Test_plan`      | Documents with test plans and procedures

## Contributors List and Summary

SF No. |  Name   |    Features    | Issuess Raised |Issues Resolved|No Test Cases|Test Case Pass
-------|---------|----------------|----------------|---------------|-------------|--------------
`52` | Ashwini Kumar | User Module     | Nil     | Blog Side   | 2   | YES    
`48` | Dr.Ruhul amin | Hardware Module | Physical Architecture  | 1 | YES

## Challenges Faced and How Was It Overcome

Major challenge faced was segregating the fingerprint sensor with the system.


## Learning Resources
1. [markdownCheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
2. [markdownBasics](https://guides.github.com/features/mastering-markdown/)
3. [git inspector](https://github.com/ejwa/gitinspector.git)
4. [github workflow](https://docs.github.com/en/actions/learn-github-action)
