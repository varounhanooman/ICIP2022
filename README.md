# ICIP2022

AN EMPIRICAL APPROACH FOR OPTIMISING THE IMPACT OF A PREPROCESSOR IN A
TRANSCODING PIPELINE

The volume of User Generated Content (UGC) on the internet has exploded throughout the pandemic. The relatively low quality of that content generally implies an increased bitrate and much reduced quality after transcoding. Preprocessing e.g. using a noise reducer, is one approach for reducing bitrate and increasing quality. The impact of the noise reducer is however affected by the target bitrate of the encoder. That relationship is known but not previously quantitatively examined. In this paper we present a methodology and new metric for measuring this impact based on the Rate-Distortion curves before and after pre-processing. The metric is used as a cost function for estimating the optimal filter parameter for our chosen denoiser. Our experiments show that optimising the filter parameter in this way yields as much as 4-5dB improvement in PSNR at 3 Mbps.

This repository has the data generated from our empirical approach 


![Final_six (1)](https://user-images.githubusercontent.com/44379467/171439254-b9f1769f-39e1-4a2a-aa55-daddb175683b.png)
