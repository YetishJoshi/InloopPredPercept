# Low complexity in-loop prediction perceptual video coding for HEVC
----
The source code in this respository refers to the modified HEVC encoder used to generate results for the  paper titled:

"Low complexity in-loop prediction perceptual video coding for HEVC"

Published in: Broadband Multimedia Systems and Broadcasting (BMSB), 2016 IEEE International Symposium on 
Paper available on IEEExplore website:

[https://doi.org/10.1109/BMSB.2016.7521919](https://doi.org/10.1109/BMSB.2016.7521919)

Abstract:
This paper applies the concept of hybrid framework for perceptual video coding (PVC) during the 'in-loop' stages by extending it to the prediction stage. As low complexity environments of mobile phones and tablets are increasingly used to capture video, PVC is not occurring here due to the high complexity of perceptual algorithms. Being able to encode using PVC will enable distortion to be merited by non-linear perceptual means than by uniform cost. While ideally, existing perceptual assessments of Structural Similarity (SSIM) is used, it is not processor friendly. The hybrid framework involves applying an additional low complexity perceptual assessment on top of existing Sum of Absolute Differences (SAD) and Sum of Absolute Transform Differences (SATD) only where distortion is perceptually significant. Consequently, the results show an increase in timing of < +4% and < +6% for video encoded with low delay P and random access profiles respectively, which is complexity competitively to other PVC solutions. This also affects bit redistribution with large reductions in bits allocated to signalling, -5 to -25%, with increases in small, medium and large block sizes. Visually, the proposed encoder encourages larger blocks on perceptually homogeneous regions and more dynamic smaller block where boundaries for textures or activity is occurring. This work can be extended to allow for perceptual quantisation to enable bandwidth reduction while maintaining perceptual quality.

Other related files available here:
[https://dx.doi.org/10.6084/m9.figshare.c.3651632](https://dx.doi.org/10.6084/m9.figshare.c.3651632)

[![DOI](https://zenodo.org/badge/77175238.svg)](https://zenodo.org/badge/latestdoi/77175238)
