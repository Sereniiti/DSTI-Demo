# DSTI-Demo

Public repository showcasing the work of DSTI students for Sereniiti

This directory contain [DSTI](https://www.datasciencetech.institute/) student work that is built as tutorials and relased publicly.

This is not the work of Sereniiti engineers and is not representative of what is actually implemented inside Sereniiti's products. Sereniiti use this work as proposals to improve its current model. Also, the technical founder of Sereniiti is an ex. DSTI student and propose these projects as a way to learn over real world use cases.

A part of this work is based on Sereniiti dataset and public datasets such as [SST](https://huggingface.co/datasets/sst).

## Usages

This repository is public and released under and open source MIT licence.

### What this repository is for

* Demo website
* Demo API
* Demo Jupyter Notebooks
* Python files for inference

### What this repository is ***not*** for

* Experiments on the website and API (use private repository "DSTI experiments")
* Experiments on models (use private repository "DSTI experiments")
* Third party datasets and related model weights saves (Too heavy, use DVC or pull it from HuggingFace/TensorFlow Hub)
* Sereniiti's dataset and related model weights saves (/!\ Not public, store it in AWS S3 with an access key)
* Secret access keys (use [GitHub Secrets](https://docs.github.com/en/actions/security-guides/encrypted-secrets))

## Tools

The students need to install the folowing tools

* [Git](https://git-scm.com/) and learn how to use it ***from the command line***.
* [GitFlow extension for Git](https://github.com/nvie/gitflow) and to learn how to use the [GitFlow process](https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow).
* [DVC](https://dvc.org/), to access the dataset and model saves
* [Python + JupyterLab](https://www.anaconda.com/) and an IDE such as [VSCode](https://code.visualstudio.com/)
* Python's [Numpy](https://numpy.org/) and [Pandas](https://pandas.pydata.org/) and learn it during the first weeks
* [MLFlow](https://mlflow.org/docs/latest/quickstart.html) to store results and models parameters values
* Data Scientists: [TensorFlow](https://www.tensorflow.org/) and [PyTorch](https://pytorch.org/) with required GPU libraries (CUDA, cuDNN...)
* Data Engineers: [AWS CLI](https://aws.amazon.com/cli/) and [Amplify CLI](https://docs.amplify.aws/cli/)
