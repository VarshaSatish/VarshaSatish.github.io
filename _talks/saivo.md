---
title: "Conference Proceedings: 2026 The Society for AI in Vision and Ophthalmology (SAIVO) Annual Meeting Program"
collection: talks
type: "Conference Proceedings"
permalink: /talks/conf
date: 2026-05-01
---
Conference proceedings on our abstract : "Ultra-widefield Diabetic Retinopathy Prescreening Using a Patch-Based Attention Multiple Instance Learning Model"

<p>Abstract:<br>
Ultra-widefield (UWF) color fundus imaging provides extensive retinal coverage for diabetic retinopathy (DR) assessment but introduces challenges for automated analysis due to the trade-off between field of view, image resolution, and computational efficiency. This study evaluated a weakly supervised, patch-based Multiple Instance Learning (MIL) framework with attention-based aggregation for prescreening DR severity at the ETDRS ≥47 threshold while preserving fine lesion detail typically lost through global image down-sampling. A total of 835 UWF images from multiple DR studies were classified as ETDRS <47 or ≥47 based on double grading with adjudication. Images were cropped to the mid-periphery to remove lashes and background artifacts and tiled into 224×224 patches. Patch-level features were extracted using a pre-trained EfficientNet_B0 backbone to generate 1280-dimensional embeddings, which were aggregated using an attention-based MIL pooling module to produce image-level predictions. Model development used 5-fold cross-validation on 663 eyes, with 172 eyes reserved for independent testing. Across cross-validation folds, the model achieved a mean accuracy of 0.69, AUROC of 0.74, sensitivity of 0.52, specificity of 0.82, and F1 score of 0.59. On the independent test set, performance included an accuracy of 0.61, AUROC of 0.76, sensitivity of 0.40, specificity of 0.87, and F1 score of 0.65. Attention heatmaps frequently localized regions containing clinically relevant DR lesions, supporting biologically plausible instance weighting under weak supervision. These findings demonstrate that a patch-based attention MIL framework can effectively classify DR severity on large UWF images while maintaining lesion-level information, with future work focused on improving sensitivity through hybrid global–local architectures and task-aligned optimization strategies.

[Presentation Link](https://docs.google.com/presentation/d/1yE49MKSEFjM7BRdvAAlTacEk0fri4G6w/edit?usp=sharing&ouid=103649360721438111904&rtpof=true&sd=true)
