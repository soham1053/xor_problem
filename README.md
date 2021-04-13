# XOR Problem
---

From warmups in https://openai.com/blog/requests-for-research-2/

Instead of a many-to-one sequence to parity model, I wrote a many-to-many model: sequence to cumulative parities.

### Generate a dataset of random 100,000 binary strings of length 50. Train the LSTM.

`fixed_length.ipynb`

### Generate a dataset of random 100,000 binary strings, where the length of each string is independently and randomly chosen between 1 and 50. Train the LSTM.
`variable_length.ipynb`
