Model description:
We adapt a well-established ordinary differential equation framework to describe cell signaling pathways by explicitly incorporating receptor trafficking and compartmentalized signaling. We apply a quantitative model selection and calibration approach on the follicle-stimulating hormone receptor (FSHR) using kinetic data on receptor trafficking and signaling dynamics. In the article a model selection on 200 models is realized, but only the best selected model is presented here (see ressources for all models tested). 

Data description: 
Using Bioluminescence Resonance Energy Transfer (BRET) measurements, we monitored the temporal dynamics of molecular species following FSH stimulation in a cell system overexpressing FSHR. 
We considered four different BRET experiments: (i) the total cAMP levels upon continuous stimulation with varying FSH concentrations, (ii) the cAMP level when there is a endocytosis inhibitor, the FSHR localized at the plasma membrane, which decrease upon ligand-induced internalization and the time-dependent accumulation of ligand-receptors complexes in early endosomes. 

Most information about the code and all the scripts are available to this following git: 
https://gitlab.inria.fr/cweckel/spatiotemporal_modeling2

Differences between the implementation and the original publication: 
There is some different notations between the code and in the article. In the code, `alpha_2` and `alpha_3` correspond to the normalized parameters `alpha_2*` and `alpha_3*, all in the article all the normalized parameters are written: `k^*`. 

Experience of fitting / uncertainty analysis: 
The optimize used for the fit is FidesOptimizer()and the seed used for each fit is written in the beginning of each fit. 

The nominal parameters come from our own fitting. 

