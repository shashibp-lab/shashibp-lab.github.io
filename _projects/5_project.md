---
layout: page
header: CSmetaPred
title: Prediction of catalytic residues    
description: Meta-approach to predict catalytic residues
img: assets/img/projects/CsmetaPred_image.jpg
importance: 5
category: work
---

<div class="row text-justify">
The knowledge of catalytic residues can also assist in elucidation of reaction mechanism apart from enhanced function annotation of enzymes. Moreover, provides enhanced protein function annotations. The determination of active site residues involves both time-consuming experimental endeavours and computational catalytic prediction approaches. In our group, we have developed a consensus based or meta-approach (CSmetaPred) to predict catalytic residues that combines four well-known catalytic residue prediction methods (CRPred, EXIA2, DISCERN, and WCN) to ranks residues in order of their likelihood to be catalytic residues. This method was improved upon including predicted pocket information as catalytic sites occur nearby binding site residues and this improved method is referred to as CSmetaPred_poc.

<div class="text-capitalize font-weight-bold align-center"> Overview of CSmetaPred </div>
<div class="row mt-4 align-center">
    <div class="col-sm mt-3 ml-2 mt-md-0">
        {% include figure.html path="assets/img/projects/csmetapred1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

We assessed our methods on multiple benchmark datasets using performance on ROC and PR curves. The average ROC curves showed that CSmetaPred outperformed its constituent methods on pooled dataset. CSmetaPred is the best among evaluated methods. See below the performance on ROC and PR curves.

<div class="row mt-4">
    <div class="col-sm mt-3 ml-10 mt-md-0 align-center">
        {% include figure.html path="assets/img/projects/csmetapred2.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
Figure showing comparison of CSmetaPred with its constituent methods on CSAMAC dataset using Average ROC (Left panel) and Average PR curves (Right panel).
</div>

The assessment of prediction results on multiple benchmark datasets showed our methods CSmetaPred/CSmetaPred_poc has the highest accuracy among the evaluated methods. Having shown that meta-predictors are the best among evaluated methods, next we have analyzed ranked position of known catalytic residues from all methods. As a metric to compare methods, we have used median rank of catalytic residues. Both meta-predictors achieve lower (better) median rank in comparison to other methods across all datasets. In fact, CSmetaPred_poc achieves the lowest catalytic residue median rank. The same is observed when either polar/charged or non-polar residues. These analyses suggest that meta-predictors are able to rank putative catalytic residues at lower (better) ranked positions, which is also observed in median ranks. In top 20 ranked residues of CSmetaPred, we are able to predict all known catalytic residues for ~73% of enzymes.
<br><br>
This is important because it can help experimentalist to prioritize residues for mutational studies in their efforts to identify and characterize catalytic residues. These analyses suggest that CSmetaPred_poc is able to rank putative catalytic residues at lower (better) ranked positions, which can facilitate and expedite their experimental characterization. 


</div>
