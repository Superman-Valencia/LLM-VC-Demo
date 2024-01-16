<style>
    			.image-container {
      				display: flex;
      				justify-content: center;
    				}
    			.image-container img {
      			max-width: 45%; /* 可以根据需要调整图片的最大宽度 */
      			margin-right: 10px; /* 设置图片之间的间隔 */
    				}
    			.image-caption {
    			font-size: 20px; /* 设置字号 */
    			font-weight: normal;
  					}
 			 </style>
     
# LLM-VC: Voice Conversion based on the Pre-trained Large Language Model with a Specific Disentanglement Strategy
<p align="justify"> This paper proposes a VC model based on the pre-trained large language model with a specific disentanglement strategy. First, the pre-trained WavLM is employed to extract layer-specific embeddings as the input of the speaker and content encoder, respectively, to improve the model's generalization. The content and speaker encoder are simplified due to the change in features. Second, the formant-shifting-based augmentation loss is introduced in content encoding to reduce redundant information effectively. Third, the AM-Softmax loss is adopted to enlarge the inter-speaker distance and reduce the intra-speaker distance, improving the model‘s separability to speakers. Experimental results demonstrate that the proposed model achieves excellent performance in objective and subjective evaluations under both seen and unseen scenarios.</p>

The following is the overall model architecture.
<img src="images/proposed_model_revise.png" alt="示例图片" width="300" height="200">

