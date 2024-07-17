# Deep Learning Inference in Facebook Data Centers: Characterization, Performance Optimizations and Hardware Implications
## Motivation 
a great challenge has been the fast pace of changes in DL applications: the previously relevant AlexNet [40] is no longer representative of the computation characteristics of today’s computer vision (CV) systems. The rate of change in DL models is so fast that hardware optimized for old models can easily become inefficient for new models.

<ol>
    <li>High memory bandwidth and capacity for embeddings</li>
    <li>Support for powerful matrix and vector engines</li>
    <li>Large on-chip memory for inference with small batches</li>
    <li> Support for half-precision floating-point computation </li>
</ol>

## Characterization of DL Inference
In conclusion, all these following models need scale-up for precision and accuracy which need more in-chip memory and computer power and increasing both the temporal and spatial resolution.
<ol>
    <li>Ranking and Recommendation: 
    Support for powerful matrix and vector engines: Recommendation is usually formulated as an event-probability prediction problem, where an ML model predicts the probability of one or multiple events at the same time.These models usually use a combination of signals from dense and sparse features. If incorporating time into the event-probability models, it need more compute power.</li>
    <li>Computer Vision: 1. Image Classification: large parameters 2. Object Detection: involves identifying specific regions that contain objects of interest. The recent model rely on Faster-RCNN architecture. 3. Video Understanding: frame-based approach where sampled video frames are applied through image models. However, recently 3D convolutions gained wide adoption owing to higher accuracies given their ability to model temporal in addition to spatial domain   </li>
   <li>  Language Models:  Neural machine translation (NMT) has become the dominant approach to machine translation. It relies on the encoder-decoder approach, also called seq2seq. The former encodes the input sentence, while the latter decodes the encoding into the target output sentence.           </li>
</ol>
