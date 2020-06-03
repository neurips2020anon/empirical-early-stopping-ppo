# An Empirical Investigation of Early Stopping inProximal Policy Optimization Algorithm

Source code and reproduction step for the paper _An Empirical Investigation of Early Stopping in Proximal Policy Optimization Algorithm_, NeurIPS2020 submission

## Training

## Evaluation

The results of the experiments can be accessed in an interactive way using the following ![Weights and Biases Project](https://app.wandb.ai/neurips2020-early-stopping/ppo-early-stopping/reports/Final-Report--VmlldzoxMjYxNjc).

Furthermore, the various plots used in the paper can be generated using the `AllPlots` Jupyter Notebook located in the `evaluation` folder.
To quickly generate the various plots, we also provided pre-cached data corresponding to the `ppo-early-stopping` as the `evaluation/neurips2020_early_stopping_ppo_early_stopping` folder.
To regenerate the data used for the plots, please remove the folder specified above and rerun the notebook. However, depending on the machine used, the data can take up to a few hours to generate.

In case you have you have followed the "Training" section and generated your experiments and a different WANDB project, please edit the `wandb_entity_project` variable in the first cell of the notebook and re-run it to obtain the corresponding plots as in the paper.
