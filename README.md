# LLM-VC: Voice Conversion based on the Pre-trained Large Language Model with a Specific Disentanglement Strategy
<p align="justify"> This paper proposes a VC model based on the pre-trained large language model with a specific disentanglement strategy. First, the pre-trained WavLM is employed to extract layer-specific embeddings as the input of the speaker and content encoder, respectively, to improve the model's generalization. The content and speaker encoder are simplified due to the change in features. Second, the formant-shifting-based augmentation loss is introduced in content encoding to reduce redundant information effectively. Third, the AM-Softmax loss is adopted to enlarge the inter-speaker distance and reduce the intra-speaker distance, improving the model‘s separability to speakers. Experimental results demonstrate that the proposed model achieves excellent performance in objective and subjective evaluations under both seen and unseen scenarios.</p>

The following is the overall model architecture.
<div style="text-align:center">
  <img src="images/proposed_model_revise.png" width="300" height="200">
  <p>Fig.1: The overall architecture of the proposed model.</p>
</div>


