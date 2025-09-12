---
layout: page
title: Design of Polymer Colloids
# description: from single chain to Janus particles
img: assets/img/FNP.jpg
importance: 3
category: work
related_publications: true
---
<div style="text-align: justify"> <i> Polymer solutions are ubiquitous in nature and technological applications where they pursue a variety of roles, such as storage of biological information in the form of DNA, and formation of polymer colloids. The latter is often governed by the change in polymer conformation. Namely, under good solvent conditions, a polymer obtains a swollen-like coil conformation, contrary to poor solvent conditions, where a polymer is in a compact globule state. To minimise their interaction with a poor solvent, polymer globules can further assemble into aggregates. This conformational change is exploited, for example, in the flash nanoprecipitation (<b>FNP</b>) technique, which employs rapid micromixing of polymers in solution and a miscible poor solvent for fabricating colloids of varied morphology. Below, I highlight several works where I investigated single-chain and aggregate properties both numerically and experimentally. </i> </div>
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/FNP_ext.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Figure 1: (left) Representative snapshots of a polystyrene chain in good and poor solvents; (middle) colloidal morphologies as a function of block copolymer concentration obtained in the simulations and the experiments; (right) particle size fabricated in THF-hexane and toluene-hexane mixtures and corresponding TEM images. 
</div>

<div style="text-align: justify"> 
Motivated by an experimental system of interest for FNP, we investigated a single polystyrene (<b>PS</b>) chain of varied length in solutions of tetrahydrofuran (THF), e.g., a <b>good</b> solvent, and water, e.g., a <b>poor</b> solvent {% cite morozova2018coil %}. We employed molecular dynamics simulation with atomistic description to preserve the chemical information of the compounds. We gradually changed the solution composition from good to poor solvent conditions mimicking the change of the solvent replacement in the fabrication method. We discovered that in water-rich mixtures, a <b>substantial</b> amount of THF molecules is trapped inside of the polymer globule with an excess amount located on its surface acting as a protective layer between the hydrophobic polymer and the aqueous medium. This indicates that when polymer globules further aggregate to form colloids good solvent molecules might be trapped inside impacting the final colloidal <b> morphology</b>. </div>


Together with the <a href="https://priestley.princeton.edu"> experimental group</a> at Princeton University, we set out to design amphiphilic Janus colloids with two distinct surface domains, e.g., one hydrophobic and one hydrophilic {% cite morozova2020silico %}. Such nanoparticles are promising candidates that can act as emulsion stabilisers, offering enlarged system stability against aggregation. To produce such Janus colloids, we considered the assembly of two hydrophobic homopolymers and one amphiphilic block copolymer (BCP), both numerically and experimentally. First, we developed a <b>coarse-grained model</b> that qualitatively captures the experiments as shown in Fig. 1 (middle). It allowed us to investigate the design space <i>efficiently</i> and <b>guide the experiments</b> to produce colloids of the desired morphology. We determined the optimal process parameters for the formation of the amphiphilic Janus particles. Additionally, computer simulations provided precise information about the polymer conformations within particles, which are extremely difficult to extract from the experiments.


Polymer colloids produced through FNP using a polymer solution and <b>water</b> were usually electrostatically stabilised even when the polymers employed were electroneutral. In this experimental work, we attempted to elucidate the stabilisation mechanism as well as to expand the operation mode of the FNP technique by  <b>utilising </b> non-polar poor solvents  {% cite morozova2018stability %}. Surprisingly, we were able to fabricate stable colloidal suspensions for a wide range of non-polar solvents. We developed a theoretical framework to rationalise the experimental observations. Theoretical considerations suggest that steric stabilisation, originating from the <b>roughness</b> of the surface of the produced polymer colloids, is the most likely candidate. 
---