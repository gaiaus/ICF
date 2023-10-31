## Atom

The ICF was allocated 10% of the total genesis ATOM allocation. This amounts to **23,619,895.81 ATOM**, as detailed in the [`cosmos/mainnet/genesis`](https://github.com/cosmos/mainnet/blob/master/genesis/GENESIS.md).

This allocation was divided into three distinct sets. Notably, these allocations did not have any vesting conditions attached to them; they were unrestricted from the outset.

For accurate financial reporting and accountability, it would be essential to monitor how these ATOMs have been utilized or retained by the ICF over time, especially given their unrestricted nature.

**First set**: For the initial establishment of the fundraiser and foundation structure, a sum of **3,054,207.32 ATOM** was designated for advisors and early contributors. These ATOMs were distributed across 8 distinct addresses. 

[`first set`](https://github.com/cosmos/mainnet/blob/master/accounts/icf/early.json). 

```
[
    "cosmos1gu0mkhx3w76wz3v2pd0vscsm94zu3htgnmjku8", 62500,
    "cosmos1grgelyng2v6v3t8z87wu3sxgt9m5s03xvslewd", 150000,
    "cosmos1j2ec43eha7u0nqwd3f7fy4ufehlnh2k5u7c599", 6300,
    "cosmos1ga6hy630ejh2s8p2kvql4jxjt6fcnj0nl5vjqu", 944802.44,
    "cosmos1f70nsqtq0wcd0kymq79ca2p0k5napnm6yqc94x", 944802.44,
    "cosmos1g0y2xpyzz4we4zwlafus9vvpd3tey76mhp0pw7", 472401.22,
    "cosmos1kvy9pqu3ul0x9263cgl3x58g3jccqyf2jdu00x", 472401.22,
    "cosmos1zp6kg7qlmztyw2km2af4z5ruz5vn04cpq84vjk", 1000
]
```

**Second set**: An allocation of 288,500 ATOMs was set aside for the "Game-of-Stakes" participants. These allocations were determined based on the scoring criteria outlined by AiB. The distribution was made to a total of 53 participants. 

[`second set`](https://github.com/cosmos/mainnet/blob/master/accounts/icf/gos.json). 

**Third set**: The balance of Genesis ATOMs, a total amounting to **20,277,188.49 ATOMs** was distributed between two multisig accounts managed by foundation. 

[`icf multisig`](https://github.com/cosmos/mainnet/blob/master/accounts/icf/multisig.json)

* A multisig mechanism with a 2-out-of-3 approval threshold was designated to manage 30% of the allocated ATOMs.
* The balance, which is 70%, was overseen by a multisig structure requiring a 3-out-of-5 approval threshold.

#### How much ATOM does the ICF hold today?
We do not know -- however, we can determine the number of ATOM held by the ICF using the data provided by the [2022 ICF annual report](https://drive.google.com/file/d/1gkEQTu5wf8e_ejTMpEnaYz8kYksqzmEM/view):
* **43% of $304M** (Total value of treasury) = 304,000,000* 0,43 = **$130.72M**
* **$130.72M** is held in ATOM

<img width="1549" alt="Screenshot 2023-10-11 at 8 38 38 AM" src="https://github.com/gaiaus/ICF/assets/146326929/fba1f6fa-bfd5-4255-8018-38092701c32a">

In the [2022 ICF annual report](https://drive.google.com/file/d/1gkEQTu5wf8e_ejTMpEnaYz8kYksqzmEM/view), the disclosed financials are *also* as follows:

The ICF treasury's crypto assets are valued at $191M, which is 62.8% of the entire treasury.
When we break down these crypto assets:
ATOM constitutes the bulk, being 68% by value. This translates to:
$190,912,000* 0,68 = $129,820,160

Thus, the ATOM assets are valued at **$129,820,160**.
Combined, ETH and BTC account for the next significant portion, representing 30% of the crypto assets. This is equivalent to 19% of the total treasury assets.

* We know from the 2022 ICF annual report that the ATOM assets are valued at $129,820,160.
* Using the average ATOM price on 04/14/2023 from [CoinmarketCap](https://coinmarketcap.com/currencies/cosmos/historical-data/) as $12.13, the calculation would be:
  	- $129,820,160/$12.13 = **10,702,403.957 ATOM**


| ICF multisig address                         | ATOM balance on 4/14/2023           | Total |
|:---                                          |:---                                | :---  |
|[`cosmos1z8mzakma7vnaajysmtkwt4wgjqr2m84tzvyfkz`](https://www.mintscan.io/cosmos/address/cosmos1z8mzakma7vnaajysmtkwt4wgjqr2m84tzvyfkz) | 7,044,632.83 | |
|[`cosmos1unc788q8md2jymsns24eyhua58palg5kc7cstv`](https://dev.mintscan.io/cosmos/account/cosmos1unc788q8md2jymsns24eyhua58palg5kc7cstv)| 0.018464 | |
|[`cosmos1sufkm72dw7ua9crpfhhp0dqpyuggtlhdse98e7`](https://dev.mintscan.io/cosmos/account/cosmos1sufkm72dw7ua9crpfhhp0dqpyuggtlhdse98e7) | 1,000,007.811525 | |
|*Unconfirmed* [**cosmos1z6czaavlk6kjd48rpf58kqqw9ssad2uaxnazgl**](https://www.mintscan.io/cosmos/address/cosmos1z6czaavlk6kjd48rpf58kqqw9ssad2uaxnazgl) | 5,612,889.872664 | **13,657,530.532653 ATOM** |

From an accounting perspective:

There's a discrepancy of **2,955,126.576 ATOM** between the reported ATOM figure and the ATOM amount actually held in known wallets, *assuming* the wallet designated as ****nazgl** belongs to the ICF. Alternatively, it appears that the ICF annual report has utilised an average ATOM price of $9.51. However, a review of historical data indicates that ATOM didn't have an average closing price of $9.51 at any point from 01/02 to 04/14/2023. 

Given that this is a 2022 annual report, one can assume that the treasury snapshot might be basing its values on late December 2022 token prices. 

All this said, employing percentages in reports, especially concerning Treasury holdings, can sometimes mask the true financial situation. Without clarity on the exact token unit quantity, we're left with an incomplete financial picture.

A complete and transparent financial report typically includes **both percentage and unit values** to provide a more comprehensive view of an entity's financial position. Percentages alone do not allow for accurate benchmarking or risk analysis.

Please see: 
* [`wallets`](https://github.com/gaiaus/ICF/tree/main/investigations/wallets)
* [`unknown_wallets`](https://github.com/gaiaus/ICF/tree/main/investigations/wallets/unknown_wallets)

