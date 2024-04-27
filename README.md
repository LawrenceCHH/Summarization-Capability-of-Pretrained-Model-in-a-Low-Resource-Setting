## Introduction

This repository contains experimental data for reproduce the models of Two-Stage Summarization Method and Idealized Method.
- Json files: fine-tune Classifiers or Summarizers.
- General Labels (268 judgments): sentences are labeled based on "摘要", "無關", "訴訟要件不足".
- Testing dataset from 28 judgments (General and Fine Classifers): labeled sentences can be used to test the performance of classifiers.
- Testing dataset from 28 judgments (Six methods): generated summaries provide experimental result from the paper: Summarization Capability of Pretrained Model in a Low-Resource Setting: A Case Study on Traffic-Event Judgements of Negligent Injury Behavior.
- 268 Judgments and Summaries: dataset from https://hdl.handle.net/11296/259yu4.

## License

This repository is licensed under the [Apache-2.0 License](LICENSE). 

## Citation
If you appreciate the Two-Stage Summarization Framework, please consider citing the associated paper:
1. 黃千翔（2023）。預訓練模型在少資源環境下的摘要能力：以交通過失傷害判決書為例。﹝碩士論文。臺北市立大學﹞臺灣博碩士論文知識加值系統。 https://hdl.handle.net/11296/ha5vm8。
2. 遲佑成（2022）。以GPT2模型進行遷移式訓練交通過失傷害罪判決之摘要。﹝碩士論文。臺北市立大學﹞臺灣博碩士論文知識加值系統。https://hdl.handle.net/11296/259yu4。

Furthermore, if you find ChatGLM-6B useful, please consider citing the following papers:

```
@inproceedings{
  zeng2023glm-130b,
  title={{GLM}-130B: An Open Bilingual Pre-trained Model},
  author={Aohan Zeng and Xiao Liu and Zhengxiao Du and Zihan Wang and Hanyu Lai and Ming Ding and Zhuoyi Yang and Yifan Xu and Wendi Zheng and Xiao Xia and Weng Lam Tam and Zixuan Ma and Yufei Xue and Jidong Zhai and Wenguang Chen and Zhiyuan Liu and Peng Zhang and Yuxiao Dong and Jie Tang},
  booktitle={The Eleventh International Conference on Learning Representations (ICLR)},
  year={2023},
  url={https://openreview.net/forum?id=-Aw0rrrPUF}
}
```

```
@inproceedings{du2022glm,
  title={GLM: General Language Model Pretraining with Autoregressive Blank Infilling},
  author={Du, Zhengxiao and Qian, Yujie and Liu, Xiao and Ding, Ming and Qiu, Jiezhong and Yang, Zhilin and Tang, Jie},
  booktitle={Proceedings of the 60th Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers)},
  pages={320--335},
  year={2022}
}
```
