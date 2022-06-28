# 3_hours_RL_Practice
Implementing the RL practical code by using baselines3 library in OpenAI

1. Import Denepdencies - Import overall necessary libraries
(+. Creating Environment)
2. Testing Environment
- env = gym.make(environment_name)
- env.action_space.sample()
- env.observation_space.sample()
3. Train Model
- model = PPO(policy_type, environment, tensorboard_log = log_path)
4. Save Model
- model.save(want_path)
5. Test and Evaluate
- Making loop framework which is given in this code.

Reference
https://youtu.be/Mut_u40Sqz4
Reinforcement Learning in 3 Hours | Full Course using Python

