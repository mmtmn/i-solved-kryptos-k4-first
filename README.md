# Kryptos

Since its dedication on November 3, 1990, there has been much speculation about the meaning of the four encrypted messages it bears. Of these four messages, the first three have been solved, while the fourth message remains one of the most famous unsolved codes in the world. The sculpture continues to be of interest to cryptanalysts, both amateur and professional, who are attempting to decipher the fourth passage. The artist has so far given four clues to this passage. 

**This respository is dedicated to bruteforcing the fourth passage.**

<br>
<br>
<br>
<br>
<br>
<br>

# Latest NN: unbiased_NN.c 

gcc -o unbiased_NN unbiased_NN.c -lm;./unbiased_NN

<br>
<br>
<br>
<br>
<br>
<br>

# Update (June 10th,2024)

two new folders have been added and a new unbiased neural network. 
The new NN only consideres the positive and negative number shifts instead of letters.
This attempts to avoid the previous attempts bias.
You can find the old attempts in one of the folders, where the clues are placed correctly but the bias is still there.

The new neural network (unbiased_NN.c) is still training and it is not known if it'll get the clues's plain text in the right place as of right now.

<br>
<br>
<br>
<br>
<br>
<br>

# older versions of the Neural Networks

On the older versions of the results are biased. You can find them in the folder biased_NN_&_RNN. The plain text response only includes letters present in the clues, suggesting a biased approach towards the bruteforced attempt. Further work would be required to **potentially** bruteforce the 30+ year old cipher.

# to run the older models:

## NN.c
gcc -o NN NN.c -lm;./NN

## RNN.c
gcc -o RNN RNN.c -lm;./RNN

## Breaking Kryptos K4 (older models README.md)

change the EPOCHS variable to be above 10M for better results. the higher it is, the better the results.

