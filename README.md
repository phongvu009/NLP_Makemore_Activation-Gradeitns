# NLP_Makemore: Activation, Gradeitns & BatchNorm

## Overview:
- Model has only 1 hidden layer: inputs -> hidden layer -> output

## weight initialization Around 0

### Before:

- Result before Applying activation function
```
  hpreact = embcat @ W1 + b1
```

- Hidden Layer output
```
  h = torch.tanh(hpreact
```

### After:
