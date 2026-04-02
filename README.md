The purpose of this project is to emulate chess grandmaster’s memory of boards by training Neural Networks on possible board states. 

We accomplish this by training an autoencoder with a bottleneck layer on chess board configurations, forcing the autoencoder to compress boards and learn patterns. 
After training, we plan to evaluate on both possible and impossible chess boards, seeing if the neural network learned patterns that only form in actual chess games. 
The benefits of running this experiment is that we are able to decode the patterns that grandmasters might use when remembering chess boards, providing us with a unique insight. 
