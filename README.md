# 1D Grid LSTM on XOR problem

Code in reference to [my post](http://christopher5106.github.io/deep/learning/2016/10/21/1d-grid-lstm-and-the-xor-problem.html)

![](grid-1d.png)

As written in paper [Grid Long Short-Term Memory](https://arxiv.org/abs/1507.01526)

Working example on 10 bit input strings :

	python main.py --bits 10 --layers 10 --hidden 1000 --batch_size 20 --learning_rate 0.06
