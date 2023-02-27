# WatchFy.io

Open the gates to high finance by investing in fractional ownership of luxury watches!

During the past decade, high-end luxury watches have had better returns than stocks, bonds, gold, real estate, and fine art. However, not everyone is able to invest in the luxury watches that have experienced these returns because of how expensive they are.

That's where we come in.

With a team consisting of high finance professionals who have spent their careers making the rich, richer, we now want to provide the same level of investing expertise and optionality to the public. We've decided that the best way to begin this journey is by utilizing the blockchain to facilitate our investment funds. This way, we can ensure that most everyone can invest in our funds while keeping the fees low.

![image](https://user-images.githubusercontent.com/114412800/221577990-eb435f05-fb65-4797-9ff2-b5a921fa9c24.png)

In the files uploaded to this repository, you will see the smart contracts which correspond to our second investment fund, the fund which houses the Richard Mille RM 055 Bubba Watson Grey.

The way we allow people to invest in fractional ownership of luxury watches is by creating a smart contract that represents a fund which houses a luxury watch / watches ("TokenFarm.sol") and another smart contract that mints the fund's tokens ("TimeToken.sol") which are directly tied to the value of the luxury watch / watches that are in the fund (each token represents US$1 at the time of issuance). The smart contract that represents a fund ("TokenFarm.sol") allows people to invest any amount they want into a luxury watch / watches. When the total fund size ("goal" - line 31 in "TokenFarm.sol") is reached, we will distribute tokens which were minted from "TimeToken.sol" to the respected investors, in proportion to the amount they invested. For example, if you invested US$5000 in equivalent cryptocurrency into our second investment fund (houses the Richard Mille RM 055 Bubba Watson Grey), you will have 1% ownership in the fund and thus in the Richard Mille RM 055 Bubba Watson Grey - meaning that when the fund's tokens are issued, you will receive 1% of the available tokens, in this case "T002" tokens.

If the total fund size is not met within 6 months from the first investment (investments from 0x84Fec3F099678483Be3796aDEB42f413FCBc9Cf5 do not count as the first investment), we will provide a full refund to all investors of that fund.

Additionally, you would have noticed that in "TimeToken.sol" we have issued more tokens than the total fund size, in this case, 580,000 tokens were minted. This is because of our annual fee. Every year we hold the watch / watches that are a part of the fund, we charge a 2% fee - further, we have a maximum invest horizon of 8 years. Thus, for this fund, every year, we will make 10,000 "T002" tokens available to the public through a concurent sale with each token priced at US$1. The remaining "T002" tokens that are reserved for the 2% fee are held with 0x84Fec3F099678483Be3796aDEB42f413FCBc9Cf5 until time for their release. If we sell the watch before all the tokens reserved for the annual fee are released (before 8 years), we will burn the remaining tokens.

We also charge two additional fees. The first is an upfront fee of 5% which is collected by setting the "goal" amount in "TokenFarm.sol" to be 5% higher than the cost of the watch / watches in the fund. This is to cover initial storage, securtiy, etc. expenses. The other fee is a performance fee where we take 10% of future profits in order to ensure that our views are aligned with yours.

To get the full breakdown of our fee structure visit our White Paper on our About Page here: https://www.watchfy.io/About

Further, the way we will be issuing the profts after selling the watch / watches in a fund is through a token swap. We will host a token swap which the respective time tokens will be swapped for a USD stablecoin. For example, if we sold the Richard Mille RM 055 Bubba Watson Grey for US$700,000, we would host a swap for "T002" tokens to be exchange for a USD stablecoin: after the performance fee, each "T002" token would be worth US$1.26 and you would be able to swap each one of your "T002" tokens for 1.26 USD stablecoins.

If you would like to learn more, head over to https://www.watchfy.io/ 

Email:support@watchfy.io
Twitter: @watchfyofficial
Instagram: @watchfyofficial
Facebook: @watchfyofficial
