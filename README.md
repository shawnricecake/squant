# Squant
Official repo for the paper: [Squat: Quant Small Language Models on the Edge](https://arxiv.org/abs/2402.10787)


## Implementation
Follow the instructions of the [BabyLLaMA](https://github.com/timinar/BabyLlama) to implement the training environment, and [BabyLM Challenge](https://babylm.github.io/index.html) to implement the evaluation environment.


## Usage
1. Download dataset from [BabyLM Challenge](https://babylm.github.io/index.html)
2. Clean the dataset according to [BabyLLaMA](https://github.com/timinar/BabyLlama)
3. Pretrain teacher model
4. Download FP16 LLaMA-58M model from [BabyLLaMA](https://github.com/timinar/BabyLlama)
5. QAT with scripts in `distill_train/scripts/`
6. Evaluation with scripts in `evaluation_pipeline/`


## Citation
```
@article{shen2025squant,
  title={Squat: Quant Small Language Models on the Edge},
  author={Shen, Xuan and Peiyan, Dong and Kong, Zhenglun and Gong, Yifan and Yang, Changdi and Han, Zhaoyang and Xie, Yanyue and Lu, Lei and others},
  journal={arXiv preprint arXiv:2402.10787},
  year={2025}
}
```

## Acknowledgment
Code is mainly based on [BabyLLaMA](https://github.com/timinar/BabyLlama) and [LSQ](https://github.com/zhutmost/lsq-net).

