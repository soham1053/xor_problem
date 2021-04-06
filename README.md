#XOR Problem
⭐ Train an LSTM to solve the XOR problem: that is, given a sequence of bits, determine its parity. The LSTM should consume the sequence, one bit at a time, and then output the correct answer at the sequence’s end. Test the two approaches below:

Instead of a many-to-one sequence to parity model, I wrote a many-to-many sequence to cumulative parities model.

### Generate a dataset of random 100,000 binary strings of length 50. Train the LSTM

`fixed_length.ipynb`

### Generate a dataset of random 100,000 binary strings, where the length of each string is independently and randomly chosen between 1 and 50. Train the LSTM. Does it succeed? What explains the difference?
`variable_length.ipynb`