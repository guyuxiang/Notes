大家好。

我是顾宇翔 Lucas。

我们是来自加拿大多伦多的开发团队。很高兴有机会参加Dorahacks 两周前的这次defi hackathon。

我们团队从2017年开始进入blockchain和cryptocurrency领域。开发过crypto wallet， smart contract相关的多个项目。等一下介绍完这一次demo之后，我会简单介绍一下我们之前做的项目。

今天我想跟大家介绍一下我们这次参加这次hackathon的项目。项目的我们对Uniswap的gas 费用高的问题有一些想法，这次hackathon打算开发一个实验性产品，来减低小额uniswap交易的交易成本。希望有机会与大家多交流，一起进步。

Reddit title: A solution to reduce Uniswap gas cost, specially for small-amount trading

post: video


Shuttle is a light-weight optimized smart contract that designed to work with Uniswap, which has very low gas cost itself.

Given a Uniswap pair, Shuttle combines multiple trades into one single trade and execute a single swap to save gas. Traders first deposit funds into the smart contract, once the enough traders have deposited, the batch swap function of the smart contract is triggered and it executes a swap with uniswap, the output tokens of the swap
are then transfered backed to traders. Therefore, each trader only have to pay a fraction of the gas cost of the single Uniswap transaction.



