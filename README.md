# transformer-from-scratch

A decoder-only Transformer language model implemented **from scratch in PyTorch** — no `transformers`, no `nn.MultiheadAttention`, no training framework.

The goal is to understand every tensor in the stack. Every matrix multiply is explicit, every gradient comes from autograd, and every architectural choice is visible in the code.

## Roadmap

- [ ] Byte-pair encoding tokenizer — train, encode, decode
- [ ] Scaled dot-product attention, written by hand
- [ ] Multi-head attention with causal masking
- [ ] Positional encoding — sinusoidal vs. learned vs. RoPE
- [ ] Pre-norm transformer block and residual stream
- [ ] Training loop: AdamW, cosine schedule, gradient clipping
- [ ] Sampling: greedy, temperature, top-k, nucleus
- [ ] Train a small model on TinyShakespeare / TinyStories
- [ ] Benchmark against a reference implementation

## Stack

`Python` · `PyTorch` · `NumPy`

## Status

Scaffolded. Implementation in progress.
