- https://github.com/drozdj/nanoGPT/worklog.md
- https://github.com/drozdj/nanoGPT/todos.md

## motivation?
- work with performance implementations; maybe also kernels
- reproduce original gpt-2 (124M) training

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