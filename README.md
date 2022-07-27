# CSTTN: Cross-dynamic Spatial Temporal Transformer Network for Traffic Prediction
The official tensorflow implementation for Cross-dynamic Spatial Temporal Transformer Network for Traffic Prediction.
## Introduction
In this paper, we propose an end-to-end framework termed Cross-dynamic Spatial Temporal Transformer Network(CSTTN), which models spatial-temporal correlations jointly in a cross-dynamic manner to address the aforementioned challenges.

Specifically, we utilize encoders to embed spatial and temporal correlations to obtain features, and then adopt decoders that interactively build a bridge between the embedded spatial and temporal features to capture the comprehensive representations for prediction. By stacking multiple CSTT blocks, more refined and deep spatial-temporal features can be learned.

Compared with previous works, CSTTN enables more efficient and scalable training for long-range spatial-temporal dependencies. Experimental results on two real-world public datasets, namely PeMS-BAY and PeMSD7, demonstrate that the proposed framework is competitive with the state-of-the-arts.
![filename_H128PIC](https://user-images.githubusercontent.com/62272745/181165405-cf2f4d79-dc10-4d9a-8287-3ac45df03a8b.jpg)
