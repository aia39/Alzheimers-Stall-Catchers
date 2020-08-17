To produce the final submission result we have used hard voting multistage ensemble.
For ensemble of any two models, we have considered the following two issues:

1. First we measure the dissimilarity between the results produced by the 2 models. To do so, we calculated The Matthews’ Correlation Coefficient (mcc).Lower mcc indicates that there is sufficient dissimilarity to boost the ensemble result. From our experiment we have found that mcc>.60 did not do well in ensemble.
 
2. After ensemble, we also checked the similarity among the ensemble result and the all single model results by calculating mcc. If ensemble result was just copied from one single model result, the mcc would be high and we did not get promising improvement.
From our experiment we have found mcc>0.9 (between ensemble result and single model result) did not give favorable results.   

After doing the experiment we have chosen 12 model results to ensemble

2 stage Ensemble:
Among the 12 models, 4 of them were from image based approach and the remaining 8 of them were from point cloud based approach. 
We ensembled image based model and point cloud based model separately and then reensembled the two results.
