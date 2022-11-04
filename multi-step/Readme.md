# Multi-step Retrosynthesis: methods and implementations

## Methods

| Paper                                                        | Search Algorithm            | Year | Journal / Conference | Code                                                         |
| ------------------------------------------------------------ | --------------------------- | ---- | -------------------- | ------------------------------------------------------------ |
| Construction of new medicines via game proof search          | Proof-number Search         | 2012 | AAAI                 | [link](https://www.cs.toronto.edu/~aheifets/ChemicalPlanning/) |
| Planning chemical syntheses with deep neural networks and symbolic AI | MCTS                        | 2018 | Nature               | -                                                            |
| Learning Retrosynthetic Planning through Simulated Experience | Deep Reinforcement Learning | 2019 | ACS Central Science  | [link](https://github.com/jsschreck/retroRL)                 |
| Depth-First Proof-Number Search with Heuristic Edge Cost and Application to Chemical Synthesis Planning | Proof-number Search         | 2019 | NIPS                 | -                                                            |
| Automatic Retrosynthetic Pathway Planning Using Template-free Models | MCTS                        | 2020 | Chemical Science     | [link](https://github.com/PKUMDL-AI/AutoSynRoute)            |
| Predicting retrosynthetic pathways using transformer-based models and a hyper-graph exploration strategy | Hyper-Graph                 | 2020 | Chemical Science     | -                                                            |
| Retro* Learning Retrosynthetic Planning with Neural Guided A star Search | A* Search                   | 2020 | ICML                 | [link](https://github.com/binghong-ml/retro_star)            |
| Self-Improved Retrosynthetic Planning                        | A* Search                   | 2021 | ICML                 | [link](https://github.com/junsu-kim97/self_improved_retro)   |
| AI-Driven Synthetic Route Design with Retrosynthesis Knowledge | MCTS                        | 2022 | JCIM                 | [link](https://github.com/clinfo/ReTReK)                     |
| RetroGraph Retrosyntheic Planing with Graph Search           | A* Search                   | 2022 | SIGKDD               | -                                                            |


## Performance

(Copy from [RetroGraph](https://arxiv.org/abs/2206.11477v1))

### USPTO dataset proposed by Retrostar

| Algorithm  | Success Rate of  Iteration Limit (%) ↑ |       |       |       |       | Iteration ↓ | Rec. Nodes ↓ | Mol. Nodes ↓ |
| ---------- | -------------------------------------- | ----- | ----- | ----- | ----- | ----------- | ------------ | ------------ |
|            | 100                                    | 200   | 300   | 400   | 500   |             |              |              |
| Greedy DFS | 38.42                                  | 40.53 | 44.21 | 45.26 | 46.84 | 300.56      | -            | -            |
| DFPN-E     | 50.53                                  | 58.42 | 64.21 | 68.42 | 75.26 | 208.12      | 3123.33      | 4635.08      |
| MCTS       | 43.68                                  | 47.37 | 54.74 | 58.95 | 62.63 | 254.32      | -            | -            |
| Retro*     | 52.11                                  | 66.32 | 76.84 | 81.05 | 86.84 | 166.72      | 2927.92      | 4174.52      |
| RetroGraph | 88.42                                  | 97.89 | 98.95 | 99.47 | 99.47 | 45.13       | 674.22       | 500.43       |

### USPTO-EXT dataset proposed by RetroGraph

| Algorithm  | Success Rate of  Iteration Limit (%) ↑ |       |       |       |       |       | Iteration ↓ | Rec. Nodes ↓ | Mol. Nodes ↓ |
| ---------- | -------------------------------------- | ----- | ----- | ----- | ----- | ----- | ----------- | ------------ | ------------ |
|            | 10                                     | 20    | 30    | 40    | 50    | 100   |             |              |              |
| Retro*     | 42.47                                  | 48.79 | 51.84 | 53.63 | 55.00 | 57.89 | 48.49       | 790.49       | 1136.51      |
| RetroGraph | 50.84                                  | 58.05 | 62.05 | 64.26 | 66.89 | 72.89 | 37.25       | 491.97       | 373.80       |