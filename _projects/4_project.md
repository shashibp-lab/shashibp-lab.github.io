---
layout: page
header: Multidomain structure prediction 
title: Analyses of domain-domain interfaces
description: Modeling interfaces
img: assets/img/projects/multidomain.png
importance: 2
category: work
---

<div class="row text-justify">

Intra-chain domain intearactions in multidomain proteins are known to play a significant role in their function and stability. These interactions are usually mediated through a direct physical interaction between domains at domain-domain interfaces (DDIs). In our group, we are broadly interested in understanding domain-domain interfaces with emphasis on characterizing the structural variability to gain insights into evolution of interfaces. These analyses will assist in accurate modeling of domain interfaces. 
<div class="text-capitalize font-weight-bold"> Analyses of intra-chain domain interfaces among structures of same proteins </div>
In a preliminary analysis of domain interface similarity among protein structures determined under various crystallization conditions, showed that domain-domain orientation and interfaces (average interface RMSD of 1.1 &#8491;) are mostly conserved. Most of the large changes in domain orientations are observed due to binding of DNA (Figure 1) and ligand (Figure 2).

<br><br> 
<div class="row ">
    <div class="col-sm mt-3 ml-2 mt-md-0">
        {% include figure.html path="assets/img/projects/modeling_img1.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="caption">
Images showing suprposed domains of multidomain proteins upon binding of DNA (Figure 1) and ligand (Figure 2). The domain orientation are also shown on left in holo and apo forms of structures.
</div>

<div class="text-capitalize font-weight-bold"> Analyses of intra-chain domain interfaces among domains of no structural/sequence similarity</div>
In another work, we analyzed interface structural variability among domains having no sequence or structural relationship. The domain interfaces were aligned using iAlign and computed IS-score/iRMSD as a measure of interface structural similarity. The non-redundant datasets of CATH domains were constructed that had consecutive and non-consecutive domains. We structurally aligned intra-chain domain interfaces having no structural/apparent sequence relationships. The interface alignment of spatially constrained domains (due to inter-domain linkers) showed that ~88% of these could identify a structural matching interface having similar C-alpha geometry and contact pattern despite that aligned domain pairs are not structurally related. The distribution of the best aligned interface is shown in Figure below. This suggests that interfaces are structurally redundant. Moreover, the mean interface similarity score (IS-score) is 0.307, which is higher compared to the average random score (0.207). 

<div class="row align-center">
    <div class="col mt-3 mt-md-0">
        {% include figure.html path="assets/img/projects/modeling_img2.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption text-justify">
Scatter plot of the interfacial RMSD versus (A) fraction of aligned residues  (fres) and (B) fraction of aligned contacts (fcon) for the closest match of 1511 domain-domain interfaces extracted from proteins having only two CATH classified structural domains. Each point is represented using color gradient based on IS-score. Histogram and density plots of RMSD, fres, fcon and IS-score are shown surrounding main scatter plot.
</div>

The above results suggest that intra-chain DDIs of consecutive/non-consecutive continuous or discontinuous domains are degenerate as has been shown for Protein-protein interfaces (PPI). Based on these, we investigated whether domain interfaces from intra-chain (DDIs) and inter-chain (PPIs) show degeneracy when compared to each other. We constructed non-redundant PPIs having CATH domains and compared with previously constructed intra-chain domain interfaces. The best structural match of a protein-protein interface is one with the highest IS-score interface from three template libraries. The Figure below shows distribution of various parameters for the best match of interfaces. The mean (SD) IS-score of the closest match of inter-chain interface with intra-chain domain interface is 0.311 (0.031). Among these, ~86% of protein-protein interfaces have the best matches with statistically significant IS-score (p-value <0.05). Thus, shows that interfaces of inter-chain domains are similar to intra-chain domain interfaces despite having no similarity at the level of domains. 

<div class="row align-center">
    <div class="col mt-3 mt-md-0">
        {% include figure.html path="assets/img/projects/modeling_img3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption text-justify">
Structural comparison of inter-chain domain and intra-chain domain interfaces. Scatter plot of interfacial RMSD versus (A) fraction of aligned residues  (fres) and (B) fraction of aligned contacts (fcon) for the closest match of 1464 protein-protein interfaces with intra-chain domain interfaces. Distribution of IS-score is shown as histogram.
</div>

Examples of structural superposition of domain interfaces showing similarity in them is depicted below:
<br><br>
<div class="row">
    <div class="col-sm ml-2 mt-3 mt-md-0">
        {% include figure.html path="assets/img/projects/modeling_img4.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 ml-2 mt-md-0">
        {% include figure.html path="assets/img/projects/modeling_img5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption text-justify">
Example of structural alignment of DDIs
</div>

Subsequently, we analyzed structural space of DDIs and found it to be highly connected as ~84% of all possible directed edges among interfaces are found having at most path length of 8 when 0.26 is IS-score threshold. At this threshold, ~83% of interfaces form the largest strongly connected component. Thus, suggesting that structural space of intra-domain interface is degenerate and highly connected, as has been observed for PPI interfaces. Interestingly, combining intra- and inter-chain DDIs resulted in identifying more number of related interfaces suggesting that domain interfaces are degenerate whether formed within a protein or between proteins. This may be due to limited possible ways of packing secondary structures. In principle, such similarities could be exploited to improve the modeling of multidomain proteins.

<div class="row text-justify p-2">
<div class="text-capitalize font-weight-bold"> Modeling of domain interfaces </div>
Having observed extensive intra/inter-chain domain interfaces, we constructed a combined dataset of domain interfaces (intra/inter-chain) to search for template for modeling domain interfaces.

</div>

</div>
