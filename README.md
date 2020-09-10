**Status:** Maintenance (expect bug fixes and minor updates)

usage:
```bash
python -m baselines.run --alg=her --env=FetchPickAndPlace-v1 --num_timesteps=1e6 --n_cycles=100 --save_path=/home/user/policies/her/iter --log_path=/home/user/log_data/her/iter --before_GER_minibatch_size=256 --n_KER=8 --n_GER=4
```

