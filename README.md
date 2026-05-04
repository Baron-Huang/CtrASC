# HACircuit
Human-prior Aligned Multi-order Instance Interaction Circuits Construct Diagnostically-transparent and Objective Pan-squamous Grading Score Systems

## 🧔: Authors [*Corresponding author]
Pan Huang, Chentao Li*, Jing Qin*

## :fire: News

- [xxx/xxx/xxx] xxx



## :rocket: Pipeline

Here's an overview of our **Human-prior Aligned Multi-order Instance Interaction Circuits (HACircuit)** method:

![Figure 1](./images/xxx.jpg)



## :mag: TODO
<font color="red">**We are currently organizing all the code. Stay tuned!**</font>
- [x] training code
- [x] Evaluation code
- [x] Model code
- [ ] Pretrained weights
- [ ] Datasets


## 🛠️ Getting Started

To get started with **AE-PATH**, follow the installation instructions below.

1.  Clone the repo

```sh
git clone https://github.com/Prince-Lee-PathAI/HCF-MIL
```

2. Install dependencies
   
```sh
pip install -r requirements.txt
```

3. Training on Swin Transformer-S Backbone
```sh
sh run_swinT.sh
Modify: --abla_type sota --run_mode train --random_seed ${seed}
```

4. Evaluation
```sh
sh run_swinT.sh
Modify: --abla_type sota --run_mode test --random_seed ${seed}
```

5. Extract features for plots
```sh
sh run_swinT.sh
Modify: --abla_type sota --run_mode test --random_seed ${seed} --feat_extract
```

6. Interpretability plots
```sh
sh run_swinT.sh
Modify: --abla_type sota --run_mode test --random_seed ${seed} --bag_weight
```

## :postbox: Contact
If you have any questions, please contact [Dr.Pan Huang](https://scholar.google.com/citations?user=V_7bX4QAAAAJ&hl=zh-CN) (`panhuang@polyu.edu.hk`).



