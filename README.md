About pytorch-pretrained-bert
=============================

Home: https://github.com/huggingface/pytorch-pretrained-BERT

Package license: Apache 2.0

Feedstock license: BSD 3-Clause

Summary: A PyTorch implementation of Google AI's BERT model provided with Google's pre-trained models, examples and utilities.

A PyTorch implementation of Google AI's BERT model provided with Google's pre-trained models, examples and utilities.

Current build status
====================

[![Linux](https://img.shields.io/circleci/project/github/nelson-liu/pytorch-pretrained-bert-feedstock/master.svg?label=Linux)](https://circleci.com/gh/nelson-liu/pytorch-pretrained-bert-feedstock)
[![OSX](https://img.shields.io/travis/nelson-liu/pytorch-pretrained-bert-feedstock/master.svg?label=macOS)](https://travis-ci.org/nelson-liu/pytorch-pretrained-bert-feedstock)
![Windows disabled](https://img.shields.io/badge/Windows-disabled-lightgrey.svg)

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-pytorch--pretrained--bert-green.svg)](https://anaconda.org/allennlp/pytorch-pretrained-bert) | [![Conda Downloads](https://img.shields.io/conda/dn/allennlp/pytorch-pretrained-bert.svg)](https://anaconda.org/allennlp/pytorch-pretrained-bert) | [![Conda Version](https://img.shields.io/conda/vn/allennlp/pytorch-pretrained-bert.svg)](https://anaconda.org/allennlp/pytorch-pretrained-bert) | [![Conda Platforms](https://img.shields.io/conda/pn/allennlp/pytorch-pretrained-bert.svg)](https://anaconda.org/allennlp/pytorch-pretrained-bert) |

Installing pytorch-pretrained-bert
==================================

Installing `pytorch-pretrained-bert` from the `allennlp` channel can be achieved by adding `allennlp` to your channels with:

```
conda config --add channels allennlp
```

Once the `allennlp` channel has been enabled, `pytorch-pretrained-bert` can be installed with:

```
conda install pytorch-pretrained-bert
```

It is possible to list all of the versions of `pytorch-pretrained-bert` available on your platform with:

```
conda search pytorch-pretrained-bert --channel allennlp
```




Updating pytorch-pretrained-bert-feedstock
==========================================

If you would like to improve the pytorch-pretrained-bert recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`allennlp` channel, whereupon the built conda packages will be available for
everybody to install and use from the `allennlp` channel.
Note that all branches in the conda-forge/pytorch-pretrained-bert-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://conda.io/docs/user-guide/tasks/build-packages/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://conda.io/docs/user-guide/tasks/build-packages/define-metadata.html#build-number-and-string)
   back to 0.
