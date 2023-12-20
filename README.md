# miniGPT
Summary

- We have trained character level auto-regressive causal language model
- Key Architecture points: (layernorm, self attention, residual pathways, feedforward) x 8 followed by languagehead
- Our data has ~1M tokens
- Our model has ~6.4M parameters
- Our Vocab size is ~78
- Context window: 256 tokens (characters)
- 8 heads each of dim 32
- Train time ~ 5 hrs on single GPU RTX4080
- Final val loss: ~0.09
  
<br>
Here is a generated sample text from trained miniGPT <br>
<img width="491" alt="image" src="https://github.com/Sachin-Bharadwaj/miniGPT/assets/26499326/f2b81c66-d481-4f14-ad07-8e8ce37b13ee">
