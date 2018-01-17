# PolicyGradient

Policy Gradient Methods for HalfCheetah and Cartpole openAIgym tasks.
Base code is taken from Berkeley's CS294-112 course

Dependencies:
tensorflow 1.4.1
python 3.5.1
mujoco-py 0.5.7 (HalfCheetah only)
numpy 1.13.3
openAIgym HalfCheetah and Cartpole environments

python train_pg.py HalfCheetah-v1 -ep 150 --discount 0.9 -rtg -b 30000 --n_layers 10 --learning_rate=0.03. Highest average return attained was 173 after 100 iterations. 

