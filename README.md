# Lotto miner
Playground for solo-mining bitcoin on regtest and mainnet

# What is this?
This is a webapp where you can attempt to mine a bitcoin block and put the block reward directly in a bitcoin address of your choice. Your browser will try to find a block whose hash is below a certain target. The difficulty setting will be low at first, but you can increase it til it matches that of the real bitcoin network. Raising the difficulty will take increasingly more work and, probably, more time. You can also mine on regtest.

# How can I try it?
Just click here and follow the instructions: https://supertestnet.github.io/lotto_miner/

# Why did you make this?
To help folks learn how bitcoin's difficulty assessment algorithm works and gain an appreciation for how much work goes into mining bitcoin blocks. Also, I'm not aware of any open source tools for creating custom bitcoin block templates on regtest, and this is a starting point for such a tool. The codebase is pretty small and since it produces valid regtest blocks, devs should be able to customize it to suit their regtest needs.
