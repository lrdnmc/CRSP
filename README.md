# Emulating Human Cooperative Reasoning for Intelligible Story Point Estimation
## Data preparation
put the dataset under `data/`
## Fine tune generator
Set the hyperparameters in `train.slurm` and execute `bash train.slurm`
## Fine tune verifiers
Set the hyperparameters in `train_verifier.slurm` and execute `bash train_verifier.slurm`
## MCTS
After fine-tuning, specify the model path in `mcts.slurm`, execute `bash mcts.slurm`. Note that the provided script will not produce reasonable outputs unless the generator and verifiers are properly fine-tuned.

