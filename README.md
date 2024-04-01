# Cerebro_SYNC
A verilog based Convolution Neural Network implementation

## neuron architecture 
![alt text](/images/neuron.png)


### an idea
* I could make a tic tac toe game in verilog. which would have 3x3 matrix of rgb leds for control and a 3x3 numpad of button switches for input.
* The first task would be to execute the entire playable game while 2 humans can play by pressing buttons to give inputs to the game and the winning condition can be coded and as a player(1 or 2) wins, that number is displayed on the 3x3 matrix to signify who has won.
* The tricky part now
  * I make a convolution neural network against which humans can play
  * The inputs to this neural network will be a 9 bit input based on what move the human has played.
  * The output of this neural network will be a 9 bit output which will be the move the neural network wants to play.
  * The neural network will have to be trained in software with multiple plays with wins and losses.