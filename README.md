# secp256k1_-cuda
secp256k1 , sha256, ripemd160, base58 algos in cuda 
this code computes a bitcoin address from a provided private key.
all computations done on gpu in a single file to easly be used on other projects.
i understand that the  majority of people interested on BITCRACK want to code theyr own version but is very hard to analize bitcrack code and extract what is needed,
whith this code can be used/modefy easely for any project, coliders, etc... even for less experienced people.
the code dont use boost-multiprecision or any other library to represent precision values, insted it has its own structure full compatible with GPU.
On the example provided, the code will compute the btc uncompressed address of the respective private ley "0x0000000000000000000000000000000000000000000000000000000000000100", producing "1CPp1y7oyRkxjiVjap5ytgUFh5crqMrUqL" as the correct correspondent address for the key.
