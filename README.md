To run the code, install COBRApy and the Gurobi/IBM Cplex optimizer. All the input files and scripts are added to github, which can be executed to reproduce the community models and data.

Community modelling code:
The community modelling code integrates individual models by maintaining their abundance to create disease-specific gut microbiota simulations.
All the individual models are given in the file, i.e., P. copri.xml, L. ruminis.xml, M. smithii.xml, and F. prausnitzii.xml.
The script for community modelling has also been added to the file, i.e., Community_modelling.ipynb.

Optimization code:
The optimization code checks the growth rates of individual models as well as the community model. Furthermore, it incorporates various analyses like FBA and FVA.
All the individual models, i.e., P. copri.xml, L. ruminis.xml, M. smithii.xml, and F. prausnitzii.xml and the community models, i.e., HC_Model_enrich_media.xml and T2D_Model_enrich_media.xml are given in the file.
The script for model optimization and analysis is also added to the file i.e., GEM & CM Optimization and analysis.ipynb.
