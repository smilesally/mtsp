# 群体智能大作业：基于仿生群智算法的无人机任务分配 (多旅行商问题的求解)

## Baselines

- [x] ACO 蚁群算法
- [x] GA 遗传算法
- [x] PSO 粒子群算法

## Experiments

- 迭代200个epochs (若无明显收敛趋势，则迭代次数将更多)
- 使用Early Stop策略，若连续多次性能没有提升，则终止训练。

| 算法 | 任务点数 | 无人机数 | 求解路径长度 |
| ---- | -------- | -------- | ------------ |
| ACO  | 30       | 10       |  3000.576    |
| ACO  | 200      | 20       |  9468.424    |
| ACO  | 500      | 30       |  21323.845   |
| GA   | 30       | 10       |  2465.511    |
| GA   | 200      | 20       |  9267.250    |
| GA   | 500      | 30       |  19977.058   |
| PSO  | 30       | 10       |  2435.522    |
| PSO  | 200      | 20       |  13951.527   |
| PSO  | 500      | 30       |  43172.257   |



