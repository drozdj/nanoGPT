- https://github.com/drozdj/nanoGPT/blob/main/worklog.md
- https://github.com/drozdj/nanoGPT/blob/main/todos.md

## motivation for repo?
- understand [nanoGPT](https://github.com/karpathy/nanogpt) and how its evolved through PRs and commits
    - alot of similar repos are not reproducible from inital commit: this one is.  no suprises here, GPT2 is 6yrs old.
    - the [contributers](https://github.com/karpathy/nanoGPT/graphs/contributors) on this repo are top, can learn a ton from them

- *play* on a small scale: fueled by recent interest with [performance optimizations](https://github.com/danielvegamyhre/ml-perf-reading-group) & [kernels](https://github.com/gpu-mode)
    -  efforts like [this](https://github.com/KellerJordan/modded-nanogpt/blob/master/records/track_1_short/2025-10-04_Backout/514e7581-fbd4-4338-a3e4-e556f9c958ce.txt) are absolutely bonkers, would love to contribute

## instructions
1. ```conda create -n nanoGPT python=3.10.18 ```
    - [pytorch docs](https://shorturl.at/jpBT4)

2. ```conda activate nanoGPT```

3. ```pip install torch numpy transformers datasets tiktoken wandb tqdm```

~~4. ```python openwebtext/prepare.py```~~ 
- throws error because it has issues retrieving openwebtest 

4. ```python data/shakespear_char/prepare.py```

5. ```python train.py```

6. ```python sample.py```


## inspiration/resources
- https://github.com/karpathy/nanoGPT
- https://github.com/KellerJordan/modded-nanogpt
- https://github.com/gpu-mode/lectures
