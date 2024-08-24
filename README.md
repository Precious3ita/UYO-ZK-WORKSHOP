#WORKSHOPS

First Worksop: Transaction Id: at1xmwrtfqfrxqhyefhz6a2dz7lhqysskccfgz3fegc37tuk9n6k5zsrpd8ua
Second Workshop: Transaction Id: at1czaj9wk35zm0gugk4ypwx62zz0f57tkmsgvw2ddz0vmajvrc5q9skjjc8e
Third Workshop: Transaction Id: at12m0f7n4sgsnsjwlpyktd96s8ad5wl7mtuvf9uh96chw4uergvyxss6aery
![Screenshot of the deployed programs](https://github.com/Precious3ita/UYO-ZK-WORKSHOP/blob/master/Screenshot%20(24).png?raw=true)
#Description

#First Workshop:

open your git bash terminal and clone the repository using `git clone https://github.com/Precious3ita/UYO-ZK-WORKSHOP`
cd into the repository `cd UYO-ZK-WORKSHOP`
then cd into the first workshop folder `cd precious_first_program`
run the program `leo run main 3u32 5u32 --network testnet`
this returns 8u32 which is the sum of 3u32 and 5u32.
To deploy, use `leo deploy`
Note, before deployment go to the .env file and change the PRIVATE_KEY to your personal private key.

#Second Workshop After running the first program, cd into the root directory cd .. then cd into the folder of the second workshop cd precious_second_program then run the program using leo run mint <leo wallet id> 1000u64 --network testnet You can deploy by using leo deploy. Remember to change the PRIVATE_KEY in your .env file to your personal private key.

#Third Workshop run cd .. to get into the root directory then run cd precious_third_program to cd into the third workshop folder. You can run the program using leo run combine_hash_owner_receiver <your leo wallet address> <your friend's leo wallet address> You can deploy by using leo deploy. Remember to change the PRIVATE_KEY in your .env file to your personal private key.
