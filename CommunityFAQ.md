## Community FAQ

> Originally posted by TheElderJay(Twatsquad) on the [Bittensor Discord channel](https://discord.com/channels/799672011265015819/1050699421408575539)

Disclaimer: This is a community FAQ. Nothing official. Many questions being asked in one nice spot. Want to add a question, post it here but delete your response after to keep the topic clear. 

=============

Q: How do I acquire a cold/hotkey?
A: To join the Bittensor network, you need to register a few things using the BTCLI client. This includes a coldkey (your wallet) and a hotkey (or multiple hotkeys). Currently, obtaining a key involves doing proof of work (PoW). When you solve a block, you have a limited time to get your setup running, which is called the immunity window. This window is particularly important for miners, as your model/miner will need to prove itself and perform well in order to remain registered. For validators, you need to start your node and stake your preferred amount of Tao in order to participate in the network.

============================

Q: What makes Mining TAO different?
A: Mining TAO involves serving a natural language processing model to the Bittensor network. In conventional mining, you would solve complex mathematical problems in order to earn a reward. In Bittensor, you earn a reward based on how well your model interacts with the network. The better your model performs, the better your rewards will be.

============================

Q: What are the requirements for running on Bittensor?
A: There are several requirements for running a miner on Bittensor. These include having a powerful enough computer with a GPU, a fast and stable internet connection, and enough storage space to store the blockchain and any models you plan on mining with. While not necessary to have a Subtensor set up, it's highly recommended to registered and participate with the network. Validators (as of right now) do not need a GPU. Refer to the Bittensor documentation for more details on these requirements.

============================

Q: So, how do I validate and how much tokens do I need?
A: To run a validator node you need to install the BTCLI client and run a validator. You canvalidate with any amount, however, 1024 or more TAO is a recommended amount due the fact that it's also the same amount that "protects" your key from deregistering. See: https://docs.bittensor.com/css/ValidatorCustomization.html

============================

Q: So, how do I start mining TAO (serving a model)?
A: Check out the following documents https://docs.bittensor.com/Installation.html for installation guides. The most important feature to keep in mind, is the amount of VRAM your GPU's have, as serving models requires a fair amount of VRAM.

============================

Q: Where and how do I get models to mine on Bittensor?
A: You can download models from https://huggingface.co/. However, be advised that running standard models is no guarantee that you will remain registered in the network.

============================

Q: What is a Subtensor and why do I need one?
A: A Subtensor is your own shadow copy of the blockchain. While it is possible to run a miner/validator without a Subtensor, it is highly recommended to use and set up a Subtensor. See the Bittensor documentation for more information on Subtensors and how to set one up.

============================ 

**Q:** What is the difference between registering a key and mining on Bittensor? **A:** **Registering a key:** This refers to the process of obtaining a unique identifier, called a "key", that allows you to access and use a blockchain network. To register a key, you typically need to perform a certain amount of computational work, such as solving a cryptographic puzzle. This is known as proof-of-work (PoW) and is used to prevent spam and ensure the security of the network. **Mining:** In this context, mining refers to the process of using specialized hardware, such as a graphics processing unit (GPU), to perform computational work that helps maintain the security and integrity of a blockchain network. Instead of being rewarded with cryptocurrency for their efforts, miners in this scenario earn fees based on the performance of the natural language model (NLM) that they serve into the network. ============================ **Q:** How long does it take to register a key? 

**A:** This has many factors. It can take an hour or 14 days; it's equal luck and hashing power. **Giving an example:** 5 TerraHash (difficulty) / 10MH/s (hashrate)  = 50000000000 / 10,000,000 = 500,000 seconds This means that it would take approximately 5.7 days, to solve a PoW block with a difficulty of 5 TerraHash and a solving speed of 10MH/s. **Other examples:** 40 TerraHash / 10MH/s = 400000000000 / 10,000,000 = 4,000,000 seconds, or about 46 Days, 7 Hours, 6 Minutes. 20 TerraHash / 10MH/s = 200000000000 / 10,000,000 = 2,000,000 seconds, or about 23 Days, 3 Hours, 33 Minutes. 10 TerraHash / 10MH/s = 100000000000 / 10,000,000 = 1,000,000 seconds, or about 11 Days, 13 Hours, 46 Minutes. ============================ **Q:** Where can I buy TAO? **A:** TAO OTC: https://discord.gg/98h6MW7G3k - The Bittensor Exchange will be back later; initially said to shutdown and sell, they decided to come back. Use at your own discretion. https://bittensor.exchange/ =============