<p align="center">
    <br>
        <img src="docs/source/imgs/Group 13.png" width="500"/>
    </br>
    <br>
        <strong> Transmute AI Model Efficiency Toolkit </strong>
    </br>
</p>

# Trailmet
<h3 align="center">
<p>Transmute AI Lab Model Efficiency Toolkit
</h3>

## Introduction
Trailmet is a model efficiency toolkit for compressing deep learning models using state of the art compression techniques. 
Today deep learning models are not deployable because of their huge memory footprint, TRAILMET is an effort to make deep learning models more efficient in their size to performance ratio. It is developed using Pytorch 1.5.

### Major features
- State of the art compression algorithms implemented.
- Demo notebooks for training each algorithm.
- Modular Design: All alogithms are modular and can customized easily for any kind of model and dataset.

## Installation

Below are quick steps for installation:

```shell
conda create -n trailmet python=3.8 pytorch=1.10 cudatoolkit=11.3 torchvision==0.11.0 -c pytorch -y
conda activate trailmet
git clone https://github.com/transmuteAI/trailmet.git
cd trailmet
```
## Algorithms Implemented

Results and models weights are available in the model zoo (coming soon..)

<details open>
<summary> Knowledge Distillation</summary>
  
- [x] [Response KD](https://arxiv.org/abs/1503.02531)
- [x] [Factor Transfer](https://arxiv.org/abs/1802.04977)
- [x] [Attention Transfer](https://arxiv.org/abs/1612.03928)
  
</details>

<details open>  
<summary> Pruning </summary>

- [x] [Chipnet](https://arxiv.org/abs/2102.07156)
- [x] [Network slimming](https://arxiv.org/abs/1708.06519)
  
</details>
  
<details open>
<summary> Quantization</summary>
  
- [x] [BitSplit](https://dl.acm.org/doi/abs/10.5555/3524938.3525851)
- [x] [BRECQ](https://arxiv.org/abs/2102.05426)
- [x] [LAPQ](https://arxiv.org/abs/1911.07190)  

</details>

<details open>
<summary> Binerization</summary>
  
- [x] [BiRealNet](https://arxiv.org/abs/1808.00278)
- [x] [ReActNet](https://arxiv.org/abs/2003.03488)
- [x] [BNN-BN](https://arxiv.org/abs/2104.08215v1)

</details>

## Acknowledgement



## Citation

If you find this project useful in your research, please consider cite:

```BibTeX
@misc{,
    title={},
    author={},
    howpublished = {}},
    year={2023}
}
```

## License

This project is released under the [Apache 2.0 license](LICENSE).
