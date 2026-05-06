# French-G2P-model-

A grapeme-to-phonem (G2P) conversion model for Frenchm fine-tuned on ByT5 using the GLÀFF phonetic dictionary


## Overview
1. Evaluation model (g2p-multilingual-byt5-tiny) with data French dictionary GLÀFF

3. Sequence-to-sequence model for converting 
French orthographic text into its phonetic transcription (IPA). It leverages 
[ByT5](https://github.com/google-research/byt5), a token-free Transformer that 
operates directly on UTF-8 bytes — particularly well-suited for G2P tasks 
where character-level information matters.