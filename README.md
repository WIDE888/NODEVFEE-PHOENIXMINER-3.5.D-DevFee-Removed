# NODEVFEE-PHOENIXMINER-3.5.D-DevFee-Removed
NODEVFEE-PHOENIXMINER-3-5-D-DevFee-Removed - Auto Start first nodevfee then Phoenixminer-Download : 
Phoenixminer 3.5.D No Fee Miner
DevFee Phoenixminer 3.0.C Remove Remove DevFee Phoenixminer 3.5.D
1:START FiRST Nodevfee.exe
2:PLACE YOUR WALLET ADRESS START_MINER.BAT THEN
3:START_MINER.BAT AND BEGIN WITH MINING
Note that this is not an official release yet. The changes from 3.5 D are:

Changes in version 3.5d (since 3.0c):
Support for Linux (tested on Ubuntu 16.04 LTS and Debian 9.5 stable). Note that we have tested with AMD GPU-Pro drivers (not the open source drivers) and the official Nvidia closed-source drivers. Please note that this is the first version that supports Linux, so some glitches are to be expected. Do not hesitate to write us about any problems. NOTE. Hardware control options (-tt, -fanmin, -fanmax, -powlim, -tmax, -cclock, -cvddc, etc.) are not supported yet under Linux - only the temperatures and fan speeds are reported. Full support for these options will be added in the next release.
With the recent drop in prices of most cryptos, we are trying to come up with ways to increase the profitability. Since the cost of the electric power a major factor now, we worked hard to create new, power-efficient kernels for most widely used AMD cards (RX580/570/560/480/470/460). To use these kernels, you must specify the option -clgreen 1 on the command-line, or in the config.txt file. In our tests the green kernels lower the power consumption by 2-3% on the supported cards. These kernels may also slightly lower the hashrate (by 0.2-0.5%), so you have to check if they are more efficient for you depending on the electricity costs in your area.
Small improvements in the normal AMD kernels to increase hashrate (RX4xx, RX5xx, Tonga, and Fury).
Added advanced stats option (you have to turn this on with the command-line option -astats 1) that will try to estimate the daily earnings depending on the current price of the coin you are mining and the current difficulty. Note that this is only an estimation and it uses information from third-party web sites, which may not be accurate.
Added support for direct mining (without DAG switching during the DevFee periods) of the following coins: DubaiCoin (DBIX), MOAC, Ether-1 (ETHO), and EtherCC (ETCC). See the -coin option documentation below for details how to specify the coin you are mining.
Added -leaveoc option to prevent resetting of the HW OC settings to defaults on exit
Many small fixes and changes

PhoenixMiner is fast (arguably the fastest) Ethash (ETH, ETC, Muiscoin, EXP, UBQ, etc.) miner that supports
both AMD and Nvidia cards (including in mixed mining rigs). It runs under Windows x64 and Linux x64
and has a developer fee of 0.65% (the lowest in the industry). This means that every 90
minutes the miner will mine for us, its developers, for 35 seconds.
