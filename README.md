# weekend_1_encode

DEPLOYED CONTRACT: https://goerli.etherscan.io/address/0x45335dcDf32d77b0096efa3fBfd26b7dC2a0bFd5

REPORT:\
WALLET1: 0x3836bF8F3762820F95CBab66Fa462550E0F8d99c (DEPLOYER)\
WALLET2: 0xd692ecfeA7B7Fb6c197dcB6de07B122CC19AB764

SetText(“aaa”)\
Transaction made by: WALLET1\
Transaction hash: 0xee7e8e99d06f1af0dd22502a036871219067342d469c8fe0365c7e9d19f866bd\
Change text of helloWorld read function. \
Transaction successful helloWorld() returns aaa

transferOwnership(Wallet2)\
Transaction made by: WALLET1\
Transaction hash: 0xfbaaeb31c30e4410a1be6cd2dde0feaaf4c137beb7c0049ad88e3f52b7c2d559\
Change ownership to wallet2\
Transaction successful owner() returns WALLET2 address

SetText(“bbb”)\
Transaction made by: WALLET1\
Transaction hash: 0xbf26b41316dba55da66df8be18c22ff9692b250ea595c190446ecc990aa78b01\
Transaction FAILED helloWorld() still returns aaa\
Transaction failed because WALLET1 no longer owner of contract

SetText(“bbb”)\
Transaction made by: WALLET2\
Transaction hash: 0x9a32abe51f20f2dd313d56c7a41d5311da1014aecb351d61d9595458cc125782\
Change text of helloWorld read function.\
Transaction successful helloWorld() returns bbb 
 
