
# Tsetlin Machine Autoencoder based Embeddings Collection

The repo contains some Embeddings produced using Tsetlin Machine Autoencoder. 


## Folder Structure

```
Intrinsic - Contains similarity score for word pairs
Extrinsic- Contains embedding for target words.
```
## Usage/Examples

Each folder consist of .pkl file. Below is how .pkl is structured for each folder.

### Intrinsic Folder- .pkl file contains
```
{[(word1, word2)]= score, [(word1, word3)]= score, .....}
```

### Extrinsic Folder- .pkl file contains

```
{target word 1: [embedding1], target word 2: [embedding2], ....}
```
## How to load

We can load pickle file as:

Example:
```
import pickle

with open('embedding.pkl', 'rb') as f:
    embeddings = pickle.load(f)

```

