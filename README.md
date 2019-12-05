# Machine playing Chrome Dinosar Game (trained with Convolutional Neural Network) 
Original name of the project: "dinoAI"
This is a simple game that learns how we play the dinosar game in Google chrome and then play by itself.

## FILE DESCRIPTION

### capture_training_data.py

Starts game and captures training data, frame and respective action (do nothing, jump, duck). Writes these actions to actions.csv and frames to images folder.

### network.py

Trains CNN on captured data.

### play_game.py

Opens and plays game with trained network (Note that you can play the Dinosaur game when the wifi is off).
