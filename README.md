Project to predict critical temperature of superconductors.

Two setups were used: 
- CNN architectures with formula information of the elements in the material using the atomic properties
- XGBoost regressor on the material data, using MIC and distance correlation for feature reduction, a GA to refine selected features
