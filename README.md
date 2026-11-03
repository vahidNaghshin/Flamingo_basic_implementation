# Flamingo_basic_implementation

A step-by-step PyTorch implementation of the Flamingo Visual Language Model (VLM) for educational purposes. Features clean, modular implementations of the Perceiver Resampler, Gated Cross-Attention blocks, Interleaved Multi-Modal Attention Masking, and Flamingo Layer wrappers with a verified end-to-end dummy training loop.

Quick Highlights to include in your README:

Perceiver Resampler: Maps arbitrary visual feature sequences to a fixed number of latent visual tokens.
Gated Cross-Attention: Implements stable tanh-gated cross-attention layers initialized to zero to protect pre-trained LLM weights.
Interleaved Multi-Modal Masking: Enables text tokens to dynamically attend only to their preceding media context.
Frozen Backbone Compatibility: Seamlessly wraps pre-existing language model decoders.
