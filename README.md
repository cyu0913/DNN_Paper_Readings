# DNN_Paper_Readings
Track Interesting DNN Papers 

- Fully Character-Level Neural Machine Translation without Explicit Segmentation [(PAPER)](https://arxiv.org/pdf/1610.03017v2.pdf)
  - character-character translation
  - encoder: uses convolutional and pooling layer to reduce the input length, and pass to highway network followed by bidirectional GRU.
- Neural Machine Translation in Linear Time (ByteNet) [(PAPER)](https://arxiv.org/pdf/1610.10099v1.pdf)
  - character-character tranlaton
  - encoder: full dilated convolution, and residual blocks
  - decoder: masked diliated convolution (avoid looking into future frames)
- WaveNet: A Generative Model for Raw Audio [(PAPER)](https://arxiv.org/pdf/1609.03499v2.pdf)
  - audio generation, TTS speech synthesis
  - encoder: causal convolution (with dilated convolustion + residual blocks).
- Google's Multilingual Neural Machine Translation System: Enabling Zero-Shot Translation [(PAPER)](https://arxiv.org/pdf/1611.04558v1.pdf)
  - Key: Could translate language pair not exist during training.
- Densely Connected Convolutional Networks (DenseNet) [(PAPER)](https://arxiv.org/pdf/1608.06993v2.pdf)
  - An extension of Resnet that connects each layer with all its previous layers.
  - Table 2: is very good summary of all related techniques, its layer number and final performance.
