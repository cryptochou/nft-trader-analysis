# nft-trader-analysis


https://github.com/nfttrader-io/sdk-js

https://www.nfttrader.io/

https://etherscan.io/address/0x657e383edb9a7407e468acbcc9fe4c9730c7c275

https://etherscan.io/tx/0xb42da8ba7ac0d56dd0b9994d25f517be89ca457a060394bed2ccfcba9ab70568

_swapId  2096

```
struct swapIntent {
		0x65a8092020176D83fd580Eb9e55ADC9e2b849Ec6
            address payable addressMaker; // maker address of the swap
		false
            bool    discountMaker; // if the maker of the swap have a TRADESQUAD or a PARTNERSQUAD he'll get a discount
		0
            uint256 valueMaker; // native token value of the Maker
		5000000000000000
            uint256 flatFeeMaker; // Protocol flat fee
		0x05882f535C4cC7077018Cc20A60223d2EC2Ea34a
            address payable addressTaker; // taker address of the swap
		false
            bool    discountTaker; // if the taker of the swap have a TRADESQUAD or a PARTNERSQUAD he'll get a discount
		5500000000000000000
            uint256 valueTaker; // native token value of the Taker
		5000000000000000
            uint256 flatFeeTaker; // Protocol flat fee
		1665949535
            uint256 swapStart; // creation date
		1665949727
            uint256 swapEnd; // closing / expiring date
		false
            bool    flagFlatFee; // flag used for check if the flat fees are enabled
		false
            bool    flagRoyalties; // flag used for check if the royalties are enabled
		1	Opened, Closed, Cancelled
            swapStatus status; // status of the deal. Could be Opened, Closed or Cancelled
		0
            uint256 royaltiesMaker; // Royalties in native token paid by the Maker
		0
            uint256 royaltiesTaker; // Royalties in native token paid by the Taker
        }

```


0x65a8092020176D83fd580Eb9e55ADC9e2b849Ec6,
false,
0,
5000000000000000,
0x05882f535C4cC7077018Cc20A60223d2EC2Ea34a,
false,
5500000000000000000,
5000000000000000,
1665949535,
1665949727,
false,
false,
1,
0,
0


```
struct swapStruct {
		0xED5AF388653567Af2F388E6224dC7C4b3241C544
            address dapp; // dapp address
		1
            typeStd typeStd; // identify the standard related to the DAPP
		767
            uint256[] tokenId; // tokenID if is an ERC721/ERC1155
            uint256[] blc; // balance if is an ERC20/ERC1155
            uint256[] roy; // royalties that have been paid
            bytes data;
        }
```

0xED5AF388653567Af2F388E6224dC7C4b3241C544,
1,
767,
,
,
0x
