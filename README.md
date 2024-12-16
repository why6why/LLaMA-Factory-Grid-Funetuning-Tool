To address the need for multiple runs of different parameter when facing the problem of parameters fine-tuning in LLaMA-Factory, we have provided a tool named 'LLaMA-Factory-Grid-Funetuning-Tool' for large model grid search parameter tuning tailored for LLaMA-Factory. 


The parameters fine-tuning method of the grid search is an approach that involves exhaustively trying different combinations of parameters to find the optimal parameter configuration. It is same to covering a range of parameter values with a grid of points and then trying each combination of parameters at these grid points one by one, ultimately identifying the parameter configuration that yields the best performance. 

Two main method is provided:
1. Generate a new YAML file through grid parameters and the original YAML
2. Execute the new YAML files in sequence. Before that, you can delete the YAML file with the parameters you don't want to execute.


We welcome everyone to further modify and optimize the tool based on the code provided.


