# LAKE
LAKE (Knowledge-Based Systems) official code

The code for the paper ["Layer-constrained variational autoencoding kernel density estimation model for anomaly detection" (authors: Peng Lv*, Yanwei Yu *, Yangyang Fan*, Xianfeng Tang, Xiangrong Tong)](https://www.sciencedirect.com/science/article/pii/S0950705120301635) is now open source! 

Please reach us via emails or via github issues for any enquiries!

Please cite our work if you find it useful for your research and work.
```
@article{lv2020layer,
  title={Layer-constrained variational autoencoding kernel density estimation model for anomaly detection},
  author={Lv, Peng and Yu, Yanwei and Fan, Yangyang and Tang, Xianfeng and Tong, Xiangrong},
  journal={Knowledge-Based Systems},
  pages={105753},
  year={2020},
  publisher={Elsevier}
}
```
## Prerequisites.
To run the code, follow those steps:

Download the project code and install requirements (in the cloned repository):

```
pip3 install -r requirements.txt
```
This is part of the function description, such as KDDCUP:
```
KDD99Loader is to preprocess the data.

get_loader is to load the dataset.

loss_function defines the loss function of the network.

VAE defines the structure of the network.
```
