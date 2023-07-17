# NLP_Makemore: Activation, Gradeitns & BatchNorm

## Overview:
- Model has only 1 hidden layer: inputs -> hidden layer -> output

## weight initialization Around 0

### Before:

- Result before Applying the activation function
```
  hpreact = embcat @ W1 + b1
```
The plot shows that the result is in a wide range of big numbers

<img width="573" alt="Screenshot 2023-07-17 at 3 07 50 PM" src="https://github.com/phongvu009/NLP_Makemore_Activation-Gradeitns/assets/54299527/dc642a08-0cb6-4802-9188-d2f7da73544b">


- Hidden Layer output
```
  h = torch.tanh(hpreact)
```
It will lead to squashing the result highly in -1 and 1

<img width="592" alt="Screenshot 2023-07-17 at 3 10 05 PM" src="https://github.com/phongvu009/NLP_Makemore_Activation-Gradeitns/assets/54299527/aa447795-9824-46d4-8c9b-42bd33a9b898">


### After:
