# Remote Voice-activated System
An Matlab emulation system that focuses on signal encoding, transmission, and decoding.   
**Not a realistic implementation!!**

Here's the methods:
1. Signal Quantization: N-bit quantization, take `N = 5`
2. Source Encoding: Huffman
3. Channel Transmitting: Using Convolutional codes, BPSK modulation with AWGN added.
4. Demodulation and Decoding: Consistent, corresponding operations with modulation and encoding.
5. Instruction Recognization: inferenced by trained CNN model, with MFCC features of the audio. 
