### 深度学习笔记
- [1. DQN all in one](ALL_DQN.html)
- [2. PG 策略梯度 all in on](ALL_PG.html)
- [3. DDPG all in one](ALL_DDPG.html)


### 算法列表
分类 | 名称 | 说明
---|---|---
DQN | DQN | 记忆池+固定目标网络
DQN | Double DQN | 将动作选择和价值估计分开，避免价值过高估计
DQN | Dueling DQN |将Q值分解为状态价值和优势函数，得到更多有用信息
DQN | Prioritized Replay Buffer | 将经验池中的经验按照优先级进行采样
DQN | Multi-Step Learnin | 多步执行使得目标价值估计更为准确
DQN | Distributional DQN(Categorical DQN) | 得到价值分布
DQN | NoisyNet| 增强模型的探索能力
DQN | Rainbow: all in one | 六种方法进行了一个整合
DQN | Deep Recurrent Q-Learning for Partially Observable MDPs| DQN 和 LSTM 的结合
PG | TNPG | 共轭梯度法 求解自然策略梯度 (NPG) 
PG | ACKTR | 完全正交的Kronecker-factor技术 求解自然策略梯度 (NPG) 
PG | TRPO | 相比TNPG，TRPO由于有了一个检验手段和线搜索，能承受更大的步长。
PG | PPO-clip | 对优势的估计进行一个截断，限制了新策略空间的范围。
PG | GAE | discounted rewards to estimate the advantage
PG | Actor-Critic | 结合了 Policy Gradient (Actor) 和 Function Approximation (Critic) 的方法
PG | A3C | A3C （基于 actor-critic）算法是并行算法，可以有效的利用多核。
DDPG | DDPG | 连续空间
DDPG | TD3 |
DDPG | SAC |

