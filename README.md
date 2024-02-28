# <p align="justify"> LLM-VC: Voice Conversion based on the Pre-trained Large Language Model and a Specific Disentanglement Strategy

# ABSTRACT
<p align="justify"> One-shot voice conversion (VC) is challenging, especially in unseen scenarios. This paper proposes a VC model based on the pre-trained large language model and a specific disentanglement strategy. First, the embeddings extracted by specific layers of pre-trained WavLM are employed as input for the speaker and content encoders to improve the model's generalization and simplify their architectures. Second, a specific disentanglement strategy is proposed to remove redundant information in pre-trained embeddings. i) The formant-shifting-based augmentation loss is adopted to reduce content-irrelevant information in content encoding; ii) The AM-Softmax loss is introduced to adjust the distance between different speakers; iii) L1 loss is adopted in pitch and mel-spectrogram reconstruction to ensure the converted speech's quality. Experimental results demonstrate that the proposed model achieves excellent performance in objective and subjective evaluations under both seen and unseen scenarios.</p>

The following is the overall model architecture.
<div align="center">
  <img src="images/LLM-VC-131.png" width="80%">
  <p>Fig.1: The overall architecture of the proposed model.</p>
</div>

# DEMO
For the converted samples, you can visit [the demo page](https://superman-valencia.github.io/LLM-VC-Demo/).
