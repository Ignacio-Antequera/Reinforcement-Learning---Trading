# Reinforcement Learning for Stock Trading

## Introduction
Hello there! My name is Ignacio Antequera and this repository contains a project focused on applying reinforcement learning techniques to stock trading scenarios. The project aims to develop an agent capable of making buy and sell decisions based on historical market data, with the goal of maximizing profits in a simulated trading environment.

Link to visualize demo of the project on the browser: [Automated Stock Trading System using Reinforcement Learning](https://stocktradingsystem-rl.netlify.app/)

## Models Used
- Deep Q-Learning: The project utilizes the deep Q-learning algorithm, which combines Q-learning with deep neural networks to approximate the Q-function. This allows the agent to learn an optimal policy for making buy and sell decisions based on historical market data.
- Monte Carlo Simulations: Monte Carlo simulations are used to evaluate the agent's performance across multiple simulations, providing a more accurate estimate of its expected performance.

## Approach
1. Data Preprocessing: Historical stock market data is preprocessed and analyzed to calculate various technical indicators such as exponential moving averages (EMA), Moving Average Convergence Divergence (MACD), Relative Strength Index (RSI), On-Balance Volume (OBV), and Bollinger Bands.
2. Environment Definition: A custom OpenAI Gym environment is created to simulate a stock trading scenario. The environment defines the action and observation spaces, as well as the reward function, to facilitate training of the reinforcement learning agent.
3. Agent Definition: A deep Q-learning agent is defined using TensorFlow and Keras. The agent learns to make buy and sell decisions in the stock trading environment based on the historical market data provided in the environment's observations.
4. Training: The agent is trained using historical market data and reinforcement learning techniques such as deep Q-learning. The agent's performance is evaluated using Monte Carlo simulations to estimate its expected performance in various scenarios.

## Tools and Libraries
- Python: The project is implemented using Python programming language.
- TensorFlow: TensorFlow is used to define and train the deep Q-learning agent.
- Keras: Keras is used as a high-level neural networks API, providing an interface for building and training neural networks.
- NumPy: NumPy is used for numerical computing, particularly for handling arrays and matrices.
- OpenAI Gym: OpenAI Gym is used to define the custom environment for simulating the stock trading scenario.

## Conclusions
This project has provided valuable insights into the application of reinforcement learning techniques to stock trading scenarios. By leveraging deep Q-learning and Monte Carlo simulations, we have developed an agent capable of making buy and sell decisions based on historical market data. The agent's performance can be further improved through additional training and refinement of the reinforcement learning algorithms used.

Throughout the development of this project, I've gained valuable insights into the field of reinforcement learning applied to stock trading scenarios. This project has allowed me to deepen my understanding of key concepts such as Q-learning and deep Q-networks (DQN). I've also expanded my knowledge on how to implement these concepts using Python libraries such as TensorFlow, NumPy, and OpenAI Gym.

One of the key techniques used in this project is the deep Q-learning algorithm, which combines Q-learning with deep neural networks to approximate the Q-function. This allowed the agent to learn an optimal policy for making buy and sell decisions in the stock trading environment based on historical market data.

Additionally, the use of Monte Carlo simulations provided a robust method for evaluating the agent's performance across multiple simulations, which helps provide a more accurate estimate of its expected performance.

The project also involved preprocessing and analyzing stock market data, including the calculation of various technical indicators such as exponential moving averages (EMA), Moving Average Convergence Divergence (MACD), Relative Strength Index (RSI), On-Balance Volume (OBV), and Bollinger Bands. These indicators were used to define the state space for the reinforcement learning agent and provide relevant market information for decision-making.

I would like to express my excitement for completing this project and acknowledge the guidance provided by [Sina Nazeri](https://www.linkedin.com/in/sina-nazeri), a data scientist at IBM. Their expertise and insights have greatly enriched my learning experience and encouraged me to overcome various challenges encountered during the development process.

Overall, this project has been a rewarding learning experience that has equipped me with valuable knowledge and skills in reinforcement learning and its application to stock trading environments. I look forward to applying these skills to other projects and continuing to explore new developments in the AI/ML field.

I invite you to provide any feedback or pose inquiries you may have. Kindly find my contact details listed below for your convenience. Your input is greatly appreciated.

Ignacio Antequera Sanchez

***

[LinkedIn](https://www.linkedin.com/in/ignacio-antequera)  ||  [GitHub](https://github.com/Ignacio-Antequera)  ||  [Leetcode](https://leetcode.com/Ignacio_antequera)