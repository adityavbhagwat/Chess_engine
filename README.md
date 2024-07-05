The project aims to build a fully functional chess engine, that reccomends best moves for a given chess position.
Dataset Generation is done by using python chess library, which aids in generation of random chess boards, which is then processed into a 3-D numpy array which can be fed into a
neural network.
A CNN model is then built and trained on the dataset with labels for a chess position evaluated by stockfish. Once the model is trained, it is used to evaluate a fresh position
encountered during the game to predict an approximate evaluation, which is used by a mini-max function to explore all possible legal moves upto certain depth and decide upon
a best move
