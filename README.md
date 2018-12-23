# GateMemN2N

Implementation of [Gated End-to-End Memory Networks](https://arxiv.org/pdf/1610.04211.pdf) with sklearn-like interface using Tensorflow. Tasks are from the [bAbl](http://arxiv.org/abs/1502.05698) dataset.

## Get Started

```
git clone https://github.com/cstghitpku/GateMemN2N.git

mkdir ./gmemn2n/data/
cd ./gmemn2n/data/
wget http://www.thespermwhale.com/jaseweston/babi/tasks_1-20_v1-2.tar.gz
tar xzvf ./tasks_1-20_v1-2.tar.gz

cd ../
python single.py
```

## Examples

Running a [single bAbI task](./single.py)

Running a [joint model on all bAbI tasks](./joint.py)

These files are also a good example of usage.

## Requirements

* tensorflow 1.0
* scikit-learn 0.17.1
* six 1.10.0

## References

* Julien Perez, Fei Liu, "Gated End-to-End Memory Networks", [*arXiv:1610.04211*](https://arxiv.org/abs/1610.04211) [cs.CL].
* Sainbayar Sukhbaatar, Arthur Szlam, Jason Weston, Rob Fergus, "End-To-End Memory Networks", [*arXiv:1503.08895*](https://arxiv.org/abs/1503.08895) [cs.CL].
