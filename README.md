# contributions
links to contributions in task 1,2,3



# task 1


1. commit: https://github.com/Epic-Byte/Nestcoin-Manager/commit/6a4c141a1e4a50612e4b8f482847c37b26dbd6cb
   description: wrote second half of contract code, added destroy function(unmerged)to burn tokens, added samerewardbatchmint function to mint same amount of tokens to multiple people, made payable(unmerged), added event for singleamountbatchreward to make a record for UI to read, added event for burnt tokens(unmerged), made contract burnable(unmerged), added require statements for 0 address and max of 200 addresses to make sure 0 address cant be inputed and maximum of 200 addresses can be put at once.
    proof:https://github.com/Epic-Byte/NestCoinFullStack/blob/stage_1/packages/hardhat/contracts/NestToken.sol


2. commit: https://github.com/Epic-Byte/Nestcoin-Manager/commit/be45eb738926b77b1c6d50e526c75bd709a069bc
   description: added roles mapping to give access controll to different admins, added admin roles to contract to create a role for administrator, added remove and add admin functions to remove or add new or old admins, made functions only admin to make sure functions can only be accessible by an administrator.
   proof: https://github.com/Epic-Byte/NestCoinFullStack/blob/stage_1/packages/hardhat/contracts/NestToken.sol
   
   
3. commit: https://github.com/Epic-Byte/NestCoinFullStack/commit/efb2b2e49bc55a7d9c0b46eab925afbe68058853
   description: added dead function modifier to check if contract is paused,created pause and play functions to pause or play the contract, added dev constant to set a dev that can access the pause and play functions, corrected some natspec comments for good practice.
   proof: https://github.com/Epic-Byte/NestCoinFullStack/blob/stage_1/packages/hardhat/contracts/NestToken.sol
   
   
4. commit: https://github.com/Epic-Byte/NestCoinFullStack/commit/f227f05892cd16aa213b354fff096d8fce3f622b
   description: added some natspec comments for good practice and easy to understand contract.
   proof: https://github.com/Epic-Byte/NestCoinFullStack/commit/f227f05892cd16aa213b354fff096d8fce3f622b
   
   
5.  commit: https://github.com/Epic-Byte/NestCoinFullStack/commit/fb5b95bc8ec9505dee9831fb55be0904b2657ffa
    description: added dead function modifier to check if contract is paused, added dead function to all functions so all functions can be paused,edited pause and play functions for better logic, corrected I++ logic error to count and use i correctly.
    proof: https://github.com/Epic-Byte/NestCoinFullStack/commit/fb5b95bc8ec9505dee9831fb55be0904b2657ffa
   
   
   
   
# task 2


1. commit:  https://github.com/Epic-Byte/Library/commit/c15b8a96342df9e50f458d58230f429512e52d0c
  description: wrote 90% code for library, wrote library code logic(this is the code that makes the library work or exist), added natspec comments, added struct for items to hold contents of a persons library, mapping to hold users and contents to connect a user to their library items, created private and public share function  to share an item from one personal library to another,created upload function to add item to ones library, created function to view private library to show contents of ones library .
  proof: https://github.com/Epic-Byte/NestCoinLibrary/blob/main/packages/hardhat/contracts/Library.sol
  
  
2. commit:  https://github.com/Epic-Byte/Library/commit/e4188561ec954ab228ca1871c2fb0128416a102f
 description: added event for public and private uploads to provide a record for front end to read, made public array private so it can be accessed outside the contact.
 proof: https://github.com/Epic-Byte/NestCoinLibrary/blob/main/packages/hardhat/contracts/Library.sol
 
 
3. commit: https://github.com/Epic-Byte/Library/commit/fb0539383d2b678df6ee256fbdeb4faddc1c450e
 description: corrected event for public and private upload, added require function for 0 address to prevent sharing to an invalid address.
 proof: https://github.com/Epic-Byte/NestCoinLibrary/blob/main/packages/hardhat/contracts/Library.sol
 
 
4: commit: https://github.com/Epic-Byte/NestCoinLibrary/commit/8ecbfcb5b2c6b38f4e1a1ef1c175035f237d9f23
description: added function to make a public item private to add item from public library to private one, added counter for public uploads to give an id to all uploads, added counter to the events to give record for front end, added id to contents struct to have id for all items added to private library.
proof: https://github.com/Epic-Byte/NestCoinLibrary/blob/main/packages/hardhat/contracts/Library.sol


5. commit: https://github.com/Epic-Byte/NestCoinLibrary/commit/c49395d03a336334a3582a9435353ce85ba968ec(unmerged)
description: made share function to only share to one address(unmerged).
proof:https://github.com/Epic-Byte/NestCoinLibrary/commit/c49395d03a336334a3582a9435353ce85ba968ec


6. commit:  https://github.com/Epic-Byte/NestCoinLibrary/commit/9b946b7ca8a9bce62f5ee5822e0f9cf276ede84e
 description: added share to multiple addresses back to allow one share to more than one person at the same time.
 proof: https://github.com/Epic-Byte/NestCoinLibrary/blob/main/packages/hardhat/contracts/Library.sol
 
 
7. commit: https://github.com/Epic-Byte/NestCoinLibrary/commit/7b8d7b00576cd09dd79bae19d4544eba9dd093b9
  description: added array to view contents of private library on frontend.
  proof: https://github.com/Epic-Byte/NestCoinLibrary/blob/main/packages/hardhat/contracts/Library.sol
  
  
  
  
# task 3
## Repo Url- https://github.com/G-DAO/G-DAO/tree/main
 
 
 1. commit and proof: https://github.com/G-DAO/G-DAO/commit/5d960101a13d1c25d189bebdd4ed6593d53a1653
     description: added function to vote for a candidate, added function to view result of a candidate, added mappings to connect a candidate to their votes,
     to check if they are a candidate, mapping to check if a user has voted.
     
     
 2. commit and proof: https://github.com/G-DAO/G-DAO/commit/7e460474dbe4b013bb14c81fbfc960066d0a3144
    description: added modifier for start voting to make sure its time to vote, addedfuntion to add stakeholder, add teacher, beginvote and end vote
    
    
 3. commit and proof: https://github.com/G-DAO/G-DAO/commit/2df416ed90de83cbad3698cc9b6269ed233a557c
    description:corrected error in add teacher function
    
    
 4. commit and proof: https://github.com/G-DAO/G-DAO/commit/060a1fd33dcc2647d8c64899a76a3192f36c0253
    description: added public result function to make result public to students, added events for the result 
    
    
 5. commit and proof: https://github.com/G-DAO/G-DAO/commit/6ae8e8177f9b5bb0d731c20c3bdf762306dfb03e
    description: corrected contract errors.
    
    
 6.commit and proof: https://github.com/G-DAO/G-DAO/commit/1c9bf9b7e4cb5aaeafadd5da870f9d5cb9a7c45a
 description:added add candidate function to add a candidate for election
 
 
 7. commit and proof: https://github.com/G-DAO/G-DAO/commit/0df88f236ae9dade8cc47a8ae1bf3a0e82c1438f
  description: added hash to compare string values
  
  
 8. commit and proof: https://github.com/G-DAO/G-DAO/commit/a3c065fa1b3601ce651e1fbe85313319c2b4dc02
  description: added struct to represent a candidate, added arguments in addcandidate function to recieve ipfs link and position,changed logic for addcandidate, added   function to show winner of election,added event for the winner
  
  
 9. commit and proof: https://github.com/G-DAO/G-DAO/commit/173fd9965b40a0c7cd6c44f63580ed8f12841c09
    description: wrote unit tests for the smart contract
    
    
 10. commit and proof:  https://github.com/G-DAO/G-DAO/commit/903f6010b56b3c09a7e029f3a980239b1b69cc87
    description: corrected unit test errors
    
    
 11. commit and proof: https://github.com/G-DAO/G-DAO/commit/e2765a6e7efc78fdc3e72edbb0a52fd16f6f310d
     description: added function to clear contents of a contract so it can be reused for another election, added login functions for frontend to check if a user is a student      or stakeholder or chairman, added other stakeholders to represent stakeholders that are not students
     
     
 12.commit and proof: https://github.com/G-DAO/G-DAO/commit/3c28360a5189ba06e306bc5c7cb0e22fdea5ef5d
    describe: changed voting logic to allow one vote for multiple people at once, reduced size of login function for frontend to do the check in just one function
    
    
 13. commit and proof: https://github.com/G-DAO/G-DAO/commit/937aed5463199b4bbb03f24130eea94928e3e144
     description: changed add stake holders function to be able to recieve roles for each stake holder   
     
 14. commit and proof: https://github.com/G-DAO/G-DAO/commit/e76ff6dd24c43c5b240e6e5648f3d97439c02fef
     description: added more unit tests, test for  addcandidate, voote, enable,disable, beginvote, endvote, candidatevotes, public results, contract stake, addstaker, cleardata functions
     
    
 15. commit and proof: https://github.com/G-DAO/G-DAO/commit/1cddc35f78025b1de3146f96130186aa7e539da8
    description: created repo template


 16. commit and proof: https://github.com/G-DAO/G-DAO/commit/3d97650fda7ddf63b7f137c4b45d14e08b402589
    description: added problem definition
    
 
# PLEASE NOTE
 
 if you've noticed, for TASK ! AND TASK 2 alone there are two different repos for some of the proof and commits(NOT ALL), the Reason is that my team made use of a repo then had one person push all to a new repo for presenting which is the repo link in the proof sections of this readme.md file. So sorry for any inconvenience this may or may not have caused, we werent aware(As team Lead My Apologies are given).
 
So evidence of the commit is shown in the commit link section and the proof it was implemented or merged or unmerged in the presented repo is shown in the proof section link, 
for any doubts the dates of the commits and pushes can be checked so as to confirm this was all done since and no foul play attempted.


for any further clarifications please contact me with @Godand on the slack channel.
THANK YOU VERY MUCH !
  
