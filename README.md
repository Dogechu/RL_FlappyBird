# RL_FlappyBird

This repository contains an individual assignment for the **Reinforcement Learning** course at **CentraleSupélec**. The objective of this project is to train two reinforcement learning agents—**Monte Carlo (MC)** and **SARSA(λ)**—to play a simplified game called **Text Flappy Bird (TFB)**.


## Structure of files:
<pre> ``` 
│  Flapy_Bird.ipynb
│  README.md
│
├─best_model_mc
│      best_model_mont_carlo.pkl
│      monte_Q_final.txt
│      mont_results_final.txt
│
└─best_model_sarsa
        best_model_sarsa.pkl
        sarsa_Q_final.txt
        sarsa_results_final.txt ``` </pre>

## Training and Implementation

Most of the work was conducted in Jupyter notebooks(Flapy_Bird.ipynb), primarily executed on **Google Colab** to take advantage of available computing resources. 

After extensive experimentation, both trained agents are capable of achieving **a score of at least 1000 without mistakes**. The trained models are stored in `.pkl` format within their respective directories.

## Reproducing Results

If you wish to reproduce the results, ensure that **all file paths are correctly updated**, especially when using the pre-trained agents with the best scores.


