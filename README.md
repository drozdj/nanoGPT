

1. ```conda create -n nanoGPT python=3.10.18 ```
    - [pytorch docs](https://shorturl.at/jpBT4)

2. ```conda activate nanoGPT```

3. ```pip install --pre torch torchvision --index-url https://download.pytorch.org/whl/nightly/cpu```

4. ```pip install torch numpy transformers datasets tiktoken wandb tqdm```

~~5. ```python openwebtext/prepare.py```~~ 
- throws error because it has issues retrieving openwebtest 

5. ```python data/shakespear_char/prepare.py```

6. ```python train.py```

7. ```python sample.py```

---

- [original nanoGPT on M1](https://github.com/karpathy/nanoGPT/issues/28)
- [Sebastian Raschka on pytorch](https://shorturl.at/ztcVV)
