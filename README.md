Fork of [spragunr](https://github.com/spragunr)'s [deep_q_rl](https://github.com/spragunr/deep_q_rl), modified for compatibility with [OpenAI Gym](https://github.com/openai/gym]).

Training networks happens headless, per usual, but watching the network play is possible with `gym` by calling `gym_run_watch.py` in place of `ale_run_watch.py`, and supplying the gym environment name.  As of now, only supports Atari gym environments.

```bash
$ python gym_run_watch.py breakout_05-28-17-09_0p00025_0p99/network_file_99.pkl Breakout-v0
``` 

See [original project](https://github.com/spragunr/deep_q_rl) for more information.
