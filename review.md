# Review of the Hotels in Vienna project
### Written by Borbala Kovacs

## Reproducibility
I could almost run the analysis with one click. I could install almost all of the dependencies, however I had a problem with installing `contourpy==1.3.1` (no matching binary wheel) and had to either allow building from source (with build tools) or adjust the version to a compatible one. After resolving that, the Jupyter notebook in `analysis/` ran and produced the plots and tables. Therefore, I would say I could run the analysis with changing one line. It would be better practice to use an environment .yaml file, so that these kind of issues can be avoided. 

## Structure 
I think the README file for this project is clear and gives straightforward instructions for reproducing the code. The folder structure is also clear and logical. 

## Clean coding
I think the code is very well structured, the variable names are straightforward, there are good explanations for each step. 

## Ideas to improve the project
* Use a more robust environment specification. Providing an `environment.yml` (for conda) could be helpful so that installs are reproducible without needing build tools.
* In the analysis part you could write a short interpretation of your graphs so that the project feels a bit more complete. Also, you could save final charts in an output folder for further use. 