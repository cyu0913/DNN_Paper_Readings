# DNN_Paper_Readings
## Already Read 
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
- Identity Mappings in Deep Residual Networks [(PAPER)](https://arxiv.org/pdf/1603.05027.pdf)
  - An extension of original Resnet with indentity mapping for both connection and after addition activation.
  - More thant 1000 layers are possible.
- Deep Networks with Stochastic Depth [(PAPER)](https://arxiv.org/pdf/1603.09382.pdf)
  - Randomly dropping entire layers during training (like droppout)
  - More than 1000 layers are possible
- Densely Connected Convolutional Networks (DenseNet) [(PAPER)](https://arxiv.org/pdf/1608.06993v2.pdf)
  - An extension of Resnet that connects each layer with all its previous layers.
  - Table 2: is very good summary of all related techniques, its layer number and final performance.
- Listen, Attend and Spell [(PAPER)](https://arxiv.org/abs/1508.01211)
  - From audio signal to english character output
  - Uses Pyramid-like RNN to compress input length (audio frames too long), and pass to attention mechanism
  - Still big gap compared to state-of-the-art (10.3 vs 8.0)
- Neural Speech Recognizer: Acoustic-to-Word LSTM Model for Large Vocabulary Speech Recognition [(PAPER)](https://arxiv.org/pdf/1610.09975v1.pdf)
  - CTC with words as output, outperform previous character output based
  - uses 120000 hours of data, to resolve the sparseness problem of using words as output.
  - No language model, and no decoding.
 

## To Read
- Dual Learning for Machine Translation ([PAPER])(https://arxiv.org/pdf/1611.00179v1.pdf)
- Deep Residual Learning for Image Recognition ([PAPER])(http://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)
