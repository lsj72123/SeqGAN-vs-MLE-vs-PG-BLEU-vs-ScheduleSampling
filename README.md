# SeqGAN-vs-MLE-vs-PG-BLEU-vs-ScheduledSampling-PyTorch
A implementation of SeqGAN, MLE, PG-BLEU and Scheduled Sampling in PyTorch. We compare the methods on synthetic dataset, and real dataset consisting of Barack Obama speeches.


## Tested with:
* **PyTorch v1 Stable**
* Python 3.6
* CUDA at least 8.0 (For GPU)

## Origin
The idea is from paper [SeqGAN: Sequence Generative Adversarial Nets with Policy Gradient]   (https://arxiv.org/pdf/1609.05473.pdf)

The code is written in PyTorch with SeqGAN is based on the implementation from https://github.com/ZiJianZhao/SeqGAN-PyTorch

## Runing
```
$ python main.py
```

