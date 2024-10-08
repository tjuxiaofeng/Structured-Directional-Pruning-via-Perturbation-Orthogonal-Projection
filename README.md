# Structured-Directional-Pruning-via-Perturbation-Orthogonal-Projection

Despite the great potential of artificial intelligence (AI), which promotes machines to mimic human intelligence in performing tasks, it requires a deep/extensive model with a sufficient number of parameters to enhance the expressive ability. This aspect often hinders the application of AI on resource-constrained devices.
Structured pruning is an effective compression technique that reduces the computation of neural networks. However, it typically achieves parameter reduction at the cost of non-negligible accuracy loss, necessitating fine-tuning.
This paper introduces a novel technique called Structured Directional Pruning (SDP) and its fast solver, Alternating Structured Directional Pruning (AltSDP). SDP is a general energy-efficient coarse-grained pruning method that enables efficient model pruning without requiring fine-tuning or expert knowledge of the desired sparsity level.
Theoretical analysis confirms that the fast solver, AltSDP, achieves SDP asymptotically after sufficient training. Experimental results validate that AltSDP reaches the same minimum valley as the vanilla optimizer, namely stochastic gradient descent (SGD), while maintaining a constant training loss. Additionally, AltSDP achieves state-of-the-art pruned accuracy integrating pruning into the initial training process without the need for fine-tuning. 
Consequently, the newly proposed SDP, along with its fast solver AltSDP, can significantly facilitate the development of shrinking deep neural networks (DNNs) and enable the deployment of AI on resource-constrained devices.

(The code will be available soon)
