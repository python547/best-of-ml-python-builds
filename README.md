<!-- markdownlint-disable -->
<h1 align="center">
    Best-of Machine Learning with Python
    <br>
</h1>

<p align="center">
    <strong>🏆&nbsp; A ranked list of awesome machine learning Python libraries. Updated weekly.</strong>
</p>

<p align="center">
    <a href="https://github.com/ml-tooling/best-of" title="Best-of-badge"><img src="http://bit.ly/3o3EHNN"></a>
    <a href="#Contents" title="Project Count"><img src="https://img.shields.io/badge/projects-900-blue.svg?color=5ac4bf"></a>
    <a href="#Contribution" title="Contributions are welcome"><img src="https://img.shields.io/badge/contributions-welcome-green.svg"></a>
    <a href="https://github.com/ml-tooling/best-of-ml-python/releases" title="Best-of Updates"><img src="https://img.shields.io/github/release-date/ml-tooling/best-of-ml-python?color=green&label=updated"></a>
    <a href="https://mltooling.substack.com/subscribe" title="Subscribe to newsletter"><img src="http://bit.ly/2Md9rxM"></a>
    <a href="https://twitter.com/mltooling" title="Follow on Twitter"><img src="https://img.shields.io/twitter/follow/mltooling.svg?style=social&label=Follow"></a>
</p>

This curated list contains 900 awesome open-source projects with a total of 3.4M stars grouped into 34 categories. All projects are ranked by a project-quality score, which is calculated based on various metrics automatically collected from GitHub and different package managers. If you like to add or update projects, feel free to open an [issue](https://github.com/ml-tooling/best-of-ml-python/issues/new/choose), submit a [pull request](https://github.com/ml-tooling/best-of-ml-python/pulls), or directly edit the [projects.yaml](https://github.com/ml-tooling/best-of-ml-python/edit/main/projects.yaml). Contributions are very welcome!

---

<p align="center">
     🧙‍♂️&nbsp; Discover other <a href="https://best-of.org">best-of lists</a> or create <a href="https://github.com/best-of-lists/best-of/blob/main/create-best-of-list.md">your own</a>.<br>
    📫&nbsp; Subscribe to our <a href="https://mltooling.substack.com/subscribe">newsletter</a> for updates and trending projects.
</p>

---


## Contents

- [Machine Learning Frameworks](#machine-learning-frameworks) _56 projects_
- [Data Visualization](#data-visualization) _51 projects_
- [Text Data & NLP](#text-data--nlp) _96 projects_
- [Image Data](#image-data) _60 projects_
- [Graph Data](#graph-data) _36 projects_
- [Audio Data](#audio-data) _28 projects_
- [Geospatial Data](#geospatial-data) _22 projects_
- [Financial Data](#financial-data) _25 projects_
- [Time Series Data](#time-series-data) _26 projects_
- [Medical Data](#medical-data) _19 projects_
- [Tabular Data](#tabular-data) _5 projects_
- [Optical Character Recognition](#optical-character-recognition) _12 projects_
- [Data Containers & Structures](#data-containers--structures) _0 projects_
- [Data Loading & Extraction](#data-loading--extraction) _2 projects_
- [Web Scraping & Crawling](#web-scraping--crawling) _1 projects_
- [Data Pipelines & Streaming](#data-pipelines--streaming) _43 projects_
- [Distributed Machine Learning](#distributed-machine-learning) _33 projects_
- [Hyperparameter Optimization & AutoML](#hyperparameter-optimization--automl) _47 projects_
- [Reinforcement Learning](#reinforcement-learning) _23 projects_
- [Recommender Systems](#recommender-systems) _16 projects_
- [Privacy Machine Learning](#privacy-machine-learning) _6 projects_
- [Workflow & Experiment Tracking](#workflow--experiment-tracking) _39 projects_
- [Model Serialization & Deployment](#model-serialization--deployment) _16 projects_
- [Model Interpretability](#model-interpretability) _52 projects_
- [Vector Similarity Search (ANN)](#vector-similarity-search-ann) _12 projects_
- [Probabilistics & Statistics](#probabilistics--statistics) _22 projects_
- [Adversarial Robustness](#adversarial-robustness) _9 projects_
- [GPU Utilities](#gpu-utilities) _18 projects_
- [Tensorflow Utilities](#tensorflow-utilities) _15 projects_
- [Jax Utilities](#jax-utilities) _2 projects_
- [Sklearn Utilities](#sklearn-utilities) _17 projects_
- [Pytorch Utilities](#pytorch-utilities) _32 projects_
- [Database Clients](#database-clients) _1 projects_
- [Others](#others) _61 projects_

## Explanation
- 🥇🥈🥉&nbsp; Combined project-quality score
- ⭐️&nbsp; Star count from GitHub
- 🐣&nbsp; New project _(less than 6 months old)_
- 💤&nbsp; Inactive project _(6 months no activity)_
- 💀&nbsp; Dead project _(12 months no activity)_
- 📈📉&nbsp; Project is trending up or down
- ➕&nbsp; Project was recently added
- ❗️&nbsp; Warning _(e.g. missing/risky license)_
- 👨‍💻&nbsp; Contributors count from GitHub
- 🔀&nbsp; Fork count from GitHub
- 📋&nbsp; Issue count from GitHub
- ⏱️&nbsp; Last update timestamp on package manager
- 📥&nbsp; Download count from package manager
- 📦&nbsp; Number of dependent projects
- <img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13">&nbsp; Tensorflow related project
- <img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13">&nbsp; Sklearn related project
- <img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13">&nbsp; PyTorch related project
- <img src="https://git.io/JLy1X" style="display:inline;" width="13" height="13">&nbsp; MxNet related project
- <img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13">&nbsp; Apache Spark related project
- <img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13">&nbsp; Jupyter related project
- <img src="https://git.io/JLy1M" style="display:inline;" width="13" height="13">&nbsp; PaddlePaddle related project
- <img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13">&nbsp; Pandas related project
- <img src="https://jax.readthedocs.io/en/latest/_static/favicon.png" style="display:inline;" width="13" height="13">&nbsp; Jax related project

<br>

## Machine Learning Frameworks

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_General-purpose machine learning and deep learning frameworks._

<details><summary><b><a href="https://github.com/tensorflow/tensorflow">Tensorflow</a></b> (🥇55 ·  ⭐ 170K) - An Open Source Machine Learning Framework for Everyone. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/tensorflow) (👨‍💻 4K · 🔀 70K · 📦 200K · 📋 35K - 6% open · ⏱️ 09.06.2022):

	```
	git clone https://github.com/tensorflow/tensorflow
	```
- [PyPi](https://pypi.org/project/tensorflow) (📥 18M / month):
	```
	pip install tensorflow
	```
- [Conda](https://anaconda.org/conda-forge/tensorflow) (📥 3.4M · ⏱️ 24.05.2022):
	```
	conda install -c conda-forge tensorflow
	```
- [Docker Hub](https://hub.docker.com/r/tensorflow/tensorflow) (📥 66M · ⭐ 2K · ⏱️ 09.06.2022):
	```
	docker pull tensorflow/tensorflow
	```
</details>
<details><summary><b><a href="https://github.com/scikit-learn/scikit-learn">scikit-learn</a></b> (🥇51 ·  ⭐ 50K) - scikit-learn: machine learning in Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/scikit-learn/scikit-learn) (👨‍💻 2.6K · 🔀 22K · 📥 800 · 📦 360K · 📋 9.4K - 16% open · ⏱️ 09.06.2022):

	```
	git clone https://github.com/scikit-learn/scikit-learn
	```
- [PyPi](https://pypi.org/project/scikit-learn) (📥 35M / month):
	```
	pip install scikit-learn
	```
- [Conda](https://anaconda.org/conda-forge/scikit-learn) (📥 13M · ⏱️ 19.05.2022):
	```
	conda install -c conda-forge scikit-learn
	```
</details>
<details><summary><b><a href="https://github.com/pytorch/pytorch">PyTorch</a></b> (🥇43 ·  ⭐ 57K · 📉) - Tensors and Dynamic neural networks in Python with strong GPU.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytorch/pytorch) (👨‍💻 3.3K · 🔀 15K · 📥 3.7K · 📋 26K - 31% open · ⏱️ 09.06.2022):

	```
	git clone https://github.com/pytorch/pytorch
	```
- [PyPi](https://pypi.org/project/torch) (📥 11M / month):
	```
	pip install torch
	```
- [Conda](https://anaconda.org/pytorch/pytorch) (📥 17M · ⏱️ 10.03.2022):
	```
	conda install -c pytorch pytorch
	```
</details>
<details><summary><b><a href="https://github.com/dmlc/xgboost">XGBoost</a></b> (🥇43 ·  ⭐ 23K) - Scalable, Portable and Distributed Gradient Boosting (GBDT, GBRT or.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/dmlc/xgboost) (👨‍💻 560 · 🔀 7.9K · 📥 4.3K · 📦 32K · 📋 4.4K - 5% open · ⏱️ 09.06.2022):

	```
	git clone https://github.com/dmlc/xgboost
	```
- [PyPi](https://pypi.org/project/xgboost) (📥 11M / month):
	```
	pip install xgboost
	```
- [Conda](https://anaconda.org/conda-forge/xgboost) (📥 2.7M · ⏱️ 17.02.2022):
	```
	conda install -c conda-forge xgboost
	```
</details>
<details><summary><b><a href="https://github.com/PyTorchLightning/pytorch-lightning">pytorch-lightning</a></b> (🥇43 ·  ⭐ 19K) - The lightweight PyTorch wrapper for high-performance.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PyTorchLightning/pytorch-lightning) (👨‍💻 690 · 🔀 2.3K · 📥 6.9K · 📦 9.4K · 📋 5K - 8% open · ⏱️ 08.06.2022):

	```
	git clone https://github.com/PyTorchLightning/pytorch-lightning
	```
- [PyPi](https://pypi.org/project/pytorch-lightning) (📥 4.7M / month):
	```
	pip install pytorch-lightning
	```
- [Conda](https://anaconda.org/conda-forge/pytorch-lightning) (📥 450K · ⏱️ 07.06.2022):
	```
	conda install -c conda-forge pytorch-lightning
	```
</details>
<details><summary><b><a href="https://github.com/google/jax">jax</a></b> (🥇43 ·  ⭐ 18K) - Composable transformations of Python+NumPy programs: differentiate,.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/google/jax) (👨‍💻 400 · 🔀 1.6K · 📦 4.5K · 📋 3.2K - 28% open · ⏱️ 09.06.2022):

	```
	git clone https://github.com/google/jax
	```
- [PyPi](https://pypi.org/project/jax) (📥 480K / month):
	```
	pip install jax
	```
- [Conda](https://anaconda.org/conda-forge/jaxlib) (📥 330K · ⏱️ 25.05.2022):
	```
	conda install -c conda-forge jaxlib
	```
</details>
<details><summary><b><a href="https://github.com/statsmodels/statsmodels">StatsModels</a></b> (🥇43 ·  ⭐ 7.4K) - Statsmodels: statistical modeling and econometrics in Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/statsmodels/statsmodels) (👨‍💻 380 · 🔀 2.3K · 📥 26 · 📦 64K · 📋 4.7K - 46% open · ⏱️ 05.06.2022):

	```
	git clone https://github.com/statsmodels/statsmodels
	```
- [PyPi](https://pypi.org/project/statsmodels) (📥 12M / month):
	```
	pip install statsmodels
	```
- [Conda](https://anaconda.org/conda-forge/statsmodels) (📥 6.3M · ⏱️ 11.02.2022):
	```
	conda install -c conda-forge statsmodels
	```
</details>
<details><summary><b><a href="https://github.com/microsoft/LightGBM">LightGBM</a></b> (🥈42 ·  ⭐ 14K) - A fast, distributed, high performance gradient boosting (GBT, GBDT, GBRT,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/microsoft/LightGBM) (👨‍💻 260 · 🔀 3.4K · 📥 150K · 📦 14K · 📋 2.7K - 7% open · ⏱️ 08.06.2022):

	```
	git clone https://github.com/microsoft/LightGBM
	```
- [PyPi](https://pypi.org/project/lightgbm) (📥 7.5M / month):
	```
	pip install lightgbm
	```
- [Conda](https://anaconda.org/conda-forge/lightgbm) (📥 1M · ⏱️ 08.01.2022):
	```
	conda install -c conda-forge lightgbm
	```
</details>
<details><summary><b><a href="https://github.com/fastai/fastai">Fastai</a></b> (🥈41 ·  ⭐ 22K · 📈) - The fastai deep learning library. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/fastai/fastai) (👨‍💻 200 · 🔀 7K · 📦 10K · 📋 1.6K - 6% open · ⏱️ 03.06.2022):

	```
	git clone https://github.com/fastai/fastai
	```
- [PyPi](https://pypi.org/project/fastai) (📥 300K / month):
	```
	pip install fastai
	```
</details>
<details><summary><b><a href="https://github.com/PaddlePaddle/Paddle">PaddlePaddle</a></b> (🥈41 ·  ⭐ 18K) - PArallel Distributed Deep LEarning: Machine Learning.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1M" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PaddlePaddle/Paddle) (👨‍💻 750 · 🔀 4.4K · 📥 15K · 📦 120 · 📋 15K - 14% open · ⏱️ 09.06.2022):

	```
	git clone https://github.com/PaddlePaddle/Paddle
	```
- [PyPi](https://pypi.org/project/paddlepaddle) (📥 100K / month):
	```
	pip install paddlepaddle
	```
</details>
<details><summary><b><a href="https://github.com/keras-team/keras">Keras</a></b> (🥈40 ·  ⭐ 55K) - Deep Learning for humans. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/keras-team/keras) (👨‍💻 1.1K · 🔀 18K · 📋 11K - 2% open · ⏱️ 08.06.2022):

	```
	git clone https://github.com/keras-team/keras
	```
- [PyPi](https://pypi.org/project/keras) (📥 12M / month):
	```
	pip install keras
	```
- [Conda](https://anaconda.org/conda-forge/keras) (📥 2.3M · ⏱️ 19.05.2022):
	```
	conda install -c conda-forge keras
	```
</details>
<details><summary><b><a href="https://github.com/jina-ai/jina">Jina</a></b> (🥈38 ·  ⭐ 15K) - Build cross-modal and multi-modal applications on the cloud. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/jina-ai/jina) (👨‍💻 150 · 🔀 1.9K · 📦 290 · 📋 1.5K - 3% open · ⏱️ 09.06.2022):

	```
	git clone https://github.com/jina-ai/jina
	```
- [PyPi](https://pypi.org/project/jina) (📥 61K / month):
	```
	pip install jina
	```
- [Conda](https://anaconda.org/conda-forge/jina-core) (📥 6.5K · ⏱️ 22.04.2022):
	```
	conda install -c conda-forge jina-core
	```
- [Docker Hub](https://hub.docker.com/r/jinaai/jina) (📥 1.1M · ⭐ 7 · ⏱️ 09.06.2022):
	```
	docker pull jinaai/jina
	```
</details>
<details><summary><b><a href="https://github.com/explosion/thinc">Thinc</a></b> (🥈37 ·  ⭐ 2.5K) - A refreshing functional take on deep learning, compatible with your favorite.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/explosion/thinc) (👨‍💻 52 · 🔀 240 · 📦 22K · 📋 120 - 11% open · ⏱️ 09.06.2022):

	```
	git clone https://github.com/explosion/thinc
	```
- [PyPi](https://pypi.org/project/thinc) (📥 6.7M / month):
	```
	pip install thinc
	```
- [Conda](https://anaconda.org/conda-forge/thinc) (📥 2.1M · ⏱️ 02.06.2022):
	```
	conda install -c conda-forge thinc
	```
</details>
<details><summary><b><a href="https://github.com/apache/spark">PySpark</a></b> (🥈36 ·  ⭐ 33K · 📉) - Apache Spark Python API. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/apache/spark) (👨‍💻 2.7K · 🔀 25K · ⏱️ 09.06.2022):

	```
	git clone https://github.com/apache/spark
	```
- [PyPi](https://pypi.org/project/pyspark) (📥 22M / month):
	```
	pip install pyspark
	```
- [Conda](https://anaconda.org/conda-forge/pyspark) (📥 1.7M · ⏱️ 26.01.2022):
	```
	conda install -c conda-forge pyspark
	```
</details>
<details><summary><b><a href="https://github.com/catboost/catboost">Catboost</a></b> (🥈36 ·  ⭐ 6.6K) - A fast, scalable, high performance Gradient Boosting on Decision.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/catboost/catboost) (👨‍💻 990 · 🔀 970 · 📥 81K · 📋 1.8K - 21% open · ⏱️ 07.06.2022):

	```
	git clone https://github.com/catboost/catboost
	```
- [PyPi](https://pypi.org/project/catboost) (📥 2.6M / month):
	```
	pip install catboost
	```
- [Conda](https://anaconda.org/conda-forge/catboost) (📥 1M · ⏱️ 19.05.2022):
	```
	conda install -c conda-forge catboost
	```
</details>
<details><summary><b><a href="https://github.com/chainer/chainer">Chainer</a></b> (🥈35 ·  ⭐ 5.7K) - A flexible framework of neural networks for deep learning. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/chainer/chainer) (👨‍💻 320 · 🔀 1.3K · 📦 2.6K · 📋 2K - 0% open · ⏱️ 05.01.2022):

	```
	git clone https://github.com/chainer/chainer
	```
- [PyPi](https://pypi.org/project/chainer) (📥 23K / month):
	```
	pip install chainer
	```
- [Conda](https://anaconda.org/conda-forge/chainer) (📥 7.9K · ⏱️ 21.01.2022):
	```
	conda install -c conda-forge chainer
	```
</details>
<details><summary><b><a href="https://github.com/google/flax">Flax</a></b> (🥈35 ·  ⭐ 3.1K) - Flax is a neural network library for JAX that is designed for.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://jax.readthedocs.io/en/latest/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/google/flax) (👨‍💻 150 · 🔀 340 · 📥 42 · 📦 1K · 📋 490 - 17% open · ⏱️ 08.06.2022):

	```
	git clone https://github.com/google/flax
	```
- [PyPi](https://pypi.org/project/flax) (📥 230K / month):
	```
	pip install flax
	```
- [Conda](https://anaconda.org/conda-forge/flax) (📥 4.6K · ⏱️ 23.05.2022):
	```
	conda install -c conda-forge flax
	```
</details>
<details><summary><b><a href="https://github.com/apache/incubator-mxnet">MXNet</a></b> (🥈34 ·  ⭐ 20K · 📉) - Lightweight, Portable, Flexible Distributed/Mobile Deep.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1X" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/apache/incubator-mxnet) (👨‍💻 970 · 🔀 6.5K · 📥 25K · 📋 9.5K - 18% open · ⏱️ 07.06.2022):

	```
	git clone https://github.com/apache/incubator-mxnet
	```
- [PyPi](https://pypi.org/project/mxnet) (📥 350K / month):
	```
	pip install mxnet
	```
- [Conda](https://anaconda.org/anaconda/mxnet) (📥 7.6K · ⏱️ 02.05.2022):
	```
	conda install -c anaconda mxnet
	```
</details>
<details><summary><b><a href="https://github.com/ludwig-ai/ludwig">Ludwig</a></b> (🥈33 ·  ⭐ 8.4K) - Data-centric declarative deep learning framework. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/ludwig-ai/ludwig) (👨‍💻 120 · 🔀 940 · 📦 120 · 📋 730 - 25% open · ⏱️ 08.06.2022):

	```
	git clone https://github.com/ludwig-ai/ludwig
	```
- [PyPi](https://pypi.org/project/ludwig) (📥 3.8K / month):
	```
	pip install ludwig
	```
</details>
<details><summary><b><a href="https://github.com/VowpalWabbit/vowpal_wabbit">Vowpal Wabbit</a></b> (🥈33 ·  ⭐ 8K) - Vowpal Wabbit is a machine learning system which pushes the.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/VowpalWabbit/vowpal_wabbit) (👨‍💻 320 · 🔀 1.7K · 📋 1.2K - 10% open · ⏱️ 07.06.2022):

	```
	git clone https://github.com/VowpalWabbit/vowpal_wabbit
	```
- [PyPi](https://pypi.org/project/vowpalwabbit) (📥 60K / month):
	```
	pip install vowpalwabbit
	```
- [Conda](https://anaconda.org/conda-forge/vowpalwabbit) (📥 61K · ⏱️ 07.04.2022):
	```
	conda install -c conda-forge vowpalwabbit
	```
</details>
<details><summary><b><a href="https://github.com/apple/turicreate">Turi Create</a></b> (🥈32 ·  ⭐ 11K · 💤) - Turi Create simplifies the development of custom machine.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/apple/turicreate) (👨‍💻 85 · 🔀 1.1K · 📥 6.1K · 📦 310 · 📋 1.8K - 27% open · ⏱️ 29.11.2021):

	```
	git clone https://github.com/apple/turicreate
	```
- [PyPi](https://pypi.org/project/turicreate) (📥 30K / month):
	```
	pip install turicreate
	```
</details>
<details><summary><b><a href="https://github.com/apache/flink">PyFlink</a></b> (🥉31 ·  ⭐ 19K) - Apache Flink Python API. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/apache/flink) (👨‍💻 1.5K · 🔀 11K · ⏱️ 09.06.2022):

	```
	git clone https://github.com/apache/flink
	```
- [PyPi](https://pypi.org/project/apache-flink) (📥 20K / month):
	```
	pip install apache-flink
	```
</details>
<details><summary><b><a href="https://github.com/deepmind/sonnet">Sonnet</a></b> (🥉31 ·  ⭐ 9.3K) - TensorFlow-based neural network library. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/deepmind/sonnet) (👨‍💻 53 · 🔀 1.2K · 📦 850 · 📋 180 - 13% open · ⏱️ 07.03.2022):

	```
	git clone https://github.com/deepmind/sonnet
	```
- [PyPi](https://pypi.org/project/dm-sonnet) (📥 23K / month):
	```
	pip install dm-sonnet
	```
- [Conda](https://anaconda.org/conda-forge/sonnet) (📥 14K · ⏱️ 14.11.2020):
	```
	conda install -c conda-forge sonnet
	```
</details>
<details><summary><b><a href="https://github.com/tensorpack/tensorpack">tensorpack</a></b> (🥉31 ·  ⭐ 6.2K) - A Neural Net Training Interface on TensorFlow, with focus.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorpack/tensorpack) (👨‍💻 58 · 🔀 1.8K · 📥 130 · 📦 1K · 📋 1.3K - 0% open · ⏱️ 04.05.2022):

	```
	git clone https://github.com/tensorpack/tensorpack
	```
- [PyPi](https://pypi.org/project/tensorpack) (📥 17K / month):
	```
	pip install tensorpack
	```
- [Conda](https://anaconda.org/conda-forge/tensorpack) (📥 1.4K · ⏱️ 06.02.2022):
	```
	conda install -c conda-forge tensorpack
	```
</details>
<details><summary><b><a href="https://github.com/arogozhnikov/einops">einops</a></b> (🥉31 ·  ⭐ 5.1K) - Deep learning operations reinvented (for pytorch, tensorflow, jax and.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/arogozhnikov/einops) (👨‍💻 17 · 🔀 220 · 📦 3K · 📋 110 - 30% open · ⏱️ 01.04.2022):

	```
	git clone https://github.com/arogozhnikov/einops
	```
- [PyPi](https://pypi.org/project/einops) (📥 3.9M / month):
	```
	pip install einops
	```
- [Conda](https://anaconda.org/conda-forge/einops) (📥 17K · ⏱️ 04.03.2022):
	```
	conda install -c conda-forge einops
	```
</details>
<details><summary><b><a href="https://github.com/deepmind/dm-haiku">Haiku</a></b> (🥉31 ·  ⭐ 1.9K) - JAX-based neural network library. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/deepmind/dm-haiku) (👨‍💻 61 · 🔀 150 · 📦 460 · 📋 160 - 23% open · ⏱️ 07.06.2022):

	```
	git clone https://github.com/deepmind/dm-haiku
	```
- [PyPi](https://pypi.org/project/dm-haiku) (📥 94K / month):
	```
	pip install dm-haiku
	```
- [Conda](https://anaconda.org/conda-forge/dm-haiku) (📥 2.9K · ⏱️ 14.02.2022):
	```
	conda install -c conda-forge dm-haiku
	```
</details>
<details><summary><b><a href="https://github.com/amaiya/ktrain">ktrain</a></b> (🥉31 ·  ⭐ 1K) - ktrain is a Python library that makes deep learning and AI more.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/amaiya/ktrain) (👨‍💻 15 · 🔀 230 · 📦 300 · ⏱️ 22.05.2022):

	```
	git clone https://github.com/amaiya/ktrain
	```
- [PyPi](https://pypi.org/project/ktrain) (📥 25K / month):
	```
	pip install ktrain
	```
</details>
<details><summary><b><a href="https://github.com/ROCmSoftwarePlatform/tensorflow-upstream">tensorflow-upstream</a></b> (🥉31 ·  ⭐ 590) - TensorFlow ROCm port. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/ROCmSoftwarePlatform/tensorflow-upstream) (👨‍💻 4K · 🔀 68 · 📥 20 · 📋 320 - 16% open · ⏱️ 05.06.2022):

	```
	git clone https://github.com/ROCmSoftwarePlatform/tensorflow-upstream
	```
- [PyPi](https://pypi.org/project/tensorflow-rocm) (📥 14K / month):
	```
	pip install tensorflow-rocm
	```
</details>
<details><summary><b><a href="https://github.com/clab/dynet">dyNET</a></b> (🥉30 ·  ⭐ 3.3K) - DyNet: The Dynamic Neural Network Toolkit. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/clab/dynet) (👨‍💻 160 · 🔀 670 · 📥 6K · 📦 210 · 📋 920 - 27% open · ⏱️ 11.03.2022):

	```
	git clone https://github.com/clab/dynet
	```
- [PyPi](https://pypi.org/project/dyNET) (📥 23K / month):
	```
	pip install dyNET
	```
</details>
<details><summary><b><a href="https://github.com/pytorch/ignite">Ignite</a></b> (🥉29 ·  ⭐ 4K) - High-level library to help with training and evaluating neural.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytorch/ignite) (👨‍💻 170 · 🔀 540 · 📋 1.1K - 11% open · ⏱️ 31.05.2022):

	```
	git clone https://github.com/pytorch/ignite
	```
- [PyPi](https://pypi.org/project/pytorch-ignite) (📥 170K / month):
	```
	pip install pytorch-ignite
	```
- [Conda](https://anaconda.org/pytorch/ignite) (📥 89K · ⏱️ 04.05.2022):
	```
	conda install -c pytorch ignite
	```
</details>
<details><summary><b><a href="https://github.com/skorch-dev/skorch">skorch</a></b> (🥉28 ·  ⭐ 4.5K) - A scikit-learn compatible neural network library that wraps.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/skorch-dev/skorch) (👨‍💻 49 · 🔀 300 · 📦 510 · 📋 440 - 10% open · ⏱️ 06.06.2022):

	```
	git clone https://github.com/skorch-dev/skorch
	```
- [PyPi](https://pypi.org/project/skorch) (📥 22K / month):
	```
	pip install skorch
	```
- [Conda](https://anaconda.org/conda-forge/skorch) (📥 550K · ⏱️ 30.11.2021):
	```
	conda install -c conda-forge skorch
	```
</details>
<details><summary><b><a href="https://github.com/sony/nnabla">Neural Network Libraries</a></b> (🥉27 ·  ⭐ 2.5K) - Neural Network Libraries. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/sony/nnabla) (👨‍💻 66 · 🔀 300 · 📥 540 · 📋 69 - 31% open · ⏱️ 09.06.2022):

	```
	git clone https://github.com/sony/nnabla
	```
- [PyPi](https://pypi.org/project/nnabla) (📥 3.6K / month):
	```
	pip install nnabla
	```
</details>
<details><summary><b><a href="https://github.com/google/neural-tangents">Neural Tangents</a></b> (🥉26 ·  ⭐ 1.8K) - Fast and Easy Infinite Neural Networks in Python. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/google/neural-tangents) (👨‍💻 22 · 🔀 200 · 📥 230 · 📦 40 · 📋 120 - 33% open · ⏱️ 09.06.2022):

	```
	git clone https://github.com/google/neural-tangents
	```
- [PyPi](https://pypi.org/project/neural-tangents) (📥 2.8K / month):
	```
	pip install neural-tangents
	```
</details>
<details><summary><b><a href="https://github.com/aksnzhy/xlearn">xLearn</a></b> (🥉25 ·  ⭐ 3K) - High performance, easy-to-use, and scalable machine learning (ML).. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/aksnzhy/xlearn) (👨‍💻 30 · 🔀 510 · 📥 3.3K · 📦 87 · 📋 300 - 61% open · ⏱️ 05.06.2022):

	```
	git clone https://github.com/aksnzhy/xlearn
	```
- [PyPi](https://pypi.org/project/xlearn) (📥 3.2K / month):
	```
	pip install xlearn
	```
</details>
<details><summary><b><a href="https://github.com/XiaoMi/mace">mace</a></b> (🥉24 ·  ⭐ 4.6K) - MACE is a deep learning inference framework optimized for mobile.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/XiaoMi/mace) (👨‍💻 63 · 🔀 790 · 📥 1.4K · 📋 660 - 6% open · ⏱️ 11.02.2022):

	```
	git clone https://github.com/XiaoMi/mace
	```
</details>
<details><summary><b><a href="https://github.com/nubank/fklearn">fklearn</a></b> (🥉23 ·  ⭐ 1.4K) - fklearn: Functional Machine Learning. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/nubank/fklearn) (👨‍💻 43 · 🔀 160 · 📦 12 · 📋 46 - 52% open · ⏱️ 18.04.2022):

	```
	git clone https://github.com/nubank/fklearn
	```
- [PyPi](https://pypi.org/project/fklearn) (📥 4.7K / month):
	```
	pip install fklearn
	```
</details>
<details><summary><b><a href="https://github.com/towhee-io/towhee">Towhee</a></b> (🥉21 ·  ⭐ 540) - A framework that provides a simple API for developing ML-driven data.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/towhee-io/towhee) (👨‍💻 26 · 🔀 92 · 📥 17 · 📋 360 - 5% open · ⏱️ 09.06.2022):

	```
	git clone https://github.com/towhee-io/towhee
	```
- [PyPi](https://pypi.org/project/towhee) (📥 530 / month):
	```
	pip install towhee
	```
</details>
<details><summary><b><a href="https://github.com/Xtra-Computing/thundersvm">ThunderSVM</a></b> (🥉20 ·  ⭐ 1.4K) - ThunderSVM: A Fast SVM Library on GPUs and CPUs. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/Xtra-Computing/thundersvm) (👨‍💻 34 · 🔀 190 · 📥 2.4K · 📋 210 - 29% open · ⏱️ 09.04.2022):

	```
	git clone https://github.com/Xtra-Computing/thundersvm
	```
- [PyPi](https://pypi.org/project/thundersvm) (📥 860 / month):
	```
	pip install thundersvm
	```
</details>
<details><summary><b><a href="https://github.com/neoml-lib/neoml">NeoML</a></b> (🥉20 ·  ⭐ 680) - Machine learning framework for both deep learning and traditional.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/neoml-lib/neoml) (👨‍💻 31 · 🔀 110 · 📋 60 - 21% open · ⏱️ 08.06.2022):

	```
	git clone https://github.com/neoml-lib/neoml
	```
- [PyPi](https://pypi.org/project/neoml) (📥 410 / month):
	```
	pip install neoml
	```
</details>
<details><summary><b><a href="https://github.com/poets-ai/elegy">elegy</a></b> (🥉18 ·  ⭐ 370) - A High Level API for Deep Learning in JAX. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code> <code><img src="https://jax.readthedocs.io/en/latest/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/poets-ai/elegy) (👨‍💻 17 · 🔀 26 · 📋 92 - 28% open · ⏱️ 23.05.2022):

	```
	git clone https://github.com/poets-ai/elegy
	```
- [PyPi](https://pypi.org/project/elegy) (📥 750 / month):
	```
	pip install elegy
	```
</details>
<details><summary><b><a href="https://github.com/serengil/chefboost">chefboost</a></b> (🥉17 ·  ⭐ 330) - A Lightweight Decision Tree Framework supporting regular algorithms:.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/serengil/chefboost) (👨‍💻 6 · 🔀 88 · 📦 23 · 📋 25 - 4% open · ⏱️ 21.05.2022):

	```
	git clone https://github.com/serengil/chefboost
	```
- [PyPi](https://pypi.org/project/chefboost) (📥 680 / month):
	```
	pip install chefboost
	```
</details>
<details><summary>Show 15 hidden projects...</summary>

- <b><a href="https://github.com/davisking/dlib">dlib</a></b> (🥈37 ·  ⭐ 11K) - A toolkit for making real world machine learning and data analysis.. <code><a href="https://tldrlegal.com/search?q=BSL-1.0">❗️BSL-1.0</a></code>
- <b><a href="https://github.com/Theano/Theano">Theano</a></b> (🥈34 ·  ⭐ 9.6K · 💤) - Theano was a Python library that allows you to define,.. <code>❗Unlicensed</code>
- <b><a href="https://github.com/tflearn/tflearn">TFlearn</a></b> (🥉30 ·  ⭐ 9.6K · 💀) - Deep learning library featuring a higher-level API for.. <code>❗Unlicensed</code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/mlpack/mlpack">mlpack</a></b> (🥉30 ·  ⭐ 4K) - mlpack: a scalable C++ machine learning library --. <code>❗Unlicensed</code>
- <b><a href="https://github.com/numenta/nupic">NuPIC</a></b> (🥉28 ·  ⭐ 6.3K · 💀) - Numenta Platform for Intelligent Computing is an implementation.. <code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code>
- <b><a href="https://github.com/microsoft/CNTK">CNTK</a></b> (🥉27 ·  ⭐ 17K · 💀) - Microsoft Cognitive Toolkit (CNTK), an open source deep-learning.. <code>❗Unlicensed</code>
- <b><a href="https://github.com/mindsdb/mindsdb">MindsDB</a></b> (🥉27 ·  ⭐ 7.5K) - In-Database Machine Learning. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/shogun-toolbox/shogun">SHOGUN</a></b> (🥉26 ·  ⭐ 2.9K · 💀) - Unified and efficient Machine Learning. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/Lasagne/Lasagne">Lasagne</a></b> (🥉25 ·  ⭐ 3.8K · 💀) - Lightweight library to build and train neural networks in.. <code>❗Unlicensed</code>
- <b><a href="https://github.com/itdxer/neupy">NeuPy</a></b> (🥉24 ·  ⭐ 710 · 💀) - NeuPy is a Tensorflow based python library for prototyping and building.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/NervanaSystems/neon">neon</a></b> (🥉23 ·  ⭐ 3.9K · 💀) - Intel Nervana reference deep learning framework committed to best.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/pytorchbearer/torchbearer">Torchbearer</a></b> (🥉21 ·  ⭐ 630 · 💀) - torchbearer: A model fitting library for PyTorch. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/google/objax">Objax</a></b> (🥉20 ·  ⭐ 690) -  <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://jax.readthedocs.io/en/latest/_static/favicon.png" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/facebookresearch/StarSpace">StarSpace</a></b> (🥉16 ·  ⭐ 3.8K · 💀) - Learning embeddings for classification, retrieval and ranking. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/Xtra-Computing/thundergbm">ThunderGBM</a></b> (🥉16 ·  ⭐ 620 · 💀) - ThunderGBM: Fast GBDTs and Random Forests on GPUs. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
</details>
<br>

## Data Visualization

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_General-purpose and task-specific data visualization libraries._

<details><summary><b><a href="https://github.com/matplotlib/matplotlib">Matplotlib</a></b> (🥇47 ·  ⭐ 16K) - matplotlib: plotting with Python. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/matplotlib/matplotlib) (👨‍💻 1.4K · 🔀 6.2K · 📦 570K · 📋 8.6K - 17% open · ⏱️ 09.06.2022):

	```
	git clone https://github.com/matplotlib/matplotlib
	```
- [PyPi](https://pypi.org/project/matplotlib) (📥 30M / month):
	```
	pip install matplotlib
	```
- [Conda](https://anaconda.org/conda-forge/matplotlib) (📥 12M · ⏱️ 04.05.2022):
	```
	conda install -c conda-forge matplotlib
	```
</details>
<details><summary><b><a href="https://github.com/mwaskom/seaborn">Seaborn</a></b> (🥇43 ·  ⭐ 9.5K) - Statistical data visualization in Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/mwaskom/seaborn) (👨‍💻 170 · 🔀 1.5K · 📥 220 · 📦 160K · 📋 2K - 5% open · ⏱️ 07.06.2022):

	```
	git clone https://github.com/mwaskom/seaborn
	```
- [PyPi](https://pypi.org/project/seaborn) (📥 10M / month):
	```
	pip install seaborn
	```
- [Conda](https://anaconda.org/conda-forge/seaborn) (📥 3.9M · ⏱️ 16.08.2021):
	```
	conda install -c conda-forge seaborn
	```
</details>
<details><summary><b><a href="https://github.com/bokeh/bokeh">Bokeh</a></b> (🥇41 ·  ⭐ 16K) - Interactive Data Visualization in the browser, from Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/bokeh/bokeh) (👨‍💻 600 · 🔀 3.9K · 📦 52K · 📋 6.9K - 10% open · ⏱️ 08.06.2022):

	```
	git clone https://github.com/bokeh/bokeh
	```
- [PyPi](https://pypi.org/project/bokeh) (📥 2.8M / month):
	```
	pip install bokeh
	```
- [Conda](https://anaconda.org/conda-forge/bokeh) (📥 7.5M · ⏱️ 19.05.2022):
	```
	conda install -c conda-forge bokeh
	```
</details>
<details><summary><b><a href="https://github.com/plotly/dash">dash</a></b> (🥇38 ·  ⭐ 17K) - Analytical Web Apps for Python, R, Julia, and Jupyter. No JavaScript Required. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/plotly/dash) (👨‍💻 120 · 🔀 1.6K · 📦 190 · 📋 1.3K - 47% open · ⏱️ 07.06.2022):

	```
	git clone https://github.com/plotly/dash
	```
- [PyPi](https://pypi.org/project/dash) (📥 870K / month):
	```
	pip install dash
	```
- [Conda](https://anaconda.org/conda-forge/dash) (📥 480K · ⏱️ 09.06.2022):
	```
	conda install -c conda-forge dash
	```
</details>
<details><summary><b><a href="https://github.com/plotly/plotly.py">Plotly</a></b> (🥇38 ·  ⭐ 12K) - The interactive graphing library for Python (includes Plotly Express). <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/plotly/plotly.py) (👨‍💻 200 · 🔀 2.1K · 📦 10 · 📋 2.3K - 48% open · ⏱️ 08.06.2022):

	```
	git clone https://github.com/plotly/plotly.py
	```
- [PyPi](https://pypi.org/project/plotly) (📥 7.7M / month):
	```
	pip install plotly
	```
- [Conda](https://anaconda.org/conda-forge/plotly) (📥 2.7M · ⏱️ 08.06.2022):
	```
	conda install -c conda-forge plotly
	```
- [npm](https://www.npmjs.com/package/plotlywidget) (📥 46K / month):
	```
	npm install plotlywidget
	```
</details>
<details><summary><b><a href="https://github.com/ydataai/pandas-profiling">pandas-profiling</a></b> (🥇38 ·  ⭐ 9.1K) - Create HTML profiling reports from pandas DataFrame.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/ydataai/pandas-profiling) (👨‍💻 88 · 🔀 1.3K · 📦 8.1K · 📋 570 - 18% open · ⏱️ 03.06.2022):

	```
	git clone https://github.com/ydataai/pandas-profiling
	```
- [PyPi](https://pypi.org/project/pandas-profiling) (📥 1.2M / month):
	```
	pip install pandas-profiling
	```
- [Conda](https://anaconda.org/conda-forge/pandas-profiling) (📥 210K · ⏱️ 02.05.2022):
	```
	conda install -c conda-forge pandas-profiling
	```
</details>
<details><summary><b><a href="https://github.com/altair-viz/altair">Altair</a></b> (🥇38 ·  ⭐ 7.6K) - Declarative statistical visualization library for Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/altair-viz/altair) (👨‍💻 140 · 🔀 640 · 📦 28K · 📋 1.6K - 12% open · ⏱️ 25.03.2022):

	```
	git clone https://github.com/altair-viz/altair
	```
- [PyPi](https://pypi.org/project/altair) (📥 9.3M / month):
	```
	pip install altair
	```
- [Conda](https://anaconda.org/conda-forge/altair) (📥 1.2M · ⏱️ 29.12.2021):
	```
	conda install -c conda-forge altair
	```
</details>
<details><summary><b><a href="https://github.com/lmcinnes/umap">UMAP</a></b> (🥈34 ·  ⭐ 5.6K) - Uniform Manifold Approximation and Projection. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/lmcinnes/umap) (👨‍💻 100 · 🔀 620 · 📦 5.5K · 📋 620 - 52% open · ⏱️ 06.05.2022):

	```
	git clone https://github.com/lmcinnes/umap
	```
- [PyPi](https://pypi.org/project/umap-learn) (📥 730K / month):
	```
	pip install umap-learn
	```
- [Conda](https://anaconda.org/conda-forge/umap-learn) (📥 1.1M · ⏱️ 14.04.2022):
	```
	conda install -c conda-forge umap-learn
	```
</details>
<details><summary><b><a href="https://github.com/pyvista/pyvista">PyVista</a></b> (🥈33 ·  ⭐ 1.3K) - 3D plotting and mesh analysis through a streamlined interface for.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pyvista/pyvista) (👨‍💻 91 · 🔀 250 · 📥 650 · 📦 770 · 📋 800 - 28% open · ⏱️ 09.06.2022):

	```
	git clone https://github.com/pyvista/pyvista
	```
- [PyPi](https://pypi.org/project/pyvista) (📥 77K / month):
	```
	pip install pyvista
	```
- [Conda](https://anaconda.org/conda-forge/pyvista) (📥 180K · ⏱️ 15.04.2022):
	```
	conda install -c conda-forge pyvista
	```
</details>
<details><summary><b><a href="https://github.com/xflr6/graphviz">Graphviz</a></b> (🥈33 ·  ⭐ 1.2K) - Simple Python interface for Graphviz. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/xflr6/graphviz) (👨‍💻 18 · 🔀 180 · 📦 32K · 📋 140 - 4% open · ⏱️ 03.06.2022):

	```
	git clone https://github.com/xflr6/graphviz
	```
- [PyPi](https://pypi.org/project/graphviz) (📥 12M / month):
	```
	pip install graphviz
	```
- [Conda](https://anaconda.org/anaconda/python-graphviz) (📥 21K · ⏱️ 04.02.2021):
	```
	conda install -c anaconda python-graphviz
	```
</details>
<details><summary><b><a href="https://github.com/pyecharts/pyecharts">pyecharts</a></b> (🥈32 ·  ⭐ 12K) - Python Echarts Plotting Library. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pyecharts/pyecharts) (👨‍💻 30 · 🔀 2.6K · 📦 2.3K · 📋 1.6K - 1% open · ⏱️ 25.04.2022):

	```
	git clone https://github.com/pyecharts/pyecharts
	```
- [PyPi](https://pypi.org/project/pyecharts) (📥 97K / month):
	```
	pip install pyecharts
	```
</details>
<details><summary><b><a href="https://github.com/holoviz/datashader">datashader</a></b> (🥈32 ·  ⭐ 2.8K) - Quickly and accurately render even the largest data. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/holoviz/datashader) (👨‍💻 47 · 🔀 340 · 📦 1.1K · 📋 500 - 25% open · ⏱️ 30.05.2022):

	```
	git clone https://github.com/holoviz/datashader
	```
- [PyPi](https://pypi.org/project/datashader) (📥 47K / month):
	```
	pip install datashader
	```
- [Conda](https://anaconda.org/conda-forge/datashader) (📥 310K · ⏱️ 26.04.2022):
	```
	conda install -c conda-forge datashader
	```
</details>
<details><summary><b><a href="https://github.com/voxel51/fiftyone">FiftyOne</a></b> (🥈32 ·  ⭐ 1.3K) - Visualize, create, and debug image and video datasets.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/voxel51/fiftyone) (👨‍💻 40 · 🔀 170 · 📦 120 · 📋 790 - 31% open · ⏱️ 09.06.2022):

	```
	git clone https://github.com/voxel51/fiftyone
	```
- [PyPi](https://pypi.org/project/fiftyone) (📥 21K / month):
	```
	pip install fiftyone
	```
</details>
<details><summary><b><a href="https://github.com/holoviz/holoviews">HoloViews</a></b> (🥈31 ·  ⭐ 2.2K) - With Holoviews, your data visualizes itself. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/holoviz/holoviews) (👨‍💻 120 · 🔀 350 · 📋 2.8K - 30% open · ⏱️ 07.06.2022):

	```
	git clone https://github.com/holoviz/holoviews
	```
- [PyPi](https://pypi.org/project/holoviews) (📥 310K / month):
	```
	pip install holoviews
	```
- [Conda](https://anaconda.org/conda-forge/holoviews) (📥 740K · ⏱️ 09.05.2022):
	```
	conda install -c conda-forge holoviews
	```
- [npm](https://www.npmjs.com/package/@pyviz/jupyterlab_pyviz) (📥 1.4K / month):
	```
	npm install @pyviz/jupyterlab_pyviz
	```
</details>
<details><summary><b><a href="https://github.com/finos/perspective">Perspective</a></b> (🥈30 ·  ⭐ 4.6K) - A data visualization and analytics component, especially.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/finos/perspective) (👨‍💻 70 · 🔀 470 · 📦 250 · 📋 520 - 14% open · ⏱️ 09.06.2022):

	```
	git clone https://github.com/finos/perspective
	```
- [PyPi](https://pypi.org/project/perspective-python) (📥 3.3K / month):
	```
	pip install perspective-python
	```
- [Conda](https://anaconda.org/conda-forge/perspective) (📥 75K · ⏱️ 07.06.2022):
	```
	conda install -c conda-forge perspective
	```
- [npm](https://www.npmjs.com/package/@finos/perspective-jupyterlab) (📥 2.3K / month):
	```
	npm install @finos/perspective-jupyterlab
	```
</details>
<details><summary><b><a href="https://github.com/man-group/dtale">D-Tale</a></b> (🥈30 ·  ⭐ 3.5K) - Visualizer for pandas data structures. <code><a href="https://tldrlegal.com/search?q=LGPL-2.1">❗️LGPL-2.1</a></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/man-group/dtale) (👨‍💻 23 · 🔀 280 · 📦 380 · 📋 460 - 7% open · ⏱️ 29.05.2022):

	```
	git clone https://github.com/man-group/dtale
	```
- [PyPi](https://pypi.org/project/dtale) (📥 66K / month):
	```
	pip install dtale
	```
- [Conda](https://anaconda.org/conda-forge/dtale) (📥 120K · ⏱️ 29.05.2022):
	```
	conda install -c conda-forge dtale
	```
</details>
<details><summary><b><a href="https://github.com/bqplot/bqplot">bqplot</a></b> (🥈30 ·  ⭐ 3.3K) - Plotting library for IPython/Jupyter notebooks. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/bqplot/bqplot) (👨‍💻 58 · 🔀 430 · 📦 32 · 📋 570 - 36% open · ⏱️ 31.05.2022):

	```
	git clone https://github.com/bqplot/bqplot
	```
- [PyPi](https://pypi.org/project/bqplot) (📥 91K / month):
	```
	pip install bqplot
	```
- [Conda](https://anaconda.org/conda-forge/bqplot) (📥 980K · ⏱️ 11.02.2022):
	```
	conda install -c conda-forge bqplot
	```
- [npm](https://www.npmjs.com/package/bqplot) (📥 27K / month):
	```
	npm install bqplot
	```
</details>
<details><summary><b><a href="https://github.com/ResidentMario/missingno">missingno</a></b> (🥈30 ·  ⭐ 3.2K) - Missing data visualization module for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/ResidentMario/missingno) (👨‍💻 17 · 🔀 400 · 📦 7.6K · 📋 120 - 5% open · ⏱️ 27.02.2022):

	```
	git clone https://github.com/ResidentMario/missingno
	```
- [PyPi](https://pypi.org/project/missingno) (📥 1M / month):
	```
	pip install missingno
	```
- [Conda](https://anaconda.org/conda-forge/missingno) (📥 160K · ⏱️ 15.02.2020):
	```
	conda install -c conda-forge missingno
	```
</details>
<details><summary><b><a href="https://github.com/holoviz/hvplot">hvPlot</a></b> (🥈30 ·  ⭐ 570) - A high-level plotting API for pandas, dask, xarray, and networkx built on.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/holoviz/hvplot) (👨‍💻 36 · 🔀 68 · 📦 1.3K · 📋 420 - 33% open · ⏱️ 30.05.2022):

	```
	git clone https://github.com/holoviz/hvplot
	```
- [PyPi](https://pypi.org/project/hvplot) (📥 130K / month):
	```
	pip install hvplot
	```
- [Conda](https://anaconda.org/conda-forge/hvplot) (📥 180K · ⏱️ 09.05.2022):
	```
	conda install -c conda-forge hvplot
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/data-validation">data-validation</a></b> (🥉29 ·  ⭐ 640) - Library for exploring and validating machine learning.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/data-validation) (👨‍💻 24 · 🔀 120 · 📥 360 · 📦 480 · 📋 140 - 17% open · ⏱️ 06.06.2022):

	```
	git clone https://github.com/tensorflow/data-validation
	```
- [PyPi](https://pypi.org/project/tensorflow-data-validation) (📥 1.9M / month):
	```
	pip install tensorflow-data-validation
	```
</details>
<details><summary><b><a href="https://github.com/amueller/word_cloud">wordcloud</a></b> (🥉28 ·  ⭐ 8.8K) - A little word cloud generator in Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/amueller/word_cloud) (👨‍💻 65 · 🔀 2.2K · 📋 470 - 21% open · ⏱️ 26.04.2022):

	```
	git clone https://github.com/amueller/word_cloud
	```
- [PyPi](https://pypi.org/project/wordcloud) (📥 760K / month):
	```
	pip install wordcloud
	```
- [Conda](https://anaconda.org/conda-forge/wordcloud) (📥 290K · ⏱️ 15.11.2021):
	```
	conda install -c conda-forge wordcloud
	```
</details>
<details><summary><b><a href="https://github.com/has2k1/plotnine">plotnine</a></b> (🥉28 ·  ⭐ 3.1K) - A grammar of graphics for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/has2k1/plotnine) (👨‍💻 96 · 🔀 170 · 📋 490 - 12% open · ⏱️ 06.06.2022):

	```
	git clone https://github.com/has2k1/plotnine
	```
- [PyPi](https://pypi.org/project/plotnine) (📥 240K / month):
	```
	pip install plotnine
	```
- [Conda](https://anaconda.org/conda-forge/plotnine) (📥 170K · ⏱️ 25.03.2021):
	```
	conda install -c conda-forge plotnine
	```
</details>
<details><summary><b><a href="https://github.com/pavlin-policar/openTSNE">openTSNE</a></b> (🥉26 ·  ⭐ 1K) - Extensible, parallel implementations of t-SNE. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/pavlin-policar/openTSNE) (👨‍💻 10 · 🔀 110 · 📦 340 · 📋 100 - 3% open · ⏱️ 18.03.2022):

	```
	git clone https://github.com/pavlin-policar/openTSNE
	```
- [PyPi](https://pypi.org/project/opentsne) (📥 15K / month):
	```
	pip install opentsne
	```
- [Conda](https://anaconda.org/conda-forge/opentsne) (📥 140K · ⏱️ 27.05.2022):
	```
	conda install -c conda-forge opentsne
	```
</details>
<details><summary><b><a href="https://github.com/JetBrains/lets-plot">lets-plot</a></b> (🥉26 ·  ⭐ 750) - An open-source plotting library for statistical data. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/JetBrains/lets-plot) (👨‍💻 16 · 🔀 32 · 📥 270 · 📦 17 · 📋 240 - 25% open · ⏱️ 09.06.2022):

	```
	git clone https://github.com/JetBrains/lets-plot
	```
- [PyPi](https://pypi.org/project/lets-plot) (📥 1.5K / month):
	```
	pip install lets-plot
	```
</details>
<details><summary><b><a href="https://github.com/ContextLab/hypertools">HyperTools</a></b> (🥉25 ·  ⭐ 1.7K) - A Python toolbox for gaining geometric insights into high-dimensional.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/ContextLab/hypertools) (👨‍💻 21 · 🔀 160 · 📥 14 · 📦 190 · 📋 190 - 36% open · ⏱️ 12.02.2022):

	```
	git clone https://github.com/ContextLab/hypertools
	```
- [PyPi](https://pypi.org/project/hypertools) (📥 960 / month):
	```
	pip install hypertools
	```
</details>
<details><summary><b><a href="https://github.com/ing-bank/popmon">Popmon</a></b> (🥉23 ·  ⭐ 340) - Monitor the stability of a Pandas or Spark dataframe. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/ing-bank/popmon) (👨‍💻 14 · 🔀 24 · 📥 16 · 📦 11 · 📋 34 - 47% open · ⏱️ 27.05.2022):

	```
	git clone https://github.com/ing-bank/popmon
	```
- [PyPi](https://pypi.org/project/popmon) (📥 12K / month):
	```
	pip install popmon
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/hiplot">HiPlot</a></b> (🥉22 ·  ⭐ 2.3K) - HiPlot makes understanding high dimensional data easy. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/facebookresearch/hiplot) (👨‍💻 8 · 🔀 120 · 📦 4 · 📋 78 - 15% open · ⏱️ 31.05.2022):

	```
	git clone https://github.com/facebookresearch/hiplot
	```
- [PyPi](https://pypi.org/project/hiplot) (📥 18K / month):
	```
	pip install hiplot
	```
- [Conda](https://anaconda.org/conda-forge/hiplot) (📥 87K · ⏱️ 31.05.2022):
	```
	conda install -c conda-forge hiplot
	```
</details>
<details><summary><b><a href="https://github.com/AutoViML/AutoViz">AutoViz</a></b> (🥉22 ·  ⭐ 720) - Automatically Visualize any dataset, any size with a single line of.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/AutoViML/AutoViz) (👨‍💻 12 · 🔀 100 · 📦 190 · 📋 55 - 7% open · ⏱️ 28.04.2022):

	```
	git clone https://github.com/AutoViML/AutoViz
	```
- [PyPi](https://pypi.org/project/autoviz) (📥 56K / month):
	```
	pip install autoviz
	```
- [Conda](https://anaconda.org/conda-forge/autoviz) (📥 5.4K · ⏱️ 28.04.2022):
	```
	conda install -c conda-forge autoviz
	```
</details>
<details><summary><b><a href="https://github.com/marcharper/python-ternary">python-ternary</a></b> (🥉22 ·  ⭐ 560) - Ternary plotting library for python with matplotlib. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/marcharper/python-ternary) (👨‍💻 27 · 🔀 140 · 📥 17 · 📦 93 · 📋 120 - 22% open · ⏱️ 27.02.2022):

	```
	git clone https://github.com/marcharper/python-ternary
	```
- [PyPi](https://pypi.org/project/python-ternary) (📥 14K / month):
	```
	pip install python-ternary
	```
- [Conda](https://anaconda.org/conda-forge/python-ternary) (📥 63K · ⏱️ 17.02.2021):
	```
	conda install -c conda-forge python-ternary
	```
</details>
<details><summary><b><a href="https://github.com/fbdesignpro/sweetviz">Sweetviz</a></b> (🥉21 ·  ⭐ 2K) - Visualize and compare datasets, target values and associations, with one.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/fbdesignpro/sweetviz) (👨‍💻 6 · 🔀 200 · 📋 100 - 28% open · ⏱️ 08.06.2022):

	```
	git clone https://github.com/fbdesignpro/sweetviz
	```
- [PyPi](https://pypi.org/project/sweetviz) (📥 87K / month):
	```
	pip install sweetviz
	```
- [Conda](https://anaconda.org/conda-forge/sweetviz) (📥 10K · ⏱️ 09.07.2021):
	```
	conda install -c conda-forge sweetviz
	```
</details>
<details><summary><b><a href="https://github.com/gyli/PyWaffle">PyWaffle</a></b> (🥉21 ·  ⭐ 490) - Make Waffle Charts in Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/gyli/PyWaffle) (👨‍💻 6 · 🔀 90 · 📦 140 · 📋 18 - 22% open · ⏱️ 08.06.2022):

	```
	git clone https://github.com/gyli/PyWaffle
	```
- [PyPi](https://pypi.org/project/pywaffle) (📥 3.2K / month):
	```
	pip install pywaffle
	```
- [Conda](https://anaconda.org/conda-forge/pywaffle) (📥 4.8K · ⏱️ 05.06.2022):
	```
	conda install -c conda-forge pywaffle
	```
</details>
<details><summary><b><a href="https://github.com/vega/ipyvega">vega</a></b> (🥉20 ·  ⭐ 330) - IPython/Jupyter notebook module for Vega and Vega-Lite. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/vega/ipyvega) (👨‍💻 11 · 🔀 55 · 📋 94 - 12% open · ⏱️ 01.06.2022):

	```
	git clone https://github.com/vega/ipyvega
	```
- [PyPi](https://pypi.org/project/vega) (📥 6K / month):
	```
	pip install vega
	```
- [Conda](https://anaconda.org/conda-forge/vega) (📥 480K · ⏱️ 10.02.2022):
	```
	conda install -c conda-forge vega
	```
</details>
<details><summary><b><a href="https://github.com/PatrikHlobil/Pandas-Bokeh">Pandas-Bokeh</a></b> (🥉19 ·  ⭐ 780) - Bokeh Plotting Backend for Pandas and GeoPandas. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PatrikHlobil/Pandas-Bokeh) (👨‍💻 14 · 🔀 100 · 📋 97 - 31% open · ⏱️ 25.03.2022):

	```
	git clone https://github.com/PatrikHlobil/Pandas-Bokeh
	```
- [PyPi](https://pypi.org/project/pandas-bokeh) (📥 14K / month):
	```
	pip install pandas-bokeh
	```
</details>
<details><summary><b><a href="https://github.com/leotac/joypy">joypy</a></b> (🥉19 ·  ⭐ 420) - Joyplots in Python with matplotlib & pandas. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/leotac/joypy) (👨‍💻 6 · 🔀 47 · 📦 160 · 📋 47 - 21% open · ⏱️ 19.12.2021):

	```
	git clone https://github.com/leotac/joypy
	```
- [PyPi](https://pypi.org/project/joypy) (📥 25K / month):
	```
	pip install joypy
	```
- [Conda](https://anaconda.org/conda-forge/joypy) (📥 14K · ⏱️ 28.12.2020):
	```
	conda install -c conda-forge joypy
	```
</details>
<details><summary>Show 17 hidden projects...</summary>

- <b><a href="https://github.com/SciTools/cartopy">cartopy</a></b> (🥈31 ·  ⭐ 1.1K) - Cartopy - a cartographic python library with matplotlib support. <code><a href="http://bit.ly/37RvQcA">❗️LGPL-3.0</a></code>
- <b><a href="https://github.com/vispy/vispy">VisPy</a></b> (🥈30 ·  ⭐ 2.9K) - High-performance interactive 2D/3D data visualization library. <code>❗Unlicensed</code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/PAIR-code/facets">Facets Overview</a></b> (🥉27 ·  ⭐ 6.9K · 💀) - Visualizations for machine learning datasets. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/pyqtgraph/pyqtgraph">PyQtGraph</a></b> (🥉27 ·  ⭐ 2.8K) - Fast data visualization and GUI tools for scientific /.. <code>❗Unlicensed</code>
- <b><a href="https://github.com/santosjorge/cufflinks">Cufflinks</a></b> (🥉27 ·  ⭐ 2.6K · 💀) - Productivity Tools for Plotly + Pandas. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/spotify/chartify">Chartify</a></b> (🥉25 ·  ⭐ 3.2K · 💀) - Python library that makes it easy for data scientists to create.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/jupyter-widgets/pythreejs">pythreejs</a></b> (🥉23 ·  ⭐ 820) - A Jupyter - Three.js bridge. <code>❗Unlicensed</code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/DmitryUlyanov/Multicore-TSNE">Multicore-TSNE</a></b> (🥉22 ·  ⭐ 1.7K · 💀) - Parallel t-SNE implementation with Python and Torch.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/SauceCat/PDPbox">PDPbox</a></b> (🥉22 ·  ⭐ 680 · 💀) - python partial dependence plot toolbox. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/nicolaskruchten/jupyter_pivottablejs">pivottablejs</a></b> (🥉21 ·  ⭐ 460 · 💀) - Dragndrop Pivot Tables and Charts for Jupyter/IPython.. <code>❗Unlicensed</code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/adamerose/PandasGUI">PandasGUI</a></b> (🥉20 ·  ⭐ 2.7K) - A GUI for Pandas DataFrames. <code><a href="https://tldrlegal.com/search?q=MIT-0">❗️MIT-0</a></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/beringresearch/ivis">ivis</a></b> (🥉18 ·  ⭐ 270) - Dimensionality reduction in very large datasets using Siamese.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/t-makaro/animatplot">animatplot</a></b> (🥉17 ·  ⭐ 390 · 💀) - A python package for animating plots build on matplotlib. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/altair-viz/pdvega">pdvega</a></b> (🥉16 ·  ⭐ 340 · 💀) - Interactive plotting for Pandas using Vega-Lite. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/data-describe/data-describe">data-describe</a></b> (🥉15 ·  ⭐ 290 · 💤) - datadescribe: Pythonic EDA Accelerator for Data.. <code>❗Unlicensed</code>
- <b><a href="https://github.com/Zsailer/nx_altair">nx-altair</a></b> (🥉13 ·  ⭐ 190 · 💀) - Draw interactive NetworkX graphs with Altair. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/biovault/nptsne">nptsne</a></b> (🥉10 ·  ⭐ 28 · 💀) - nptsne is a numpy compatible python binary package that offers a.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
</details>
<br>

## Text Data & NLP

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for processing, cleaning, manipulating, and analyzing text data as well as libraries for NLP tasks such as language detection, fuzzy matching, classification, seq2seq learning, conversational AI, keyword extraction, and translation._

<details><summary><b><a href="https://github.com/huggingface/transformers">transformers</a></b> (🥇49 ·  ⭐ 65K) - Transformers: State-of-the-art Machine Learning for.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/huggingface/transformers) (👨‍💻 1.3K · 🔀 14K · 📥 1.5K · 📦 29K · 📋 9.4K - 4% open · ⏱️ 09.06.2022):

	```
	git clone https://github.com/huggingface/transformers
	```
- [PyPi](https://pypi.org/project/transformers) (📥 8.2M / month):
	```
	pip install transformers
	```
- [Conda](https://anaconda.org/conda-forge/transformers) (📥 240K · ⏱️ 22.05.2022):
	```
	conda install -c conda-forge transformers
	```
</details>
<details><summary><b><a href="https://github.com/explosion/spaCy">spaCy</a></b> (🥇44 ·  ⭐ 24K) - Industrial-strength Natural Language Processing (NLP) in Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/explosion/spaCy) (👨‍💻 680 · 🔀 3.8K · 📥 3.1K · 📦 40K · 📋 5.1K - 1% open · ⏱️ 08.06.2022):

	```
	git clone https://github.com/explosion/spaCy
	```
- [PyPi](https://pypi.org/project/spacy) (📥 7.2M / month):
	```
	pip install spacy
	```
- [Conda](https://anaconda.org/conda-forge/spacy) (📥 2.7M · ⏱️ 03.05.2022):
	```
	conda install -c conda-forge spacy
	```
</details>
<details><summary><b><a href="https://github.com/RaRe-Technologies/gensim">gensim</a></b> (🥇42 ·  ⭐ 13K) - Topic Modelling for Humans. <code><a href="https://tldrlegal.com/search?q=LGPL-2.1">❗️LGPL-2.1</a></code></summary>

- [GitHub](https://github.com/RaRe-Technologies/gensim) (👨‍💻 430 · 🔀 4K · 📥 3.8K · 📦 34K · 📋 1.7K - 20% open · ⏱️ 06.05.2022):

	```
	git clone https://github.com/RaRe-Technologies/gensim
	```
- [PyPi](https://pypi.org/project/gensim) (📥 7.5M / month):
	```
	pip install gensim
	```
- [Conda](https://anaconda.org/conda-forge/gensim) (📥 810K · ⏱️ 25.05.2022):
	```
	conda install -c conda-forge gensim
	```
</details>
<details><summary><b><a href="https://github.com/nltk/nltk">nltk</a></b> (🥇42 ·  ⭐ 11K) - Suite of libraries and programs for symbolic and statistical natural.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/nltk/nltk) (👨‍💻 420 · 🔀 2.5K · 📦 140K · 📋 1.6K - 13% open · ⏱️ 25.05.2022):

	```
	git clone https://github.com/nltk/nltk
	```
- [PyPi](https://pypi.org/project/nltk) (📥 14M / month):
	```
	pip install nltk
	```
- [Conda](https://anaconda.org/conda-forge/nltk) (📥 1.3M · ⏱️ 29.12.2021):
	```
	conda install -c conda-forge nltk
	```
</details>
<details><summary><b><a href="https://github.com/allenai/allennlp">AllenNLP</a></b> (🥇38 ·  ⭐ 11K) - An open-source NLP research library, built on PyTorch. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/allenai/allennlp) (👨‍💻 260 · 🔀 2.1K · 📥 46 · 📦 2.5K · 📋 2.5K - 3% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/allenai/allennlp
	```
- [PyPi](https://pypi.org/project/allennlp) (📥 74K / month):
	```
	pip install allennlp
	```
- [Conda](https://anaconda.org/conda-forge/allennlp) (📥 65K · ⏱️ 15.04.2022):
	```
	conda install -c conda-forge allennlp
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/fairseq">fairseq</a></b> (🥇37 ·  ⭐ 17K) - Facebook AI Research Sequence-to-Sequence Toolkit written in Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/facebookresearch/fairseq) (👨‍💻 390 · 🔀 4.4K · 📥 240 · 📦 820 · 📋 3.4K - 16% open · ⏱️ 08.06.2022):

	```
	git clone https://github.com/pytorch/fairseq
	```
- [PyPi](https://pypi.org/project/fairseq) (📥 59K / month):
	```
	pip install fairseq
	```
- [Conda](https://anaconda.org/conda-forge/fairseq) (📥 15K · ⏱️ 28.05.2022):
	```
	conda install -c conda-forge fairseq
	```
</details>
<details><summary><b><a href="https://github.com/RasaHQ/rasa">Rasa</a></b> (🥇36 ·  ⭐ 14K) - Open source machine learning framework to automate text- and voice-.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/RasaHQ/rasa) (👨‍💻 540 · 🔀 3.9K · 📋 6.5K - 12% open · ⏱️ 09.06.2022):

	```
	git clone https://github.com/RasaHQ/rasa
	```
- [PyPi](https://pypi.org/project/rasa) (📥 170K / month):
	```
	pip install rasa
	```
</details>
<details><summary><b><a href="https://github.com/gunthercox/ChatterBot">ChatterBot</a></b> (🥇36 ·  ⭐ 12K · 💤) - ChatterBot is a machine learning, conversational dialog engine.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/gunthercox/ChatterBot) (👨‍💻 100 · 🔀 4K · 📦 4.4K · 📋 1.5K - 18% open · ⏱️ 01.06.2021):

	```
	git clone https://github.com/gunthercox/ChatterBot
	```
- [PyPi](https://pypi.org/project/chatterbot) (📥 82K / month):
	```
	pip install chatterbot
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/ParlAI">ParlAI</a></b> (🥇35 ·  ⭐ 8.9K) - A framework for training and evaluating AI models on a variety of.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/facebookresearch/ParlAI) (👨‍💻 190 · 🔀 1.8K · 📦 78 · 📋 1.3K - 6% open · ⏱️ 07.06.2022):

	```
	git clone https://github.com/facebookresearch/ParlAI
	```
- [PyPi](https://pypi.org/project/parlai) (📥 1.9K / month):
	```
	pip install parlai
	```
</details>
<details><summary><b><a href="https://github.com/UKPLab/sentence-transformers">sentence-transformers</a></b> (🥇35 ·  ⭐ 7.8K) - Multilingual Sentence & Image Embeddings with BERT. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/UKPLab/sentence-transformers) (👨‍💻 80 · 🔀 1.5K · 📦 3.4K · 📋 1.4K - 50% open · ⏱️ 03.06.2022):

	```
	git clone https://github.com/UKPLab/sentence-transformers
	```
- [PyPi](https://pypi.org/project/sentence-transformers) (📥 4.2M / month):
	```
	pip install sentence-transformers
	```
- [Conda](https://anaconda.org/conda-forge/sentence-transformers) (📥 23K · ⏱️ 20.02.2022):
	```
	conda install -c conda-forge sentence-transformers
	```
</details>
<details><summary><b><a href="https://github.com/google/sentencepiece">sentencepiece</a></b> (🥇35 ·  ⭐ 5.9K) - Unsupervised text tokenizer for Neural Network-based text.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/google/sentencepiece) (👨‍💻 66 · 🔀 780 · 📥 21K · 📦 16K · 📋 520 - 5% open · ⏱️ 08.06.2022):

	```
	git clone https://github.com/google/sentencepiece
	```
- [PyPi](https://pypi.org/project/sentencepiece) (📥 7.8M / month):
	```
	pip install sentencepiece
	```
- [Conda](https://anaconda.org/conda-forge/sentencepiece) (📥 190K · ⏱️ 08.04.2022):
	```
	conda install -c conda-forge sentencepiece
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/fastText">fastText</a></b> (🥈34 ·  ⭐ 24K) - Library for fast text representation and classification. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/facebookresearch/fastText) (👨‍💻 59 · 🔀 4.3K · 📦 3K · 📋 1K - 41% open · ⏱️ 04.03.2022):

	```
	git clone https://github.com/facebookresearch/fastText
	```
- [PyPi](https://pypi.org/project/fasttext) (📥 510K / month):
	```
	pip install fasttext
	```
- [Conda](https://anaconda.org/conda-forge/fasttext) (📥 31K · ⏱️ 16.04.2022):
	```
	conda install -c conda-forge fasttext
	```
</details>
<details><summary><b><a href="https://github.com/sloria/TextBlob">TextBlob</a></b> (🥈34 ·  ⭐ 8.2K · 💤) - Simple, Pythonic, text processing--Sentiment analysis, part-of-.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/sloria/TextBlob) (👨‍💻 35 · 🔀 1K · 📥 99 · 📦 21K · 📋 250 - 37% open · ⏱️ 22.10.2021):

	```
	git clone https://github.com/sloria/TextBlob
	```
- [PyPi](https://pypi.org/project/textblob) (📥 940K / month):
	```
	pip install textblob
	```
- [Conda](https://anaconda.org/conda-forge/textblob) (📥 160K · ⏱️ 24.02.2019):
	```
	conda install -c conda-forge textblob
	```
</details>
<details><summary><b><a href="https://github.com/JohnSnowLabs/spark-nlp">spark-nlp</a></b> (🥈33 ·  ⭐ 2.8K) - State of the Art Natural Language Processing. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/JohnSnowLabs/spark-nlp) (👨‍💻 120 · 🔀 550 · 📋 660 - 4% open · ⏱️ 09.06.2022):

	```
	git clone https://github.com/JohnSnowLabs/spark-nlp
	```
- [PyPi](https://pypi.org/project/spark-nlp) (📥 1.7M / month):
	```
	pip install spark-nlp
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/text">TensorFlow Text</a></b> (🥈33 ·  ⭐ 950) - Making text a first-class citizen in TensorFlow. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/text) (👨‍💻 89 · 🔀 220 · 📦 1.9K · 📋 160 - 20% open · ⏱️ 07.06.2022):

	```
	git clone https://github.com/tensorflow/text
	```
- [PyPi](https://pypi.org/project/tensorflow-text) (📥 5M / month):
	```
	pip install tensorflow-text
	```
</details>
<details><summary><b><a href="https://github.com/huggingface/tokenizers">Tokenizers</a></b> (🥈32 ·  ⭐ 5.7K) - Fast State-of-the-Art Tokenizers optimized for Research and.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/huggingface/tokenizers) (👨‍💻 56 · 🔀 460 · 📦 49 · 📋 620 - 28% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/huggingface/tokenizers
	```
- [PyPi](https://pypi.org/project/tokenizers) (📥 8.2M / month):
	```
	pip install tokenizers
	```
- [Conda](https://anaconda.org/conda-forge/tokenizers) (📥 200K · ⏱️ 21.05.2022):
	```
	conda install -c conda-forge tokenizers
	```
</details>
<details><summary><b><a href="https://github.com/deepmipt/DeepPavlov">DeepPavlov</a></b> (🥈31 ·  ⭐ 5.8K) - An open source library for deep learning end-to-end dialog.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/deepmipt/DeepPavlov) (👨‍💻 67 · 🔀 1K · 📦 270 · 📋 620 - 10% open · ⏱️ 31.05.2022):

	```
	git clone https://github.com/deepmipt/DeepPavlov
	```
- [PyPi](https://pypi.org/project/deeppavlov) (📥 12K / month):
	```
	pip install deeppavlov
	```
</details>
<details><summary><b><a href="https://github.com/OpenNMT/OpenNMT-py">OpenNMT</a></b> (🥈31 ·  ⭐ 5.6K) - Open Source Neural Machine Translation in PyTorch. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/OpenNMT/OpenNMT-py) (👨‍💻 170 · 🔀 2K · 📦 140 · 📋 1.3K - 6% open · ⏱️ 09.02.2022):

	```
	git clone https://github.com/OpenNMT/OpenNMT-py
	```
- [PyPi](https://pypi.org/project/OpenNMT-py) (📥 5.1K / month):
	```
	pip install OpenNMT-py
	```
</details>
<details><summary><b><a href="https://github.com/dedupeio/dedupe">Dedupe</a></b> (🥈31 ·  ⭐ 3.4K) - A python library for accurate and scalable fuzzy matching, record.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/dedupeio/dedupe) (👨‍💻 64 · 🔀 460 · 📦 220 · 📋 740 - 6% open · ⏱️ 06.06.2022):

	```
	git clone https://github.com/dedupeio/dedupe
	```
- [PyPi](https://pypi.org/project/dedupe) (📥 310K / month):
	```
	pip install dedupe
	```
- [Conda](https://anaconda.org/conda-forge/dedupe) (📥 4.9K · ⏱️ 23.05.2022):
	```
	conda install -c conda-forge dedupe
	```
</details>
<details><summary><b><a href="https://github.com/NVIDIA/NeMo">NeMo</a></b> (🥈30 ·  ⭐ 4.3K) - NeMo: a toolkit for conversational AI. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/NVIDIA/NeMo) (👨‍💻 150 · 🔀 990 · 📥 7.2K · 📋 1.1K - 2% open · ⏱️ 09.06.2022):

	```
	git clone https://github.com/NVIDIA/NeMo
	```
- [PyPi](https://pypi.org/project/nemo-toolkit) (📥 20K / month):
	```
	pip install nemo-toolkit
	```
</details>
<details><summary><b><a href="https://github.com/pytorch/text">torchtext</a></b> (🥈30 ·  ⭐ 3K) - Data loaders and abstractions for text and NLP. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytorch/text) (👨‍💻 130 · 🔀 690 · 📋 650 - 39% open · ⏱️ 08.06.2022):

	```
	git clone https://github.com/pytorch/text
	```
- [PyPi](https://pypi.org/project/torchtext) (📥 140K / month):
	```
	pip install torchtext
	```
</details>
<details><summary><b><a href="https://github.com/makcedward/nlpaug">nlpaug</a></b> (🥈29 ·  ⭐ 3.3K) - Data augmentation for NLP. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/makcedward/nlpaug) (👨‍💻 30 · 🔀 370 · 📦 340 · 📋 180 - 21% open · ⏱️ 03.04.2022):

	```
	git clone https://github.com/makcedward/nlpaug
	```
- [PyPi](https://pypi.org/project/nlpaug) (📥 71K / month):
	```
	pip install nlpaug
	```
- [Conda](https://anaconda.org/conda-forge/nlpaug) (📥 2.1K · ⏱️ 25.12.2021):
	```
	conda install -c conda-forge nlpaug
	```
</details>
<details><summary><b><a href="https://github.com/rspeer/python-ftfy">ftfy</a></b> (🥈29 ·  ⭐ 3.2K) - Fixes mojibake and other glitches in Unicode text, after the fact. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/rspeer/python-ftfy) (👨‍💻 18 · 🔀 110 · 📦 5.9K · 📋 130 - 9% open · ⏱️ 09.02.2022):

	```
	git clone https://github.com/rspeer/python-ftfy
	```
- [PyPi](https://pypi.org/project/ftfy) (📥 1.7M / month):
	```
	pip install ftfy
	```
- [Conda](https://anaconda.org/conda-forge/ftfy) (📥 160K · ⏱️ 13.03.2022):
	```
	conda install -c conda-forge ftfy
	```
</details>
<details><summary><b><a href="https://github.com/miso-belica/sumy">Sumy</a></b> (🥈29 ·  ⭐ 2.8K) - Module for automatic summarization of text documents and HTML pages. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/miso-belica/sumy) (👨‍💻 22 · 🔀 460 · 📦 1.3K · 📋 100 - 13% open · ⏱️ 21.04.2022):

	```
	git clone https://github.com/miso-belica/sumy
	```
- [PyPi](https://pypi.org/project/sumy) (📥 23K / month):
	```
	pip install sumy
	```
- [Conda](https://anaconda.org/conda-forge/sumy) (📥 1.1K · ⏱️ 22.04.2022):
	```
	conda install -c conda-forge sumy
	```
</details>
<details><summary><b><a href="https://github.com/dmlc/gluon-nlp">GluonNLP</a></b> (🥈29 ·  ⭐ 2.4K · 💤) - Toolkit that enables easy text preprocessing, datasets.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1X" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/dmlc/gluon-nlp) (👨‍💻 82 · 🔀 500 · 📦 830 · 📋 530 - 43% open · ⏱️ 24.08.2021):

	```
	git clone https://github.com/dmlc/gluon-nlp
	```
- [PyPi](https://pypi.org/project/gluonnlp) (📥 79K / month):
	```
	pip install gluonnlp
	```
</details>
<details><summary><b><a href="https://github.com/deepset-ai/haystack">haystack</a></b> (🥈28 ·  ⭐ 4.8K) - Haystack is an open source NLP framework that leverages Transformer.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/deepset-ai/haystack) (👨‍💻 120 · 🔀 760 · 📥 13 · 📋 1.4K - 14% open · ⏱️ 09.06.2022):

	```
	git clone https://github.com/deepset-ai/haystack
	```
- [PyPi](https://pypi.org/project/haystack) (📥 1.4K / month):
	```
	pip install haystack
	```
</details>
<details><summary><b><a href="https://github.com/jamesturk/jellyfish">jellyfish</a></b> (🥈28 ·  ⭐ 1.7K) - a python library for doing approximate and phonetic matching of.. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/jamesturk/jellyfish) (👨‍💻 25 · 🔀 140 · 📦 3.8K · 📋 110 - 9% open · ⏱️ 07.01.2022):

	```
	git clone https://github.com/jamesturk/jellyfish
	```
- [PyPi](https://pypi.org/project/jellyfish) (📥 2.1M / month):
	```
	pip install jellyfish
	```
- [Conda](https://anaconda.org/conda-forge/jellyfish) (📥 230K · ⏱️ 08.04.2022):
	```
	conda install -c conda-forge jellyfish
	```
</details>
<details><summary><b><a href="https://github.com/allenai/scispacy">SciSpacy</a></b> (🥈28 ·  ⭐ 1.2K) - A full spaCy pipeline and models for scientific/biomedical documents. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/allenai/scispacy) (👨‍💻 23 · 🔀 150 · 📦 470 · 📋 250 - 11% open · ⏱️ 10.03.2022):

	```
	git clone https://github.com/allenai/scispacy
	```
- [PyPi](https://pypi.org/project/scispacy) (📥 21K / month):
	```
	pip install scispacy
	```
</details>
<details><summary><b><a href="https://github.com/Ciphey/Ciphey">Ciphey</a></b> (🥈27 ·  ⭐ 10K) - Automatically decrypt encryptions without knowing the key or cipher, decode.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/Ciphey/Ciphey) (👨‍💻 45 · 🔀 620 · 📋 280 - 14% open · ⏱️ 18.05.2022):

	```
	git clone https://github.com/Ciphey/Ciphey
	```
- [PyPi](https://pypi.org/project/ciphey) (📥 20K / month):
	```
	pip install ciphey
	```
- [Docker Hub](https://hub.docker.com/r/remnux/ciphey) (📥 16K · ⭐ 7 · ⏱️ 27.05.2022):
	```
	docker pull remnux/ciphey
	```
</details>
<details><summary><b><a href="https://github.com/life4/textdistance">TextDistance</a></b> (🥈27 ·  ⭐ 2.9K · 💤) - Compute distance between sequences. 30+ algorithms, pure.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/life4/textdistance) (👨‍💻 11 · 🔀 230 · 📥 670 · 📦 2.3K · ⏱️ 29.11.2021):

	```
	git clone https://github.com/life4/textdistance
	```
- [PyPi](https://pypi.org/project/textdistance) (📥 540K / month):
	```
	pip install textdistance
	```
- [Conda](https://anaconda.org/conda-forge/textdistance) (📥 120K · ⏱️ 27.10.2021):
	```
	conda install -c conda-forge textdistance
	```
</details>
<details><summary><b><a href="https://github.com/fastnlp/fastNLP">fastNLP</a></b> (🥈27 ·  ⭐ 2.6K) - fastNLP: A Modularized and Extensible NLP Framework. Currently still.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/fastnlp/fastNLP) (👨‍💻 54 · 🔀 420 · 📥 66 · 📦 80 · 📋 190 - 21% open · ⏱️ 06.12.2021):

	```
	git clone https://github.com/fastnlp/fastNLP
	```
- [PyPi](https://pypi.org/project/fastnlp) (📥 1.2K / month):
	```
	pip install fastnlp
	```
</details>
<details><summary><b><a href="https://github.com/huggingface/neuralcoref">neuralcoref</a></b> (🥈27 ·  ⭐ 2.5K · 💤) - Fast Coreference Resolution in spaCy with Neural Networks. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/huggingface/neuralcoref) (👨‍💻 21 · 🔀 440 · 📥 400 · 📦 500 · 📋 300 - 15% open · ⏱️ 22.06.2021):

	```
	git clone https://github.com/huggingface/neuralcoref
	```
- [PyPi](https://pypi.org/project/neuralcoref) (📥 190K / month):
	```
	pip install neuralcoref
	```
- [Conda](https://anaconda.org/conda-forge/neuralcoref) (📥 11K · ⏱️ 21.02.2020):
	```
	conda install -c conda-forge neuralcoref
	```
</details>
<details><summary><b><a href="https://github.com/DerwenAI/pytextrank">PyTextRank</a></b> (🥈27 ·  ⭐ 1.8K) - Python implementation of TextRank algorithms (textgraphs) for phrase.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/DerwenAI/pytextrank) (👨‍💻 18 · 🔀 300 · 📦 260 · 📋 87 - 29% open · ⏱️ 07.03.2022):

	```
	git clone https://github.com/DerwenAI/pytextrank
	```
- [PyPi](https://pypi.org/project/pytextrank) (📥 19K / month):
	```
	pip install pytextrank
	```
</details>
<details><summary><b><a href="https://github.com/explosion/spacy-transformers">spacy-transformers</a></b> (🥈27 ·  ⭐ 1.1K) - Use pretrained transformers like BERT, XLNet and GPT-2.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>spacy</code></summary>

- [GitHub](https://github.com/explosion/spacy-transformers) (👨‍💻 18 · 🔀 130 · 📦 520 · ⏱️ 02.06.2022):

	```
	git clone https://github.com/explosion/spacy-transformers
	```
- [PyPi](https://pypi.org/project/spacy-transformers) (📥 99K / month):
	```
	pip install spacy-transformers
	```
- [Conda](https://anaconda.org/conda-forge/spacy-transformers) (📥 1.6K · ⏱️ 02.06.2022):
	```
	conda install -c conda-forge spacy-transformers
	```
</details>
<details><summary><b><a href="https://github.com/cltk/cltk">CLTK</a></b> (🥈27 ·  ⭐ 720) - The Classical Language Toolkit. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/cltk/cltk) (👨‍💻 120 · 🔀 300 · 📥 25 · 📦 200 · 📋 520 - 4% open · ⏱️ 01.05.2022):

	```
	git clone https://github.com/cltk/cltk
	```
- [PyPi](https://pypi.org/project/cltk) (📥 1.5K / month):
	```
	pip install cltk
	```
</details>
<details><summary><b><a href="https://github.com/google-research/text-to-text-transfer-transformer">T5</a></b> (🥈26 ·  ⭐ 4.2K) - Code for the paper Exploring the Limits of Transfer Learning with a.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/google-research/text-to-text-transfer-transformer) (👨‍💻 48 · 🔀 580 · 📦 100 · 📋 380 - 10% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/google-research/text-to-text-transfer-transformer
	```
- [PyPi](https://pypi.org/project/t5) (📥 7.1K / month):
	```
	pip install t5
	```
</details>
<details><summary><b><a href="https://github.com/cjhutto/vaderSentiment">vaderSentiment</a></b> (🥈26 ·  ⭐ 3.6K) - VADER Sentiment Analysis. VADER (Valence Aware Dictionary and.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/cjhutto/vaderSentiment) (👨‍💻 11 · 🔀 870 · 📦 3.9K · 📋 110 - 30% open · ⏱️ 01.04.2022):

	```
	git clone https://github.com/cjhutto/vaderSentiment
	```
- [PyPi](https://pypi.org/project/vadersentiment) (📥 210K / month):
	```
	pip install vadersentiment
	```
- [Conda](https://anaconda.org/conda-forge/vadersentiment) (📥 8.7K · ⏱️ 22.03.2021):
	```
	conda install -c conda-forge vadersentiment
	```
</details>
<details><summary><b><a href="https://github.com/PetrochukM/PyTorch-NLP">pytorch-nlp</a></b> (🥉24 ·  ⭐ 2.1K · 💤) - Basic Utilities for PyTorch Natural Language Processing.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PetrochukM/PyTorch-NLP) (👨‍💻 18 · 🔀 250 · 📦 390 · 📋 67 - 26% open · ⏱️ 10.07.2021):

	```
	git clone https://github.com/PetrochukM/PyTorch-NLP
	```
- [PyPi](https://pypi.org/project/pytorch-nlp) (📥 6.4K / month):
	```
	pip install pytorch-nlp
	```
</details>
<details><summary><b><a href="https://github.com/awslabs/sockeye">Sockeye</a></b> (🥉24 ·  ⭐ 1.1K) - Sequence-to-sequence framework with a focus on Neural Machine.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1X" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/awslabs/sockeye) (👨‍💻 56 · 🔀 290 · 📥 14 · 📋 280 - 1% open · ⏱️ 29.05.2022):

	```
	git clone https://github.com/awslabs/sockeye
	```
- [PyPi](https://pypi.org/project/sockeye) (📥 1.2K / month):
	```
	pip install sockeye
	```
</details>
<details><summary><b><a href="https://github.com/snowballstem/snowball">snowballstemmer</a></b> (🥉24 ·  ⭐ 560 · 📉) - Snowball compiler and stemming algorithms. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/snowballstem/snowball) (👨‍💻 28 · 🔀 150 · 📦 4 · 📋 59 - 25% open · ⏱️ 17.12.2021):

	```
	git clone https://github.com/snowballstem/snowball
	```
- [PyPi](https://pypi.org/project/snowballstemmer) (📥 6.8M / month):
	```
	pip install snowballstemmer
	```
- [Conda](https://anaconda.org/conda-forge/snowballstemmer) (📥 4.4M · ⏱️ 17.11.2021):
	```
	conda install -c conda-forge snowballstemmer
	```
</details>
<details><summary><b><a href="https://github.com/NTMC-Community/MatchZoo">MatchZoo</a></b> (🥉23 ·  ⭐ 3.7K · 💤) - Facilitating the design, comparison and sharing of deep.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/NTMC-Community/MatchZoo) (👨‍💻 36 · 🔀 900 · 📦 11 · 📋 460 - 6% open · ⏱️ 02.06.2021):

	```
	git clone https://github.com/NTMC-Community/MatchZoo
	```
- [PyPi](https://pypi.org/project/matchzoo) (📥 110 / month):
	```
	pip install matchzoo
	```
</details>
<details><summary><b><a href="https://github.com/BrikerMan/Kashgari">Kashgari</a></b> (🥉23 ·  ⭐ 2.3K · 💤) - Kashgari is a production-level NLP Transfer learning.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/BrikerMan/Kashgari) (👨‍💻 21 · 🔀 430 · 📦 52 · 📋 370 - 11% open · ⏱️ 09.07.2021):

	```
	git clone https://github.com/BrikerMan/Kashgari
	```
- [PyPi](https://pypi.org/project/kashgari-tf) (📥 88 / month):
	```
	pip install kashgari-tf
	```
</details>
<details><summary><b><a href="https://github.com/qdrant/qdrant">qdrant</a></b> (🥉23 ·  ⭐ 1.8K) - Qdrant - vector similarity search engine with extended filtering.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/qdrant/qdrant) (👨‍💻 25 · 🔀 93 · 📋 210 - 12% open · ⏱️ 08.06.2022):

	```
	git clone https://github.com/qdrant/qdrant
	```
</details>
<details><summary><b><a href="https://github.com/utterworks/fast-bert">fast-bert</a></b> (🥉23 ·  ⭐ 1.7K) - Super easy library for BERT based NLP models. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/utterworks/fast-bert) (👨‍💻 36 · 🔀 330 · 📋 240 - 61% open · ⏱️ 03.06.2022):

	```
	git clone https://github.com/utterworks/fast-bert
	```
- [PyPi](https://pypi.org/project/fast-bert) (📥 2.1K / month):
	```
	pip install fast-bert
	```
</details>
<details><summary><b><a href="https://github.com/thunlp/OpenPrompt">OpenPrompt</a></b> (🥉23 ·  ⭐ 1.6K) - An Open-Source Framework for Prompt-Learning. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/thunlp/OpenPrompt) (👨‍💻 14 · 🔀 160 · 📦 10 · 📋 130 - 0% open · ⏱️ 05.06.2022):

	```
	git clone https://github.com/thunlp/OpenPrompt
	```
- [PyPi](https://pypi.org/project/openprompt) (📥 770 / month):
	```
	pip install openprompt
	```
</details>
<details><summary><b><a href="https://github.com/explosion/sense2vec">sense2vec</a></b> (🥉23 ·  ⭐ 1.4K · 💤) - Contextually-keyed word vectors. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/explosion/sense2vec) (👨‍💻 17 · 🔀 220 · 📥 31K · 📦 150 · 📋 110 - 18% open · ⏱️ 16.08.2021):

	```
	git clone https://github.com/explosion/sense2vec
	```
- [PyPi](https://pypi.org/project/sense2vec) (📥 4.2K / month):
	```
	pip install sense2vec
	```
- [Conda](https://anaconda.org/conda-forge/sense2vec) (📥 26K · ⏱️ 14.07.2021):
	```
	conda install -c conda-forge sense2vec
	```
</details>
<details><summary><b><a href="https://github.com/recognai/rubrix">rubrix</a></b> (🥉23 ·  ⭐ 1.1K) - Rubrix, open-source framework for data-centric NLP. Data annotation.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/recognai/rubrix) (👨‍💻 19 · 🔀 88 · 📋 540 - 4% open · ⏱️ 08.06.2022):

	```
	git clone https://github.com/recognai/rubrix
	```
- [PyPi](https://pypi.org/project/rubrix) (📥 1.7K / month):
	```
	pip install rubrix
	```
- [Conda](https://anaconda.org/conda-forge/rubrix) (📥 2K · ⏱️ 09.06.2022):
	```
	conda install -c conda-forge rubrix
	```
</details>
<details><summary><b><a href="https://github.com/dwyl/english-words">english-words</a></b> (🥉22 ·  ⭐ 7.2K) - A text file containing 479k English words for all your.. <code><a href="http://bit.ly/3rvuUlR">Unlicense</a></code></summary>

- [GitHub](https://github.com/dwyl/english-words) (👨‍💻 27 · 🔀 1.4K · 📋 80 - 63% open · ⏱️ 20.04.2022):

	```
	git clone https://github.com/dwyl/english-words
	```
- [PyPi](https://pypi.org/project/english-words) (📥 15K / month):
	```
	pip install english-words
	```
</details>
<details><summary><b><a href="https://github.com/JasonKessler/scattertext">scattertext</a></b> (🥉22 ·  ⭐ 1.8K) - Beautiful visualizations of how language differs among document.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/JasonKessler/scattertext) (👨‍💻 12 · 🔀 250 · 📦 280 · 📋 86 - 18% open · ⏱️ 26.03.2022):

	```
	git clone https://github.com/JasonKessler/scattertext
	```
- [PyPi](https://pypi.org/project/scattertext) (📥 3.5K / month):
	```
	pip install scattertext
	```
- [Conda](https://anaconda.org/conda-forge/scattertext) (📥 62K · ⏱️ 26.03.2022):
	```
	conda install -c conda-forge scattertext
	```
</details>
<details><summary><b><a href="https://github.com/deepset-ai/FARM">FARM</a></b> (🥉22 ·  ⭐ 1.5K) - Fast & easy transfer learning for NLP. Harvesting language models.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/deepset-ai/FARM) (👨‍💻 37 · 🔀 220 · 📋 400 - 0% open · ⏱️ 25.04.2022):

	```
	git clone https://github.com/deepset-ai/FARM
	```
- [PyPi](https://pypi.org/project/farm) (📥 3.9K / month):
	```
	pip install farm
	```
- [Conda](https://anaconda.org/conda-forge/farm) (📥 1.1K · ⏱️ 14.06.2021):
	```
	conda install -c conda-forge farm
	```
</details>
<details><summary><b><a href="https://github.com/unitaryai/detoxify">detoxify</a></b> (🥉22 ·  ⭐ 440) - Trained models & code to predict toxic comments on all 3 Jigsaw.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/unitaryai/detoxify) (👨‍💻 6 · 🔀 53 · 📥 46K · 📦 91 · 📋 31 - 45% open · ⏱️ 20.04.2022):

	```
	git clone https://github.com/unitaryai/detoxify
	```
- [PyPi](https://pypi.org/project/detoxify) (📥 10K / month):
	```
	pip install detoxify
	```
</details>
<details><summary><b><a href="https://github.com/IntelLabs/nlp-architect">NLP Architect</a></b> (🥉21 ·  ⭐ 2.8K · 💤) - A model library for exploring state-of-the-art deep.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/IntelLabs/nlp-architect) (👨‍💻 37 · 🔀 430 · 📦 8 · 📋 130 - 11% open · ⏱️ 12.09.2021):

	```
	git clone https://github.com/IntelLabs/nlp-architect
	```
- [PyPi](https://pypi.org/project/nlp-architect) (📥 110 / month):
	```
	pip install nlp-architect
	```
</details>
<details><summary><b><a href="https://github.com/jbesomi/texthero">Texthero</a></b> (🥉21 ·  ⭐ 2.5K · 💤) - Text preprocessing, representation and visualization from zero to.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jbesomi/texthero) (👨‍💻 18 · 🔀 210 · 📥 90 · 📋 110 - 45% open · ⏱️ 19.07.2021):

	```
	git clone https://github.com/jbesomi/texthero
	```
- [PyPi](https://pypi.org/project/texthero) (📥 24K / month):
	```
	pip install texthero
	```
</details>
<details><summary><b><a href="https://github.com/nyu-mll/jiant">jiant</a></b> (🥉20 ·  ⭐ 1.4K) - jiant is an nlp toolkit. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/nyu-mll/jiant) (👨‍💻 58 · 🔀 270 · 📦 2 · 📋 550 - 11% open · ⏱️ 31.03.2022):

	```
	git clone https://github.com/nyu-mll/jiant
	```
- [PyPi](https://pypi.org/project/jiant) (📥 50 / month):
	```
	pip install jiant
	```
</details>
<details><summary><b><a href="https://github.com/IndicoDataSolutions/finetune">finetune</a></b> (🥉19 ·  ⭐ 660) - Scikit-learn style model finetuning for NLP. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/IndicoDataSolutions/finetune) (👨‍💻 19 · 🔀 71 · 📦 9 · 📋 140 - 15% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/IndicoDataSolutions/finetune
	```
- [PyPi](https://pypi.org/project/finetune) (📥 150 / month):
	```
	pip install finetune
	```
</details>
<details><summary><b><a href="https://github.com/Ki6an/fastT5">fastT5</a></b> (🥉17 ·  ⭐ 300) - boost inference speed of T5 models by 5x & reduce the model size by 3x. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/Ki6an/fastT5) (👨‍💻 5 · 🔀 34 · 📦 16 · 📋 46 - 19% open · ⏱️ 05.04.2022):

	```
	git clone https://github.com/Ki6an/fastT5
	```
- [PyPi](https://pypi.org/project/fastt5) (📥 2.6K / month):
	```
	pip install fastt5
	```
</details>
<details><summary><b><a href="https://github.com/thunlp/OpenNRE">OpenNRE</a></b> (🥉16 ·  ⭐ 3.7K) - An Open-Source Package for Neural Relation Extraction (NRE). <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/thunlp/OpenNRE) (👨‍💻 10 · 🔀 940 · 📋 340 - 1% open · ⏱️ 06.04.2022):

	```
	git clone https://github.com/thunlp/OpenNRE
	```
</details>
<details><summary><b><a href="https://github.com/anhaidgroup/deepmatcher">DeepMatcher</a></b> (🥉16 ·  ⭐ 430 · 💤) - Python package for performing Entity and Text Matching using.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/anhaidgroup/deepmatcher) (👨‍💻 7 · 🔀 95 · 📦 19 · 📋 83 - 72% open · ⏱️ 13.06.2021):

	```
	git clone https://github.com/anhaidgroup/deepmatcher
	```
- [PyPi](https://pypi.org/project/deepmatcher) (📥 790 / month):
	```
	pip install deepmatcher
	```
</details>
<details><summary><b><a href="https://github.com/RUCAIBox/TextBox">TextBox</a></b> (🥉16 ·  ⭐ 360) - TextBox is an open-source library for building text generation system. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/RUCAIBox/TextBox) (👨‍💻 14 · 🔀 64 · 📦 5 · 📋 20 - 15% open · ⏱️ 06.05.2022):

	```
	git clone https://github.com/RUCAIBox/TextBox
	```
- [PyPi](https://pypi.org/project/textbox) (📥 74 / month):
	```
	pip install textbox
	```
</details>
<details><summary><b><a href="https://github.com/PKSHATechnology-Research/camphr">Camphr</a></b> (🥉16 ·  ⭐ 340 · 💤) - Camphr - NLP libary for creating pipeline components. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code>spacy</code></summary>

- [GitHub](https://github.com/PKSHATechnology-Research/camphr) (👨‍💻 7 · 🔀 17 · 📋 28 - 7% open · ⏱️ 18.08.2021):

	```
	git clone https://github.com/PKSHATechnology-Research/camphr
	```
- [PyPi](https://pypi.org/project/camphr) (📥 280 / month):
	```
	pip install camphr
	```
</details>
<details><summary><b><a href="https://github.com/pytorch/translate">Translate</a></b> (🥉15 ·  ⭐ 740) - Translate - a PyTorch Language Library. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytorch/translate) (👨‍💻 87 · 🔀 180 · 📋 38 - 28% open · ⏱️ 15.05.2022):

	```
	git clone https://github.com/pytorch/translate
	```
- [PyPi](https://pypi.org/project/pytorch-translate) (📥 6 / month):
	```
	pip install pytorch-translate
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/vizseq">VizSeq</a></b> (🥉13 ·  ⭐ 400) - An Analysis Toolkit for Natural Language Generation (Translation,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/facebookresearch/vizseq) (👨‍💻 3 · 🔀 47 · 📦 6 · 📋 15 - 40% open · ⏱️ 08.06.2022):

	```
	git clone https://github.com/facebookresearch/vizseq
	```
- [PyPi](https://pypi.org/project/vizseq) (📥 87 / month):
	```
	pip install vizseq
	```
</details>
<details><summary>Show 34 hidden projects...</summary>

- <b><a href="https://github.com/flairNLP/flair">flair</a></b> (🥇36 ·  ⭐ 12K) - A very simple framework for state-of-the-art Natural Language.. <code>❗Unlicensed</code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/stanfordnlp/stanza">stanza</a></b> (🥈34 ·  ⭐ 6.1K) - Official Stanford NLP Python Library for Many Human Languages. <code>❗Unlicensed</code>
- <b><a href="https://github.com/seatgeek/fuzzywuzzy">fuzzywuzzy</a></b> (🥈32 ·  ⭐ 8.7K · 💤) - Fuzzy String Matching in Python. <code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code>
- <b><a href="https://github.com/facebookresearch/pytext">PyText</a></b> (🥈26 ·  ⭐ 6.3K) - A natural language modeling framework based on PyTorch. <code>❗Unlicensed</code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/vi3k6i5/flashtext">flashtext</a></b> (🥉24 ·  ⭐ 5.2K · 💀) - Extract Keywords from sentence or Replace keywords in sentences. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/minimaxir/textgenrnn">textgenrnn</a></b> (🥉23 ·  ⭐ 4.7K · 💀) - Easily train your own text-generating neural network.. <code>❗Unlicensed</code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/snipsco/snips-nlu">Snips NLU</a></b> (🥉23 ·  ⭐ 3.7K · 💀) - Snips Python library to extract meaning from text. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/aboSamoor/polyglot">polyglot</a></b> (🥉23 ·  ⭐ 2K · 💀) - Multilingual text (NLP) processing toolkit. <code>❗Unlicensed</code>
- <b><a href="https://github.com/saffsd/langid.py">langid</a></b> (🥉23 ·  ⭐ 2K · 💀) - Stand-alone language identification system. <code>❗Unlicensed</code>
- <b><a href="https://github.com/VKCOM/YouTokenToMe">YouTokenToMe</a></b> (🥉23 ·  ⭐ 800 · 💀) - Unsupervised text tokenizer focused on computational efficiency. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/asyml/texar">Texar</a></b> (🥉22 ·  ⭐ 2.3K · 💀) - Toolkit for Machine Learning, Natural Language Processing, and.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/chartbeat-labs/textacy">textacy</a></b> (🥉22 ·  ⭐ 1.9K) - NLP, before and after spaCy. <code>❗Unlicensed</code>
- <b><a href="https://github.com/Hironsan/anago">anaGo</a></b> (🥉22 ·  ⭐ 1.4K · 💀) - Bidirectional LSTM-CRF and ELMo for Named-Entity Recognition,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/nipunsadvilkar/pySBD">pySBD</a></b> (🥉22 ·  ⭐ 450 · 💀) - pySBD (Python Sentence Boundary Disambiguation) is a rule-based sentence.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/EricFillion/happy-transformer">happy-transformer</a></b> (🥉22 ·  ⭐ 300) - A package built on top of Hugging Faces transformers.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code>huggingface</code>
- <b><a href="https://github.com/Delta-ML/delta">DELTA</a></b> (🥉21 ·  ⭐ 1.5K · 💀) - DELTA is a deep learning based natural language and speech.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/Alir3z4/python-stop-words">stop-words</a></b> (🥉21 ·  ⭐ 140 · 💀) - Get list of common stop words in various languages in Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/minimaxir/gpt-2-simple">gpt-2-simple</a></b> (🥉20 ·  ⭐ 2.9K) - Python package to easily retrain OpenAIs GPT-2 text-.. <code>❗Unlicensed</code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/vrasneur/pyfasttext">pyfasttext</a></b> (🥉20 ·  ⭐ 230 · 💀) - Yet another Python binding for fastText. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
- <b><a href="https://github.com/bytedance/lightseq">lightseq</a></b> (🥉19 ·  ⭐ 2.2K) - LightSeq: A High Performance Library for Sequence Processing.. <code>❗Unlicensed</code>
- <b><a href="https://github.com/shaypal5/skift">skift</a></b> (🥉18 ·  ⭐ 230) - scikit-learn wrappers for Python fastText. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/textpipe/textpipe">textpipe</a></b> (🥉17 ·  ⭐ 300 · 💤) - Textpipe: clean and extract metadata from text. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/dsfsi/textaugment">textaugment</a></b> (🥉17 ·  ⭐ 250) - TextAugment: Text Augmentation Library. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/Franck-Dernoncourt/NeuroNER">NeuroNER</a></b> (🥉16 ·  ⭐ 1.6K · 💀) - Named-entity recognition using neural networks. Easy-to-use and.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/koursaros-ai/nboost">nboost</a></b> (🥉15 ·  ⭐ 620 · 💀) - NBoost is a scalable, search-api-boosting platform for deploying.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/mchaput/whoosh">whoosh</a></b> (🥉15 ·  ⭐ 240 · 📉) - Pure-Python full-text search library. <code>❗Unlicensed</code>
- <b><a href="https://github.com/facebookresearch/BLINK">BLINK</a></b> (🥉14 ·  ⭐ 890 · 💀) - Entity Linker solution. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/victordibia/neuralqa">NeuralQA</a></b> (🥉14 ·  ⭐ 220 · 💀) - NeuralQA: A Usable Library for Question Answering on Large Datasets.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/jaidevd/numerizer">numerizer</a></b> (🥉14 ·  ⭐ 150) - A Python module to convert natural language numerics into ints and.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/feedly/transfer-nlp">TransferNLP</a></b> (🥉13 ·  ⭐ 290 · 💀) - NLP library designed for reproducible experimentation.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/abelriboulot/onnxt5">ONNX-T5</a></b> (🥉13 ·  ⭐ 200 · 💀) - Summarization, translation, sentiment-analysis, text-generation.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/MartinoMensio/spacy-dbpedia-spotlight">spacy-dbpedia-spotlight</a></b> (🥉13 ·  ⭐ 64) - A spaCy wrapper for DBpedia Spotlight. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>spacy</code>
- <b><a href="https://github.com/as-ideas/headliner">Headliner</a></b> (🥉11 ·  ⭐ 230 · 💀) - Easy training and deployment of seq2seq models. <code>❗Unlicensed</code>
- <b><a href="https://github.com/textvec/textvec">textvec</a></b> (🥉11 ·  ⭐ 180 · 💀) - Text vectorization tool to outperform TFIDF for classification.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code>
</details>
<br>

## Image Data

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for image & video processing, manipulation, and augmentation as well as libraries for computer vision tasks such as facial recognition, object detection, and classification._

<details><summary><b><a href="https://github.com/python-pillow/Pillow">Pillow</a></b> (🥇47 ·  ⭐ 9.8K · 📈) - The friendly PIL fork (Python Imaging Library). <code><a href="https://tldrlegal.com/search?q=PIL">❗️PIL</a></code></summary>

- [GitHub](https://github.com/python-pillow/Pillow) (👨‍💻 400 · 🔀 1.7K · 📦 760K · 📋 2.5K - 3% open · ⏱️ 08.06.2022):

	```
	git clone https://github.com/python-pillow/Pillow
	```
- [PyPi](https://pypi.org/project/Pillow) (📥 48M / month):
	```
	pip install Pillow
	```
- [Conda](https://anaconda.org/conda-forge/pillow) (📥 16M · ⏱️ 30.05.2022):
	```
	conda install -c conda-forge pillow
	```
</details>
<details><summary><b><a href="https://github.com/rwightman/pytorch-image-models">PyTorch Image Models</a></b> (🥇38 ·  ⭐ 19K) - PyTorch image models, scripts, pretrained weights --.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/rwightman/pytorch-image-models) (👨‍💻 75 · 🔀 3.1K · 📥 1.3M · 📦 3.2K · 📋 500 - 10% open · ⏱️ 24.05.2022):

	```
	git clone https://github.com/rwightman/pytorch-image-models
	```
- [PyPi](https://pypi.org/project/timm) (📥 4M / month):
	```
	pip install timm
	```
- [Conda](https://anaconda.org/conda-forge/timm) (📥 19K · ⏱️ 30.06.2021):
	```
	conda install -c conda-forge timm
	```
</details>
<details><summary><b><a href="https://github.com/open-mmlab/mmdetection">MMDetection</a></b> (🥇37 ·  ⭐ 20K) - OpenMMLab Detection Toolbox and Benchmark. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/open-mmlab/mmdetection) (👨‍💻 340 · 🔀 6.6K · 📦 400 · 📋 5.9K - 8% open · ⏱️ 01.06.2022):

	```
	git clone https://github.com/open-mmlab/mmdetection
	```
- [PyPi](https://pypi.org/project/mmdet) (📥 34K / month):
	```
	pip install mmdet
	```
</details>
<details><summary><b><a href="https://github.com/pytorch/vision">torchvision</a></b> (🥇37 ·  ⭐ 12K) - Datasets, Transforms and Models specific to Computer Vision. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytorch/vision) (👨‍💻 490 · 🔀 5.9K · 📥 6.4K · 📋 2.4K - 23% open · ⏱️ 09.06.2022):

	```
	git clone https://github.com/pytorch/vision
	```
- [PyPi](https://pypi.org/project/torchvision) (📥 6.2M / month):
	```
	pip install torchvision
	```
- [Conda](https://anaconda.org/conda-forge/torchvision) (📥 260K · ⏱️ 29.03.2022):
	```
	conda install -c conda-forge torchvision
	```
</details>
<details><summary><b><a href="https://github.com/Zulko/moviepy">MoviePy</a></b> (🥇36 ·  ⭐ 9.3K) - Video editing with Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/Zulko/moviepy) (👨‍💻 150 · 🔀 1.2K · 📦 16K · 📋 1.2K - 23% open · ⏱️ 01.06.2022):

	```
	git clone https://github.com/Zulko/moviepy
	```
- [PyPi](https://pypi.org/project/moviepy) (📥 2.4M / month):
	```
	pip install moviepy
	```
- [Conda](https://anaconda.org/conda-forge/moviepy) (📥 110K · ⏱️ 16.04.2022):
	```
	conda install -c conda-forge moviepy
	```
</details>
<details><summary><b><a href="https://github.com/imageio/imageio">imageio</a></b> (🥇36 ·  ⭐ 1.1K) - Python library for reading and writing image data. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/imageio/imageio) (👨‍💻 90 · 🔀 210 · 📥 270 · 📦 63K · 📋 450 - 12% open · ⏱️ 30.05.2022):

	```
	git clone https://github.com/imageio/imageio
	```
- [PyPi](https://pypi.org/project/imageio) (📥 15M / month):
	```
	pip install imageio
	```
- [Conda](https://anaconda.org/conda-forge/imageio) (📥 3M · ⏱️ 01.06.2022):
	```
	conda install -c conda-forge imageio
	```
</details>
<details><summary><b><a href="https://github.com/kornia/kornia">Kornia</a></b> (🥈35 ·  ⭐ 6.6K) - Open Source Differentiable Computer Vision Library. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/kornia/kornia) (👨‍💻 170 · 🔀 650 · 📥 320 · 📦 1.4K · 📋 570 - 25% open · ⏱️ 28.05.2022):

	```
	git clone https://github.com/kornia/kornia
	```
- [PyPi](https://pypi.org/project/kornia) (📥 410K / month):
	```
	pip install kornia
	```
- [Conda](https://anaconda.org/conda-forge/kornia) (📥 18K · ⏱️ 17.05.2022):
	```
	conda install -c conda-forge kornia
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/detectron2">detectron2</a></b> (🥈33 ·  ⭐ 21K) - Detectron2 is a platform for object detection, segmentation.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/facebookresearch/detectron2) (👨‍💻 210 · 🔀 5.4K · 📦 630 · 📋 3K - 5% open · ⏱️ 09.06.2022):

	```
	git clone https://github.com/facebookresearch/detectron2
	```
- [PyPi](https://pypi.org/project/detectron2) (📥 1 / month):
	```
	pip install detectron2
	```
- [Conda](https://anaconda.org/conda-forge/detectron2) (📥 57K · ⏱️ 25.04.2022):
	```
	conda install -c conda-forge detectron2
	```
</details>
<details><summary><b><a href="https://github.com/albumentations-team/albumentations">Albumentations</a></b> (🥈33 ·  ⭐ 10K) - Fast image augmentation library and an easy-to-use wrapper.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/albumentations-team/albumentations) (👨‍💻 100 · 🔀 1.3K · 📦 8.1K · 📋 600 - 41% open · ⏱️ 09.06.2022):

	```
	git clone https://github.com/albumentations-team/albumentations
	```
- [PyPi](https://pypi.org/project/albumentations) (📥 270K / month):
	```
	pip install albumentations
	```
- [Conda](https://anaconda.org/conda-forge/albumentations) (📥 39K · ⏱️ 15.07.2021):
	```
	conda install -c conda-forge albumentations
	```
</details>
<details><summary><b><a href="https://github.com/dmlc/gluon-cv">GluonCV</a></b> (🥈32 ·  ⭐ 5.2K) - Gluon CV Toolkit. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1X" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/dmlc/gluon-cv) (👨‍💻 120 · 🔀 1.2K · 📦 770 · 📋 810 - 5% open · ⏱️ 19.05.2022):

	```
	git clone https://github.com/dmlc/gluon-cv
	```
- [PyPi](https://pypi.org/project/gluoncv) (📥 600K / month):
	```
	pip install gluoncv
	```
</details>
<details><summary><b><a href="https://github.com/emcconville/wand">Wand</a></b> (🥈32 ·  ⭐ 1.2K) - The ctypes-based simple ImageMagick binding for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/emcconville/wand) (👨‍💻 98 · 🔀 190 · 📥 7.6K · 📦 11K · 📋 370 - 4% open · ⏱️ 01.06.2022):

	```
	git clone https://github.com/emcconville/wand
	```
- [PyPi](https://pypi.org/project/wand) (📥 340K / month):
	```
	pip install wand
	```
- [Conda](https://anaconda.org/conda-forge/wand) (📥 12K · ⏱️ 18.05.2022):
	```
	conda install -c conda-forge wand
	```
</details>
<details><summary><b><a href="https://github.com/deepinsight/insightface">InsightFace</a></b> (🥈31 ·  ⭐ 12K) - State-of-the-art 2D and 3D Face Analysis Project. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1X" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/deepinsight/insightface) (👨‍💻 46 · 🔀 3.8K · 📦 170 · 📋 1.9K - 54% open · ⏱️ 31.05.2022):

	```
	git clone https://github.com/deepinsight/insightface
	```
- [PyPi](https://pypi.org/project/insightface) (📥 20K / month):
	```
	pip install insightface
	```
</details>
<details><summary><b><a href="https://github.com/PaddlePaddle/PaddleDetection">PaddleDetection</a></b> (🥈31 ·  ⭐ 7.8K) - Object Detection toolkit based on PaddlePaddle. It.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1M" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PaddlePaddle/PaddleDetection) (👨‍💻 97 · 🔀 2K · 📦 19 · 📋 3.5K - 20% open · ⏱️ 09.06.2022):

	```
	git clone https://github.com/PaddlePaddle/PaddleDetection
	```
- [PyPi](https://pypi.org/project/paddledet) (📥 280 / month):
	```
	pip install paddledet
	```
</details>
<details><summary><b><a href="https://github.com/PaddlePaddle/PaddleSeg">PaddleSeg</a></b> (🥈30 ·  ⭐ 4.9K) - Easy-to-use image segmentation library with awesome pre-.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1M" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PaddlePaddle/PaddleSeg) (👨‍💻 78 · 🔀 1.1K · 📦 570 · 📋 1.1K - 49% open · ⏱️ 06.06.2022):

	```
	git clone https://github.com/PaddlePaddle/PaddleSeg
	```
- [PyPi](https://pypi.org/project/paddleseg) (📥 1.2K / month):
	```
	pip install paddleseg
	```
</details>
<details><summary><b><a href="https://github.com/PyImageSearch/imutils">imutils</a></b> (🥈30 ·  ⭐ 4.1K) - A series of convenience functions to make basic image processing.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/PyImageSearch/imutils) (👨‍💻 21 · 🔀 970 · 📦 26K · 📋 160 - 52% open · ⏱️ 27.01.2022):

	```
	git clone https://github.com/PyImageSearch/imutils
	```
- [PyPi](https://pypi.org/project/imutils) (📥 290K / month):
	```
	pip install imutils
	```
- [Conda](https://anaconda.org/conda-forge/imutils) (📥 87K · ⏱️ 09.12.2021):
	```
	conda install -c conda-forge imutils
	```
</details>
<details><summary><b><a href="https://github.com/JohannesBuchner/imagehash">ImageHash</a></b> (🥈30 ·  ⭐ 2.4K · 💤) - A Python Perceptual Image Hashing Module. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/JohannesBuchner/imagehash) (👨‍💻 20 · 🔀 300 · 📦 5.2K · 📋 110 - 12% open · ⏱️ 07.09.2021):

	```
	git clone https://github.com/JohannesBuchner/imagehash
	```
- [PyPi](https://pypi.org/project/ImageHash) (📥 1.4M / month):
	```
	pip install ImageHash
	```
- [Conda](https://anaconda.org/conda-forge/imagehash) (📥 180K · ⏱️ 15.07.2021):
	```
	conda install -c conda-forge imagehash
	```
</details>
<details><summary><b><a href="https://github.com/ageitgey/face_recognition">Face Recognition</a></b> (🥈29 ·  ⭐ 45K · 💤) - The worlds simplest facial recognition api for Python.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/ageitgey/face_recognition) (👨‍💻 47 · 🔀 12K · 📥 460 · 📋 1.2K - 53% open · ⏱️ 14.06.2021):

	```
	git clone https://github.com/ageitgey/face_recognition
	```
- [PyPi](https://pypi.org/project/face_recognition) (📥 58K / month):
	```
	pip install face_recognition
	```
- [Conda](https://anaconda.org/conda-forge/face_recognition) (📥 7K · ⏱️ 30.04.2021):
	```
	conda install -c conda-forge face_recognition
	```
</details>
<details><summary><b><a href="https://github.com/lucidrains/vit-pytorch">vit-pytorch</a></b> (🥈29 ·  ⭐ 10K) - Implementation of Vision Transformer, a simple way to achieve.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/lucidrains/vit-pytorch) (👨‍💻 15 · 🔀 1.7K · 📦 120 · 📋 180 - 46% open · ⏱️ 04.05.2022):

	```
	git clone https://github.com/lucidrains/vit-pytorch
	```
- [PyPi](https://pypi.org/project/vit-pytorch) (📥 22K / month):
	```
	pip install vit-pytorch
	```
</details>
<details><summary><b><a href="https://github.com/serengil/deepface">deepface</a></b> (🥈28 ·  ⭐ 4K) - A Lightweight Face Recognition and Facial Attribute Analysis (Age, Gender,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/serengil/deepface) (👨‍💻 25 · 🔀 870 · 📦 610 · 📋 460 - 0% open · ⏱️ 26.05.2022):

	```
	git clone https://github.com/serengil/deepface
	```
- [PyPi](https://pypi.org/project/deepface) (📥 34K / month):
	```
	pip install deepface
	```
</details>
<details><summary><b><a href="https://github.com/opencv/opencv-python">opencv-python</a></b> (🥈28 ·  ⭐ 2.8K · 📉) - Automated CI toolchain to produce precompiled opencv-python,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/opencv/opencv-python) (👨‍💻 38 · 🔀 550 · 📋 540 - 6% open · ⏱️ 06.06.2022):

	```
	git clone https://github.com/opencv/opencv-python
	```
- [PyPi](https://pypi.org/project/opencv-python) (📥 5.4M / month):
	```
	pip install opencv-python
	```
</details>
<details><summary><b><a href="https://github.com/obss/sahi">sahi</a></b> (🥈28 ·  ⭐ 1.7K) - A lightweight vision library for performing large scale object detection/.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/obss/sahi) (👨‍💻 13 · 🔀 260 · 📥 540 · 📦 68 · 📋 140 - 7% open · ⏱️ 09.06.2022):

	```
	git clone https://github.com/obss/sahi
	```
- [PyPi](https://pypi.org/project/sahi) (📥 67K / month):
	```
	pip install sahi
	```
- [Conda](https://anaconda.org/conda-forge/sahi) (📥 3.8K · ⏱️ 28.05.2022):
	```
	conda install -c conda-forge sahi
	```
</details>
<details><summary><b><a href="https://github.com/Layout-Parser/layout-parser">layout-parser</a></b> (🥉26 ·  ⭐ 3K) - A Unified Toolkit for Deep Learning Based Document Image.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/Layout-Parser/layout-parser) (👨‍💻 8 · 🔀 290 · 📦 73 · 📋 94 - 48% open · ⏱️ 05.04.2022):

	```
	git clone https://github.com/Layout-Parser/layout-parser
	```
- [PyPi](https://pypi.org/project/layoutparser) (📥 5K / month):
	```
	pip install layoutparser
	```
</details>
<details><summary><b><a href="https://github.com/abhiTronix/vidgear">vidgear</a></b> (🥉26 ·  ⭐ 2.3K) - A High-performance cross-platform Video Processing Python framework.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/abhiTronix/vidgear) (👨‍💻 9 · 🔀 180 · 📥 590 · 📦 210 · 📋 220 - 0% open · ⏱️ 11.02.2022):

	```
	git clone https://github.com/abhiTronix/vidgear
	```
- [PyPi](https://pypi.org/project/vidgear) (📥 6.7K / month):
	```
	pip install vidgear
	```
</details>
<details><summary><b><a href="https://github.com/lightly-ai/lightly">lightly</a></b> (🥉26 ·  ⭐ 1.6K) - A python library for self-supervised learning on images. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/lightly-ai/lightly) (👨‍💻 18 · 🔀 130 · 📦 37 · 📋 320 - 19% open · ⏱️ 09.06.2022):

	```
	git clone https://github.com/lightly-ai/lightly
	```
- [PyPi](https://pypi.org/project/lightly) (📥 3.4K / month):
	```
	pip install lightly
	```
</details>
<details><summary><b><a href="https://github.com/1adrianb/face-alignment">Face Alignment</a></b> (🥉25 ·  ⭐ 5.7K · 💤) - 2D and 3D Face alignment library build using pytorch. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/1adrianb/face-alignment) (👨‍💻 23 · 🔀 1.2K · 📋 270 - 20% open · ⏱️ 04.08.2021):

	```
	git clone https://github.com/1adrianb/face-alignment
	```
- [PyPi](https://pypi.org/project/face-alignment) (📥 10K / month):
	```
	pip install face-alignment
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/mmf">MMF</a></b> (🥉25 ·  ⭐ 4.9K) - A modular framework for vision & language multimodal research from.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/facebookresearch/mmf) (👨‍💻 100 · 🔀 820 · 📦 12 · 📋 620 - 30% open · ⏱️ 04.06.2022):

	```
	git clone https://github.com/facebookresearch/mmf
	```
- [PyPi](https://pypi.org/project/mmf) (📥 460 / month):
	```
	pip install mmf
	```
</details>
<details><summary><b><a href="https://github.com/mdbloice/Augmentor">Augmentor</a></b> (🥉25 ·  ⭐ 4.7K) - Image augmentation library in Python for machine learning. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/mdbloice/Augmentor) (👨‍💻 22 · 🔀 820 · 📦 460 · 📋 180 - 60% open · ⏱️ 24.05.2022):

	```
	git clone https://github.com/mdbloice/Augmentor
	```
- [PyPi](https://pypi.org/project/Augmentor) (📥 19K / month):
	```
	pip install Augmentor
	```
</details>
<details><summary><b><a href="https://github.com/timesler/facenet-pytorch">facenet-pytorch</a></b> (🥉25 ·  ⭐ 2.9K) - Pretrained Pytorch face detection (MTCNN) and facial.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/timesler/facenet-pytorch) (👨‍💻 14 · 🔀 630 · 📥 310K · 📦 790 · 📋 150 - 39% open · ⏱️ 13.12.2021):

	```
	git clone https://github.com/timesler/facenet-pytorch
	```
- [PyPi](https://pypi.org/project/facenet-pytorch) (📥 16K / month):
	```
	pip install facenet-pytorch
	```
</details>
<details><summary><b><a href="https://github.com/ipazc/mtcnn">mtcnn</a></b> (🥉25 ·  ⭐ 1.8K · 💤) - MTCNN face detection implementation for TensorFlow, as a PIP.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/ipazc/mtcnn) (👨‍💻 15 · 🔀 450 · 📦 2.3K · 📋 98 - 61% open · ⏱️ 09.07.2021):

	```
	git clone https://github.com/ipazc/mtcnn
	```
- [PyPi](https://pypi.org/project/mtcnn) (📥 32K / month):
	```
	pip install mtcnn
	```
- [Conda](https://anaconda.org/conda-forge/mtcnn) (📥 4.9K · ⏱️ 17.08.2021):
	```
	conda install -c conda-forge mtcnn
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/pytorchvideo">pytorchvideo</a></b> (🥉24 ·  ⭐ 2.5K) - A deep learning library for video understanding research. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/facebookresearch/pytorchvideo) (👨‍💻 36 · 🔀 260 · 📋 140 - 42% open · ⏱️ 01.06.2022):

	```
	git clone https://github.com/facebookresearch/pytorchvideo
	```
- [PyPi](https://pypi.org/project/pytorchvideo) (📥 16K / month):
	```
	pip install pytorchvideo
	```
</details>
<details><summary><b><a href="https://github.com/libvips/pyvips">pyvips</a></b> (🥉24 ·  ⭐ 410) - python binding for libvips using cffi. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/libvips/pyvips) (👨‍💻 13 · 🔀 38 · 📦 330 · 📋 290 - 37% open · ⏱️ 24.05.2022):

	```
	git clone https://github.com/libvips/pyvips
	```
- [PyPi](https://pypi.org/project/pyvips) (📥 17K / month):
	```
	pip install pyvips
	```
- [Conda](https://anaconda.org/conda-forge/pyvips) (📥 20K · ⏱️ 18.04.2022):
	```
	conda install -c conda-forge pyvips
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/vissl">vissl</a></b> (🥉23 ·  ⭐ 2.7K) - VISSL is FAIRs library of extensible, modular and scalable components.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/facebookresearch/vissl) (👨‍💻 32 · 🔀 270 · 📦 7 · 📋 150 - 33% open · ⏱️ 01.06.2022):

	```
	git clone https://github.com/facebookresearch/vissl
	```
- [PyPi](https://pypi.org/project/vissl) (📥 740 / month):
	```
	pip install vissl
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/ClassyVision">Classy Vision</a></b> (🥉23 ·  ⭐ 1.5K) - An end-to-end PyTorch framework for image and video.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/facebookresearch/ClassyVision) (👨‍💻 76 · 🔀 260 · 📋 76 - 17% open · ⏱️ 06.06.2022):

	```
	git clone https://github.com/facebookresearch/ClassyVision
	```
- [PyPi](https://pypi.org/project/classy_vision) (📥 2.3K / month):
	```
	pip install classy_vision
	```
- [Conda](https://anaconda.org/conda-forge/classy_vision) (📥 13K · ⏱️ 22.03.2022):
	```
	conda install -c conda-forge classy_vision
	```
</details>
<details><summary><b><a href="https://github.com/tryolabs/norfair">Norfair</a></b> (🥉23 ·  ⭐ 1.4K) - Lightweight Python library for adding real-time object tracking to any.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/tryolabs/norfair) (👨‍💻 14 · 🔀 140 · 📥 120 · 📋 54 - 11% open · ⏱️ 08.06.2022):

	```
	git clone https://github.com/tryolabs/norfair
	```
- [PyPi](https://pypi.org/project/norfair) (📥 3.8K / month):
	```
	pip install norfair
	```
</details>
<details><summary><b><a href="https://github.com/airctic/icevision">icevision</a></b> (🥉23 ·  ⭐ 700) - An Agnostic Computer Vision Framework - Pluggable to any Training.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/airctic/icevision) (👨‍💻 39 · 🔀 100 · 📋 540 - 7% open · ⏱️ 29.04.2022):

	```
	git clone https://github.com/airctic/icevision
	```
- [PyPi](https://pypi.org/project/icevision) (📥 3.8K / month):
	```
	pip install icevision
	```
</details>
<details><summary><b><a href="https://github.com/lucidrains/deep-daze">deep-daze</a></b> (🥉22 ·  ⭐ 4.2K) - Simple command line tool for text to image generation using OpenAIs.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/lucidrains/deep-daze) (👨‍💻 14 · 🔀 300 · 📦 39 · 📋 160 - 55% open · ⏱️ 13.03.2022):

	```
	git clone https://github.com/lucidrains/deep-daze
	```
- [PyPi](https://pypi.org/project/deep-daze) (📥 2K / month):
	```
	pip install deep-daze
	```
</details>
<details><summary><b><a href="https://github.com/idealo/image-super-resolution">Image Super-Resolution</a></b> (🥉22 ·  ⭐ 3.6K · 💤) - Super-scale your images and run experiments with.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/idealo/image-super-resolution) (👨‍💻 10 · 🔀 620 · 📦 84 · 📋 200 - 44% open · ⏱️ 02.06.2021):

	```
	git clone https://github.com/idealo/image-super-resolution
	```
- [PyPi](https://pypi.org/project/ISR) (📥 4.4K / month):
	```
	pip install ISR
	```
- [Docker Hub](https://hub.docker.com/r/idealo/image-super-resolution-gpu) (📥 210 · ⏱️ 01.04.2019):
	```
	docker pull idealo/image-super-resolution-gpu
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/graphics">tensorflow-graphics</a></b> (🥉21 ·  ⭐ 2.6K) - TensorFlow Graphics: Differentiable Graphics Layers.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/graphics) (👨‍💻 36 · 🔀 330 · 📋 160 - 45% open · ⏱️ 04.04.2022):

	```
	git clone https://github.com/tensorflow/graphics
	```
- [PyPi](https://pypi.org/project/tensorflow-graphics) (📥 3.9K / month):
	```
	pip install tensorflow-graphics
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/pycls">pycls</a></b> (🥉21 ·  ⭐ 2K) - Codebase for Image Classification Research, written in PyTorch. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/facebookresearch/pycls) (👨‍💻 17 · 🔀 220 · 📦 5 · 📋 77 - 27% open · ⏱️ 03.06.2022):

	```
	git clone https://github.com/facebookresearch/pycls
	```
- [PyPi](https://pypi.org/project/pycls) (📥 1.7K / month):
	```
	pip install pycls
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/detr">DE⫶TR</a></b> (🥉19 ·  ⭐ 8.9K) - End-to-End Object Detection with Transformers. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/facebookresearch/detr) (👨‍💻 25 · 🔀 1.6K · 📋 430 - 36% open · ⏱️ 07.03.2022):

	```
	git clone https://github.com/facebookresearch/detr
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/SlowFast">PySlowFast</a></b> (🥉19 ·  ⭐ 4.8K) - PySlowFast: video understanding codebase from FAIR for.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/facebookresearch/SlowFast) (👨‍💻 27 · 🔀 930 · 📦 7 · 📋 520 - 51% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/facebookresearch/SlowFast
	```
- [PyPi](https://pypi.org/project/pyslowfast) (📥 16 / month):
	```
	pip install pyslowfast
	```
</details>
<details><summary><b><a href="https://github.com/google-research/scenic">scenic</a></b> (🥉19 ·  ⭐ 1K) - Scenic: A Jax Library for Computer Vision Research and Beyond. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://jax.readthedocs.io/en/latest/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/google-research/scenic) (👨‍💻 38 · 🔀 120 · 📦 20 · 📋 41 - 24% open · ⏱️ 09.06.2022):

	```
	git clone https://github.com/google-research/scenic
	```
</details>
<details><summary><b><a href="https://github.com/jasmcaus/caer">Caer</a></b> (🥉17 ·  ⭐ 620 · 💤) - A lightweight Computer Vision library. Scale your models, not boilerplate. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jasmcaus/caer) (👨‍💻 8 · 🔀 69 · 📥 19 · 📋 15 - 13% open · ⏱️ 13.10.2021):

	```
	git clone https://github.com/jasmcaus/caer
	```
- [PyPi](https://pypi.org/project/caer) (📥 3.3K / month):
	```
	pip install caer
	```
</details>
<details><summary>Show 17 hidden projects...</summary>

- <b><a href="https://github.com/scikit-image/scikit-image">scikit-image</a></b> (🥇42 ·  ⭐ 4.9K) - Image processing in Python. <code>❗Unlicensed</code>
- <b><a href="https://github.com/aleju/imgaug">imgaug</a></b> (🥈35 ·  ⭐ 13K · 💀) - Image augmentation for machine learning experiments. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/glfw/glfw">glfw</a></b> (🥈33 ·  ⭐ 9.2K) - A multi-platform library for OpenGL, OpenGL ES, Vulkan, window and input. <code><a href="https://tldrlegal.com/search?q=Zlib">❗️Zlib</a></code>
- <b><a href="https://github.com/OlafenwaMoses/ImageAI">imageai</a></b> (🥈29 ·  ⭐ 7.1K · 💀) - A python library built to empower developers to build applications.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/facebookresearch/pytorch3d">PyTorch3D</a></b> (🥈29 ·  ⭐ 6K) - PyTorch3D is FAIRs library of reusable components for deep.. <code>❗Unlicensed</code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/chainer/chainercv">chainercv</a></b> (🥉27 ·  ⭐ 1.5K · 💀) - ChainerCV: a Library for Deep Learning in Computer Vision. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/qubvel/segmentation_models">segmentation_models</a></b> (🥉24 ·  ⭐ 3.9K · 💀) - Segmentation models with pretrained backbones. Keras.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/luispedro/mahotas">mahotas</a></b> (🥉23 ·  ⭐ 750) - Computer Vision in Python. <code>❗Unlicensed</code>
- <b><a href="https://github.com/idealo/imagededup">Image Deduplicator</a></b> (🥉22 ·  ⭐ 4.1K · 💀) - Finding duplicate images made easy!. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/CellProfiler/CellProfiler">CellProfiler</a></b> (🥉22 ·  ⭐ 680) - An open-source application for biological image analysis. <code>❗Unlicensed</code>
- <b><a href="https://github.com/tryolabs/luminoth">Luminoth</a></b> (🥉21 ·  ⭐ 2.4K · 💀) - Deep Learning toolkit for Computer Vision. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/uploadcare/pillow-simd">Pillow-SIMD</a></b> (🥉21 ·  ⭐ 1.8K · 📉) - The friendly PIL fork. <code><a href="https://tldrlegal.com/search?q=PIL">❗️PIL</a></code>
- <b><a href="https://github.com/hhatto/nude.py">nude.py</a></b> (🥉19 ·  ⭐ 860 · 💀) - Nudity detection with Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/ProvenanceLabs/image-match">image-match</a></b> (🥉18 ·  ⭐ 2.7K · 💤) - Quickly search over billions of images. <code>❗Unlicensed</code>
- <b><a href="https://github.com/Oulu-IMEDS/solt">solt</a></b> (🥉16 ·  ⭐ 260 · 💀) - Streaming over lightweight data transformations. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/qanastek/HugsVision">HugsVision</a></b> (🥉13 ·  ⭐ 160) - HugsVision is a easy to use huggingface wrapper for state-of-the-.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>huggingface</code>
- <b><a href="https://github.com/nicolas-chaulet/torch-points3d">Torch Points 3D</a></b> (🥉12 ·  ⭐ 68 · 🐣) - Pytorch framework for doing deep learning on point.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
</details>
<br>

## Graph Data

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for graph processing, clustering, embedding, and machine learning tasks._

<details><summary><b><a href="https://github.com/dmlc/dgl">dgl</a></b> (🥇35 ·  ⭐ 9.7K) - Python package built to ease deep learning on graph, on top of existing.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/dmlc/dgl) (👨‍💻 210 · 🔀 2.2K · 📦 10 · 📋 1.5K - 10% open · ⏱️ 09.06.2022):

	```
	git clone https://github.com/dmlc/dgl
	```
- [PyPi](https://pypi.org/project/dgl) (📥 26K / month):
	```
	pip install dgl
	```
</details>
<details><summary><b><a href="https://github.com/pyg-team/pytorch_geometric">PyTorch Geometric</a></b> (🥇34 ·  ⭐ 15K) - Graph Neural Network Library for PyTorch. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pyg-team/pytorch_geometric) (👨‍💻 270 · 🔀 2.6K · 📋 2.5K - 36% open · ⏱️ 08.06.2022):

	```
	git clone https://github.com/pyg-team/pytorch_geometric
	```
- [PyPi](https://pypi.org/project/torch-geometric) (📥 85K / month):
	```
	pip install torch-geometric
	```
- [Conda](https://anaconda.org/conda-forge/pytorch_geometric) (📥 6.9K · ⏱️ 16.05.2022):
	```
	conda install -c conda-forge pytorch_geometric
	```
</details>
<details><summary><b><a href="https://github.com/stellargraph/stellargraph">StellarGraph</a></b> (🥈27 ·  ⭐ 2.4K · 💤) - StellarGraph - Machine Learning on Graphs. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/stellargraph/stellargraph) (👨‍💻 36 · 🔀 360 · 📦 140 · 📋 1K - 26% open · ⏱️ 29.10.2021):

	```
	git clone https://github.com/stellargraph/stellargraph
	```
- [PyPi](https://pypi.org/project/stellargraph) (📥 21K / month):
	```
	pip install stellargraph
	```
</details>
<details><summary><b><a href="https://github.com/danielegrattarola/spektral">Spektral</a></b> (🥈27 ·  ⭐ 2.1K) - Graph Neural Networks with Keras and Tensorflow 2. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/danielegrattarola/spektral) (👨‍💻 22 · 🔀 290 · 📦 130 · 📋 220 - 17% open · ⏱️ 07.06.2022):

	```
	git clone https://github.com/danielegrattarola/spektral
	```
- [PyPi](https://pypi.org/project/spektral) (📥 6.6K / month):
	```
	pip install spektral
	```
</details>
<details><summary><b><a href="https://github.com/PaddlePaddle/PGL">Paddle Graph Learning</a></b> (🥈27 ·  ⭐ 1.3K) - Paddle Graph Learning (PGL) is an efficient and.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1M" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PaddlePaddle/PGL) (👨‍💻 26 · 🔀 240 · 📦 26 · 📋 120 - 36% open · ⏱️ 23.05.2022):

	```
	git clone https://github.com/PaddlePaddle/PGL
	```
- [PyPi](https://pypi.org/project/pgl) (📥 4.7K / month):
	```
	pip install pgl
	```
</details>
<details><summary><b><a href="https://github.com/graphistry/pygraphistry">pygraphistry</a></b> (🥈26 ·  ⭐ 1.6K) - PyGraphistry is a Python library to quickly load, shape,.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/graphistry/pygraphistry) (👨‍💻 21 · 🔀 160 · 📦 70 · 📋 210 - 43% open · ⏱️ 12.05.2022):

	```
	git clone https://github.com/graphistry/pygraphistry
	```
- [PyPi](https://pypi.org/project/graphistry) (📥 2.8K / month):
	```
	pip install graphistry
	```
</details>
<details><summary><b><a href="https://github.com/snap-stanford/ogb">ogb</a></b> (🥈26 ·  ⭐ 1.4K) - Benchmark datasets, data loaders, and evaluators for graph machine learning. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/snap-stanford/ogb) (👨‍💻 19 · 🔀 290 · 📦 310 · 📋 210 - 4% open · ⏱️ 14.05.2022):

	```
	git clone https://github.com/snap-stanford/ogb
	```
- [PyPi](https://pypi.org/project/ogb) (📥 11K / month):
	```
	pip install ogb
	```
- [Conda](https://anaconda.org/conda-forge/ogb) (📥 8.4K · ⏱️ 23.02.2022):
	```
	conda install -c conda-forge ogb
	```
</details>
<details><summary><b><a href="https://github.com/benedekrozemberczki/pytorch_geometric_temporal">pytorch_geometric_temporal</a></b> (🥈25 ·  ⭐ 1.6K) - PyTorch Geometric Temporal: Spatiotemporal Signal.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/benedekrozemberczki/pytorch_geometric_temporal) (👨‍💻 21 · 🔀 240 · 📋 110 - 7% open · ⏱️ 24.04.2022):

	```
	git clone https://github.com/benedekrozemberczki/pytorch_geometric_temporal
	```
- [PyPi](https://pypi.org/project/torch-geometric-temporal) (📥 2.1K / month):
	```
	pip install torch-geometric-temporal
	```
</details>
<details><summary><b><a href="https://github.com/pykeen/pykeen">PyKEEN</a></b> (🥈25 ·  ⭐ 870) - A Python library for learning and evaluating knowledge graph embeddings. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pykeen/pykeen) (👨‍💻 29 · 🔀 120 · 📥 140 · 📋 390 - 25% open · ⏱️ 09.06.2022):

	```
	git clone https://github.com/pykeen/pykeen
	```
- [PyPi](https://pypi.org/project/pykeen) (📥 1.6K / month):
	```
	pip install pykeen
	```
</details>
<details><summary><b><a href="https://github.com/graph4ai/graph4nlp">graph4nlp</a></b> (🥈23 ·  ⭐ 1.3K) - Graph4nlp is the library for the easy use of Graph Neural.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/graph4ai/graph4nlp) (👨‍💻 27 · 🔀 160 · 📋 150 - 3% open · ⏱️ 28.05.2022):

	```
	git clone https://github.com/graph4ai/graph4nlp
	```
- [PyPi](https://pypi.org/project/graph4nlp) (📥 120 / month):
	```
	pip install graph4nlp
	```
</details>
<details><summary><b><a href="https://github.com/eliorc/node2vec">Node2Vec</a></b> (🥉21 ·  ⭐ 920) - Implementation of the node2vec algorithm. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/eliorc/node2vec) (👨‍💻 11 · 🔀 200 · 📋 76 - 1% open · ⏱️ 30.04.2022):

	```
	git clone https://github.com/eliorc/node2vec
	```
- [PyPi](https://pypi.org/project/node2vec) (📥 110K / month):
	```
	pip install node2vec
	```
- [Conda](https://anaconda.org/conda-forge/node2vec) (📥 21K · ⏱️ 25.04.2020):
	```
	conda install -c conda-forge node2vec
	```
</details>
<details><summary><b><a href="https://github.com/deepmind/jraph">jraph</a></b> (🥉20 ·  ⭐ 910) - A Graph Neural Network Library in Jax. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://jax.readthedocs.io/en/latest/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/deepmind/jraph) (👨‍💻 16 · 🔀 57 · 📦 20 · 📋 25 - 44% open · ⏱️ 06.06.2022):

	```
	git clone https://github.com/deepmind/jraph
	```
- [PyPi](https://pypi.org/project/jraph) (📥 1.5K / month):
	```
	pip install jraph
	```
- [Conda](https://anaconda.org/conda-forge/jraph) (📥 430 · ⏱️ 31.10.2021):
	```
	conda install -c conda-forge jraph
	```
</details>
<details><summary><b><a href="https://github.com/rusty1s/pytorch_cluster">torch-cluster</a></b> (🥉20 ·  ⭐ 520) - PyTorch Extension Library of Optimized Graph Cluster.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/rusty1s/pytorch_cluster) (👨‍💻 20 · 🔀 96 · 📋 100 - 13% open · ⏱️ 20.04.2022):

	```
	git clone https://github.com/rusty1s/pytorch_cluster
	```
- [PyPi](https://pypi.org/project/torch-cluster) (📥 11K / month):
	```
	pip install torch-cluster
	```
- [Conda](https://anaconda.org/conda-forge/pytorch_cluster) (📥 32K · ⏱️ 06.04.2022):
	```
	conda install -c conda-forge pytorch_cluster
	```
</details>
<details><summary><b><a href="https://github.com/snap-stanford/deepsnap">deepsnap</a></b> (🥉19 ·  ⭐ 420 · 💤) - Python library assists deep learning on graphs. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/snap-stanford/deepsnap) (👨‍💻 15 · 🔀 46 · 📥 8 · 📦 22 · 📋 39 - 38% open · ⏱️ 19.09.2021):

	```
	git clone https://github.com/snap-stanford/deepsnap
	```
- [PyPi](https://pypi.org/project/deepsnap) (📥 420 / month):
	```
	pip install deepsnap
	```
</details>
<details><summary><b><a href="https://github.com/THUMNLab/AutoGL">AutoGL</a></b> (🥉17 ·  ⭐ 800) - An autoML framework & toolkit for machine learning on graphs. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/THUMNLab/AutoGL) (👨‍💻 13 · 🔀 92 · 📋 20 - 30% open · ⏱️ 19.04.2022):

	```
	git clone https://github.com/THUMNLab/AutoGL
	```
- [PyPi](https://pypi.org/project/auto-graph-learning) (📥 1 / month):
	```
	pip install auto-graph-learning
	```
</details>
<details><summary><b><a href="https://github.com/vaticle/kglib">kglib</a></b> (🥉16 ·  ⭐ 510) - Grakn Knowledge Graph Library (ML R&D). <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/vaticle/kglib) (👨‍💻 7 · 🔀 88 · 📥 210 · 📋 59 - 15% open · ⏱️ 08.06.2022):

	```
	git clone https://github.com/vaticle/kglib
	```
- [PyPi](https://pypi.org/project/grakn-kglib) (📥 45 / month):
	```
	pip install grakn-kglib
	```
</details>
<details><summary><b><a href="https://github.com/microsoft/ptgnn">ptgnn</a></b> (🥉13 ·  ⭐ 330) - A PyTorch Graph Neural Network Library. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/microsoft/ptgnn) (👨‍💻 7 · 🔀 39 · 📦 1 · ⏱️ 01.02.2022):

	```
	git clone https://github.com/microsoft/ptgnn
	```
- [PyPi](https://pypi.org/project/ptgnn) (📥 66 / month):
	```
	pip install ptgnn
	```
</details>
<details><summary>Show 19 hidden projects...</summary>

- <b><a href="https://github.com/networkx/networkx">networkx</a></b> (🥇41 ·  ⭐ 11K) - Network Analysis in Python. <code>❗Unlicensed</code>
- <b><a href="https://github.com/igraph/python-igraph">igraph</a></b> (🥇30 ·  ⭐ 980) - Python interface for igraph. <code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code>
- <b><a href="https://github.com/benedekrozemberczki/karateclub">Karate Club</a></b> (🥈25 ·  ⭐ 1.6K) - Karate Club: An API Oriented Open-source Python Framework for.. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
- <b><a href="https://github.com/Accenture/AmpliGraph">AmpliGraph</a></b> (🥈24 ·  ⭐ 1.8K · 💀) - Python library for Representation Learning on Knowledge.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/Kozea/pygal">pygal</a></b> (🥈23 ·  ⭐ 2.5K · 💤) - PYthon svg GrAph plotting Library. <code><a href="http://bit.ly/37RvQcA">❗️LGPL-3.0</a></code>
- <b><a href="https://github.com/facebookresearch/PyTorch-BigGraph">PyTorch-BigGraph</a></b> (🥉22 ·  ⭐ 3.1K) - Generate embeddings from large-scale graph-structured.. <code>❗Unlicensed</code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/divelab/DIG">DIG</a></b> (🥉21 ·  ⭐ 1.1K) - A library for graph deep learning research. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
- <b><a href="https://github.com/phanein/deepwalk">DeepWalk</a></b> (🥉19 ·  ⭐ 2.4K · 💀) - DeepWalk - Deep Learning for Graphs. <code>❗Unlicensed</code>
- <b><a href="https://github.com/IBCNServices/pyRDF2Vec">pyRDF2Vec</a></b> (🥉19 ·  ⭐ 160) - Python Implementation and Extension of RDF2Vec. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/deepmind/graph_nets">graph-nets</a></b> (🥉17 ·  ⭐ 5.1K · 💀) - Build Graph Nets in Tensorflow. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/shenweichen/GraphEmbedding">GraphEmbedding</a></b> (🥉16 ·  ⭐ 2.8K · 💀) - Implementation and experiments of graph embedding.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/alibaba/euler">Euler</a></b> (🥉15 ·  ⭐ 2.8K · 💀) - A distributed graph deep learning framework. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/williamleif/GraphSAGE">GraphSAGE</a></b> (🥉15 ·  ⭐ 2.7K · 💀) - Representation learning on large graphs using stochastic.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/thunlp/OpenNE">OpenNE</a></b> (🥉15 ·  ⭐ 1.6K · 💀) - An Open-Source Package for Network Embedding (NE). <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/gsi-upm/sematch">Sematch</a></b> (🥉15 ·  ⭐ 390 · 💀) - semantic similarity framework for knowledge graph. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/deepgraph/deepgraph">DeepGraph</a></b> (🥉15 ·  ⭐ 250 · 💤) - Analyze Data with Pandas-based Networks... <code>❗Unlicensed</code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/thunlp/OpenKE">OpenKE</a></b> (🥉13 ·  ⭐ 3.1K · 💀) - An Open-Source Package for Knowledge Embedding (KE). <code>❗Unlicensed</code>
- <b><a href="https://github.com/snap-stanford/GraphGym">GraphGym</a></b> (🥉13 ·  ⭐ 1K) - Platform for designing and evaluating Graph Neural Networks (GNN). <code>❗Unlicensed</code>
- <b><a href="https://github.com/DeepGraphLearning/graphvite">GraphVite</a></b> (🥉13 ·  ⭐ 1K · 💀) - GraphVite: A General and High-performance Graph Embedding System. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
</details>
<br>

## Audio Data

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for audio analysis, manipulation, transformation, and extraction, as well as speech recognition and music generation tasks._

<details><summary><b><a href="https://github.com/espnet/espnet">espnet</a></b> (🥇36 ·  ⭐ 5.2K) - End-to-End Speech Processing Toolkit. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/espnet/espnet) (👨‍💻 270 · 🔀 1.5K · 📥 76 · 📦 52 · 📋 1.8K - 15% open · ⏱️ 09.06.2022):

	```
	git clone https://github.com/espnet/espnet
	```
- [PyPi](https://pypi.org/project/espnet) (📥 9.2K / month):
	```
	pip install espnet
	```
</details>
<details><summary><b><a href="https://github.com/mozilla/DeepSpeech">DeepSpeech</a></b> (🥇34 ·  ⭐ 20K · 💤) - DeepSpeech is an open source embedded (offline, on-.. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/mozilla/DeepSpeech) (👨‍💻 160 · 🔀 3.4K · 📥 850K · 📦 760 · 📋 2.1K - 5% open · ⏱️ 17.11.2021):

	```
	git clone https://github.com/mozilla/DeepSpeech
	```
- [PyPi](https://pypi.org/project/deepspeech) (📥 8K / month):
	```
	pip install deepspeech
	```
- [Conda](https://anaconda.org/conda-forge/deepspeech) (📥 570 · ⏱️ 29.07.2021):
	```
	conda install -c conda-forge deepspeech
	```
</details>
<details><summary><b><a href="https://github.com/magenta/magenta">Magenta</a></b> (🥇32 ·  ⭐ 18K) - Magenta: Music and Art Generation with Machine Intelligence. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/magenta/magenta) (👨‍💻 150 · 🔀 3.5K · 📦 360 · 📋 880 - 34% open · ⏱️ 16.04.2022):

	```
	git clone https://github.com/magenta/magenta
	```
- [PyPi](https://pypi.org/project/magenta) (📥 5K / month):
	```
	pip install magenta
	```
</details>
<details><summary><b><a href="https://github.com/speechbrain/speechbrain">speechbrain</a></b> (🥇32 ·  ⭐ 4.1K) - A PyTorch-based Speech Toolkit. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/speechbrain/speechbrain) (👨‍💻 160 · 🔀 770 · 📦 190 · 📋 680 - 21% open · ⏱️ 08.06.2022):

	```
	git clone https://github.com/speechbrain/speechbrain
	```
- [PyPi](https://pypi.org/project/speechbrain) (📥 10K / month):
	```
	pip install speechbrain
	```
</details>
<details><summary><b><a href="https://github.com/jiaaro/pydub">Pydub</a></b> (🥈31 ·  ⭐ 6.2K) - Manipulate audio with a simple and easy high level interface. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jiaaro/pydub) (👨‍💻 92 · 🔀 820 · 📦 13K · 📋 480 - 46% open · ⏱️ 14.05.2022):

	```
	git clone https://github.com/jiaaro/pydub
	```
- [PyPi](https://pypi.org/project/pydub) (📥 1.5M / month):
	```
	pip install pydub
	```
- [Conda](https://anaconda.org/conda-forge/pydub) (📥 24K · ⏱️ 13.03.2021):
	```
	conda install -c conda-forge pydub
	```
</details>
<details><summary><b><a href="https://github.com/pytorch/audio">torchaudio</a></b> (🥈31 ·  ⭐ 1.7K) - Data manipulation and transformation for audio signal.. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytorch/audio) (👨‍💻 160 · 🔀 400 · 📋 600 - 22% open · ⏱️ 08.06.2022):

	```
	git clone https://github.com/pytorch/audio
	```
- [PyPi](https://pypi.org/project/torchaudio) (📥 600K / month):
	```
	pip install torchaudio
	```
</details>
<details><summary><b><a href="https://github.com/librosa/librosa">librosa</a></b> (🥈28 ·  ⭐ 5.2K) - Python library for audio and music analysis. <code><a href="http://bit.ly/3hkKRql">ISC</a></code></summary>

- [GitHub](https://github.com/librosa/librosa) (👨‍💻 97 · 🔀 780 · 📋 980 - 4% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/librosa/librosa
	```
- [PyPi](https://pypi.org/project/librosa) (📥 950K / month):
	```
	pip install librosa
	```
- [Conda](https://anaconda.org/conda-forge/librosa) (📥 470K · ⏱️ 15.02.2022):
	```
	conda install -c conda-forge librosa
	```
</details>
<details><summary><b><a href="https://github.com/Uberi/speech_recognition">SpeechRecognition</a></b> (🥈27 ·  ⭐ 6.3K) - Speech recognition module for Python, supporting several.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/Uberi/speech_recognition) (👨‍💻 45 · 🔀 2K · 📋 510 - 44% open · ⏱️ 26.05.2022):

	```
	git clone https://github.com/Uberi/speech_recognition
	```
- [PyPi](https://pypi.org/project/SpeechRecognition) (📥 280K / month):
	```
	pip install SpeechRecognition
	```
- [Conda](https://anaconda.org/conda-forge/speechrecognition) (📥 140K · ⏱️ 13.12.2021):
	```
	conda install -c conda-forge speechrecognition
	```
</details>
<details><summary><b><a href="https://github.com/coqui-ai/TTS">Coqui TTS</a></b> (🥈27 ·  ⭐ 5K) - - a deep learning toolkit for Text-to-Speech, battle-.. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/coqui-ai/TTS) (👨‍💻 92 · 🔀 510 · 📥 180K · 📋 340 - 5% open · ⏱️ 08.06.2022):

	```
	git clone https://github.com/coqui-ai/TTS
	```
- [PyPi](https://pypi.org/project/tts) (📥 5.1K / month):
	```
	pip install tts
	```
- [Conda](https://anaconda.org/conda-forge/tts) (📥 2.1K · ⏱️ 15.12.2021):
	```
	conda install -c conda-forge tts
	```
</details>
<details><summary><b><a href="https://github.com/beetbox/audioread">audioread</a></b> (🥈27 ·  ⭐ 400) - cross-library (GStreamer + Core Audio + MAD + FFmpeg) audio decoding.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/beetbox/audioread) (👨‍💻 21 · 🔀 94 · 📦 8.6K · 📋 79 - 39% open · ⏱️ 03.12.2021):

	```
	git clone https://github.com/beetbox/audioread
	```
- [PyPi](https://pypi.org/project/audioread) (📥 930K / month):
	```
	pip install audioread
	```
- [Conda](https://anaconda.org/conda-forge/audioread) (📥 440K · ⏱️ 10.04.2022):
	```
	conda install -c conda-forge audioread
	```
</details>
<details><summary><b><a href="https://github.com/deezer/spleeter">spleeter</a></b> (🥉26 ·  ⭐ 20K) - Deezer source separation library including pretrained models. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/deezer/spleeter) (👨‍💻 19 · 🔀 2.2K · 📥 1.7M · 📋 680 - 20% open · ⏱️ 01.04.2022):

	```
	git clone https://github.com/deezer/spleeter
	```
- [PyPi](https://pypi.org/project/spleeter) (📥 13K / month):
	```
	pip install spleeter
	```
- [Conda](https://anaconda.org/conda-forge/spleeter) (📥 65K · ⏱️ 30.06.2020):
	```
	conda install -c conda-forge spleeter
	```
</details>
<details><summary><b><a href="https://github.com/tyiannak/pyAudioAnalysis">pyAudioAnalysis</a></b> (🥉26 ·  ⭐ 4.8K) - Python Audio Analysis Library: Feature Extraction,.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/tyiannak/pyAudioAnalysis) (👨‍💻 26 · 🔀 1.1K · 📦 270 · 📋 280 - 58% open · ⏱️ 19.04.2022):

	```
	git clone https://github.com/tyiannak/pyAudioAnalysis
	```
- [PyPi](https://pypi.org/project/pyAudioAnalysis) (📥 27K / month):
	```
	pip install pyAudioAnalysis
	```
</details>
<details><summary><b><a href="https://github.com/Picovoice/porcupine">Porcupine</a></b> (🥉26 ·  ⭐ 2.7K) - On-device wake word detection powered by deep learning. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/Picovoice/porcupine) (👨‍💻 31 · 🔀 380 · 📦 9 · ⏱️ 27.05.2022):

	```
	git clone https://github.com/Picovoice/Porcupine
	```
- [PyPi](https://pypi.org/project/pvporcupine) (📥 1.4K / month):
	```
	pip install pvporcupine
	```
</details>
<details><summary><b><a href="https://github.com/magenta/ddsp">DDSP</a></b> (🥉26 ·  ⭐ 2.2K) - DDSP: Differentiable Digital Signal Processing. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/magenta/ddsp) (👨‍💻 31 · 🔀 240 · 📦 26 · 📋 130 - 15% open · ⏱️ 16.05.2022):

	```
	git clone https://github.com/magenta/ddsp
	```
- [PyPi](https://pypi.org/project/ddsp) (📥 3.1K / month):
	```
	pip install ddsp
	```
- [Conda](https://anaconda.org/conda-forge/ddsp) (📥 11K · ⏱️ 08.06.2020):
	```
	conda install -c conda-forge ddsp
	```
</details>
<details><summary><b><a href="https://github.com/iver56/audiomentations">audiomentations</a></b> (🥉25 ·  ⭐ 1K) - A Python library for audio data augmentation. Inspired by.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/iver56/audiomentations) (👨‍💻 21 · 🔀 130 · 📦 140 · 📋 120 - 24% open · ⏱️ 09.06.2022):

	```
	git clone https://github.com/iver56/audiomentations
	```
- [PyPi](https://pypi.org/project/audiomentations) (📥 3.8K / month):
	```
	pip install audiomentations
	```
</details>
<details><summary><b><a href="https://github.com/devsnd/tinytag">tinytag</a></b> (🥉25 ·  ⭐ 530) - Read audio and music meta data and duration of MP3, OGG, OPUS, MP4, M4A,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/devsnd/tinytag) (👨‍💻 21 · 🔀 87 · 📦 530 · 📋 91 - 13% open · ⏱️ 15.03.2022):

	```
	git clone https://github.com/devsnd/tinytag
	```
- [PyPi](https://pypi.org/project/tinytag) (📥 92K / month):
	```
	pip install tinytag
	```
</details>
<details><summary><b><a href="https://github.com/keunwoochoi/kapre">kapre</a></b> (🥉23 ·  ⭐ 830) - kapre: Keras Audio Preprocessors. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/keunwoochoi/kapre) (👨‍💻 13 · 🔀 140 · 📥 22 · 📦 1.6K · 📋 94 - 12% open · ⏱️ 21.01.2022):

	```
	git clone https://github.com/keunwoochoi/kapre
	```
- [PyPi](https://pypi.org/project/kapre) (📥 3.5K / month):
	```
	pip install kapre
	```
</details>
<details><summary><b><a href="https://github.com/KinWaiCheuk/nnAudio">nnAudio</a></b> (🥉21 ·  ⭐ 680) - Audio processing by using pytorch 1D convolution network. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/KinWaiCheuk/nnAudio) (👨‍💻 13 · 🔀 66 · 📦 54 · 📋 49 - 24% open · ⏱️ 24.12.2021):

	```
	git clone https://github.com/KinWaiCheuk/nnAudio
	```
- [PyPi](https://pypi.org/project/nnAudio) (📥 33K / month):
	```
	pip install nnAudio
	```
</details>
<details><summary><b><a href="https://github.com/bastibe/python-soundfile">python-soundfile</a></b> (🥉21 ·  ⭐ 450) - SoundFile is an audio library based on libsndfile, CFFI, and.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/bastibe/python-soundfile) (👨‍💻 24 · 🔀 70 · 📥 3.3K · 📋 170 - 39% open · ⏱️ 23.02.2022):

	```
	git clone https://github.com/bastibe/python-soundfile
	```
- [PyPi](https://pypi.org/project/soundfile) (📥 1M / month):
	```
	pip install soundfile
	```
- [Conda](https://anaconda.org/anaconda/pysoundfile):
	```
	conda install -c anaconda pysoundfile
	```
</details>
<details><summary>Show 9 hidden projects...</summary>

- <b><a href="https://github.com/aubio/aubio">aubio</a></b> (🥈28 ·  ⭐ 2.7K) - a library for audio and music analysis. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
- <b><a href="https://github.com/MTG/essentia">Essentia</a></b> (🥈27 ·  ⭐ 2.1K) - C++ library for audio and music analysis, description and.. <code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code>
- <b><a href="https://github.com/CPJKU/madmom">Madmom</a></b> (🥉23 ·  ⭐ 910) - Python audio and music signal processing library. <code>❗Unlicensed</code>
- <b><a href="https://github.com/mozilla/TTS">TTS</a></b> (🥉22 ·  ⭐ 6K · 💀) - Deep learning for Text to Speech (Discussion forum:.. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code>
- <b><a href="https://github.com/jameslyons/python_speech_features">python_speech_features</a></b> (🥉21 ·  ⭐ 2.1K · 💀) - This library provides common speech features for ASR.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/Parisson/TimeSide">TimeSide</a></b> (🥉21 ·  ⭐ 320) - Scalable audio processing framework written in Python with a.. <code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code>
- <b><a href="https://github.com/worldveil/dejavu">Dejavu</a></b> (🥉20 ·  ⭐ 5.8K · 💀) - Audio fingerprinting and recognition in Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/bmcfee/muda">Muda</a></b> (🥉18 ·  ⭐ 210 · 💀) - A library for augmenting annotated audio data. <code><a href="http://bit.ly/3hkKRql">ISC</a></code>
- <b><a href="https://github.com/adefossez/julius">Julius</a></b> (🥉15 ·  ⭐ 270) - Fast PyTorch based DSP for audio and 1D signals. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
</details>
<br>

## Geospatial Data

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries to load, process, analyze, and write geographic data as well as libraries for spatial analysis, map visualization, and geocoding._

<details><summary><b><a href="https://github.com/visgl/deck.gl">pydeck</a></b> (🥇42 ·  ⭐ 9.9K) - WebGL2 powered visualization framework. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/visgl/deck.gl) (👨‍💻 200 · 🔀 1.7K · 📦 4.2K · 📋 2.4K - 6% open · ⏱️ 09.06.2022):

	```
	git clone https://github.com/visgl/deck.gl
	```
- [PyPi](https://pypi.org/project/pydeck) (📥 930K / month):
	```
	pip install pydeck
	```
- [Conda](https://anaconda.org/conda-forge/pydeck) (📥 120K · ⏱️ 26.10.2021):
	```
	conda install -c conda-forge pydeck
	```
- [npm](https://www.npmjs.com/package/deck.gl) (📥 290K / month):
	```
	npm install deck.gl
	```
</details>
<details><summary><b><a href="https://github.com/shapely/shapely">Shapely</a></b> (🥇37 ·  ⭐ 2.8K) - Manipulation and analysis of geometric objects. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/shapely/shapely) (👨‍💻 130 · 🔀 450 · 📥 45 · 📦 30K · 📋 870 - 17% open · ⏱️ 07.06.2022):

	```
	git clone https://github.com/shapely/shapely
	```
- [PyPi](https://pypi.org/project/shapely) (📥 7M / month):
	```
	pip install shapely
	```
- [Conda](https://anaconda.org/conda-forge/shapely) (📥 3.8M · ⏱️ 04.06.2022):
	```
	conda install -c conda-forge shapely
	```
</details>
<details><summary><b><a href="https://github.com/python-visualization/folium">folium</a></b> (🥇35 ·  ⭐ 5.8K) - Python Data. Leaflet.js Maps. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/python-visualization/folium) (👨‍💻 130 · 🔀 2.1K · 📦 16K · 📋 920 - 21% open · ⏱️ 06.05.2022):

	```
	git clone https://github.com/python-visualization/folium
	```
- [PyPi](https://pypi.org/project/folium) (📥 900K / month):
	```
	pip install folium
	```
- [Conda](https://anaconda.org/conda-forge/folium) (📥 820K · ⏱️ 03.12.2021):
	```
	conda install -c conda-forge folium
	```
</details>
<details><summary><b><a href="https://github.com/geopandas/geopandas">GeoPandas</a></b> (🥇35 ·  ⭐ 3.2K) - Python tools for geographic data. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/geopandas/geopandas) (👨‍💻 170 · 🔀 690 · 📥 1.5K · 📦 14K · 📋 1.3K - 26% open · ⏱️ 08.06.2022):

	```
	git clone https://github.com/geopandas/geopandas
	```
- [PyPi](https://pypi.org/project/geopandas) (📥 2.4M / month):
	```
	pip install geopandas
	```
- [Conda](https://anaconda.org/conda-forge/geopandas) (📥 1.6M · ⏱️ 01.12.2021):
	```
	conda install -c conda-forge geopandas
	```
</details>
<details><summary><b><a href="https://github.com/pyproj4/pyproj">pyproj</a></b> (🥇35 ·  ⭐ 760) - Python interface to PROJ (cartographic projections and coordinate.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pyproj4/pyproj) (👨‍💻 49 · 🔀 180 · 📦 15K · 📋 490 - 2% open · ⏱️ 09.06.2022):

	```
	git clone https://github.com/pyproj4/pyproj
	```
- [PyPi](https://pypi.org/project/pyproj) (📥 4.4M / month):
	```
	pip install pyproj
	```
- [Conda](https://anaconda.org/conda-forge/pyproj) (📥 3.5M · ⏱️ 24.04.2022):
	```
	conda install -c conda-forge pyproj
	```
</details>
<details><summary><b><a href="https://github.com/geopy/geopy">geopy</a></b> (🥈34 ·  ⭐ 3.7K) - Geocoding library for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/geopy/geopy) (👨‍💻 130 · 🔀 570 · 📦 39K · 📋 260 - 10% open · ⏱️ 16.05.2022):

	```
	git clone https://github.com/geopy/geopy
	```
- [PyPi](https://pypi.org/project/geopy) (📥 3.6M / month):
	```
	pip install geopy
	```
- [Conda](https://anaconda.org/conda-forge/geopy) (📥 720K · ⏱️ 12.07.2021):
	```
	conda install -c conda-forge geopy
	```
</details>
<details><summary><b><a href="https://github.com/jupyter-widgets/ipyleaflet">ipyleaflet</a></b> (🥈33 ·  ⭐ 1.3K) - A Jupyter - Leaflet.js bridge. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/jupyter-widgets/ipyleaflet) (👨‍💻 78 · 🔀 310 · 📦 1.8K · 📋 480 - 37% open · ⏱️ 24.05.2022):

	```
	git clone https://github.com/jupyter-widgets/ipyleaflet
	```
- [PyPi](https://pypi.org/project/ipyleaflet) (📥 78K / month):
	```
	pip install ipyleaflet
	```
- [Conda](https://anaconda.org/conda-forge/ipyleaflet) (📥 830K · ⏱️ 16.05.2022):
	```
	conda install -c conda-forge ipyleaflet
	```
- [npm](https://www.npmjs.com/package/jupyter-leaflet) (📥 51K / month):
	```
	npm install jupyter-leaflet
	```
</details>
<details><summary><b><a href="https://github.com/Toblerity/Fiona">Fiona</a></b> (🥈33 ·  ⭐ 920) - Fiona reads and writes geographic data files. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/Toblerity/Fiona) (👨‍💻 66 · 🔀 170 · 📦 8.8K · 📋 670 - 10% open · ⏱️ 01.03.2022):

	```
	git clone https://github.com/Toblerity/Fiona
	```
- [PyPi](https://pypi.org/project/fiona) (📥 2.6M / month):
	```
	pip install fiona
	```
- [Conda](https://anaconda.org/conda-forge/fiona) (📥 2.9M · ⏱️ 30.05.2022):
	```
	conda install -c conda-forge fiona
	```
</details>
<details><summary><b><a href="https://github.com/Esri/arcgis-python-api">ArcGIS API</a></b> (🥉29 ·  ⭐ 1.3K) - Documentation and samples for ArcGIS API for Python. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/Esri/arcgis-python-api) (👨‍💻 80 · 🔀 890 · 📥 3.6K · 📋 440 - 6% open · ⏱️ 09.06.2022):

	```
	git clone https://github.com/Esri/arcgis-python-api
	```
- [PyPi](https://pypi.org/project/arcgis) (📥 71K / month):
	```
	pip install arcgis
	```
- [Docker Hub](https://hub.docker.com/r/esridocker/arcgis-api-python-notebook) (📥 7K · ⭐ 34 · ⏱️ 06.06.2022):
	```
	docker pull esridocker/arcgis-api-python-notebook
	```
</details>
<details><summary><b><a href="https://github.com/jazzband/geojson">geojson</a></b> (🥉28 ·  ⭐ 720) - Python bindings and utilities for GeoJSON. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jazzband/geojson) (👨‍💻 48 · 🔀 90 · 📦 9.4K · 📋 84 - 26% open · ⏱️ 07.05.2022):

	```
	git clone https://github.com/jazzband/geojson
	```
- [PyPi](https://pypi.org/project/geojson) (📥 800K / month):
	```
	pip install geojson
	```
- [Conda](https://anaconda.org/conda-forge/geojson) (📥 510K · ⏱️ 11.08.2019):
	```
	conda install -c conda-forge geojson
	```
</details>
<details><summary><b><a href="https://github.com/earthlab/earthpy">EarthPy</a></b> (🥉26 ·  ⭐ 370) - A package built to support working with spatial data using open source.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/earthlab/earthpy) (👨‍💻 40 · 🔀 140 · 📦 150 · 📋 220 - 8% open · ⏱️ 20.12.2021):

	```
	git clone https://github.com/earthlab/earthpy
	```
- [PyPi](https://pypi.org/project/earthpy) (📥 8.6K / month):
	```
	pip install earthpy
	```
- [Conda](https://anaconda.org/conda-forge/earthpy) (📥 44K · ⏱️ 04.10.2021):
	```
	conda install -c conda-forge earthpy
	```
</details>
<details><summary><b><a href="https://github.com/pysal/pysal">PySAL</a></b> (🥉25 ·  ⭐ 1K) - PySAL: Python Spatial Analysis Library Meta-Package. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/pysal/pysal) (👨‍💻 75 · 🔀 260 · 📋 610 - 1% open · ⏱️ 30.01.2022):

	```
	git clone https://github.com/pysal/pysal
	```
- [PyPi](https://pypi.org/project/pysal) (📥 20K / month):
	```
	pip install pysal
	```
- [Conda](https://anaconda.org/conda-forge/pysal) (📥 440K · ⏱️ 31.01.2022):
	```
	conda install -c conda-forge pysal
	```
</details>
<details><summary><b><a href="https://github.com/holoviz/geoviews">GeoViews</a></b> (🥉23 ·  ⭐ 410) - Simple, concise geographical visualization in Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/holoviz/geoviews) (👨‍💻 27 · 🔀 65 · 📋 300 - 33% open · ⏱️ 30.05.2022):

	```
	git clone https://github.com/holoviz/geoviews
	```
- [PyPi](https://pypi.org/project/geoviews) (📥 9.8K / month):
	```
	pip install geoviews
	```
- [Conda](https://anaconda.org/conda-forge/geoviews) (📥 110K · ⏱️ 08.03.2022):
	```
	conda install -c conda-forge geoviews
	```
</details>
<details><summary>Show 9 hidden projects...</summary>

- <b><a href="https://github.com/rasterio/rasterio">Rasterio</a></b> (🥈34 ·  ⭐ 1.7K) - Rasterio reads and writes geospatial raster datasets. <code>❗Unlicensed</code>
- <b><a href="https://github.com/DenisCarriere/geocoder">Geocoder</a></b> (🥉32 ·  ⭐ 1.4K · 💀) - Python Geocoder. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/pytroll/satpy">Satpy</a></b> (🥉30 ·  ⭐ 840) - Python package for earth-observing satellite data processing. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
- <b><a href="https://github.com/sentinelsat/sentinelsat">Sentinelsat</a></b> (🥉28 ·  ⭐ 770) - Search and download Copernicus Sentinel satellite images. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
- <b><a href="https://github.com/mapbox/mapboxgl-jupyter">Mapbox GL</a></b> (🥉23 ·  ⭐ 610 · 💀) - Use Mapbox GL JS to visualize data in a Python Jupyter notebook. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/pbugnion/gmaps">gmaps</a></b> (🥉20 ·  ⭐ 740 · 💀) - Google maps for Jupyter notebooks. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/andrea-cuttone/geoplotlib">geoplotlib</a></b> (🥉19 ·  ⭐ 960 · 💀) - python toolbox for visualizing geographical data and making maps. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/geospace-code/pymap3d">pymap3d</a></b> (🥉19 ·  ⭐ 250) - pure-Python (Numpy optional) 3D coordinate conversions for geospace ecef.. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code>
- <b><a href="https://github.com/marceloprates/prettymaps">prettymaps</a></b> (🥉16 ·  ⭐ 8K) - A small set of Python functions to draw pretty maps from.. <code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code>
</details>
<br>

## Financial Data

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for algorithmic stock/crypto trading, risk analytics, backtesting, technical analysis, and other tasks on financial data._

<details><summary><b><a href="https://github.com/ranaroussi/yfinance">yfinance</a></b> (🥇34 ·  ⭐ 7.1K) - Download market data from Yahoo! Finances API. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/ranaroussi/yfinance) (👨‍💻 53 · 🔀 1.5K · 📦 12K · 📋 790 - 56% open · ⏱️ 30.01.2022):

	```
	git clone https://github.com/ranaroussi/yfinance
	```
- [PyPi](https://pypi.org/project/yfinance) (📥 350K / month):
	```
	pip install yfinance
	```
- [Conda](https://anaconda.org/ranaroussi/yfinance) (📥 44K · ⏱️ 10.07.2021):
	```
	conda install -c ranaroussi yfinance
	```
</details>
<details><summary><b><a href="https://github.com/microsoft/qlib">Qlib</a></b> (🥇32 ·  ⭐ 8.7K) - Qlib is an AI-oriented quantitative investment platform, which aims to.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/microsoft/qlib) (👨‍💻 94 · 🔀 1.5K · 📥 280 · 📦 20 · 📋 540 - 27% open · ⏱️ 09.06.2022):

	```
	git clone https://github.com/microsoft/qlib
	```
- [PyPi](https://pypi.org/project/pyqlib) (📥 2.8K / month):
	```
	pip install pyqlib
	```
</details>
<details><summary><b><a href="https://github.com/bukosabino/ta">ta</a></b> (🥈28 ·  ⭐ 3K) - Technical Analysis Library using Pandas and Numpy. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/bukosabino/ta) (👨‍💻 28 · 🔀 690 · 📦 1.2K · 📋 200 - 50% open · ⏱️ 24.04.2022):

	```
	git clone https://github.com/bukosabino/ta
	```
- [PyPi](https://pypi.org/project/ta) (📥 71K / month):
	```
	pip install ta
	```
- [Conda](https://anaconda.org/conda-forge/ta) (📥 3.4K · ⏱️ 21.04.2022):
	```
	conda install -c conda-forge ta
	```
</details>
<details><summary><b><a href="https://github.com/pmorissette/ffn">ffn</a></b> (🥈27 ·  ⭐ 1.2K) - ffn - a financial function library for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pmorissette/ffn) (👨‍💻 26 · 🔀 200 · 📦 200 · 📋 97 - 17% open · ⏱️ 01.06.2022):

	```
	git clone https://github.com/pmorissette/ffn
	```
- [PyPi](https://pypi.org/project/ffn) (📥 30K / month):
	```
	pip install ffn
	```
- [Conda](https://anaconda.org/conda-forge/ffn) (📥 910 · ⏱️ 22.04.2021):
	```
	conda install -c conda-forge ffn
	```
</details>
<details><summary><b><a href="https://github.com/pmorissette/bt">bt</a></b> (🥈26 ·  ⭐ 1.4K) - bt - flexible backtesting for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pmorissette/bt) (👨‍💻 25 · 🔀 310 · 📦 110 · 📋 290 - 20% open · ⏱️ 26.05.2022):

	```
	git clone https://github.com/pmorissette/bt
	```
- [PyPi](https://pypi.org/project/bt) (📥 4.4K / month):
	```
	pip install bt
	```
- [Conda](https://anaconda.org/conda-forge/bt) (📥 4.6K · ⏱️ 18.01.2022):
	```
	conda install -c conda-forge bt
	```
</details>
<details><summary><b><a href="https://github.com/tensortrade-org/tensortrade">TensorTrade</a></b> (🥉25 ·  ⭐ 3.9K) - An open source reinforcement learning framework for training,.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/tensortrade-org/tensortrade) (👨‍💻 61 · 🔀 880 · 📦 36 · 📋 230 - 15% open · ⏱️ 02.03.2022):

	```
	git clone https://github.com/tensortrade-org/tensortrade
	```
- [PyPi](https://pypi.org/project/tensortrade) (📥 610 / month):
	```
	pip install tensortrade
	```
- [Conda](https://anaconda.org/conda-forge/tensortrade) (📥 1.1K · ⏱️ 10.05.2021):
	```
	conda install -c conda-forge tensortrade
	```
</details>
<details><summary><b><a href="https://github.com/RomelTorres/alpha_vantage">Alpha Vantage</a></b> (🥉24 ·  ⭐ 3.7K · 💤) - A python wrapper for Alpha Vantage API for financial data. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/RomelTorres/alpha_vantage) (👨‍💻 39 · 🔀 640 · 📋 260 - 2% open · ⏱️ 14.06.2021):

	```
	git clone https://github.com/RomelTorres/alpha_vantage
	```
- [PyPi](https://pypi.org/project/alpha_vantage) (📥 15K / month):
	```
	pip install alpha_vantage
	```
- [Conda](https://anaconda.org/conda-forge/alpha_vantage) (📥 1.3K · ⏱️ 14.01.2021):
	```
	conda install -c conda-forge alpha_vantage
	```
</details>
<details><summary><b><a href="https://github.com/google/tf-quant-finance">tf-quant-finance</a></b> (🥉24 ·  ⭐ 3.1K) - High-performance TensorFlow library for quantitative.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/google/tf-quant-finance) (👨‍💻 39 · 🔀 410 · 📋 39 - 35% open · ⏱️ 08.06.2022):

	```
	git clone https://github.com/google/tf-quant-finance
	```
- [PyPi](https://pypi.org/project/tf-quant-finance) (📥 1.6K / month):
	```
	pip install tf-quant-finance
	```
</details>
<details><summary><b><a href="https://github.com/scrtlabs/catalyst">Enigma Catalyst</a></b> (🥉23 ·  ⭐ 2.3K · 💤) - An Algorithmic Trading Library for Crypto-Assets in.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/scrtlabs/catalyst) (👨‍💻 150 · 🔀 690 · 📦 25 · 📋 480 - 25% open · ⏱️ 22.09.2021):

	```
	git clone https://github.com/scrtlabs/catalyst
	```
- [PyPi](https://pypi.org/project/enigma-catalyst) (📥 530 / month):
	```
	pip install enigma-catalyst
	```
</details>
<details><summary><b><a href="https://github.com/erdewit/ib_insync">IB-insync</a></b> (🥉23 ·  ⭐ 1.8K) - Python sync/async framework for Interactive Brokers API. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/erdewit/ib_insync) (👨‍💻 30 · 🔀 480 · 📋 410 - 1% open · ⏱️ 20.05.2022):

	```
	git clone https://github.com/erdewit/ib_insync
	```
- [PyPi](https://pypi.org/project/ib_insync) (📥 7.4K / month):
	```
	pip install ib_insync
	```
- [Conda](https://anaconda.org/conda-forge/ib-insync) (📥 16K · ⏱️ 29.11.2021):
	```
	conda install -c conda-forge ib-insync
	```
</details>
<details><summary><b><a href="https://github.com/CryptoSignal/Crypto-Signal">Crypto Signals</a></b> (🥉22 ·  ⭐ 4K · 💤) - Github.com/CryptoSignal - #1 Quant Trading & Technical.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/CryptoSignal/Crypto-Signal) (👨‍💻 28 · 🔀 1K · 📋 260 - 19% open · ⏱️ 28.06.2021):

	```
	git clone https://github.com/CryptoSignal/crypto-signal
	```
- [Docker Hub](https://hub.docker.com/r/shadowreaver/crypto-signal) (📥 140K · ⭐ 7 · ⏱️ 03.09.2020):
	```
	docker pull shadowreaver/crypto-signal
	```
</details>
<details><summary><b><a href="https://github.com/cuemacro/finmarketpy">finmarketpy</a></b> (🥉19 ·  ⭐ 2.9K) - Python library for backtesting trading strategies & analyzing.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/cuemacro/finmarketpy) (👨‍💻 14 · 🔀 430 · 📥 40 · 📦 5 · 📋 26 - 88% open · ⏱️ 05.04.2022):

	```
	git clone https://github.com/cuemacro/finmarketpy
	```
- [PyPi](https://pypi.org/project/finmarketpy) (📥 130 / month):
	```
	pip install finmarketpy
	```
</details>
<details><summary>Show 13 hidden projects...</summary>

- <b><a href="https://github.com/quantopian/zipline">zipline</a></b> (🥇32 ·  ⭐ 15K · 💀) - Zipline, a Pythonic Algorithmic Trading Library. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/quantopian/pyfolio">pyfolio</a></b> (🥈29 ·  ⭐ 4.4K · 💀) - Portfolio and risk analytics in Python. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/mementum/backtrader">backtrader</a></b> (🥈28 ·  ⭐ 8.8K · 💤) - Python Backtesting library for trading strategies. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
- <b><a href="https://github.com/bashtage/arch">arch</a></b> (🥈28 ·  ⭐ 930) - ARCH models in Python. <code>❗Unlicensed</code>
- <b><a href="https://github.com/quantopian/alphalens">Alphalens</a></b> (🥈27 ·  ⭐ 2.3K · 💀) - Performance analysis of predictive (alpha) stock factors. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/quantopian/empyrical">empyrical</a></b> (🥈26 ·  ⭐ 930 · 💀) - Common financial risk and performance metrics. Used by zipline.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/gbeced/pyalgotrade">PyAlgoTrade</a></b> (🥉24 ·  ⭐ 3.7K · 💀) - Python Algorithmic Trading Library. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/peerchemist/finta">FinTA</a></b> (🥉24 ·  ⭐ 1.6K · 💤) - Common financial technical indicators implemented in Pandas. <code><a href="http://bit.ly/37RvQcA">❗️LGPL-3.0</a></code>
- <b><a href="https://github.com/jealous/stockstats">stockstats</a></b> (🥉22 ·  ⭐ 1K) - Supply a wrapper ``StockDataFrame`` based on the.. <code>❗Unlicensed</code>
- <b><a href="https://github.com/kernc/backtesting.py">Backtesting.py</a></b> (🥉18 ·  ⭐ 2.5K) - Backtest trading strategies in Python. <code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code>
- <b><a href="https://github.com/fmilthaler/FinQuant">FinQuant</a></b> (🥉17 ·  ⭐ 770 · 💀) - A program for financial portfolio management, analysis and.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/tradytics/surpriver">surpriver</a></b> (🥉12 ·  ⭐ 1.5K · 💀) - Find big moving stocks before they move using machine.. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
- <b><a href="https://github.com/alvarobartt/pyrtfolio">pyrtfolio</a></b> (🥉8 ·  ⭐ 110 · 💀) - Python package to generate stock portfolios. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
</details>
<br>

## Time Series Data

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for forecasting, anomaly detection, feature extraction, and machine learning on time-series and sequential data._

<details><summary><b><a href="https://github.com/alan-turing-institute/sktime">sktime</a></b> (🥇35 ·  ⭐ 5.4K) - A unified framework for machine learning with time series. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/alan-turing-institute/sktime) (👨‍💻 170 · 🔀 850 · 📥 76 · 📦 460 · 📋 1.1K - 31% open · ⏱️ 09.06.2022):

	```
	git clone https://github.com/alan-turing-institute/sktime
	```
- [PyPi](https://pypi.org/project/sktime) (📥 190K / month):
	```
	pip install sktime
	```
- [Conda](https://anaconda.org/conda-forge/sktime-all-extras) (📥 5K · ⏱️ 18.05.2022):
	```
	conda install -c conda-forge sktime-all-extras
	```
</details>
<details><summary><b><a href="https://github.com/alkaline-ml/pmdarima">pmdarima</a></b> (🥇33 ·  ⭐ 1.2K) - A statistical library designed to fill the void in Pythons time series.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/alkaline-ml/pmdarima) (👨‍💻 21 · 🔀 210 · 📦 2.2K · 📋 280 - 8% open · ⏱️ 09.06.2022):

	```
	git clone https://github.com/alkaline-ml/pmdarima
	```
- [PyPi](https://pypi.org/project/pmdarima) (📥 1.2M / month):
	```
	pip install pmdarima
	```
- [Conda](https://anaconda.org/conda-forge/pmdarima) (📥 41K · ⏱️ 24.02.2022):
	```
	conda install -c conda-forge pmdarima
	```
</details>
<details><summary><b><a href="https://github.com/TDAmeritrade/stumpy">STUMPY</a></b> (🥇32 ·  ⭐ 2.3K · 📈) - STUMPY is a powerful and scalable Python library for modern time.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/TDAmeritrade/stumpy) (👨‍💻 30 · 🔀 220 · 📦 220 · 📋 320 - 10% open · ⏱️ 07.06.2022):

	```
	git clone https://github.com/TDAmeritrade/stumpy
	```
- [PyPi](https://pypi.org/project/stumpy) (📥 320K / month):
	```
	pip install stumpy
	```
- [Conda](https://anaconda.org/conda-forge/stumpy) (📥 40K · ⏱️ 31.03.2022):
	```
	conda install -c conda-forge stumpy
	```
</details>
<details><summary><b><a href="https://github.com/facebook/prophet">Prophet</a></b> (🥈31 ·  ⭐ 15K) - Tool for producing high quality forecasts for time series data that has.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/facebook/prophet) (👨‍💻 150 · 🔀 4.1K · 📥 650 · 📋 1.8K - 11% open · ⏱️ 25.05.2022):

	```
	git clone https://github.com/facebook/prophet
	```
- [PyPi](https://pypi.org/project/fbprophet) (📥 1.5M / month):
	```
	pip install fbprophet
	```
- [Conda](https://anaconda.org/conda-forge/prophet) (📥 51K · ⏱️ 23.08.2021):
	```
	conda install -c conda-forge prophet
	```
</details>
<details><summary><b><a href="https://github.com/ourownstory/neural_prophet">NeuralProphet</a></b> (🥈30 ·  ⭐ 2.3K) - NeuralProphet: A simple forecasting package. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/ourownstory/neural_prophet) (👨‍💻 21 · 🔀 290 · 📦 87 · 📋 250 - 22% open · ⏱️ 31.05.2022):

	```
	git clone https://github.com/ourownstory/neural_prophet
	```
- [PyPi](https://pypi.org/project/neuralprophet) (📥 70K / month):
	```
	pip install neuralprophet
	```
</details>
<details><summary><b><a href="https://github.com/jdb78/pytorch-forecasting">pytorch-forecasting</a></b> (🥈30 ·  ⭐ 2K) - Time series forecasting with PyTorch. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jdb78/pytorch-forecasting) (👨‍💻 29 · 🔀 320 · 📋 470 - 46% open · ⏱️ 08.06.2022):

	```
	git clone https://github.com/jdb78/pytorch-forecasting
	```
- [PyPi](https://pypi.org/project/pytorch-forecasting) (📥 68K / month):
	```
	pip install pytorch-forecasting
	```
- [Conda](https://anaconda.org/conda-forge/pytorch-forecasting) (📥 20K · ⏱️ 23.05.2022):
	```
	conda install -c conda-forge pytorch-forecasting
	```
</details>
<details><summary><b><a href="https://github.com/tslearn-team/tslearn">tslearn</a></b> (🥈29 ·  ⭐ 2.1K) - A machine learning toolkit dedicated to time-series data. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tslearn-team/tslearn) (👨‍💻 37 · 🔀 280 · 📦 500 · 📋 270 - 30% open · ⏱️ 09.06.2022):

	```
	git clone https://github.com/tslearn-team/tslearn
	```
- [PyPi](https://pypi.org/project/tslearn) (📥 100K / month):
	```
	pip install tslearn
	```
- [Conda](https://anaconda.org/conda-forge/tslearn) (📥 260K · ⏱️ 15.01.2022):
	```
	conda install -c conda-forge tslearn
	```
</details>
<details><summary><b><a href="https://github.com/unit8co/darts">Darts</a></b> (🥈28 ·  ⭐ 4.1K) - A python library for easy manipulation and forecasting of time series. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/unit8co/darts) (👨‍💻 53 · 🔀 420 · 📦 62 · 📋 480 - 35% open · ⏱️ 08.06.2022):

	```
	git clone https://github.com/unit8co/darts
	```
- [PyPi](https://pypi.org/project/u8darts) (📥 7.5K / month):
	```
	pip install u8darts
	```
- [Conda](https://anaconda.org/conda-forge/u8darts-all) (📥 5.1K · ⏱️ 14.04.2022):
	```
	conda install -c conda-forge u8darts-all
	```
- [Docker Hub](https://hub.docker.com/r/unit8/darts) (📥 340 · ⏱️ 13.04.2022):
	```
	docker pull unit8/darts
	```
</details>
<details><summary><b><a href="https://github.com/awslabs/gluon-ts">GluonTS</a></b> (🥈27 ·  ⭐ 2.7K) - Probabilistic time series modeling in Python. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1X" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/awslabs/gluon-ts) (👨‍💻 87 · 🔀 550 · 📋 670 - 34% open · ⏱️ 08.06.2022):

	```
	git clone https://github.com/awslabs/gluon-ts
	```
- [PyPi](https://pypi.org/project/gluonts) (📥 92K / month):
	```
	pip install gluonts
	```
- [Conda](https://anaconda.org/anaconda/gluonts) (📥 52 · ⏱️ 14.10.2021):
	```
	conda install -c anaconda gluonts
	```
</details>
<details><summary><b><a href="https://github.com/blue-yonder/tsfresh">tsfresh</a></b> (🥈26 ·  ⭐ 6.4K) - Automatic extraction of relevant features from time series:. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/blue-yonder/tsfresh) (👨‍💻 82 · 🔀 980 · 📋 480 - 9% open · ⏱️ 21.12.2021):

	```
	git clone https://github.com/blue-yonder/tsfresh
	```
- [PyPi](https://pypi.org/project/tsfresh) (📥 500K / month):
	```
	pip install tsfresh
	```
- [Conda](https://anaconda.org/conda-forge/tsfresh) (📥 170K · ⏱️ 21.12.2021):
	```
	conda install -c conda-forge tsfresh
	```
</details>
<details><summary><b><a href="https://github.com/johannfaouzi/pyts">pyts</a></b> (🥈25 ·  ⭐ 1.3K) - A Python package for time series classification. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/johannfaouzi/pyts) (👨‍💻 11 · 🔀 130 · 📦 210 · 📋 61 - 57% open · ⏱️ 02.03.2022):

	```
	git clone https://github.com/johannfaouzi/pyts
	```
- [PyPi](https://pypi.org/project/pyts) (📥 150K / month):
	```
	pip install pyts
	```
- [Conda](https://anaconda.org/conda-forge/pyts) (📥 11K · ⏱️ 31.10.2021):
	```
	conda install -c conda-forge pyts
	```
</details>
<details><summary><b><a href="https://github.com/python-streamz/streamz">Streamz</a></b> (🥉23 ·  ⭐ 1.1K) - Real-time stream processing for python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/python-streamz/streamz) (👨‍💻 45 · 🔀 130 · 📦 300 · 📋 240 - 39% open · ⏱️ 24.12.2021):

	```
	git clone https://github.com/python-streamz/streamz
	```
- [PyPi](https://pypi.org/project/streamz) (📥 16K / month):
	```
	pip install streamz
	```
- [Conda](https://anaconda.org/conda-forge/streamz) (📥 310K · ⏱️ 04.10.2021):
	```
	conda install -c conda-forge streamz
	```
</details>
<details><summary><b><a href="https://github.com/Nixtla/statsforecast">StatsForecast</a></b> (🥉22 ·  ⭐ 700) - Lightning fast forecasting with statistical and econometric models. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/Nixtla/statsforecast) (👨‍💻 9 · 🔀 42 · 📋 47 - 40% open · ⏱️ 01.06.2022):

	```
	git clone https://github.com/Nixtla/statsforecast
	```
- [PyPi](https://pypi.org/project/statsforecast) (📥 45K / month):
	```
	pip install statsforecast
	```
- [Conda](https://anaconda.org/conda-forge/statsforecast) (📥 5.1K · ⏱️ 09.05.2022):
	```
	conda install -c conda-forge statsforecast
	```
</details>
<details><summary><b><a href="https://github.com/Nixtla/neuralforecast">NeuralForecast</a></b> (🥉21 ·  ⭐ 740) - Scalable and user friendly neural forecasting algorithms for time.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/Nixtla/neuralforecast) (👨‍💻 22 · 🔀 66 · 📋 83 - 43% open · ⏱️ 09.06.2022):

	```
	git clone https://github.com/Nixtla/neuralforecast
	```
- [PyPi](https://pypi.org/project/neuralforecast) (📥 400 / month):
	```
	pip install neuralforecast
	```
- [Conda](https://anaconda.org/conda-forge/neuralforecast) (📥 410 · ⏱️ 03.06.2022):
	```
	conda install -c conda-forge neuralforecast
	```
</details>
<details><summary><b><a href="https://github.com/linkedin/greykite">greykite</a></b> (🥉19 ·  ⭐ 1.5K) - A flexible, intuitive and fast forecasting library. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/linkedin/greykite) (👨‍💻 7 · 🔀 68 · 📦 9 · 📋 62 - 14% open · ⏱️ 15.12.2021):

	```
	git clone https://github.com/linkedin/greykite
	```
- [PyPi](https://pypi.org/project/greykite) (📥 31K / month):
	```
	pip install greykite
	```
</details>
<details><summary><b><a href="https://github.com/fraunhoferportugal/tsfel">TSFEL</a></b> (🥉19 ·  ⭐ 510) - An intuitive library to extract features from time series. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/fraunhoferportugal/tsfel) (👨‍💻 14 · 🔀 68 · 📦 36 · 📋 50 - 14% open · ⏱️ 16.03.2022):

	```
	git clone https://github.com/fraunhoferportugal/tsfel
	```
- [PyPi](https://pypi.org/project/tsfel) (📥 4.1K / month):
	```
	pip install tsfel
	```
</details>
<details><summary><b><a href="https://github.com/AutoViML/Auto_TS">Auto TS</a></b> (🥉17 ·  ⭐ 440) - Automatically build ARIMA, SARIMAX, VAR, FB Prophet and XGBoost.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/AutoViML/Auto_TS) (👨‍💻 6 · 🔀 83 · 📋 71 - 12% open · ⏱️ 13.02.2022):

	```
	git clone https://github.com/AutoViML/Auto_TS
	```
- [PyPi](https://pypi.org/project/auto-ts) (📥 1.4K / month):
	```
	pip install auto-ts
	```
</details>
<details><summary>Show 9 hidden projects...</summary>

- <b><a href="https://github.com/RJT1990/pyflux">PyFlux</a></b> (🥉23 ·  ⭐ 2K · 💀) - Open source time series library for Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/X-DataInitiative/tick">tick</a></b> (🥉21 ·  ⭐ 380 · 💀) - Module for statistical learning, with a particular emphasis on time-.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/linkedin/luminol">luminol</a></b> (🥉19 ·  ⭐ 1K · 💀) - Anomaly Detection and Correlation library. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/arundo/adtk">ADTK</a></b> (🥉19 ·  ⭐ 830 · 💀) - A Python toolkit for rule-based/unsupervised anomaly detection in time.. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code>
- <b><a href="https://github.com/dmbee/seglearn">seglearn</a></b> (🥉19 ·  ⭐ 520 · 💀) - Python module for machine learning time series:. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/wwrechard/pydlm">pydlm</a></b> (🥉18 ·  ⭐ 420 · 💀) - A python library for Bayesian time series modeling. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/target/matrixprofile-ts">matrixprofile-ts</a></b> (🥉17 ·  ⭐ 680 · 💀) - A Python library for detecting patterns and anomalies.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/arundo/tsaug">tsaug</a></b> (🥉14 ·  ⭐ 240 · 💀) - A Python package for time series augmentation. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/firmai/atspy">atspy</a></b> (🥉13 ·  ⭐ 450) - AtsPy: Automated Time Series Models in Python (by @firmai). <code>❗Unlicensed</code>
</details>
<br>

## Medical Data

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for processing and analyzing medical data such as MRIs, EEGs, genomic data, and other medical imaging formats._

<details><summary><b><a href="https://github.com/mne-tools/mne-python">MNE</a></b> (🥇36 ·  ⭐ 1.9K) - MNE: Magnetoencephalography (MEG) and Electroencephalography (EEG) in Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/mne-tools/mne-python) (👨‍💻 290 · 🔀 1K · 📦 1.7K · 📋 4.1K - 9% open · ⏱️ 08.06.2022):

	```
	git clone https://github.com/mne-tools/mne-python
	```
- [PyPi](https://pypi.org/project/mne) (📥 42K / month):
	```
	pip install mne
	```
- [Conda](https://anaconda.org/conda-forge/mne) (📥 200K · ⏱️ 04.06.2022):
	```
	conda install -c conda-forge mne
	```
</details>
<details><summary><b><a href="https://github.com/nipy/nipype">NIPYPE</a></b> (🥇34 ·  ⭐ 630) - Workflows and interfaces for neuroimaging packages. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/nipy/nipype) (👨‍💻 240 · 🔀 450 · 📦 940 · 📋 1.3K - 28% open · ⏱️ 06.06.2022):

	```
	git clone https://github.com/nipy/nipype
	```
- [PyPi](https://pypi.org/project/nipype) (📥 50K / month):
	```
	pip install nipype
	```
- [Conda](https://anaconda.org/conda-forge/nipype) (📥 480K · ⏱️ 06.06.2022):
	```
	conda install -c conda-forge nipype
	```
</details>
<details><summary><b><a href="https://github.com/Project-MONAI/MONAI">MONAI</a></b> (🥈33 ·  ⭐ 3.1K) - AI Toolkit for Healthcare Imaging. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/Project-MONAI/MONAI) (👨‍💻 98 · 🔀 590 · 📦 330 · 📋 1.7K - 10% open · ⏱️ 08.06.2022):

	```
	git clone https://github.com/Project-MONAI/MONAI
	```
- [PyPi](https://pypi.org/project/monai) (📥 46K / month):
	```
	pip install monai
	```
- [Conda](https://anaconda.org/conda-forge/monai) (📥 940 · ⏱️ 27.05.2022):
	```
	conda install -c conda-forge monai
	```
</details>
<details><summary><b><a href="https://github.com/CamDavidsonPilon/lifelines">Lifelines</a></b> (🥈33 ·  ⭐ 1.9K) - Survival analysis in Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/CamDavidsonPilon/lifelines) (👨‍💻 100 · 🔀 460 · 📦 920 · 📋 860 - 25% open · ⏱️ 24.05.2022):

	```
	git clone https://github.com/CamDavidsonPilon/lifelines
	```
- [PyPi](https://pypi.org/project/lifelines) (📥 350K / month):
	```
	pip install lifelines
	```
- [Conda](https://anaconda.org/conda-forge/lifelines) (📥 190K · ⏱️ 18.05.2022):
	```
	conda install -c conda-forge lifelines
	```
</details>
<details><summary><b><a href="https://github.com/hail-is/hail">Hail</a></b> (🥈33 ·  ⭐ 800) - Scalable genomic data analysis. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/hail-is/hail) (👨‍💻 79 · 🔀 210 · 📦 68 · 📋 2K - 0% open · ⏱️ 08.06.2022):

	```
	git clone https://github.com/hail-is/hail
	```
- [PyPi](https://pypi.org/project/hail) (📥 23K / month):
	```
	pip install hail
	```
</details>
<details><summary><b><a href="https://github.com/google/deepvariant">DeepVariant</a></b> (🥉27 ·  ⭐ 2.5K · 📈) - DeepVariant is an analysis pipeline that uses a deep.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/google/deepvariant) (👨‍💻 24 · 🔀 610 · 📥 4K · 📋 490 - 0% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/google/deepvariant
	```
- [Conda](https://anaconda.org/bioconda/deepvariant) (📥 41K · ⏱️ 05.06.2022):
	```
	conda install -c bioconda deepvariant
	```
</details>
<details><summary><b><a href="https://github.com/MIC-DKFZ/medicaldetectiontoolkit">Medical Detection Toolkit</a></b> (🥉14 ·  ⭐ 1.1K) - The Medical Detection Toolkit contains 2D + 3D.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/MIC-DKFZ/medicaldetectiontoolkit) (👨‍💻 3 · 🔀 280 · 📋 120 - 30% open · ⏱️ 04.04.2022):

	```
	git clone https://github.com/MIC-DKFZ/medicaldetectiontoolkit
	```
</details>
<details><summary>Show 12 hidden projects...</summary>

- <b><a href="https://github.com/nilearn/nilearn">Nilearn</a></b> (🥈33 ·  ⭐ 870) - Machine learning for NeuroImaging in Python. <code>❗Unlicensed</code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/nipy/nibabel">NiBabel</a></b> (🥈30 ·  ⭐ 480) - Python package to access a cacophony of neuro-imaging file formats. <code>❗Unlicensed</code>
- <b><a href="https://github.com/dipy/dipy">DIPY</a></b> (🥈28 ·  ⭐ 520) - DIPY is the paragon 3D/4D+ imaging library in Python. Contains.. <code>❗Unlicensed</code>
- <b><a href="https://github.com/NifTK/NiftyNet">NiftyNet</a></b> (🥉25 ·  ⭐ 1.3K · 💀) - [unmaintained] An open-source convolutional neural.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/loli/medpy">MedPy</a></b> (🥉22 ·  ⭐ 410 · 💀) - Medical image processing in Python. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
- <b><a href="https://github.com/projectglow/glow">Glow</a></b> (🥉22 ·  ⭐ 200) - An open-source toolkit for large-scale genomic analysis. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/DLTK/DLTK">DLTK</a></b> (🥉20 ·  ⭐ 1.3K · 💀) - Deep Learning Toolkit for Medical Image Analysis. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/nipy/nipy">NIPY</a></b> (🥉19 ·  ⭐ 320 · 💀) - Neuroimaging in Python FMRI analysis package. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/brainiak/brainiak">Brainiak</a></b> (🥉19 ·  ⭐ 280 · 💀) - Brain Imaging Analysis Kit. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/perone/medicaltorch">MedicalTorch</a></b> (🥉15 ·  ⭐ 780 · 💀) - A medical imaging framework for Pytorch. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/Tencent/MedicalNet">MedicalNet</a></b> (🥉13 ·  ⭐ 1.4K · 💀) - Many studies have shown that the performance on deep learning is.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/QTIM-Lab/DeepNeuro">DeepNeuro</a></b> (🥉11 ·  ⭐ 110 · 💀) - A deep learning python package for neuroimaging data. Made by:. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
</details>
<br>

## Tabular Data

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for processing tabular and structured data._

<details><summary><b><a href="https://github.com/carefree0910/carefree-learn">carefree-learn</a></b> (🥈20 ·  ⭐ 360) - Deep Learning PyTorch. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/carefree0910/carefree-learn) (🔀 27 · 📦 2 · ⏱️ 07.06.2022):

	```
	git clone https://github.com/carefree0910/carefree-learn
	```
- [PyPi](https://pypi.org/project/carefree-learn) (📥 110 / month):
	```
	pip install carefree-learn
	```
</details>
<details><summary><b><a href="https://github.com/manujosephv/pytorch_tabular">pytorch_tabular</a></b> (🥉18 ·  ⭐ 600) - A standard framework for modelling Deep Learning Models.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/manujosephv/pytorch_tabular) (👨‍💻 10 · 🔀 63 · 📋 61 - 27% open · ⏱️ 07.06.2022):

	```
	git clone https://github.com/manujosephv/pytorch_tabular
	```
- [PyPi](https://pypi.org/project/pytorch_tabular) (📥 1.3K / month):
	```
	pip install pytorch_tabular
	```
</details>
<details><summary>Show 3 hidden projects...</summary>

- <b><a href="https://github.com/AnotherSamWilson/miceforest">miceforest</a></b> (🥇21 ·  ⭐ 160) - Multiple Imputation with Random Forests in Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/upgini/upgini">upgini</a></b> (🥉14 ·  ⭐ 28 · 🐣) - Low-code feature search library for supervised machine learning.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/firmai/deltapy">deltapy</a></b> (🥉8 ·  ⭐ 430) - DeltaPy - Tabular Data Augmentation (by @firmai). <code>❗Unlicensed</code>
</details>
<br>

## Optical Character Recognition

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for optical character recognition (OCR) and text extraction from images or videos._

<details><summary><b><a href="https://github.com/PaddlePaddle/PaddleOCR">PaddleOCR</a></b> (🥇38 ·  ⭐ 23K) - Awesome multilingual OCR toolkits based on PaddlePaddle.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1M" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PaddlePaddle/PaddleOCR) (👨‍💻 100 · 🔀 4.5K · 📦 670 · 📋 4.6K - 22% open · ⏱️ 08.06.2022):

	```
	git clone https://github.com/PaddlePaddle/PaddleOCR
	```
- [PyPi](https://pypi.org/project/paddleocr) (📥 65K / month):
	```
	pip install paddleocr
	```
</details>
<details><summary><b><a href="https://github.com/JaidedAI/EasyOCR">EasyOCR</a></b> (🥇35 ·  ⭐ 15K) - Ready-to-use OCR with 80+ supported languages and all popular writing.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/JaidedAI/EasyOCR) (👨‍💻 100 · 🔀 2K · 📥 1.7M · 📦 1.2K · 📋 570 - 21% open · ⏱️ 03.06.2022):

	```
	git clone https://github.com/JaidedAI/EasyOCR
	```
- [PyPi](https://pypi.org/project/easyocr) (📥 110K / month):
	```
	pip install easyocr
	```
</details>
<details><summary><b><a href="https://github.com/sirfz/tesserocr">tesserocr</a></b> (🥈29 ·  ⭐ 1.6K · 💤) - A Python wrapper for the tesseract-ocr API. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/sirfz/tesserocr) (👨‍💻 26 · 🔀 210 · 📦 670 · 📋 240 - 31% open · ⏱️ 09.11.2021):

	```
	git clone https://github.com/sirfz/tesserocr
	```
- [PyPi](https://pypi.org/project/tesserocr) (📥 61K / month):
	```
	pip install tesserocr
	```
- [Conda](https://anaconda.org/conda-forge/tesserocr) (📥 72K · ⏱️ 04.05.2022):
	```
	conda install -c conda-forge tesserocr
	```
</details>
<details><summary><b><a href="https://github.com/madmaze/pytesseract">Tesseract</a></b> (🥈28 ·  ⭐ 4.2K) - Python-tesseract is an optical character recognition (OCR) tool.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/madmaze/pytesseract) (👨‍💻 40 · 🔀 590 · 📋 300 - 4% open · ⏱️ 10.05.2022):

	```
	git clone https://github.com/madmaze/pytesseract
	```
- [PyPi](https://pypi.org/project/pytesseract) (📥 620K / month):
	```
	pip install pytesseract
	```
- [Conda](https://anaconda.org/conda-forge/pytesseract) (📥 510K · ⏱️ 15.03.2022):
	```
	conda install -c conda-forge pytesseract
	```
</details>
<details><summary><b><a href="https://github.com/open-mmlab/mmocr">MMOCR</a></b> (🥈28 ·  ⭐ 2.5K) - OpenMMLab Text Detection, Recognition and Understanding Toolbox. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/open-mmlab/mmocr) (👨‍💻 51 · 🔀 450 · 📦 13 · 📋 550 - 13% open · ⏱️ 09.06.2022):

	```
	git clone https://github.com/open-mmlab/mmocr
	```
- [PyPi](https://pypi.org/project/mmocr) (📥 2K / month):
	```
	pip install mmocr
	```
</details>
<details><summary><b><a href="https://github.com/ocrmypdf/OCRmyPDF">OCRmyPDF</a></b> (🥉26 ·  ⭐ 6.5K) - OCRmyPDF adds an OCR text layer to scanned PDF files, allowing them.. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code></summary>

- [GitHub](https://github.com/ocrmypdf/OCRmyPDF) (👨‍💻 69 · 🔀 570 · 📋 870 - 10% open · ⏱️ 08.06.2022):

	```
	git clone https://github.com/ocrmypdf/OCRmyPDF
	```
- [PyPi](https://pypi.org/project/ocrmypdf) (📥 27K / month):
	```
	pip install ocrmypdf
	```
- [Conda](https://anaconda.org/conda-forge/ocrmypdf) (📥 12K · ⏱️ 03.06.2022):
	```
	conda install -c conda-forge ocrmypdf
	```
</details>
<details><summary><b><a href="https://github.com/faustomorales/keras-ocr">keras-ocr</a></b> (🥉21 ·  ⭐ 1K) - A packaged and flexible version of the CRAFT text detector and.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/faustomorales/keras-ocr) (👨‍💻 15 · 🔀 260 · 📥 270K · 📋 170 - 38% open · ⏱️ 19.05.2022):

	```
	git clone https://github.com/faustomorales/keras-ocr
	```
- [PyPi](https://pypi.org/project/keras-ocr) (📥 6.8K / month):
	```
	pip install keras-ocr
	```
- [Conda](https://anaconda.org/anaconda/keras-ocr) (📥 65 · ⏱️ 14.01.2022):
	```
	conda install -c anaconda keras-ocr
	```
</details>
<details><summary><b><a href="https://github.com/Calamari-OCR/calamari">calamari</a></b> (🥉21 ·  ⭐ 920) - Line based ATR Engine based on OCRopy. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/Calamari-OCR/calamari) (👨‍💻 19 · 🔀 190 · 📋 250 - 20% open · ⏱️ 24.05.2022):

	```
	git clone https://github.com/Calamari-OCR/calamari
	```
- [PyPi](https://pypi.org/project/calamari_ocr) (📥 590 / month):
	```
	pip install calamari_ocr
	```
</details>
<details><summary><b><a href="https://github.com/emedvedev/attention-ocr">attention-ocr</a></b> (🥉21 ·  ⭐ 910 · 💤) - A Tensorflow model for text recognition (CNN + seq2seq.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/emedvedev/attention-ocr) (👨‍💻 27 · 🔀 240 · 📦 19 · 📋 150 - 16% open · ⏱️ 29.10.2021):

	```
	git clone https://github.com/emedvedev/attention-ocr
	```
- [PyPi](https://pypi.org/project/aocr) (📥 210 / month):
	```
	pip install aocr
	```
</details>
<details><summary><b><a href="https://github.com/WZBSocialScienceCenter/pdftabextract">pdftabextract</a></b> (🥉17 ·  ⭐ 2K) - A set of tools for extracting tables from PDF files helping to.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/WZBSocialScienceCenter/pdftabextract) (👨‍💻 2 · 🔀 340 · 📦 39 · 📋 21 - 14% open · ⏱️ 07.03.2022):

	```
	git clone https://github.com/WZBSocialScienceCenter/pdftabextract
	```
- [PyPi](https://pypi.org/project/pdftabextract) (📥 550 / month):
	```
	pip install pdftabextract
	```
</details>
<details><summary>Show 2 hidden projects...</summary>

- <b><a href="https://github.com/jlsutherland/doc2text">doc2text</a></b> (🥉17 ·  ⭐ 1.3K · 💀) - Detect text blocks and OCR poorly scanned PDFs in bulk. Python.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/aashrafh/Mozart">Mozart</a></b> (🥉10 ·  ⭐ 370 · 💀) - An optical music recognition (OMR) system. Converts sheet.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code>
</details>
<br>

## Data Containers & Structures

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_General-purpose data containers & structures as well as utilities & extensions for pandas._

<br>

## Data Loading & Extraction

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for loading, collecting, and extracting data from a variety of data sources and formats._

🔗&nbsp;<b><a href="https://github.com/ml-tooling/best-of-python#data-loading--extraction">best-of-python - Data Extraction</a></b> ( ⭐ 2.2K)  - Collection of data-loading and -extraction libraries.

🔗&nbsp;<b><a href="https://github.com/ml-tooling/best-of-python#data-containers--dataframes">best-of-python - Data Containers</a></b> ( ⭐ 2.2K)  - Collection of data-container, dataframe, and pandas-..

<br>

## Web Scraping & Crawling

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for web scraping, crawling, downloading, and mining as well as libraries._

🔗&nbsp;<b><a href="https://github.com/ml-tooling/best-of-web-python#web-scraping--crawling">best-of-web-python - Web Scraping</a></b> ( ⭐ 1.6K)  - Collection of web-scraping and crawling libraries.

<br>

## Data Pipelines & Streaming

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for data batch- and stream-processing, workflow automation, job scheduling, and other data pipeline tasks._

<details><summary><b><a href="https://github.com/apache/airflow">Airflow</a></b> (🥇41 ·  ⭐ 27K) - Platform to programmatically author, schedule, and monitor workflows. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/apache/airflow) (👨‍💻 2.4K · 🔀 10K · 📥 300K · 📋 5.6K - 13% open · ⏱️ 09.06.2022):

	```
	git clone https://github.com/apache/airflow
	```
- [PyPi](https://pypi.org/project/apache-airflow) (📥 6.8M / month):
	```
	pip install apache-airflow
	```
- [Conda](https://anaconda.org/conda-forge/airflow) (📥 630K · ⏱️ 04.06.2022):
	```
	conda install -c conda-forge airflow
	```
- [Docker Hub](https://hub.docker.com/r/apache/airflow) (📥 74M · ⭐ 340 · ⏱️ 04.06.2022):
	```
	docker pull apache/airflow
	```
</details>
<details><summary><b><a href="https://github.com/apache/beam">Beam</a></b> (🥇38 ·  ⭐ 5.6K) - Unified programming model to define and execute data processing.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/apache/beam) (👨‍💻 1.3K · 🔀 3.4K · 📋 3.9K - 95% open · ⏱️ 09.06.2022):

	```
	git clone https://github.com/apache/beam
	```
- [PyPi](https://pypi.org/project/apache-beam) (📥 6.9M / month):
	```
	pip install apache-beam
	```
- [Conda](https://anaconda.org/conda-forge/apache-beam-with-aws) (📥 12K · ⏱️ 27.05.2022):
	```
	conda install -c conda-forge apache-beam-with-aws
	```
</details>
<details><summary><b><a href="https://github.com/spotify/luigi">luigi</a></b> (🥇37 ·  ⭐ 16K) - Luigi is a Python module that helps you build complex pipelines of batch.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/spotify/luigi) (👨‍💻 590 · 🔀 2.2K · 📦 1.8K · 📋 940 - 7% open · ⏱️ 04.06.2022):

	```
	git clone https://github.com/spotify/luigi
	```
- [PyPi](https://pypi.org/project/luigi) (📥 570K / month):
	```
	pip install luigi
	```
- [Conda](https://anaconda.org/anaconda/luigi) (📥 10K · ⏱️ 02.05.2022):
	```
	conda install -c anaconda luigi
	```
</details>
<details><summary><b><a href="https://github.com/PrefectHQ/prefect">Prefect</a></b> (🥇37 ·  ⭐ 9.2K) - The easiest way to automate your data. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/PrefectHQ/prefect) (👨‍💻 330 · 🔀 900 · 📦 840 · 📋 2.3K - 23% open · ⏱️ 07.06.2022):

	```
	git clone https://github.com/PrefectHQ/prefect
	```
- [PyPi](https://pypi.org/project/prefect) (📥 250K / month):
	```
	pip install prefect
	```
- [Conda](https://anaconda.org/conda-forge/prefect) (📥 270K · ⏱️ 28.04.2022):
	```
	conda install -c conda-forge prefect
	```
</details>
<details><summary><b><a href="https://github.com/dagster-io/dagster">Dagster</a></b> (🥇37 ·  ⭐ 4.8K) - An orchestration platform for the development, production, and.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/dagster-io/dagster) (👨‍💻 210 · 🔀 600 · 📦 400 · 📋 4.1K - 22% open · ⏱️ 09.06.2022):

	```
	git clone https://github.com/dagster-io/dagster
	```
- [PyPi](https://pypi.org/project/dagster) (📥 330K / month):
	```
	pip install dagster
	```
- [Conda](https://anaconda.org/conda-forge/dagster) (📥 530K · ⏱️ 03.06.2022):
	```
	conda install -c conda-forge dagster
	```
</details>
<details><summary><b><a href="https://github.com/dbt-labs/dbt-core">dbt</a></b> (🥈36 ·  ⭐ 5K) - dbt enables data analysts and engineers to transform their data using the.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/dbt-labs/dbt-core) (👨‍💻 220 · 🔀 900 · 📥 380 · 📦 510 · 📋 2.8K - 10% open · ⏱️ 08.06.2022):

	```
	git clone https://github.com/dbt-labs/dbt-core
	```
- [PyPi](https://pypi.org/project/dbt) (📥 760K / month):
	```
	pip install dbt
	```
- [Conda](https://anaconda.org/conda-forge/dbt) (📥 200K · ⏱️ 09.12.2021):
	```
	conda install -c conda-forge dbt
	```
</details>
<details><summary><b><a href="https://github.com/joblib/joblib">joblib</a></b> (🥈36 ·  ⭐ 2.8K) - Computing with Python functions. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/joblib/joblib) (👨‍💻 110 · 🔀 320 · 📦 190K · 📋 700 - 42% open · ⏱️ 20.05.2022):

	```
	git clone https://github.com/joblib/joblib
	```
- [PyPi](https://pypi.org/project/joblib) (📥 26M / month):
	```
	pip install joblib
	```
- [Conda](https://anaconda.org/conda-forge/joblib) (📥 9.2M · ⏱️ 07.10.2021):
	```
	conda install -c conda-forge joblib
	```
</details>
<details><summary><b><a href="https://github.com/kedro-org/kedro">Kedro</a></b> (🥈35 ·  ⭐ 7.3K) - A Python framework for creating reproducible, maintainable and modular.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/kedro-org/kedro) (👨‍💻 150 · 🔀 660 · 📦 890 · 📋 770 - 13% open · ⏱️ 09.06.2022):

	```
	git clone https://github.com/kedro-org/kedro
	```
- [PyPi](https://pypi.org/project/kedro) (📥 370K / month):
	```
	pip install kedro
	```
</details>
<details><summary><b><a href="https://github.com/great-expectations/great_expectations">Great Expectations</a></b> (🥈35 ·  ⭐ 6.7K) - Always know what to expect from your data. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/great-expectations/great_expectations) (👨‍💻 300 · 🔀 960 · 📋 1.3K - 12% open · ⏱️ 08.06.2022):

	```
	git clone https://github.com/great-expectations/great_expectations
	```
- [PyPi](https://pypi.org/project/great_expectations) (📥 7.4M / month):
	```
	pip install great_expectations
	```
- [Conda](https://anaconda.org/conda-forge/great-expectations) (📥 390K · ⏱️ 03.06.2022):
	```
	conda install -c conda-forge great-expectations
	```
</details>
<details><summary><b><a href="https://github.com/petl-developers/petl">petl</a></b> (🥈31 ·  ⭐ 1K) - Python Extract Transform and Load Tables of Data. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/petl-developers/petl) (👨‍💻 55 · 🔀 180 · 📦 730 · 📋 440 - 16% open · ⏱️ 08.06.2022):

	```
	git clone https://github.com/petl-developers/petl
	```
- [PyPi](https://pypi.org/project/petl) (📥 190K / month):
	```
	pip install petl
	```
- [Conda](https://anaconda.org/conda-forge/petl) (📥 77K · ⏱️ 08.06.2022):
	```
	conda install -c conda-forge petl
	```
</details>
<details><summary><b><a href="https://github.com/coleifer/huey">huey</a></b> (🥈30 ·  ⭐ 4.1K) - a little task queue for python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/coleifer/huey) (👨‍💻 66 · 🔀 340 · 📦 940 · ⏱️ 31.05.2022):

	```
	git clone https://github.com/coleifer/huey
	```
- [PyPi](https://pypi.org/project/huey) (📥 160K / month):
	```
	pip install huey
	```
- [Conda](https://anaconda.org/conda-forge/huey) (📥 24K · ⏱️ 16.10.2019):
	```
	conda install -c conda-forge huey
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/tfx">TFX</a></b> (🥈29 ·  ⭐ 1.8K) - TFX is an end-to-end platform for deploying production ML pipelines. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/tfx) (👨‍💻 140 · 🔀 560 · 📋 750 - 29% open · ⏱️ 09.06.2022):

	```
	git clone https://github.com/tensorflow/tfx
	```
- [PyPi](https://pypi.org/project/tfx) (📥 320K / month):
	```
	pip install tfx
	```
</details>
<details><summary><b><a href="https://github.com/activeloopai/Hub">Activeloop</a></b> (🥈28 ·  ⭐ 4.6K) - Dataset format for AI. Build, manage, query & visualize datasets.. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code></summary>

- [GitHub](https://github.com/activeloopai/Hub) (👨‍💻 98 · 🔀 380 · 📋 360 - 12% open · ⏱️ 08.06.2022):

	```
	git clone https://github.com/activeloopai/Hub
	```
- [PyPi](https://pypi.org/project/hub) (📥 5.5K / month):
	```
	pip install hub
	```
</details>
<details><summary><b><a href="https://github.com/ploomber/ploomber">ploomber</a></b> (🥈28 ·  ⭐ 2.4K) - The fastest way to build data pipelines. Develop iteratively,.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/ploomber/ploomber) (👨‍💻 52 · 🔀 160 · 📦 42 · 📋 720 - 28% open · ⏱️ 07.06.2022):

	```
	git clone https://github.com/ploomber/ploomber
	```
- [PyPi](https://pypi.org/project/ploomber) (📥 5.8K / month):
	```
	pip install ploomber
	```
- [Conda](https://anaconda.org/conda-forge/ploomber) (📥 9.3K · ⏱️ 02.06.2022):
	```
	conda install -c conda-forge ploomber
	```
</details>
<details><summary><b><a href="https://github.com/combust/mleap">mleap</a></b> (🥈28 ·  ⭐ 1.4K) - MLeap: Deploy ML Pipelines to Production. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/combust/mleap) (👨‍💻 73 · 🔀 290 · 📦 190 · 📋 440 - 19% open · ⏱️ 03.05.2022):

	```
	git clone https://github.com/combust/mleap
	```
- [PyPi](https://pypi.org/project/mleap) (📥 250K / month):
	```
	pip install mleap
	```
- [Conda](https://anaconda.org/conda-forge/mleap) (📥 47K · ⏱️ 05.04.2022):
	```
	conda install -c conda-forge mleap
	```
</details>
<details><summary><b><a href="https://github.com/zenml-io/zenml">zenml</a></b> (🥉27 ·  ⭐ 2.1K) - ZenML : Build portable, production-ready MLOps pipelines... <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/zenml-io/zenml) (👨‍💻 32 · 🔀 160 · 📋 83 - 16% open · ⏱️ 30.05.2022):

	```
	git clone https://github.com/zenml-io/zenml
	```
- [PyPi](https://pypi.org/project/zenml) (📥 1.5K / month):
	```
	pip install zenml
	```
</details>
<details><summary><b><a href="https://github.com/hi-primus/optimus">Optimus</a></b> (🥉27 ·  ⭐ 1.2K) - Agile Data Preparation Workflows madeeasy with Pandas, Dask,.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/hi-primus/optimus) (👨‍💻 23 · 🔀 210 · 📋 230 - 13% open · ⏱️ 06.06.2022):

	```
	git clone https://github.com/hi-primus/optimus
	```
- [PyPi](https://pypi.org/project/optimuspyspark) (📥 41K / month):
	```
	pip install optimuspyspark
	```
</details>
<details><summary><b><a href="https://github.com/EntilZha/PyFunctional">PyFunctional</a></b> (🥉26 ·  ⭐ 2K) - Python library for creating data pipelines with chain functional.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/EntilZha/PyFunctional) (👨‍💻 25 · 🔀 110 · 📦 440 · 📋 130 - 5% open · ⏱️ 04.06.2022):

	```
	git clone https://github.com/EntilZha/PyFunctional
	```
- [PyPi](https://pypi.org/project/pyfunctional) (📥 170K / month):
	```
	pip install pyfunctional
	```
</details>
<details><summary><b><a href="https://github.com/Parsely/streamparse">streamparse</a></b> (🥉26 ·  ⭐ 1.5K) - Run Python in Apache Storm topologies. Pythonic API, CLI.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/Parsely/streamparse) (👨‍💻 42 · 🔀 210 · 📦 55 · 📋 320 - 19% open · ⏱️ 10.01.2022):

	```
	git clone https://github.com/Parsely/streamparse
	```
- [PyPi](https://pypi.org/project/streamparse) (📥 4.2K / month):
	```
	pip install streamparse
	```
</details>
<details><summary><b><a href="https://github.com/whylabs/whylogs">whylogs</a></b> (🥉25 ·  ⭐ 1.3K) - Open standard for end-to-end data and ML monitoring for any scale in.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/whylabs/whylogs) (👨‍💻 9 · 🔀 60 · 📥 50 · 📋 150 - 25% open · ⏱️ 09.06.2022):

	```
	git clone https://github.com/whylabs/whylogs
	```
- [PyPi](https://pypi.org/project/whylogs) (📥 22K / month):
	```
	pip install whylogs
	```
</details>
<details><summary><b><a href="https://github.com/samuelcolvin/arq">arq</a></b> (🥉25 ·  ⭐ 1.2K) - Fast job queuing and RPC in python with asyncio and redis. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/samuelcolvin/arq) (👨‍💻 39 · 🔀 100 · 📦 230 · 📋 140 - 26% open · ⏱️ 28.03.2022):

	```
	git clone https://github.com/samuelcolvin/arq
	```
- [PyPi](https://pypi.org/project/arq) (📥 23K / month):
	```
	pip install arq
	```
- [Conda](https://anaconda.org/conda-forge/arq) (📥 2.3K · ⏱️ 03.09.2021):
	```
	conda install -c conda-forge arq
	```
</details>
<details><summary><b><a href="https://github.com/closeio/tasktiger">TaskTiger</a></b> (🥉23 ·  ⭐ 1.1K) - Python task queue using Redis. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/closeio/tasktiger) (👨‍💻 24 · 🔀 61 · 📦 22 · 📋 57 - 38% open · ⏱️ 25.04.2022):

	```
	git clone https://github.com/closeio/tasktiger
	```
- [PyPi](https://pypi.org/project/tasktiger) (📥 1.4K / month):
	```
	pip install tasktiger
	```
</details>
<details><summary><b><a href="https://github.com/cgarciae/pypeln">Pypeline</a></b> (🥉22 ·  ⭐ 1.3K) - Concurrent data pipelines in Python . <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/cgarciae/pypeln) (👨‍💻 12 · 🔀 80 · 📋 58 - 25% open · ⏱️ 06.01.2022):

	```
	git clone https://github.com/cgarciae/pypeln
	```
- [PyPi](https://pypi.org/project/pypeln) (📥 12K / month):
	```
	pip install pypeln
	```
- [Conda](https://anaconda.org/conda-forge/pypeln) (📥 6.8K · ⏱️ 06.01.2022):
	```
	conda install -c conda-forge pypeln
	```
</details>
<details><summary><b><a href="https://github.com/pdpipe/pdpipe">pdpipe</a></b> (🥉21 ·  ⭐ 670) - Easy pipelines for pandas DataFrames. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pdpipe/pdpipe) (👨‍💻 10 · 🔀 37 · 📦 41 · 📋 45 - 28% open · ⏱️ 07.06.2022):

	```
	git clone https://github.com/pdpipe/pdpipe
	```
- [PyPi](https://pypi.org/project/pdpipe) (📥 1.8K / month):
	```
	pip install pdpipe
	```
- [Conda](https://anaconda.org/conda-forge/pdpipe) (📥 4.9K · ⏱️ 18.05.2022):
	```
	conda install -c conda-forge pdpipe
	```
</details>
<details><summary><b><a href="https://github.com/databricks/spark-deep-learning">spark-deep-learning</a></b> (🥉18 ·  ⭐ 1.9K) - Deep Learning Pipelines for Apache Spark. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/databricks/spark-deep-learning) (👨‍💻 17 · 🔀 460 · 📦 22 · 📋 100 - 74% open · ⏱️ 21.03.2022):

	```
	git clone https://github.com/databricks/spark-deep-learning
	```
</details>
<details><summary><b><a href="https://github.com/mara/mara-pipelines">Mara Pipelines</a></b> (🥉17 ·  ⭐ 1.9K) - A lightweight opinionated ETL framework, halfway between plain.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/mara/mara-pipelines) (👨‍💻 17 · 🔀 90 · 📦 9 · 📋 29 - 51% open · ⏱️ 30.04.2022):

	```
	git clone https://github.com/mara/mara-pipelines
	```
- [PyPi](https://pypi.org/project/mara-pipelines) (📥 400 / month):
	```
	pip install mara-pipelines
	```
</details>
<details><summary><b><a href="https://github.com/kubeflow-kale/kale">kale</a></b> (🥉17 ·  ⭐ 540 · 💤) - Kubeflows superfood for Data Scientists. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/kubeflow-kale/kale) (👨‍💻 10 · 🔀 110 · 📋 160 - 52% open · ⏱️ 20.10.2021):

	```
	git clone https://github.com/kubeflow-kale/kale
	```
- [PyPi](https://pypi.org/project/kubeflow-kale) (📥 910 / month):
	```
	pip install kubeflow-kale
	```
</details>
<details><summary><b><a href="https://github.com/nerevu/riko">riko</a></b> (🥉16 ·  ⭐ 1.6K) - A Python stream processing engine modeled after Yahoo! Pipes. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/nerevu/riko) (👨‍💻 18 · 🔀 68 · 📋 29 - 72% open · ⏱️ 28.12.2021):

	```
	git clone https://github.com/nerevu/riko
	```
- [PyPi](https://pypi.org/project/riko) (📥 280 / month):
	```
	pip install riko
	```
</details>
<details><summary><b><a href="https://github.com/d6t/d6tflow">Databolt Flow</a></b> (🥉16 ·  ⭐ 940 · 💤) - Python library for building highly effective data science.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/d6t/d6tflow) (👨‍💻 12 · 🔀 71 · 📦 20 · 📋 23 - 43% open · ⏱️ 28.09.2021):

	```
	git clone https://github.com/d6t/d6tflow
	```
- [PyPi](https://pypi.org/project/d6tflow) (📥 270 / month):
	```
	pip install d6tflow
	```
</details>
<details><summary>Show 14 hidden projects...</summary>

- <b><a href="https://github.com/celery/celery">Celery</a></b> (🥇43 ·  ⭐ 19K) - Asynchronous task queue/job queue based on distributed message.. <code>❗Unlicensed</code>
- <b><a href="https://github.com/rq/rq">rq</a></b> (🥈36 ·  ⭐ 8.4K) - Simple job queues for Python. <code>❗Unlicensed</code>
- <b><a href="https://github.com/Yelp/mrjob">mrjob</a></b> (🥈30 ·  ⭐ 2.6K · 💀) - Run MapReduce jobs on Hadoop or Amazon Web Services. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/robinhood/faust">faust</a></b> (🥉27 ·  ⭐ 6.2K · 💀) - Python Stream Processing. <code>❗Unlicensed</code>
- <b><a href="https://github.com/douban/dpark">dpark</a></b> (🥉22 ·  ⭐ 2.7K · 💀) - Python clone of Spark, a MapReduce alike framework in Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/python-bonobo/bonobo">bonobo</a></b> (🥉22 ·  ⭐ 1.5K · 💀) - Extract Transform Load for Python 3.5+. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/databand-ai/dbnd">dbnd</a></b> (🥉22 ·  ⭐ 220) - DBND is an agile pipeline framework that helps data engineering teams.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/pricingassistant/mrq">mrq</a></b> (🥉21 ·  ⭐ 870 · 💀) - Mr. Queue - A distributed worker task queue in Python using Redis & gevent. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/analysiscenter/batchflow">BatchFlow</a></b> (🥉21 ·  ⭐ 180) - BatchFlow helps you conveniently work with random or sequential.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/svenkreiss/pysparkling">pysparkling</a></b> (🥉20 ·  ⭐ 250 · 💀) - A pure Python implementation of Apache Sparks RDD and.. <code>❗Unlicensed</code>
- <b><a href="https://github.com/bodywork-ml/bodywork-core">bodywork-core</a></b> (🥉16 ·  ⭐ 340) - ML pipeline orchestration and model deployments on.. <code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code>
- <b><a href="https://github.com/vincentclaes/datajob">datajob</a></b> (🥉14 ·  ⭐ 92) - Build and deploy a serverless data pipeline on AWS with no effort. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/olirice/flupy">flupy</a></b> (🥉13 ·  ⭐ 170) - Fluent data pipelines for python and your shell. <code>❗Unlicensed</code>
- <b><a href="https://github.com/kkyon/botflow">Botflow</a></b> (🥉10 ·  ⭐ 1.2K · 💀) - Python Fast Dataflow programming framework for Data pipeline.. <code>❗Unlicensed</code>
</details>
<br>

## Distributed Machine Learning

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries that provide capabilities to distribute and parallelize machine learning tasks across large-scale compute infrastructure._

<details><summary><b><a href="https://github.com/ray-project/ray">Ray</a></b> (🥇43 ·  ⭐ 21K) - An open source framework that provides a simple, universal API for.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/ray-project/ray) (👨‍💻 700 · 🔀 3.5K · 📦 5K · 📋 10K - 21% open · ⏱️ 09.06.2022):

	```
	git clone https://github.com/ray-project/ray
	```
- [PyPi](https://pypi.org/project/ray) (📥 1.3M / month):
	```
	pip install ray
	```
- [Conda](https://anaconda.org/conda-forge/ray-tune) (📥 33K · ⏱️ 23.05.2022):
	```
	conda install -c conda-forge ray-tune
	```
</details>
<details><summary><b><a href="https://github.com/dask/dask">dask</a></b> (🥇41 ·  ⭐ 10K) - Parallel computing with task scheduling. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/dask/dask) (👨‍💻 540 · 🔀 1.5K · 📦 37K · 📋 4.3K - 14% open · ⏱️ 08.06.2022):

	```
	git clone https://github.com/dask/dask
	```
- [PyPi](https://pypi.org/project/dask) (📥 6.4M / month):
	```
	pip install dask
	```
- [Conda](https://anaconda.org/conda-forge/dask) (📥 5.7M · ⏱️ 27.05.2022):
	```
	conda install -c conda-forge dask
	```
</details>
<details><summary><b><a href="https://github.com/dask/distributed">dask.distributed</a></b> (🥇39 ·  ⭐ 1.4K) - A distributed task scheduler for Dask. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/dask/distributed) (👨‍💻 270 · 🔀 610 · 📦 24K · 📋 2.7K - 33% open · ⏱️ 09.06.2022):

	```
	git clone https://github.com/dask/distributed
	```
- [PyPi](https://pypi.org/project/distributed) (📥 5.1M / month):
	```
	pip install distributed
	```
- [Conda](https://anaconda.org/conda-forge/distributed) (📥 7.1M · ⏱️ 26.05.2022):
	```
	conda install -c conda-forge distributed
	```
</details>
<details><summary><b><a href="https://github.com/microsoft/DeepSpeed">DeepSpeed</a></b> (🥈32 ·  ⭐ 6.9K) - DeepSpeed is a deep learning optimization library that makes.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/microsoft/DeepSpeed) (👨‍💻 110 · 🔀 750 · 📦 270 · 📋 870 - 48% open · ⏱️ 07.06.2022):

	```
	git clone https://github.com/microsoft/DeepSpeed
	```
- [PyPi](https://pypi.org/project/deepspeed) (📥 110K / month):
	```
	pip install deepspeed
	```
- [Docker Hub](https://hub.docker.com/r/deepspeed/deepspeed) (📥 14K · ⭐ 3 · ⏱️ 06.06.2022):
	```
	docker pull deepspeed/deepspeed
	```
</details>
<details><summary><b><a href="https://github.com/intel-analytics/BigDL">BigDL</a></b> (🥈32 ·  ⭐ 3.9K) - Building Large-Scale AI Applications for Distributed Big Data. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/intel-analytics/BigDL) (👨‍💻 140 · 🔀 940 · 📦 36 · 📋 1.3K - 30% open · ⏱️ 09.06.2022):

	```
	git clone https://github.com/intel-analytics/BigDL
	```
- [PyPi](https://pypi.org/project/bigdl) (📥 6.3K / month):
	```
	pip install bigdl
	```
- [Maven](https://search.maven.org/artifact/com.intel.analytics.bigdl/bigdl-SPARK_2.4):
	```
	<dependency>
		<groupId>com.intel.analytics.bigdl</groupId>
		<artifactId>bigdl-SPARK_2.4</artifactId>
		<version>[VERSION]</version>
	</dependency>
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/fairscale">FairScale</a></b> (🥈31 ·  ⭐ 1.8K) - PyTorch extensions for high performance and large scale training. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/facebookresearch/fairscale) (👨‍💻 61 · 🔀 180 · 📦 310 · 📋 300 - 18% open · ⏱️ 01.06.2022):

	```
	git clone https://github.com/facebookresearch/fairscale
	```
- [PyPi](https://pypi.org/project/fairscale) (📥 160K / month):
	```
	pip install fairscale
	```
- [Conda](https://anaconda.org/conda-forge/fairscale) (📥 22K · ⏱️ 22.03.2022):
	```
	conda install -c conda-forge fairscale
	```
</details>
<details><summary><b><a href="https://github.com/PyTorchLightning/metrics">metrics</a></b> (🥈31 ·  ⭐ 900) - Machine learning metrics for distributed, scalable PyTorch.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PyTorchLightning/metrics) (👨‍💻 140 · 🔀 180 · 📥 700 · 📦 3.2K · 📋 360 - 12% open · ⏱️ 09.06.2022):

	```
	git clone https://github.com/PyTorchLightning/metrics
	```
- [PyPi](https://pypi.org/project/metrics) (📥 3.4K / month):
	```
	pip install metrics
	```
- [Conda](https://anaconda.org/conda-forge/torchmetrics) (📥 360K · ⏱️ 09.06.2022):
	```
	conda install -c conda-forge torchmetrics
	```
</details>
<details><summary><b><a href="https://github.com/h2oai/h2o-3">H2O-3</a></b> (🥈29 ·  ⭐ 5.8K) - H2O is an Open Source, Distributed, Fast & Scalable Machine Learning.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/h2oai/h2o-3) (👨‍💻 230 · 🔀 1.9K · ⏱️ 08.06.2022):

	```
	git clone https://github.com/h2oai/h2o-3
	```
- [PyPi](https://pypi.org/project/h2o) (📥 430K / month):
	```
	pip install h2o
	```
</details>
<details><summary><b><a href="https://github.com/dask/dask-ml">dask-ml</a></b> (🥈29 ·  ⭐ 810) - Scalable Machine Learning with Dask. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/dask/dask-ml) (👨‍💻 75 · 🔀 220 · 📦 620 · 📋 440 - 45% open · ⏱️ 06.06.2022):

	```
	git clone https://github.com/dask/dask-ml
	```
- [PyPi](https://pypi.org/project/dask-ml) (📥 76K / month):
	```
	pip install dask-ml
	```
- [Conda](https://anaconda.org/conda-forge/dask-ml) (📥 330K · ⏱️ 27.05.2022):
	```
	conda install -c conda-forge dask-ml
	```
</details>
<details><summary><b><a href="https://github.com/microsoft/SynapseML">SynapseML</a></b> (🥈28 ·  ⭐ 3.3K) - Simple and Distributed Machine Learning. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/microsoft/SynapseML) (👨‍💻 92 · 🔀 650 · 📋 540 - 38% open · ⏱️ 09.06.2022):

	```
	git clone https://github.com/microsoft/SynapseML
	```
- [PyPi](https://pypi.org/project/synapseml) (📥 35K / month):
	```
	pip install synapseml
	```
</details>
<details><summary><b><a href="https://github.com/uber/petastorm">petastorm</a></b> (🥈28 ·  ⭐ 1.4K) - Petastorm library enables single machine or distributed training.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/uber/petastorm) (👨‍💻 44 · 🔀 240 · 📥 310 · 📦 70 · 📋 270 - 48% open · ⏱️ 21.04.2022):

	```
	git clone https://github.com/uber/petastorm
	```
- [PyPi](https://pypi.org/project/petastorm) (📥 82K / month):
	```
	pip install petastorm
	```
</details>
<details><summary><b><a href="https://github.com/yahoo/TensorFlowOnSpark">TensorFlowOnSpark</a></b> (🥉27 ·  ⭐ 3.8K) - TensorFlowOnSpark brings TensorFlow programs to.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/yahoo/TensorFlowOnSpark) (👨‍💻 34 · 🔀 920 · 📋 360 - 1% open · ⏱️ 21.04.2022):

	```
	git clone https://github.com/yahoo/TensorFlowOnSpark
	```
- [PyPi](https://pypi.org/project/tensorflowonspark) (📥 530K / month):
	```
	pip install tensorflowonspark
	```
- [Conda](https://anaconda.org/conda-forge/tensorflowonspark) (📥 11K · ⏱️ 27.03.2022):
	```
	conda install -c conda-forge tensorflowonspark
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/mesh">Mesh</a></b> (🥉26 ·  ⭐ 1.3K) - Mesh TensorFlow: Model Parallelism Made Easier. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/mesh) (👨‍💻 48 · 🔀 210 · 📦 680 · 📋 78 - 82% open · ⏱️ 12.05.2022):

	```
	git clone https://github.com/tensorflow/mesh
	```
- [PyPi](https://pypi.org/project/mesh-tensorflow) (📥 22K / month):
	```
	pip install mesh-tensorflow
	```
</details>
<details><summary><b><a href="https://github.com/intel-analytics/analytics-zoo">analytics-zoo</a></b> (🥉25 ·  ⭐ 2.5K) - Distributed Tensorflow, Keras and PyTorch on Apache.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/intel-analytics/analytics-zoo) (👨‍💻 100 · 🔀 700 · 📦 3 · 📋 1.3K - 32% open · ⏱️ 01.06.2022):

	```
	git clone https://github.com/intel-analytics/analytics-zoo
	```
- [PyPi](https://pypi.org/project/analytics-zoo) (📥 3K / month):
	```
	pip install analytics-zoo
	```
</details>
<details><summary><b><a href="https://github.com/maxpumperla/elephas">Elephas</a></b> (🥉25 ·  ⭐ 1.5K) - Distributed Deep learning with Keras & Spark. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>keras</code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/maxpumperla/elephas) (👨‍💻 27 · 🔀 300 · 📦 56 · 📋 160 - 11% open · ⏱️ 30.03.2022):

	```
	git clone https://github.com/maxpumperla/elephas
	```
- [PyPi](https://pypi.org/project/elephas) (📥 100K / month):
	```
	pip install elephas
	```
- [Conda](https://anaconda.org/conda-forge/elephas) (📥 8.3K · ⏱️ 02.06.2021):
	```
	conda install -c conda-forge elephas
	```
</details>
<details><summary><b><a href="https://github.com/microsoft/SynapseML">MMLSpark</a></b> (🥉24 ·  ⭐ 3.3K) - Simple and Distributed Machine Learning. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/microsoft/SynapseML) (👨‍💻 92 · 🔀 650 · 📋 540 - 38% open · ⏱️ 09.06.2022):

	```
	git clone https://github.com/microsoft/SynapseML
	```
- [PyPi](https://pypi.org/project/mmlspark) (📥 5 / month):
	```
	pip install mmlspark
	```
</details>
<details><summary><b><a href="https://github.com/learning-at-home/hivemind">Hivemind</a></b> (🥉23 ·  ⭐ 1K) - Decentralized deep learning in PyTorch. Built to train models on thousands.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/learning-at-home/hivemind) (👨‍💻 21 · 🔀 61 · 📦 7 · 📋 120 - 30% open · ⏱️ 08.06.2022):

	```
	git clone https://github.com/learning-at-home/hivemind
	```
- [PyPi](https://pypi.org/project/hivemind) (📥 4K / month):
	```
	pip install hivemind
	```
</details>
<details><summary><b><a href="https://github.com/mpi4py/mpi4py">mpi4py</a></b> (🥉23 ·  ⭐ 550) - Python bindings for MPI. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/mpi4py/mpi4py) (👨‍💻 20 · 🔀 77 · 📥 5K · 📋 77 - 16% open · ⏱️ 06.06.2022):

	```
	git clone https://github.com/mpi4py/mpi4py
	```
- [PyPi](https://pypi.org/project/mpi4py) (📥 230K / month):
	```
	pip install mpi4py
	```
- [Conda](https://anaconda.org/conda-forge/mpi4py) (📥 1.1M · ⏱️ 04.04.2022):
	```
	conda install -c conda-forge mpi4py
	```
</details>
<details><summary><b><a href="https://github.com/apache/singa">Apache Singa</a></b> (🥉21 ·  ⭐ 2.6K) - a distributed deep learning platform. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/apache/singa) (👨‍💻 79 · 🔀 790 · 📦 1 · 📋 72 - 20% open · ⏱️ 01.06.2022):

	```
	git clone https://github.com/apache/singa
	```
- [Conda](https://anaconda.org/nusdbsystem/singa) (📥 460 · ⏱️ 09.08.2021):
	```
	conda install -c nusdbsystem singa
	```
- [Docker Hub](https://hub.docker.com/r/apache/singa) (📥 280 · ⭐ 4 · ⏱️ 31.05.2022):
	```
	docker pull apache/singa
	```
</details>
<details><summary><b><a href="https://github.com/facebookincubator/submitit">Submit it</a></b> (🥉20 ·  ⭐ 630) - Python 3.6+ toolbox for submitting jobs to Slurm. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/facebookincubator/submitit) (👨‍💻 20 · 🔀 67 · 📋 66 - 30% open · ⏱️ 31.05.2022):

	```
	git clone https://github.com/facebookincubator/submitit
	```
- [PyPi](https://pypi.org/project/submitit) (📥 20K / month):
	```
	pip install submitit
	```
- [Conda](https://anaconda.org/conda-forge/submitit) (📥 6.3K · ⏱️ 10.02.2021):
	```
	conda install -c conda-forge submitit
	```
</details>
<details><summary><b><a href="https://github.com/bytedance/byteps">BytePS</a></b> (🥉18 ·  ⭐ 3.2K) - A high performance and generic framework for distributed DNN training. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/bytedance/byteps) (👨‍💻 19 · 🔀 450 · 📋 260 - 37% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/bytedance/byteps
	```
- [PyPi](https://pypi.org/project/byteps) (📥 66 / month):
	```
	pip install byteps
	```
- [Docker Hub](https://hub.docker.com/r/bytepsimage/tensorflow) (📥 1.3K · ⏱️ 03.03.2020):
	```
	docker pull bytepsimage/tensorflow
	```
</details>
<details><summary><b><a href="https://github.com/kingoflolz/mesh-transformer-jax">mesh-transformer-jax</a></b> (🥉17 ·  ⭐ 4.2K) - Model parallel transformers in JAX and Haiku. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://jax.readthedocs.io/en/latest/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/kingoflolz/mesh-transformer-jax) (👨‍💻 23 · 🔀 540 · 📋 180 - 12% open · ⏱️ 28.01.2022):

	```
	git clone https://github.com/kingoflolz/mesh-transformer-jax
	```
</details>
<details><summary><b><a href="https://github.com/tunib-ai/parallelformers">parallelformers</a></b> (🥉15 ·  ⭐ 470) - Parallelformers: An Efficient Model Parallelization.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/tunib-ai/parallelformers) (👨‍💻 4 · 🔀 28 · 📦 7 · 📋 18 - 38% open · ⏱️ 02.03.2022):

	```
	git clone https://github.com/tunib-ai/parallelformers
	```
- [PyPi](https://pypi.org/project/parallelformers) (📥 230 / month):
	```
	pip install parallelformers
	```
</details>
<details><summary>Show 10 hidden projects...</summary>

- <b><a href="https://github.com/horovod/horovod">horovod</a></b> (🥇34 ·  ⭐ 12K) - Distributed training framework for TensorFlow, Keras, PyTorch,.. <code>❗Unlicensed</code>
- <b><a href="https://github.com/DEAP/deap">DEAP</a></b> (🥈30 ·  ⭐ 4.7K) - Distributed Evolutionary Algorithms in Python. <code><a href="http://bit.ly/37RvQcA">❗️LGPL-3.0</a></code>
- <b><a href="https://github.com/ipython/ipyparallel">ipyparallel</a></b> (🥉24 ·  ⭐ 2.2K · 📉) - IPython Parallel: Interactive Parallel Computing in.. <code>❗Unlicensed</code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/databricks/tensorframes">TensorFrames</a></b> (🥉21 ·  ⭐ 760 · 💀) - [DEPRECATED] Tensorflow wrapper for DataFrames on.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/peterwittek/somoclu">somoclu</a></b> (🥉18 ·  ⭐ 240 · 💤) - Massively parallel self-organizing maps: accelerate training on.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/Ibotta/sk-dist">sk-dist</a></b> (🥉17 ·  ⭐ 280 · 💤) - Distributed scikit-learn meta-estimators in PySpark. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/deepmind/launchpad">launchpad</a></b> (🥉16 ·  ⭐ 270) -  <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/uber/fiber">Fiber</a></b> (🥉14 ·  ⭐ 970 · 💀) - Distributed Computing for AI Made Simple. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/ml-tooling/lazycluster">LazyCluster</a></b> (🥉14 ·  ⭐ 43 · 💤) - Distributed machine learning made simple. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/petuum/autodist">autodist</a></b> (🥉11 ·  ⭐ 120 · 💀) - Simple Distributed Deep Learning on TensorFlow. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
</details>
<br>

## Hyperparameter Optimization & AutoML

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for hyperparameter optimization, automl and neural architecture search._

<details><summary><b><a href="https://github.com/optuna/optuna">Optuna</a></b> (🥇39 ·  ⭐ 6.5K · 📈) - A hyperparameter optimization framework. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/optuna/optuna) (👨‍💻 200 · 🔀 700 · 📦 3.5K · 📋 1.2K - 8% open · ⏱️ 09.06.2022):

	```
	git clone https://github.com/optuna/optuna
	```
- [PyPi](https://pypi.org/project/optuna) (📥 4.4M / month):
	```
	pip install optuna
	```
- [Conda](https://anaconda.org/conda-forge/optuna) (📥 280K · ⏱️ 04.10.2021):
	```
	conda install -c conda-forge optuna
	```
</details>
<details><summary><b><a href="https://github.com/microsoft/nni">NNI</a></b> (🥇36 ·  ⭐ 12K) - An open source AutoML toolkit for automate machine learning lifecycle,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/microsoft/nni) (👨‍💻 170 · 🔀 1.6K · 📦 230 · 📋 1.6K - 17% open · ⏱️ 09.06.2022):

	```
	git clone https://github.com/microsoft/nni
	```
- [PyPi](https://pypi.org/project/nni) (📥 13K / month):
	```
	pip install nni
	```
</details>
<details><summary><b><a href="https://github.com/keras-team/autokeras">AutoKeras</a></b> (🥇34 ·  ⭐ 8.5K) - AutoML library for deep learning. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/keras-team/autokeras) (👨‍💻 140 · 🔀 1.3K · 📥 4.9K · 📦 330 · 📋 820 - 10% open · ⏱️ 16.05.2022):

	```
	git clone https://github.com/keras-team/autokeras
	```
- [PyPi](https://pypi.org/project/autokeras) (📥 39K / month):
	```
	pip install autokeras
	```
</details>
<details><summary><b><a href="https://github.com/automl/auto-sklearn">auto-sklearn</a></b> (🥇33 ·  ⭐ 6.3K) - Automated Machine Learning with scikit-learn. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/automl/auto-sklearn) (👨‍💻 79 · 🔀 1.1K · 📥 36 · 📦 290 · 📋 890 - 12% open · ⏱️ 24.04.2022):

	```
	git clone https://github.com/automl/auto-sklearn
	```
- [PyPi](https://pypi.org/project/auto-sklearn) (📥 37K / month):
	```
	pip install auto-sklearn
	```
- [Conda](https://anaconda.org/conda-forge/auto-sklearn) (📥 4.9K · ⏱️ 18.02.2022):
	```
	conda install -c conda-forge auto-sklearn
	```
</details>
<details><summary><b><a href="https://github.com/fmfn/BayesianOptimization">Bayesian Optimization</a></b> (🥇33 ·  ⭐ 6K · 📈) - A Python implementation of global optimization with.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/fmfn/BayesianOptimization) (👨‍💻 32 · 🔀 1.3K · 📥 86 · 📦 1.2K · 📋 240 - 7% open · ⏱️ 09.06.2022):

	```
	git clone https://github.com/fmfn/BayesianOptimization
	```
- [PyPi](https://pypi.org/project/bayesian-optimization) (📥 220K / month):
	```
	pip install bayesian-optimization
	```
</details>
<details><summary><b><a href="https://github.com/keras-team/keras-tuner">Keras Tuner</a></b> (🥇33 ·  ⭐ 2.5K) - Hyperparameter tuning for humans. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/keras-team/keras-tuner) (👨‍💻 48 · 🔀 330 · 📦 1.4K · 📋 390 - 44% open · ⏱️ 08.06.2022):

	```
	git clone https://github.com/keras-team/keras-tuner
	```
- [PyPi](https://pypi.org/project/keras-tuner) (📥 570K / month):
	```
	pip install keras-tuner
	```
- [Conda](https://anaconda.org/conda-forge/keras-tuner) (📥 6.8K · ⏱️ 12.01.2022):
	```
	conda install -c conda-forge keras-tuner
	```
</details>
<details><summary><b><a href="https://github.com/pytorch/botorch">BoTorch</a></b> (🥇33 ·  ⭐ 2.3K) - Bayesian optimization in PyTorch. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytorch/botorch) (👨‍💻 74 · 🔀 250 · 📦 260 · 📋 270 - 22% open · ⏱️ 09.06.2022):

	```
	git clone https://github.com/pytorch/botorch
	```
- [PyPi](https://pypi.org/project/botorch) (📥 180K / month):
	```
	pip install botorch
	```
- [Conda](https://anaconda.org/conda-forge/botorch) (📥 27K · ⏱️ 22.04.2022):
	```
	conda install -c conda-forge botorch
	```
</details>
<details><summary><b><a href="https://github.com/facebook/Ax">Ax</a></b> (🥈32 ·  ⭐ 1.8K) - Adaptive Experimentation Platform. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/facebook/Ax) (👨‍💻 120 · 🔀 200 · 📦 280 · 📋 400 - 6% open · ⏱️ 09.06.2022):

	```
	git clone https://github.com/facebook/Ax
	```
- [PyPi](https://pypi.org/project/ax-platform) (📥 160K / month):
	```
	pip install ax-platform
	```
- [Conda](https://anaconda.org/conda-forge/ax-platform) (📥 1.5K · ⏱️ 27.04.2022):
	```
	conda install -c conda-forge ax-platform
	```
</details>
<details><summary><b><a href="https://github.com/awslabs/autogluon">AutoGluon</a></b> (🥈31 ·  ⭐ 4.5K) - AutoGluon: AutoML for Image, Text, and Tabular Data. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1X" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/awslabs/autogluon) (👨‍💻 74 · 🔀 590 · 📦 130 · 📋 680 - 21% open · ⏱️ 09.06.2022):

	```
	git clone https://github.com/awslabs/autogluon
	```
- [PyPi](https://pypi.org/project/autogluon) (📥 64K / month):
	```
	pip install autogluon
	```
</details>
<details><summary><b><a href="https://github.com/scikit-optimize/scikit-optimize">scikit-optimize</a></b> (🥈31 ·  ⭐ 2.3K · 💤) - Sequential model-based optimization with a.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/scikit-optimize/scikit-optimize) (👨‍💻 76 · 🔀 420 · 📦 2.8K · 📋 600 - 34% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/scikit-optimize/scikit-optimize
	```
- [PyPi](https://pypi.org/project/scikit-optimize) (📥 970K / month):
	```
	pip install scikit-optimize
	```
- [Conda](https://anaconda.org/conda-forge/scikit-optimize) (📥 550K · ⏱️ 15.12.2021):
	```
	conda install -c conda-forge scikit-optimize
	```
</details>
<details><summary><b><a href="https://github.com/alteryx/featuretools">featuretools</a></b> (🥈29 ·  ⭐ 6.2K) - An open source python library for automated feature engineering. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/alteryx/featuretools) (👨‍💻 65 · 🔀 790 · 📋 800 - 20% open · ⏱️ 05.06.2022):

	```
	git clone https://github.com/alteryx/featuretools
	```
- [PyPi](https://pypi.org/project/featuretools) (📥 140K / month):
	```
	pip install featuretools
	```
- [Conda](https://anaconda.org/conda-forge/featuretools) (📥 87K · ⏱️ 31.05.2022):
	```
	conda install -c conda-forge featuretools
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/nevergrad">nevergrad</a></b> (🥈29 ·  ⭐ 3.3K) - A Python toolbox for performing gradient-free optimization. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/facebookresearch/nevergrad) (👨‍💻 49 · 🔀 310 · 📦 340 · 📋 220 - 29% open · ⏱️ 06.05.2022):

	```
	git clone https://github.com/facebookresearch/nevergrad
	```
- [PyPi](https://pypi.org/project/nevergrad) (📥 44K / month):
	```
	pip install nevergrad
	```
- [Conda](https://anaconda.org/conda-forge/nevergrad) (📥 27K · ⏱️ 14.06.2021):
	```
	conda install -c conda-forge nevergrad
	```
</details>
<details><summary><b><a href="https://github.com/autonomio/talos">Talos</a></b> (🥈28 ·  ⭐ 1.5K) - Hyperparameter Optimization for TensorFlow, Keras and PyTorch. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/autonomio/talos) (👨‍💻 22 · 🔀 250 · 📦 150 · 📋 390 - 5% open · ⏱️ 23.04.2022):

	```
	git clone https://github.com/autonomio/talos
	```
- [PyPi](https://pypi.org/project/talos) (📥 1.8K / month):
	```
	pip install talos
	```
</details>
<details><summary><b><a href="https://github.com/mljar/mljar-supervised">mljar-supervised</a></b> (🥈26 ·  ⭐ 1.9K) - Python package for AutoML on Tabular Data with Feature.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/mljar/mljar-supervised) (👨‍💻 17 · 🔀 270 · 📦 45 · 📋 480 - 19% open · ⏱️ 14.04.2022):

	```
	git clone https://github.com/mljar/mljar-supervised
	```
- [PyPi](https://pypi.org/project/mljar-supervised) (📥 9.5K / month):
	```
	pip install mljar-supervised
	```
- [Conda](https://anaconda.org/conda-forge/mljar-supervised) (📥 1.9K · ⏱️ 02.03.2022):
	```
	conda install -c conda-forge mljar-supervised
	```
</details>
<details><summary><b><a href="https://github.com/maxpumperla/hyperas">Hyperas</a></b> (🥈25 ·  ⭐ 2.1K · 💤) - Keras + Hyperopt: A very simple wrapper for convenient.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/maxpumperla/hyperas) (👨‍💻 21 · 🔀 300 · 📦 240 · 📋 250 - 37% open · ⏱️ 19.11.2021):

	```
	git clone https://github.com/maxpumperla/hyperas
	```
- [PyPi](https://pypi.org/project/hyperas) (📥 14K / month):
	```
	pip install hyperas
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/adanet">AdaNet</a></b> (🥈24 ·  ⭐ 3.4K · 💤) - Fast and flexible AutoML with learning guarantees. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/adanet) (👨‍💻 27 · 🔀 520 · 📦 43 · 📋 110 - 57% open · ⏱️ 30.08.2021):

	```
	git clone https://github.com/tensorflow/adanet
	```
- [PyPi](https://pypi.org/project/adanet) (📥 340 / month):
	```
	pip install adanet
	```
</details>
<details><summary><b><a href="https://github.com/Neuraxio/Neuraxle">Neuraxle</a></b> (🥈24 ·  ⭐ 520) - The worlds cleanest AutoML framework - Do hyperparameter tuning with.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/Neuraxio/Neuraxle) (👨‍💻 7 · 🔀 53 · 📦 32 · 📋 310 - 22% open · ⏱️ 11.05.2022):

	```
	git clone https://github.com/Neuraxio/Neuraxle
	```
- [PyPi](https://pypi.org/project/neuraxle) (📥 470 / month):
	```
	pip install neuraxle
	```
</details>
<details><summary><b><a href="https://github.com/automl/HpBandSter">HpBandSter</a></b> (🥉21 ·  ⭐ 540) - a distributed Hyperband implementation on Steroids. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/automl/HpBandSter) (👨‍💻 11 · 🔀 110 · 📦 230 · 📋 89 - 60% open · ⏱️ 22.04.2022):

	```
	git clone https://github.com/automl/HpBandSter
	```
- [PyPi](https://pypi.org/project/hpbandster) (📥 51K / month):
	```
	pip install hpbandster
	```
- [Conda](https://anaconda.org/conda-forge/hpbandster) (📥 1.8K · ⏱️ 11.12.2020):
	```
	conda install -c conda-forge hpbandster
	```
</details>
<details><summary><b><a href="https://github.com/SimonBlanke/Hyperactive">Hyperactive</a></b> (🥉21 ·  ⭐ 400) - An optimization and data collection toolbox for convenient and fast.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/SimonBlanke/Hyperactive) (👨‍💻 4 · 🔀 32 · 📥 100 · 📦 15 · 📋 44 - 9% open · ⏱️ 21.05.2022):

	```
	git clone https://github.com/SimonBlanke/Hyperactive
	```
- [PyPi](https://pypi.org/project/hyperactive) (📥 590 / month):
	```
	pip install hyperactive
	```
</details>
<details><summary><b><a href="https://github.com/ScottfreeLLC/AlphaPy">AlphaPy</a></b> (🥉19 ·  ⭐ 780) - Automated Machine Learning [AutoML] with Python, scikit-learn, Keras,.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/ScottfreeLLC/AlphaPy) (👨‍💻 3 · 🔀 160 · 📦 3 · 📋 41 - 29% open · ⏱️ 23.04.2022):

	```
	git clone https://github.com/ScottfreeLLC/AlphaPy
	```
- [PyPi](https://pypi.org/project/alphapy) (📥 100 / month):
	```
	pip install alphapy
	```
</details>
<details><summary><b><a href="https://github.com/rsteca/sklearn-deap">sklearn-deap</a></b> (🥉19 ·  ⭐ 700 · 💤) - Use evolutionary algorithms instead of gridsearch in.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/rsteca/sklearn-deap) (👨‍💻 22 · 🔀 110 · 📦 33 · 📋 50 - 32% open · ⏱️ 30.07.2021):

	```
	git clone https://github.com/rsteca/sklearn-deap
	```
- [PyPi](https://pypi.org/project/sklearn-deap) (📥 990 / month):
	```
	pip install sklearn-deap
	```
</details>
<details><summary><b><a href="https://github.com/shankarpandala/lazypredict">lazypredict</a></b> (🥉19 ·  ⭐ 360) - Lazy Predict help build a lot of basic models without much code.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/shankarpandala/lazypredict) (👨‍💻 17 · 🔀 64 · 📦 300 · 📋 63 - 46% open · ⏱️ 25.05.2022):

	```
	git clone https://github.com/shankarpandala/lazypredict
	```
- [PyPi](https://pypi.org/project/lazypredict) (📥 6.4K / month):
	```
	pip install lazypredict
	```
- [Conda](https://anaconda.org/conda-forge/lazypredict) (📥 450 · ⏱️ 24.08.2021):
	```
	conda install -c conda-forge lazypredict
	```
</details>
<details><summary><b><a href="https://github.com/AutoViML/Auto_ViML">Auto ViML</a></b> (🥉18 ·  ⭐ 340) - Automatically Build Multiple ML Models with a Single Line of Code... <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/AutoViML/Auto_ViML) (👨‍💻 6 · 🔀 77 · 📦 16 · 📋 20 - 25% open · ⏱️ 01.06.2022):

	```
	git clone https://github.com/AutoViML/Auto_ViML
	```
- [PyPi](https://pypi.org/project/autoviml) (📥 1.6K / month):
	```
	pip install autoviml
	```
</details>
<details><summary><b><a href="https://github.com/google/model_search">model_search</a></b> (🥉12 ·  ⭐ 3.2K) - AutoML algorithms for model architecture search at scale. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/google/model_search) (🔀 360 · 📋 50 - 70% open · ⏱️ 09.02.2022):

	```
	git clone https://github.com/google/model_search
	```
</details>
<details><summary>Show 23 hidden projects...</summary>

- <b><a href="https://github.com/EpistasisLab/tpot">TPOT</a></b> (🥈32 ·  ⭐ 8.6K) - A Python Automated Machine Learning tool that optimizes machine.. <code><a href="http://bit.ly/37RvQcA">❗️LGPL-3.0</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/hyperopt/hyperopt">Hyperopt</a></b> (🥈30 ·  ⭐ 6.2K · 💤) - Distributed Asynchronous Hyperparameter Optimization in.. <code>❗Unlicensed</code>
- <b><a href="https://github.com/SheffieldML/GPyOpt">GPyOpt</a></b> (🥈25 ·  ⭐ 820 · 💀) - Gaussian Process Optimization using GPy. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/AxeldeRomblay/MLBox">MLBox</a></b> (🥉23 ·  ⭐ 1.3K · 💀) - MLBox is a powerful Automated Machine Learning python library. <code>❗Unlicensed</code>
- <b><a href="https://github.com/automl/SMAC3">SMAC3</a></b> (🥉23 ·  ⭐ 700) - Sequential Model-based Algorithm Configuration. <code>❗Unlicensed</code>
- <b><a href="https://github.com/Epistimio/orion">Orion</a></b> (🥉23 ·  ⭐ 230) - Asynchronous Distributed Hyperparameter Optimization. <code>❗Unlicensed</code>
- <b><a href="https://github.com/ClimbsRocks/auto_ml">auto_ml</a></b> (🥉22 ·  ⭐ 1.6K · 💀) - [UNMAINTAINED] Automated machine learning for analytics & production. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/claesenm/optunity">optunity</a></b> (🥉22 ·  ⭐ 390 · 💀) - optimization routines for hyperparameter tuning. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/AutoViML/featurewiz">featurewiz</a></b> (🥉20 ·  ⭐ 240) - Use advanced feature engineering strategies and select best.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/sherpa-ai/sherpa">Sherpa</a></b> (🥉19 ·  ⭐ 310 · 💀) - Hyperparameter optimization that enables researchers to.. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
- <b><a href="https://github.com/williamFalcon/test-tube">Test Tube</a></b> (🥉18 ·  ⭐ 720 · 💀) - Python library to easily log experiments and parallelize.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/dragonfly/dragonfly">Dragonfly</a></b> (🥉18 ·  ⭐ 650 · 💀) - An open source python library for scalable Bayesian optimisation. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/HDI-Project/ATM">Auto Tune Models</a></b> (🥉18 ·  ⭐ 520 · 💀) - Auto Tune Models - A multi-tenant, multi-data system for.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/reiinakano/xcessiv">Xcessiv</a></b> (🥉16 ·  ⭐ 1.3K · 💀) - A web-based application for quick, scalable, and automated.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/HunterMcGushion/hyperparameter_hunter">HyperparameterHunter</a></b> (🥉16 ·  ⭐ 690 · 💀) - Easy hyperparameter optimization and automatic result.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/minimaxir/automl-gs">automl-gs</a></b> (🥉15 ·  ⭐ 1.8K · 💀) - Provide an input CSV and a target field to predict, generate a.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/tobegit3hub/advisor">Advisor</a></b> (🥉15 ·  ⭐ 1.5K · 💀) - Open-source implementation of Google Vizier for hyper parameters.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/jmcarpenter2/parfit">Parfit</a></b> (🥉15 ·  ⭐ 200 · 💀) - A package for parallelizing the fit and flexibly scoring of.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/carpedm20/ENAS-pytorch">ENAS</a></b> (🥉13 ·  ⭐ 2.6K · 💀) - PyTorch implementation of Efficient Neural Architecture Search via.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/LGE-ARC-AdvancedAI/auptimizer">Auptimizer</a></b> (🥉13 ·  ⭐ 190 · 💀) - An automatic ML model optimization tool. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
- <b><a href="https://github.com/joeddav/devol">Devol</a></b> (🥉11 ·  ⭐ 940 · 💀) - Genetic neural architecture search with Keras. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/electricbrainio/hypermax">Hypermax</a></b> (🥉10 ·  ⭐ 100 · 💀) - Better, faster hyper-parameter optimization. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/gdikov/hypertunity">Hypertunity</a></b> (🥉8 ·  ⭐ 120 · 💀) - A toolset for black-box hyperparameter optimisation. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
</details>
<br>

## Reinforcement Learning

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for building and evaluating reinforcement learning & agent-based systems._

<details><summary><b><a href="https://github.com/openai/gym">OpenAI Gym</a></b> (🥇42 ·  ⭐ 28K) - A toolkit for developing and comparing reinforcement learning.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/openai/gym) (👨‍💻 360 · 🔀 7.3K · 📦 30K · 📋 1.6K - 0% open · ⏱️ 09.06.2022):

	```
	git clone https://github.com/openai/gym
	```
- [PyPi](https://pypi.org/project/gym) (📥 570K / month):
	```
	pip install gym
	```
- [Conda](https://anaconda.org/conda-forge/gym) (📥 110K · ⏱️ 08.02.2022):
	```
	conda install -c conda-forge gym
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/agents">TF-Agents</a></b> (🥇30 ·  ⭐ 2.3K) - TF-Agents: A reliable, scalable and easy to use TensorFlow.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/agents) (👨‍💻 120 · 🔀 600 · 📦 820 · 📋 560 - 22% open · ⏱️ 08.06.2022):

	```
	git clone https://github.com/tensorflow/agents
	```
- [PyPi](https://pypi.org/project/tf-agents) (📥 190K / month):
	```
	pip install tf-agents
	```
</details>
<details><summary><b><a href="https://github.com/deepmind/acme">Acme</a></b> (🥇29 ·  ⭐ 2.7K) - A library of reinforcement learning components and agents. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/deepmind/acme) (👨‍💻 68 · 🔀 330 · 📦 81 · 📋 190 - 12% open · ⏱️ 08.06.2022):

	```
	git clone https://github.com/deepmind/acme
	```
- [PyPi](https://pypi.org/project/dm-acme) (📥 4K / month):
	```
	pip install dm-acme
	```
- [Conda](https://anaconda.org/conda-forge/dm-acme) (📥 2.4K · ⏱️ 09.12.2021):
	```
	conda install -c conda-forge dm-acme
	```
</details>
<details><summary><b><a href="https://github.com/AI4Finance-Foundation/FinRL">FinRL</a></b> (🥈28 ·  ⭐ 5.5K) - FinRL: The first open-source project for financial reinforcement learning... <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/AI4Finance-Foundation/FinRL) (👨‍💻 67 · 🔀 1.2K · 📦 12 · 📋 400 - 13% open · ⏱️ 08.06.2022):

	```
	git clone https://github.com/AI4Finance-Foundation/FinRL
	```
- [PyPi](https://pypi.org/project/finrl) (📥 270 / month):
	```
	pip install finrl
	```
</details>
<details><summary><b><a href="https://github.com/PaddlePaddle/PARL">PARL</a></b> (🥈26 ·  ⭐ 2.6K) - A high-performance distributed training framework for Reinforcement.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1M" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PaddlePaddle/PARL) (👨‍💻 30 · 🔀 710 · 📦 91 · 📋 370 - 16% open · ⏱️ 07.06.2022):

	```
	git clone https://github.com/PaddlePaddle/PARL
	```
- [PyPi](https://pypi.org/project/parl) (📥 800 / month):
	```
	pip install parl
	```
</details>
<details><summary><b><a href="https://github.com/google/dopamine">Dopamine</a></b> (🥈25 ·  ⭐ 9.8K) - Dopamine is a research framework for fast prototyping of.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/google/dopamine) (👨‍💻 15 · 🔀 1.3K · 📋 150 - 43% open · ⏱️ 20.05.2022):

	```
	git clone https://github.com/google/dopamine
	```
- [PyPi](https://pypi.org/project/dopamine-rl) (📥 51K / month):
	```
	pip install dopamine-rl
	```
</details>
<details><summary><b><a href="https://github.com/tensorforce/tensorforce">TensorForce</a></b> (🥉24 ·  ⭐ 3.1K) - Tensorforce: a TensorFlow library for applied.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorforce/tensorforce) (👨‍💻 82 · 🔀 500 · 📋 640 - 2% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/tensorforce/tensorforce
	```
- [PyPi](https://pypi.org/project/tensorforce) (📥 1.7K / month):
	```
	pip install tensorforce
	```
</details>
<details><summary><b><a href="https://github.com/rlworkgroup/garage">garage</a></b> (🥉24 ·  ⭐ 1.5K) - A toolkit for reproducible reinforcement learning research. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/rlworkgroup/garage) (👨‍💻 78 · 🔀 260 · 📦 42 · 📋 1K - 19% open · ⏱️ 20.05.2022):

	```
	git clone https://github.com/rlworkgroup/garage
	```
- [PyPi](https://pypi.org/project/garage) (📥 450 / month):
	```
	pip install garage
	```
</details>
<details><summary><b><a href="https://github.com/hill-a/stable-baselines">Stable Baselines</a></b> (🥉23 ·  ⭐ 3.5K · 💤) - A fork of OpenAI Baselines, implementations of.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/hill-a/stable-baselines) (👨‍💻 110 · 🔀 690 · 📋 920 - 11% open · ⏱️ 25.08.2021):

	```
	git clone https://github.com/hill-a/stable-baselines
	```
- [PyPi](https://pypi.org/project/stable-baselines) (📥 8.2K / month):
	```
	pip install stable-baselines
	```
</details>
<details><summary><b><a href="https://github.com/pfnet/pfrl">PFRL</a></b> (🥉22 ·  ⭐ 850) - PFRL: a PyTorch-based deep reinforcement learning library. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pfnet/pfrl) (👨‍💻 16 · 🔀 110 · 📦 44 · 📋 63 - 38% open · ⏱️ 14.03.2022):

	```
	git clone https://github.com/pfnet/pfrl
	```
- [PyPi](https://pypi.org/project/pfrl) (📥 1.3K / month):
	```
	pip install pfrl
	```
</details>
<details><summary><b><a href="https://github.com/IntelLabs/coach">Coach</a></b> (🥉21 ·  ⭐ 2.2K · 💤) - Reinforcement Learning Coach by Intel AI Lab enables easy.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/IntelLabs/coach) (👨‍💻 35 · 🔀 420 · 📋 260 - 30% open · ⏱️ 28.06.2021):

	```
	git clone https://github.com/IntelLabs/coach
	```
- [PyPi](https://pypi.org/project/rl_coach) (📥 180 / month):
	```
	pip install rl_coach
	```
</details>
<details><summary><b><a href="https://github.com/deepmind/trfl">TRFL</a></b> (🥉20 ·  ⭐ 3.1K · 💤) - TensorFlow Reinforcement Learning. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/deepmind/trfl) (👨‍💻 13 · 🔀 380 · 📦 82 · 📋 20 - 20% open · ⏱️ 16.08.2021):

	```
	git clone https://github.com/deepmind/trfl
	```
- [PyPi](https://pypi.org/project/trfl) (📥 4.7K / month):
	```
	pip install trfl
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/ReAgent">ReAgent</a></b> (🥉19 ·  ⭐ 3.2K) - A platform for Reasoning systems (Reinforcement Learning,.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/facebookresearch/ReAgent) (👨‍💻 130 · 🔀 440 · 📋 100 - 25% open · ⏱️ 01.06.2022):

	```
	git clone https://github.com/facebookresearch/ReAgent
	```
- [PyPi](https://pypi.org/project/reagent) (📥 8 / month):
	```
	pip install reagent
	```
</details>
<details><summary><b><a href="https://github.com/google-research/rliable">rliable</a></b> (🥉12 ·  ⭐ 420) - [NeurIPS21 Outstanding Paper] Library for reliable evaluation on RL.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/google-research/rliable) (👨‍💻 2 · 🔀 23 · 📦 10 · ⏱️ 18.04.2022):

	```
	git clone https://github.com/google-research/rliable
	```
- [PyPi](https://pypi.org/project/rliable`):
	```
	pip install rliable`
	```
</details>
<details><summary>Show 9 hidden projects...</summary>

- <b><a href="https://github.com/keras-rl/keras-rl">keras-rl</a></b> (🥇29 ·  ⭐ 5.3K · 💀) - Deep Reinforcement Learning for Keras. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/openai/baselines">baselines</a></b> (🥈27 ·  ⭐ 13K · 💀) - OpenAI Baselines: high-quality implementations of reinforcement.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/mwydmuch/ViZDoom">ViZDoom</a></b> (🥈27 ·  ⭐ 1.4K) - Doom-based AI Research Platform for Reinforcement Learning from.. <code>❗Unlicensed</code>
- <b><a href="https://github.com/tensorlayer/TensorLayer">TensorLayer</a></b> (🥉23 ·  ⭐ 7K) - Deep Learning and Reinforcement Learning Library for.. <code>❗Unlicensed</code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/chainer/chainerrl">ChainerRL</a></b> (🥉23 ·  ⭐ 1.1K · 💀) - ChainerRL is a deep reinforcement learning library built on top of.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/deepmind/rlax">RLax</a></b> (🥉22 ·  ⭐ 820) -  <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://jax.readthedocs.io/en/latest/_static/favicon.png" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/deepmind/lab">DeepMind Lab</a></b> (🥉18 ·  ⭐ 6.7K) - A customisable 3D platform for agent-based AI research. <code>❗Unlicensed</code>
- <b><a href="https://github.com/SerpentAI/SerpentAI">SerpentAI</a></b> (🥉16 ·  ⭐ 6.3K · 💀) - Game Agent Framework. Helping you create AIs / Bots that learn to.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/enlite-ai/maze">Maze</a></b> (🥉12 ·  ⭐ 210) - Maze Applied Reinforcement Learning Framework. <code><a href="https://tldrlegal.com/search?q=Custom">❗️Custom</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
</details>
<br>

## Recommender Systems

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for building and evaluating recommendation systems._

<details><summary><b><a href="https://github.com/microsoft/recommenders">Recommenders</a></b> (🥇35 ·  ⭐ 13K) - Best Practices on Recommendation Systems. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/microsoft/recommenders) (👨‍💻 120 · 🔀 2.3K · 📥 180 · 📦 29 · 📋 690 - 18% open · ⏱️ 06.06.2022):

	```
	git clone https://github.com/microsoft/recommenders
	```
- [PyPi](https://pypi.org/project/recommenders) (📥 110K / month):
	```
	pip install recommenders
	```
</details>
<details><summary><b><a href="https://github.com/benfred/implicit">implicit</a></b> (🥇31 ·  ⭐ 2.8K) - Fast Python Collaborative Filtering for Implicit Feedback Datasets. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/benfred/implicit) (👨‍💻 30 · 🔀 520 · 📦 610 · 📋 400 - 17% open · ⏱️ 07.06.2022):

	```
	git clone https://github.com/benfred/implicit
	```
- [PyPi](https://pypi.org/project/implicit) (📥 150K / month):
	```
	pip install implicit
	```
- [Conda](https://anaconda.org/conda-forge/implicit) (📥 360K · ⏱️ 29.01.2022):
	```
	conda install -c conda-forge implicit
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/recommenders">TF Recommenders</a></b> (🥈28 ·  ⭐ 1.3K) - TensorFlow Recommenders is a library for building.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/recommenders) (👨‍💻 33 · 🔀 190 · 📦 120 · 📋 260 - 49% open · ⏱️ 01.06.2022):

	```
	git clone https://github.com/tensorflow/recommenders
	```
- [PyPi](https://pypi.org/project/tensorflow-recommenders) (📥 3.2M / month):
	```
	pip install tensorflow-recommenders
	```
</details>
<details><summary><b><a href="https://github.com/lyst/lightfm">lightfm</a></b> (🥈27 ·  ⭐ 4K) - A Python implementation of LightFM, a hybrid recommendation algorithm. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/lyst/lightfm) (👨‍💻 44 · 🔀 620 · 📦 750 · 📋 450 - 22% open · ⏱️ 09.03.2022):

	```
	git clone https://github.com/lyst/lightfm
	```
- [PyPi](https://pypi.org/project/lightfm) (📥 420K / month):
	```
	pip install lightfm
	```
- [Conda](https://anaconda.org/conda-forge/lightfm) (📥 120K · ⏱️ 09.03.2022):
	```
	conda install -c conda-forge lightfm
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/ranking">TF Ranking</a></b> (🥈26 ·  ⭐ 2.5K) - Learning to Rank in TensorFlow. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/ranking) (👨‍💻 28 · 🔀 430 · 📋 290 - 18% open · ⏱️ 26.04.2022):

	```
	git clone https://github.com/tensorflow/ranking
	```
- [PyPi](https://pypi.org/project/tensorflow_ranking) (📥 77K / month):
	```
	pip install tensorflow_ranking
	```
</details>
<details><summary><b><a href="https://github.com/RUCAIBox/RecBole">RecBole</a></b> (🥈26 ·  ⭐ 1.9K) - A unified, comprehensive and efficient recommendation library. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/RUCAIBox/RecBole) (👨‍💻 45 · 🔀 350 · 📋 410 - 9% open · ⏱️ 03.06.2022):

	```
	git clone https://github.com/RUCAIBox/RecBole
	```
- [PyPi](https://pypi.org/project/recbole) (📥 1.4K / month):
	```
	pip install recbole
	```
- [Conda](https://anaconda.org/aibox/recbole) (📥 1.6K · ⏱️ 25.02.2022):
	```
	conda install -c aibox recbole
	```
</details>
<details><summary><b><a href="https://github.com/PreferredAI/cornac">Cornac</a></b> (🥈25 ·  ⭐ 590) - A Comparative Framework for Multimodal Recommender Systems. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/PreferredAI/cornac) (👨‍💻 13 · 🔀 97 · 📦 110 · 📋 94 - 6% open · ⏱️ 29.04.2022):

	```
	git clone https://github.com/PreferredAI/cornac
	```
- [PyPi](https://pypi.org/project/cornac) (📥 120K / month):
	```
	pip install cornac
	```
- [Conda](https://anaconda.org/conda-forge/cornac) (📥 220K · ⏱️ 19.02.2022):
	```
	conda install -c conda-forge cornac
	```
</details>
<details><summary><b><a href="https://github.com/statisticianinstilettos/recmetrics">recmetrics</a></b> (🥉19 ·  ⭐ 400) - A library of metrics for evaluating recommender systems. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/statisticianinstilettos/recmetrics) (👨‍💻 16 · 🔀 83 · 📦 25 · 📋 20 - 40% open · ⏱️ 17.04.2022):

	```
	git clone https://github.com/statisticianinstilettos/recmetrics
	```
- [PyPi](https://pypi.org/project/recmetrics) (📥 780 / month):
	```
	pip install recmetrics
	```
</details>
<details><summary><b><a href="https://github.com/caserec/CaseRecommender">Case Recommender</a></b> (🥉18 ·  ⭐ 410 · 💤) - Case Recommender: A Flexible and Extensible Python.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/caserec/CaseRecommender) (👨‍💻 11 · 🔀 79 · 📦 10 · 📋 25 - 20% open · ⏱️ 25.11.2021):

	```
	git clone https://github.com/caserec/CaseRecommender
	```
- [PyPi](https://pypi.org/project/caserecommender) (📥 160 / month):
	```
	pip install caserecommender
	```
</details>
<details><summary>Show 7 hidden projects...</summary>

- <b><a href="https://github.com/NicolasHug/Surprise">scikit-surprise</a></b> (🥉24 ·  ⭐ 5.4K · 💀) - A Python scikit for building and analyzing recommender.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/lenskit/lkpy">lkpy</a></b> (🥉21 ·  ⭐ 210) - Python recommendation toolkit. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/jfkirk/tensorrec">tensorrec</a></b> (🥉19 ·  ⭐ 1.2K · 💀) - A TensorFlow recommendation algorithm and framework in.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/ibayer/fastFM">fastFM</a></b> (🥉19 ·  ⭐ 990 · 💀) - fastFM: A Library for Factorization Machines. <code>❗Unlicensed</code>
- <b><a href="https://github.com/maciejkula/spotlight">Spotlight</a></b> (🥉18 ·  ⭐ 2.7K · 💀) - Deep recommender models using PyTorch. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/ylongqi/openrec">OpenRec</a></b> (🥉14 ·  ⭐ 390 · 💀) - OpenRec is an open-source and modular library for neural network-.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/ShopRunner/collie">Collie</a></b> (🥉14 ·  ⭐ 90) - A library for preparing, training, and evaluating scalable deep.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
</details>
<br>

## Privacy Machine Learning

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for encrypted and privacy-preserving machine learning using methods like federated learning & differential privacy._

<details><summary><b><a href="https://github.com/pytorch/opacus">Opacus</a></b> (🥈27 ·  ⭐ 1.2K) - Training PyTorch models with differential privacy. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytorch/opacus) (👨‍💻 50 · 🔀 200 · 📥 45 · 📦 110 · 📋 180 - 18% open · ⏱️ 01.06.2022):

	```
	git clone https://github.com/pytorch/opacus
	```
- [PyPi](https://pypi.org/project/opacus) (📥 4.2K / month):
	```
	pip install opacus
	```
- [Conda](https://anaconda.org/conda-forge/opacus) (📥 940 · ⏱️ 06.05.2022):
	```
	conda install -c conda-forge opacus
	```
</details>
<details><summary><b><a href="https://github.com/FederatedAI/FATE">FATE</a></b> (🥈26 ·  ⭐ 4.3K) - An Industrial Grade Federated Learning Framework. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/FederatedAI/FATE) (👨‍💻 74 · 🔀 1.3K · 📋 1.2K - 33% open · ⏱️ 15.04.2022):

	```
	git clone https://github.com/FederatedAI/FATE
	```
- [PyPi](https://pypi.org/project/ETAF) (📥 15 / month):
	```
	pip install ETAF
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/privacy">TensorFlow Privacy</a></b> (🥉24 ·  ⭐ 1.6K) - Library for training machine learning models with.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/privacy) (👨‍💻 46 · 🔀 350 · 📥 71 · 📋 150 - 42% open · ⏱️ 07.06.2022):

	```
	git clone https://github.com/tensorflow/privacy
	```
- [PyPi](https://pypi.org/project/tensorflow-privacy) (📥 32K / month):
	```
	pip install tensorflow-privacy
	```
</details>
<details><summary><b><a href="https://github.com/tf-encrypted/tf-encrypted">TFEncrypted</a></b> (🥉22 ·  ⭐ 1K) - A Framework for Encrypted Machine Learning in TensorFlow. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tf-encrypted/tf-encrypted) (👨‍💻 28 · 🔀 170 · 📦 61 · 📋 420 - 40% open · ⏱️ 10.03.2022):

	```
	git clone https://github.com/tf-encrypted/tf-encrypted
	```
- [PyPi](https://pypi.org/project/tf-encrypted) (📥 780 / month):
	```
	pip install tf-encrypted
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/CrypTen">CrypTen</a></b> (🥉21 ·  ⭐ 1.1K) - A framework for Privacy Preserving Machine Learning. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/facebookresearch/CrypTen) (👨‍💻 29 · 🔀 170 · 📦 19 · 📋 140 - 13% open · ⏱️ 15.05.2022):

	```
	git clone https://github.com/facebookresearch/CrypTen
	```
- [PyPi](https://pypi.org/project/crypten) (📥 220 / month):
	```
	pip install crypten
	```
</details>
<details><summary>Show 1 hidden projects...</summary>

- <b><a href="https://github.com/OpenMined/PySyft">PySyft</a></b> (🥇32 ·  ⭐ 8.2K) - A library for answering questions using data you cannot see. <code>❗Unlicensed</code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
</details>
<br>

## Workflow & Experiment Tracking

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries to organize, track, and visualize machine learning experiments._

<details><summary><b><a href="https://github.com/tensorflow/tensorboard">Tensorboard</a></b> (🥇43 ·  ⭐ 5.9K) - TensorFlows Visualization Toolkit. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/tensorboard) (👨‍💻 280 · 🔀 1.5K · 📦 110K · 📋 1.6K - 31% open · ⏱️ 09.06.2022):

	```
	git clone https://github.com/tensorflow/tensorboard
	```
- [PyPi](https://pypi.org/project/tensorboard) (📥 17M / month):
	```
	pip install tensorboard
	```
- [Conda](https://anaconda.org/conda-forge/tensorboard) (📥 3M · ⏱️ 02.05.2022):
	```
	conda install -c conda-forge tensorboard
	```
</details>
<details><summary><b><a href="https://github.com/mlflow/mlflow">mlflow</a></b> (🥇37 ·  ⭐ 12K) - Open source platform for the machine learning lifecycle. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/mlflow/mlflow) (👨‍💻 430 · 🔀 2.7K · 📋 2.3K - 34% open · ⏱️ 08.06.2022):

	```
	git clone https://github.com/mlflow/mlflow
	```
- [PyPi](https://pypi.org/project/mlflow) (📥 11M / month):
	```
	pip install mlflow
	```
- [Conda](https://anaconda.org/conda-forge/mlflow) (📥 590K · ⏱️ 28.05.2022):
	```
	conda install -c conda-forge mlflow
	```
</details>
<details><summary><b><a href="https://github.com/pycaret/pycaret">PyCaret</a></b> (🥇37 ·  ⭐ 5.8K) - An open-source, low-code machine learning library in Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pycaret/pycaret) (👨‍💻 87 · 🔀 1.3K · 📥 570 · 📦 2.2K · 📋 1.6K - 15% open · ⏱️ 07.06.2022):

	```
	git clone https://github.com/pycaret/pycaret
	```
- [PyPi](https://pypi.org/project/pycaret) (📥 420K / month):
	```
	pip install pycaret
	```
- [Conda](https://anaconda.org/conda-forge/pycaret) (📥 11K · ⏱️ 18.04.2022):
	```
	conda install -c conda-forge pycaret
	```
</details>
<details><summary><b><a href="https://github.com/aws/sagemaker-python-sdk">SageMaker SDK</a></b> (🥇37 ·  ⭐ 1.6K) - A library for training and deploying machine learning.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1X" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/aws/sagemaker-python-sdk) (👨‍💻 260 · 🔀 770 · 📦 1.4K · 📋 1K - 31% open · ⏱️ 08.06.2022):

	```
	git clone https://github.com/aws/sagemaker-python-sdk
	```
- [PyPi](https://pypi.org/project/sagemaker) (📥 10M / month):
	```
	pip install sagemaker
	```
- [Conda](https://anaconda.org/conda-forge/sagemaker-python-sdk) (📥 290K · ⏱️ 08.06.2022):
	```
	conda install -c conda-forge sagemaker-python-sdk
	```
</details>
<details><summary><b><a href="https://github.com/iterative/dvc">DVC</a></b> (🥈34 ·  ⭐ 9.8K) - Data Version Control | Git for Data & Models | ML Experiments Management. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/iterative/dvc) (👨‍💻 270 · 🔀 920 · 📥 88K · 📋 3.7K - 17% open · ⏱️ 09.06.2022):

	```
	git clone https://github.com/iterative/dvc
	```
- [PyPi](https://pypi.org/project/dvc) (📥 510K / month):
	```
	pip install dvc
	```
- [Conda](https://anaconda.org/conda-forge/dvc) (📥 1.1M · ⏱️ 08.06.2022):
	```
	conda install -c conda-forge dvc
	```
</details>
<details><summary><b><a href="https://github.com/lanpa/tensorboardX">tensorboardX</a></b> (🥈34 ·  ⭐ 7.4K) - tensorboard for pytorch (and chainer, mxnet, numpy, ...). <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/lanpa/tensorboardX) (👨‍💻 72 · 🔀 850 · 📥 350 · 📦 20K · 📋 430 - 14% open · ⏱️ 08.06.2022):

	```
	git clone https://github.com/lanpa/tensorboardX
	```
- [PyPi](https://pypi.org/project/tensorboardX) (📥 3.8M / month):
	```
	pip install tensorboardX
	```
- [Conda](https://anaconda.org/conda-forge/tensorboardx) (📥 700K · ⏱️ 07.06.2022):
	```
	conda install -c conda-forge tensorboardx
	```
</details>
<details><summary><b><a href="https://github.com/allegroai/clearml">ClearML</a></b> (🥈33 ·  ⭐ 3.2K) - ClearML - Auto-Magical CI/CD to streamline your ML workflow... <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/allegroai/clearml) (👨‍💻 49 · 🔀 430 · 📥 430 · 📦 250 · 📋 550 - 41% open · ⏱️ 08.06.2022):

	```
	git clone https://github.com/allegroai/clearml
	```
- [PyPi](https://pypi.org/project/clearml) (📥 82K / month):
	```
	pip install clearml
	```
- [Docker Hub](https://hub.docker.com/r/allegroai/trains) (📥 30K · ⏱️ 05.10.2020):
	```
	docker pull allegroai/trains
	```
</details>
<details><summary><b><a href="https://github.com/snakemake/snakemake">snakemake</a></b> (🥈33 ·  ⭐ 1.4K) - This is the development home of the workflow management system.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/snakemake/snakemake) (👨‍💻 250 · 🔀 330 · 📦 1.1K · 📋 990 - 58% open · ⏱️ 08.06.2022):

	```
	git clone https://github.com/snakemake/snakemake
	```
- [PyPi](https://pypi.org/project/snakemake) (📥 51K / month):
	```
	pip install snakemake
	```
- [Conda](https://anaconda.org/bioconda/snakemake) (📥 450K · ⏱️ 08.06.2022):
	```
	conda install -c bioconda snakemake
	```
</details>
<details><summary><b><a href="https://github.com/wandb/client">wandb client</a></b> (🥈32 ·  ⭐ 3.9K) - A tool for visualizing and tracking your machine learning.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/wandb/client) (👨‍💻 110 · 🔀 320 · 📋 1.8K - 19% open · ⏱️ 08.06.2022):

	```
	git clone https://github.com/wandb/client
	```
- [PyPi](https://pypi.org/project/wandb) (📥 4M / month):
	```
	pip install wandb
	```
- [Conda](https://anaconda.org/conda-forge/wandb) (📥 61K · ⏱️ 26.05.2022):
	```
	conda install -c conda-forge wandb
	```
</details>
<details><summary><b><a href="https://github.com/Netflix/metaflow">Metaflow</a></b> (🥈31 ·  ⭐ 5.7K) - Build and manage real-life data science projects with ease!. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/Netflix/metaflow) (👨‍💻 52 · 🔀 490 · 📦 290 · 📋 400 - 43% open · ⏱️ 01.06.2022):

	```
	git clone https://github.com/Netflix/metaflow
	```
- [PyPi](https://pypi.org/project/metaflow) (📥 46K / month):
	```
	pip install metaflow
	```
- [Conda](https://anaconda.org/conda-forge/metaflow) (📥 43K · ⏱️ 29.05.2022):
	```
	conda install -c conda-forge metaflow
	```
</details>
<details><summary><b><a href="https://github.com/catalyst-team/catalyst">Catalyst</a></b> (🥈31 ·  ⭐ 2.9K) - Accelerated deep learning R&D. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/catalyst-team/catalyst) (👨‍💻 100 · 🔀 340 · 📦 560 · 📋 330 - 0% open · ⏱️ 29.04.2022):

	```
	git clone https://github.com/catalyst-team/catalyst
	```
- [PyPi](https://pypi.org/project/catalyst) (📥 3M / month):
	```
	pip install catalyst
	```
</details>
<details><summary><b><a href="https://github.com/aimhubio/aim">aim</a></b> (🥈31 ·  ⭐ 2.5K) - Aim easy-to-use and performant open-source ML experiment tracker. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/aimhubio/aim) (👨‍💻 38 · 🔀 150 · 📦 82 · 📋 530 - 27% open · ⏱️ 09.06.2022):

	```
	git clone https://github.com/aimhubio/aim
	```
- [PyPi](https://pypi.org/project/aim) (📥 47K / month):
	```
	pip install aim
	```
- [Conda](https://anaconda.org/conda-forge/aim) (📥 13K · ⏱️ 15.10.2021):
	```
	conda install -c conda-forge aim
	```
</details>
<details><summary><b><a href="https://github.com/PaddlePaddle/VisualDL">VisualDL</a></b> (🥈30 ·  ⭐ 4.4K) - Deep Learning Visualization Toolkit. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1M" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PaddlePaddle/VisualDL) (👨‍💻 31 · 🔀 580 · 📥 180 · 📦 1.2K · 📋 410 - 18% open · ⏱️ 01.04.2022):

	```
	git clone https://github.com/PaddlePaddle/VisualDL
	```
- [PyPi](https://pypi.org/project/visualdl) (📥 94K / month):
	```
	pip install visualdl
	```
</details>
<details><summary><b><a href="https://github.com/IDSIA/sacred">sacred</a></b> (🥈30 ·  ⭐ 3.8K) - Sacred is a tool to help you configure, organize, log and reproduce.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/IDSIA/sacred) (👨‍💻 97 · 🔀 340 · 📦 1.4K · 📋 530 - 16% open · ⏱️ 28.03.2022):

	```
	git clone https://github.com/IDSIA/sacred
	```
- [PyPi](https://pypi.org/project/sacred) (📥 49K / month):
	```
	pip install sacred
	```
- [Conda](https://anaconda.org/conda-forge/sacred) (📥 510 · ⏱️ 14.11.2021):
	```
	conda install -c conda-forge sacred
	```
</details>
<details><summary><b><a href="https://github.com/Azure/MachineLearningNotebooks">AzureML SDK</a></b> (🥈30 ·  ⭐ 3.3K) - Python notebooks with ML and deep learning examples with Azure.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/Azure/MachineLearningNotebooks) (👨‍💻 60 · 🔀 2.1K · 📥 460 · 📋 1.3K - 19% open · ⏱️ 03.06.2022):

	```
	git clone https://github.com/Azure/MachineLearningNotebooks
	```
- [PyPi](https://pypi.org/project/azureml-sdk) (📥 1.5M / month):
	```
	pip install azureml-sdk
	```
</details>
<details><summary><b><a href="https://github.com/google/ml-metadata">ml-metadata</a></b> (🥉28 ·  ⭐ 470) - For recording and retrieving metadata associated with ML.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/google/ml-metadata) (👨‍💻 15 · 🔀 91 · 📥 1.7K · 📦 220 · 📋 86 - 27% open · ⏱️ 09.06.2022):

	```
	git clone https://github.com/google/ml-metadata
	```
- [PyPi](https://pypi.org/project/ml-metadata) (📥 620K / month):
	```
	pip install ml-metadata
	```
</details>
<details><summary><b><a href="https://github.com/guildai/guildai">Guild AI</a></b> (🥉27 ·  ⭐ 710) - Experiment tracking, ML developer tools. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/guildai/guildai) (👨‍💻 20 · 🔀 63 · 📥 1 · 📦 51 · 📋 360 - 44% open · ⏱️ 08.06.2022):

	```
	git clone https://github.com/guildai/guildai
	```
- [PyPi](https://pypi.org/project/guildai) (📥 4K / month):
	```
	pip install guildai
	```
</details>
<details><summary><b><a href="https://github.com/stared/livelossplot">livelossplot</a></b> (🥉23 ·  ⭐ 1.2K) - Live training loss plot in Jupyter Notebook for Keras,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/stared/livelossplot) (👨‍💻 17 · 🔀 140 · 📦 800 · 📋 75 - 6% open · ⏱️ 04.04.2022):

	```
	git clone https://github.com/stared/livelossplot
	```
- [PyPi](https://pypi.org/project/livelossplot) (📥 72K / month):
	```
	pip install livelossplot
	```
</details>
<details><summary><b><a href="https://github.com/labmlai/labml">Labml</a></b> (🥉23 ·  ⭐ 1.1K) - Monitor deep learning model training and hardware usage from your mobile.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/labmlai/labml) (👨‍💻 7 · 🔀 73 · 📦 49 · 📋 26 - 53% open · ⏱️ 09.06.2022):

	```
	git clone https://github.com/labmlai/labml
	```
- [PyPi](https://pypi.org/project/labml) (📥 4.1K / month):
	```
	pip install labml
	```
</details>
<details><summary><b><a href="https://github.com/studioml/studio">Studio.ml</a></b> (🥉21 ·  ⭐ 370 · 💤) - Studio: Simplify and expedite model building process. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/studioml/studio) (👨‍💻 21 · 🔀 51 · 📦 5 · 📋 250 - 22% open · ⏱️ 14.09.2021):

	```
	git clone https://github.com/studioml/studio
	```
- [PyPi](https://pypi.org/project/studioml) (📥 550 / month):
	```
	pip install studioml
	```
</details>
<details><summary><b><a href="https://github.com/instacart/lore">lore</a></b> (🥉19 ·  ⭐ 1.5K) - Lore makes machine learning approachable for Software Engineers and.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/instacart/lore) (👨‍💻 26 · 🔀 120 · 📦 19 · 📋 35 - 45% open · ⏱️ 11.04.2022):

	```
	git clone https://github.com/instacart/lore
	```
- [PyPi](https://pypi.org/project/lore) (📥 870 / month):
	```
	pip install lore
	```
</details>
<details><summary><b><a href="https://github.com/replicate/keepsake">keepsake</a></b> (🥉18 ·  ⭐ 1.6K) - Version control for machine learning. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/replicate/keepsake) (👨‍💻 17 · 🔀 63 · 📋 180 - 63% open · ⏱️ 24.05.2022):

	```
	git clone https://github.com/replicate/keepsake
	```
- [PyPi](https://pypi.org/project/keepsake) (📥 500 / month):
	```
	pip install keepsake
	```
</details>
<details><summary>Show 17 hidden projects...</summary>

- <b><a href="https://github.com/neptune-ai/neptune-client">Neptune.ai</a></b> (🥈29 ·  ⭐ 290) - Experiment tracking tool and model registry. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/Kaggle/kaggle-api">kaggle</a></b> (🥉23 ·  ⭐ 4.8K · 💀) - Official Kaggle API. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/huggingface/knockknock">knockknock</a></b> (🥉23 ·  ⭐ 2.4K · 💀) - Knock Knock: Get notified when your training ends with only two.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/m3dev/gokart">gokart</a></b> (🥉22 ·  ⭐ 250) - Gokart solves reproducibility, task dependencies, constraints of good code,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/pytorch/tnt">TNT</a></b> (🥉21 ·  ⭐ 1.4K · 💀) - Simple tools for logging and visualizing, loading and training. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/waleedka/hiddenlayer">hiddenlayer</a></b> (🥉20 ·  ⭐ 1.6K · 💀) - Neural network graphs and training metrics for.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/microsoft/tensorwatch">TensorWatch</a></b> (🥉19 ·  ⭐ 3.2K · 💀) - Debugging, monitoring and visualization for Python Machine.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/EducationalTestingService/skll">SKLL</a></b> (🥉19 ·  ⭐ 530) - SciKit-Learn Laboratory (SKLL) makes it easy to run machine.. <code>❗Unlicensed</code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/awslabs/mxboard">MXBoard</a></b> (🥉18 ·  ⭐ 330 · 💀) - Logging MXNet data for visualization in TensorBoard. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1X" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/MrPowers/quinn">quinn</a></b> (🥉17 ·  ⭐ 330 · 💀) - pyspark methods to enhance developer productivity. <code>❗Unlicensed</code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/gradsflow/chitra">chitra</a></b> (🥉17 ·  ⭐ 190) - A multi-functional library for full-stack Deep Learning. Simplifies.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/minerva-ml/steppy">steppy</a></b> (🥉16 ·  ⭐ 130 · 💀) - Lightweight, Python library for fast and reproducible experimentation. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/TeamHG-Memex/tensorboard_logger">TensorBoard Logger</a></b> (🥉15 ·  ⭐ 620 · 💀) - Log TensorBoard events without touching TensorFlow. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/datmo/datmo">datmo</a></b> (🥉15 ·  ⭐ 340 · 💀) - Open source production model management tool for data scientists. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/google/caliban">caliban</a></b> (🥉14 ·  ⭐ 430 · 💀) - Research workflows made easy, locally and in the Cloud. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/ModelChimp/modelchimp">ModelChimp</a></b> (🥉13 ·  ⭐ 120 · 💤) - Experiment tracking for machine and deep learning projects. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code>
- <b><a href="https://github.com/jrieke/traintool">traintool</a></b> (🥉6 ·  ⭐ 9 · 💀) - Train off-the-shelf machine learning models in one.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code>
</details>
<br>

## Model Serialization & Deployment

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries to serialize models to files, convert between a variety of model formats, and optimize models for deployment._

<details><summary><b><a href="https://github.com/onnx/onnx">onnx</a></b> (🥇41 ·  ⭐ 13K) - Open standard for machine learning interoperability. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/onnx/onnx) (👨‍💻 240 · 🔀 2.7K · 📥 18K · 📦 7.1K · 📋 1.9K - 10% open · ⏱️ 08.06.2022):

	```
	git clone https://github.com/onnx/onnx
	```
- [PyPi](https://pypi.org/project/onnx) (📥 1.2M / month):
	```
	pip install onnx
	```
- [Conda](https://anaconda.org/conda-forge/onnx) (📥 420K · ⏱️ 24.04.2022):
	```
	conda install -c conda-forge onnx
	```
</details>
<details><summary><b><a href="https://github.com/apple/coremltools">Core ML Tools</a></b> (🥇31 ·  ⭐ 2.7K) - Core ML tools contain supporting tools for Core ML model.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/apple/coremltools) (👨‍💻 120 · 🔀 400 · 📥 4.3K · 📦 920 · 📋 930 - 27% open · ⏱️ 08.06.2022):

	```
	git clone https://github.com/apple/coremltools
	```
- [PyPi](https://pypi.org/project/coremltools) (📥 95K / month):
	```
	pip install coremltools
	```
- [Conda](https://anaconda.org/conda-forge/coremltools) (📥 32K · ⏱️ 15.10.2021):
	```
	conda install -c conda-forge coremltools
	```
</details>
<details><summary><b><a href="https://github.com/pytorch/serve">TorchServe</a></b> (🥈29 ·  ⭐ 2.7K) - Serve, optimize and scale PyTorch models in production. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytorch/serve) (👨‍💻 120 · 🔀 520 · 📥 1.8K · 📋 890 - 14% open · ⏱️ 26.05.2022):

	```
	git clone https://github.com/pytorch/serve
	```
- [PyPi](https://pypi.org/project/torchserve) (📥 23K / month):
	```
	pip install torchserve
	```
- [Conda](https://anaconda.org/pytorch/torchserve) (📥 24K · ⏱️ 13.05.2022):
	```
	conda install -c pytorch torchserve
	```
- [Docker Hub](https://hub.docker.com/r/pytorch/torchserve) (📥 1M · ⭐ 12 · ⏱️ 09.06.2022):
	```
	docker pull pytorch/torchserve
	```
</details>
<details><summary><b><a href="https://github.com/huggingface/huggingface_hub">huggingface_hub</a></b> (🥈28 ·  ⭐ 440) - All the open source things related to the Hugging Face Hub. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/huggingface/huggingface_hub) (👨‍💻 63 · 🔀 100 · 📋 230 - 28% open · ⏱️ 09.06.2022):

	```
	git clone https://github.com/huggingface/huggingface_hub
	```
- [PyPi](https://pypi.org/project/huggingface_hub) (📥 6.9M / month):
	```
	pip install huggingface_hub
	```
- [Conda](https://anaconda.org/conda-forge/huggingface_hub) (📥 160K · ⏱️ 25.05.2022):
	```
	conda install -c conda-forge huggingface_hub
	```
</details>
<details><summary><b><a href="https://github.com/openai/triton">triton</a></b> (🥈27 ·  ⭐ 3.7K) - Development repository for the Triton language and compiler. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/openai/triton) (👨‍💻 36 · 🔀 270 · 📦 110 · 📋 200 - 36% open · ⏱️ 08.06.2022):

	```
	git clone https://github.com/openai/triton
	```
- [PyPi](https://pypi.org/project/triton) (📥 73K / month):
	```
	pip install triton
	```
</details>
<details><summary><b><a href="https://github.com/bentoml/BentoML">BentoML</a></b> (🥈27 ·  ⭐ 3.5K) - The Unified Model Serving Framework. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/bentoml/BentoML) (👨‍💻 110 · 🔀 400 · 📥 1.5K · 📋 590 - 9% open · ⏱️ 09.06.2022):

	```
	git clone https://github.com/bentoml/BentoML
	```
- [PyPi](https://pypi.org/project/bentoml) (📥 41K / month):
	```
	pip install bentoml
	```
</details>
<details><summary><b><a href="https://github.com/microsoft/hummingbird">Hummingbird</a></b> (🥈26 ·  ⭐ 2.8K) - Hummingbird compiles trained ML models into tensor computation for.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/microsoft/hummingbird) (👨‍💻 29 · 🔀 220 · 📥 170 · 📦 32 · 📋 240 - 19% open · ⏱️ 05.06.2022):

	```
	git clone https://github.com/microsoft/hummingbird
	```
- [PyPi](https://pypi.org/project/hummingbird-ml) (📥 3.1K / month):
	```
	pip install hummingbird-ml
	```
- [Conda](https://anaconda.org/conda-forge/hummingbird-ml) (📥 8.1K · ⏱️ 02.05.2022):
	```
	conda install -c conda-forge hummingbird-ml
	```
</details>
<details><summary><b><a href="https://github.com/BayesWitnesses/m2cgen">m2cgen</a></b> (🥈26 ·  ⭐ 2.1K) - Transform ML models into a native code (Java, C, Python, Go, JavaScript,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/BayesWitnesses/m2cgen) (👨‍💻 13 · 🔀 180 · 📥 19 · 📦 35 · 📋 87 - 24% open · ⏱️ 23.05.2022):

	```
	git clone https://github.com/BayesWitnesses/m2cgen
	```
- [PyPi](https://pypi.org/project/m2cgen) (📥 42K / month):
	```
	pip install m2cgen
	```
</details>
<details><summary><b><a href="https://github.com/cortexlabs/cortex">cortex</a></b> (🥉25 ·  ⭐ 7.8K) - Production infrastructure for machine learning at scale. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/cortexlabs/cortex) (👨‍💻 24 · 🔀 580 · 📋 1.1K - 9% open · ⏱️ 23.04.2022):

	```
	git clone https://github.com/cortexlabs/cortex
	```
- [PyPi](https://pypi.org/project/cortex) (📥 1.6K / month):
	```
	pip install cortex
	```
</details>
<details><summary><b><a href="https://github.com/nok/sklearn-porter">sklearn-porter</a></b> (🥉25 ·  ⭐ 1.2K) - Transpile trained scikit-learn estimators to C, Java,.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/nok/sklearn-porter) (👨‍💻 12 · 🔀 160 · 📦 43 · 📋 67 - 49% open · ⏱️ 22.05.2022):

	```
	git clone https://github.com/nok/sklearn-porter
	```
- [PyPi](https://pypi.org/project/sklearn-porter) (📥 280 / month):
	```
	pip install sklearn-porter
	```
</details>
<details><summary><b><a href="https://github.com/gmalivenko/pytorch2keras">pytorch2keras</a></b> (🥉17 ·  ⭐ 800 · 💤) - PyTorch to Keras model convertor. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/gmalivenko/pytorch2keras) (👨‍💻 13 · 🔀 130 · 📦 46 · 📋 120 - 44% open · ⏱️ 06.08.2021):

	```
	git clone https://github.com/gmalivenko/pytorch2keras
	```
- [PyPi](https://pypi.org/project/pytorch2keras) (📥 670 / month):
	```
	pip install pytorch2keras
	```
</details>
<details><summary><b><a href="https://github.com/nebuly-ai/nebullvm">nebullvm</a></b> (🥉15 ·  ⭐ 1.2K · 🐣) - Easy-to-use library to boost AI inference leveraging state-of-.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/nebuly-ai/nebullvm) (👨‍💻 7 · 🔀 55 · 📦 1 · 📋 36 - 58% open · ⏱️ 07.06.2022):

	```
	git clone https://github.com/nebuly-ai/nebullvm
	```
- [PyPi](https://pypi.org/project/nebullvm) (📥 600 / month):
	```
	pip install nebullvm
	```
</details>
<details><summary>Show 4 hidden projects...</summary>

- <b><a href="https://github.com/microsoft/MMdnn">mmdnn</a></b> (🥉25 ·  ⭐ 5.6K · 💀) - MMdnn is a set of tools to help users inter-operate among different deep.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/larq/compute-engine">Larq Compute Engine</a></b> (🥉21 ·  ⭐ 190) - Highly optimized inference engine for Binarized.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/riga/tfdeploy">tfdeploy</a></b> (🥉16 ·  ⭐ 350 · 💀) - Deploy tensorflow graphs for fast evaluation and export to.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/backprop-ai/backprop">backprop</a></b> (🥉9 ·  ⭐ 230 · 💀) - Backprop makes it simple to use, finetune, and deploy state-.. <code>❗Unlicensed</code>
</details>
<br>

## Model Interpretability

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries to visualize, explain, debug, evaluate, and interpret machine learning models._

<details><summary><b><a href="https://github.com/slundberg/shap">shap</a></b> (🥇40 ·  ⭐ 17K) - A game theoretic approach to explain the output of any machine learning model. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/slundberg/shap) (👨‍💻 180 · 🔀 2.5K · 📦 5.6K · 📋 2K - 69% open · ⏱️ 24.05.2022):

	```
	git clone https://github.com/slundberg/shap
	```
- [PyPi](https://pypi.org/project/shap) (📥 5.1M / month):
	```
	pip install shap
	```
- [Conda](https://anaconda.org/conda-forge/shap) (📥 1.2M · ⏱️ 23.01.2022):
	```
	conda install -c conda-forge shap
	```
</details>
<details><summary><b><a href="https://github.com/arviz-devs/arviz">arviz</a></b> (🥇34 ·  ⭐ 1.2K) - Exploratory analysis of Bayesian models with Python. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/arviz-devs/arviz) (👨‍💻 120 · 🔀 280 · 📥 110 · 📦 2.4K · 📋 720 - 20% open · ⏱️ 18.05.2022):

	```
	git clone https://github.com/arviz-devs/arviz
	```
- [PyPi](https://pypi.org/project/arviz) (📥 620K / month):
	```
	pip install arviz
	```
- [Conda](https://anaconda.org/conda-forge/arviz) (📥 730K · ⏱️ 17.05.2022):
	```
	conda install -c conda-forge arviz
	```
</details>
<details><summary><b><a href="https://github.com/lutzroeder/netron">Netron</a></b> (🥇32 ·  ⭐ 19K) - Visualizer for neural network, deep learning, and machine.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/lutzroeder/netron) (🔀 2.1K · 📥 22K · 📦 7 · 📋 800 - 2% open · ⏱️ 09.06.2022):

	```
	git clone https://github.com/lutzroeder/netron
	```
- [PyPi](https://pypi.org/project/netron) (📥 12K / month):
	```
	pip install netron
	```
</details>
<details><summary><b><a href="https://github.com/marcotcr/lime">Lime</a></b> (🥇32 ·  ⭐ 9.9K · 💤) - Lime: Explaining the predictions of any machine learning classifier. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/marcotcr/lime) (👨‍💻 61 · 🔀 1.6K · 📦 2.3K · 📋 570 - 7% open · ⏱️ 29.07.2021):

	```
	git clone https://github.com/marcotcr/lime
	```
- [PyPi](https://pypi.org/project/lime) (📥 560K / month):
	```
	pip install lime
	```
- [Conda](https://anaconda.org/conda-forge/lime) (📥 100K · ⏱️ 28.06.2020):
	```
	conda install -c conda-forge lime
	```
</details>
<details><summary><b><a href="https://github.com/interpretml/interpret">InterpretML</a></b> (🥇32 ·  ⭐ 4.8K) - Fit interpretable models. Explain blackbox machine learning. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/interpretml/interpret) (👨‍💻 29 · 🔀 580 · 📦 220 · 📋 300 - 32% open · ⏱️ 08.06.2022):

	```
	git clone https://github.com/interpretml/interpret
	```
- [PyPi](https://pypi.org/project/interpret) (📥 95K / month):
	```
	pip install interpret
	```
</details>
<details><summary><b><a href="https://github.com/pytorch/captum">Captum</a></b> (🥇31 ·  ⭐ 3.2K) - Model interpretability and understanding for PyTorch. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytorch/captum) (👨‍💻 83 · 🔀 330 · 📦 560 · 📋 360 - 22% open · ⏱️ 19.05.2022):

	```
	git clone https://github.com/pytorch/captum
	```
- [PyPi](https://pypi.org/project/captum) (📥 55K / month):
	```
	pip install captum
	```
- [Conda](https://anaconda.org/conda-forge/captum) (📥 1.1K · ⏱️ 04.03.2022):
	```
	conda install -c conda-forge captum
	```
</details>
<details><summary><b><a href="https://github.com/py-why/dowhy">DoWhy</a></b> (🥈30 ·  ⭐ 4.5K · 📈) - DoWhy is a Python library for causal inference that supports explicit.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/py-why/dowhy) (👨‍💻 52 · 🔀 640 · 📥 31 · 📦 110 · 📋 200 - 27% open · ⏱️ 09.06.2022):

	```
	git clone https://github.com/Microsoft/dowhy
	```
- [PyPi](https://pypi.org/project/dowhy) (📥 110K / month):
	```
	pip install dowhy
	```
- [Conda](https://anaconda.org/conda-forge/dowhy) (📥 5.7K · ⏱️ 21.03.2022):
	```
	conda install -c conda-forge dowhy
	```
</details>
<details><summary><b><a href="https://github.com/MAIF/shapash">shapash</a></b> (🥈30 ·  ⭐ 1.8K) - Shapash makes Machine Learning models transparent and.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/MAIF/shapash) (👨‍💻 34 · 🔀 230 · 📦 74 · 📋 120 - 14% open · ⏱️ 09.05.2022):

	```
	git clone https://github.com/MAIF/shapash
	```
- [PyPi](https://pypi.org/project/shapash) (📥 18K / month):
	```
	pip install shapash
	```
</details>
<details><summary><b><a href="https://github.com/SeldonIO/alibi">Alibi</a></b> (🥈29 ·  ⭐ 1.6K) - Algorithms for explaining machine learning models. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/SeldonIO/alibi) (👨‍💻 18 · 🔀 180 · 📦 170 · 📋 290 - 40% open · ⏱️ 08.06.2022):

	```
	git clone https://github.com/SeldonIO/alibi
	```
- [PyPi](https://pypi.org/project/alibi) (📥 23K / month):
	```
	pip install alibi
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/model-analysis">Model Analysis</a></b> (🥈29 ·  ⭐ 1.2K) - Model analysis tools for TensorFlow. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/model-analysis) (👨‍💻 43 · 🔀 230 · 📋 64 - 23% open · ⏱️ 09.06.2022):

	```
	git clone https://github.com/tensorflow/model-analysis
	```
- [PyPi](https://pypi.org/project/tensorflow-model-analysis) (📥 780K / month):
	```
	pip install tensorflow-model-analysis
	```
</details>
<details><summary><b><a href="https://github.com/oegedijk/explainerdashboard">explainerdashboard</a></b> (🥈28 ·  ⭐ 1.2K) - Quickly build Explainable AI dashboards that show the inner.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/oegedijk/explainerdashboard) (👨‍💻 14 · 🔀 160 · 📦 110 · 📋 180 - 6% open · ⏱️ 23.05.2022):

	```
	git clone https://github.com/oegedijk/explainerdashboard
	```
- [PyPi](https://pypi.org/project/explainerdashboard) (📥 39K / month):
	```
	pip install explainerdashboard
	```
- [Conda](https://anaconda.org/conda-forge/explainerdashboard) (📥 17K · ⏱️ 15.02.2022):
	```
	conda install -c conda-forge explainerdashboard
	```
</details>
<details><summary><b><a href="https://github.com/parrt/dtreeviz">dtreeviz</a></b> (🥈27 ·  ⭐ 2.1K) - A python library for decision tree visualization and model interpretation. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/parrt/dtreeviz) (👨‍💻 19 · 🔀 270 · 📦 390 · 📋 120 - 19% open · ⏱️ 29.04.2022):

	```
	git clone https://github.com/parrt/dtreeviz
	```
- [PyPi](https://pypi.org/project/dtreeviz) (📥 110K / month):
	```
	pip install dtreeviz
	```
- [Conda](https://anaconda.org/conda-forge/dtreeviz) (📥 12K · ⏱️ 29.04.2022):
	```
	conda install -c conda-forge dtreeviz
	```
</details>
<details><summary><b><a href="https://github.com/DistrictDataLabs/yellowbrick">yellowbrick</a></b> (🥈26 ·  ⭐ 3.6K) - Visual analysis and diagnostic tools to facilitate machine.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/DistrictDataLabs/yellowbrick) (👨‍💻 110 · 🔀 500 · 📋 660 - 12% open · ⏱️ 29.05.2022):

	```
	git clone https://github.com/DistrictDataLabs/yellowbrick
	```
- [PyPi](https://pypi.org/project/yellowbrick) (📥 620K / month):
	```
	pip install yellowbrick
	```
- [Conda](https://anaconda.org/conda-forge/yellowbrick) (📥 28K · ⏱️ 24.03.2022):
	```
	conda install -c conda-forge yellowbrick
	```
</details>
<details><summary><b><a href="https://github.com/fairlearn/fairlearn">fairlearn</a></b> (🥈26 ·  ⭐ 1.3K) - A Python package to assess and improve fairness of machine.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/fairlearn/fairlearn) (👨‍💻 67 · 🔀 300 · 📋 360 - 38% open · ⏱️ 09.06.2022):

	```
	git clone https://github.com/fairlearn/fairlearn
	```
- [PyPi](https://pypi.org/project/fairlearn) (📥 96K / month):
	```
	pip install fairlearn
	```
- [Conda](https://anaconda.org/conda-forge/fairlearn) (📥 18K · ⏱️ 07.07.2021):
	```
	conda install -c conda-forge fairlearn
	```
</details>
<details><summary><b><a href="https://github.com/microsoft/responsible-ai-toolbox">responsible-ai-widgets</a></b> (🥈26 ·  ⭐ 500) - This project provides responsible AI user interfaces.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/microsoft/responsible-ai-toolbox) (👨‍💻 24 · 🔀 120 · 📦 30 · 📋 240 - 13% open · ⏱️ 09.06.2022):

	```
	git clone https://github.com/microsoft/responsible-ai-toolbox
	```
- [PyPi](https://pypi.org/project/raiwidgets) (📥 11K / month):
	```
	pip install raiwidgets
	```
</details>
<details><summary><b><a href="https://github.com/Trusted-AI/AIF360">Fairness 360</a></b> (🥈25 ·  ⭐ 1.7K) - A comprehensive set of fairness metrics for datasets and.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/Trusted-AI/AIF360) (👨‍💻 49 · 🔀 550 · 📦 160 · 📋 140 - 55% open · ⏱️ 05.05.2022):

	```
	git clone https://github.com/Trusted-AI/AIF360
	```
- [PyPi](https://pypi.org/project/aif360) (📥 7.3K / month):
	```
	pip install aif360
	```
- [Conda](https://anaconda.org/conda-forge/aif360) (📥 2.2K · ⏱️ 29.09.2021):
	```
	conda install -c conda-forge aif360
	```
</details>
<details><summary><b><a href="https://github.com/Trusted-AI/AIX360">Explainability 360</a></b> (🥈25 ·  ⭐ 1.1K) - Interpretability and explainability of data and.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/Trusted-AI/AIX360) (👨‍💻 29 · 🔀 220 · 📦 45 · 📋 60 - 56% open · ⏱️ 18.02.2022):

	```
	git clone https://github.com/Trusted-AI/AIX360
	```
- [PyPi](https://pypi.org/project/aix360) (📥 1.2K / month):
	```
	pip install aix360
	```
</details>
<details><summary><b><a href="https://github.com/marcotcr/checklist">checklist</a></b> (🥉24 ·  ⭐ 1.7K · 💤) - Beyond Accuracy: Behavioral Testing of NLP models with.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/marcotcr/checklist) (👨‍💻 12 · 🔀 160 · 📦 130 · 📋 83 - 3% open · ⏱️ 28.09.2021):

	```
	git clone https://github.com/marcotcr/checklist
	```
- [PyPi](https://pypi.org/project/checklist) (📥 53K / month):
	```
	pip install checklist
	```
- [Conda](https://anaconda.org/conda-forge/checklist) (📥 3K · ⏱️ 15.07.2021):
	```
	conda install -c conda-forge checklist
	```
</details>
<details><summary><b><a href="https://github.com/quantumblacklabs/causalnex">CausalNex</a></b> (🥉24 ·  ⭐ 1.6K · 💤) - A Python library that helps data scientists to infer.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/quantumblacklabs/causalnex) (👨‍💻 22 · 🔀 170 · 📦 39 · 📋 110 - 16% open · ⏱️ 11.11.2021):

	```
	git clone https://github.com/quantumblacklabs/causalnex
	```
- [PyPi](https://pypi.org/project/causalnex) (📥 1.6K / month):
	```
	pip install causalnex
	```
</details>
<details><summary><b><a href="https://github.com/csinva/imodels">imodels</a></b> (🥉24 ·  ⭐ 780) - Interpretable ML package for concise, transparent, and accurate predictive.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/csinva/imodels) (👨‍💻 11 · 🔀 73 · 📦 18 · 📋 32 - 25% open · ⏱️ 28.05.2022):

	```
	git clone https://github.com/csinva/imodels
	```
- [PyPi](https://pypi.org/project/imodels) (📥 3.3K / month):
	```
	pip install imodels
	```
</details>
<details><summary><b><a href="https://github.com/PAIR-code/lit">LIT</a></b> (🥉22 ·  ⭐ 2.9K) - The Language Interpretability Tool: Interactively analyze NLP models for.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/PAIR-code/lit) (👨‍💻 18 · 🔀 300 · 📦 10 · 📋 100 - 34% open · ⏱️ 15.03.2022):

	```
	git clone https://github.com/PAIR-code/lit
	```
- [PyPi](https://pypi.org/project/lit-nlp) (📥 1.1K / month):
	```
	pip install lit-nlp
	```
- [Conda](https://anaconda.org/conda-forge/lit-nlp) (📥 36K · ⏱️ 09.11.2021):
	```
	conda install -c conda-forge lit-nlp
	```
</details>
<details><summary><b><a href="https://github.com/philipperemy/keract">keract</a></b> (🥉21 ·  ⭐ 990) - Layers Outputs and Gradients in Keras. Made easy. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/philipperemy/keract) (👨‍💻 16 · 🔀 180 · 📦 140 · 📋 87 - 5% open · ⏱️ 10.05.2022):

	```
	git clone https://github.com/philipperemy/keract
	```
- [PyPi](https://pypi.org/project/keract) (📥 1.1K / month):
	```
	pip install keract
	```
</details>
<details><summary><b><a href="https://github.com/sicara/tf-explain">tf-explain</a></b> (🥉21 ·  ⭐ 930) - Interpretability Methods for tf.keras models with Tensorflow 2.x. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/sicara/tf-explain) (👨‍💻 17 · 🔀 97 · 📦 120 · 📋 88 - 42% open · ⏱️ 22.04.2022):

	```
	git clone https://github.com/sicara/tf-explain
	```
- [PyPi](https://pypi.org/project/tf-explain) (📥 2K / month):
	```
	pip install tf-explain
	```
</details>
<details><summary><b><a href="https://github.com/kundajelab/deeplift">deeplift</a></b> (🥉21 ·  ⭐ 640 · 💤) - Public facing deeplift repo. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/kundajelab/deeplift) (👨‍💻 11 · 🔀 150 · 📦 59 · 📋 84 - 42% open · ⏱️ 11.11.2021):

	```
	git clone https://github.com/kundajelab/deeplift
	```
- [PyPi](https://pypi.org/project/deeplift) (📥 870 / month):
	```
	pip install deeplift
	```
</details>
<details><summary><b><a href="https://github.com/interpretml/DiCE">DiCE</a></b> (🥉20 ·  ⭐ 850) - Generate Diverse Counterfactual Explanations for any machine.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/interpretml/DiCE) (👨‍💻 12 · 🔀 120 · 📋 120 - 44% open · ⏱️ 01.06.2022):

	```
	git clone https://github.com/interpretml/DiCE
	```
- [PyPi](https://pypi.org/project/dice-ml) (📥 52K / month):
	```
	pip install dice-ml
	```
</details>
<details><summary><b><a href="https://github.com/PAIR-code/what-if-tool">What-If Tool</a></b> (🥉20 ·  ⭐ 680) - Source code/webpage/demos for the What-If Tool. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/PAIR-code/what-if-tool) (👨‍💻 20 · 🔀 130 · 📋 110 - 53% open · ⏱️ 05.01.2022):

	```
	git clone https://github.com/PAIR-code/what-if-tool
	```
- [PyPi](https://pypi.org/project/witwidget) (📥 7.8K / month):
	```
	pip install witwidget
	```
- [Conda](https://anaconda.org/conda-forge/tensorboard-plugin-wit) (📥 1M · ⏱️ 06.01.2022):
	```
	conda install -c conda-forge tensorboard-plugin-wit
	```
- [npm](https://www.npmjs.com/package/wit-widget) (📥 4.7K / month):
	```
	npm install wit-widget
	```
</details>
<details><summary><b><a href="https://github.com/edublancas/sklearn-evaluation">sklearn-evaluation</a></b> (🥉20 ·  ⭐ 320) - Machine learning model evaluation made easy: plots,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/edublancas/sklearn-evaluation) (👨‍💻 8 · 🔀 28 · 📦 46 · 📋 39 - 23% open · ⏱️ 16.04.2022):

	```
	git clone https://github.com/edublancas/sklearn-evaluation
	```
- [PyPi](https://pypi.org/project/sklearn-evaluation) (📥 980 / month):
	```
	pip install sklearn-evaluation
	```
</details>
<details><summary><b><a href="https://github.com/jalammar/ecco">ecco</a></b> (🥉19 ·  ⭐ 1.4K) - Explain, analyze, and visualize NLP language models. Ecco creates.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/jalammar/ecco) (👨‍💻 10 · 🔀 95 · 📥 19 · 📦 7 · 📋 37 - 40% open · ⏱️ 18.01.2022):

	```
	git clone https://github.com/jalammar/ecco
	```
- [PyPi](https://pypi.org/project/ecco) (📥 280 / month):
	```
	pip install ecco
	```
- [Conda](https://anaconda.org/conda-forge/ecco) (📥 500 · ⏱️ 10.01.2022):
	```
	conda install -c conda-forge ecco
	```
</details>
<details><summary><b><a href="https://github.com/albermax/innvestigate">iNNvestigate</a></b> (🥉18 ·  ⭐ 990 · 💤) - A toolbox to iNNvestigate neural networks predictions!. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/albermax/innvestigate) (👨‍💻 19 · 🔀 220 · 📋 230 - 27% open · ⏱️ 03.08.2021):

	```
	git clone https://github.com/albermax/innvestigate
	```
- [PyPi](https://pypi.org/project/innvestigate) (📥 360 / month):
	```
	pip install innvestigate
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/tcav">tcav</a></b> (🥉18 ·  ⭐ 520 · 💤) - Code for the TCAV ML interpretability project. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/tcav) (👨‍💻 19 · 🔀 130 · 📦 12 · 📋 61 - 11% open · ⏱️ 16.09.2021):

	```
	git clone https://github.com/tensorflow/tcav
	```
- [PyPi](https://pypi.org/project/tcav) (📥 90 / month):
	```
	pip install tcav
	```
</details>
<details><summary><b><a href="https://github.com/EthicalML/xai">XAI</a></b> (🥉15 ·  ⭐ 820 · 💤) - XAI - An eXplainability toolbox for machine learning. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/EthicalML/xai) (👨‍💻 3 · 🔀 120 · 📦 15 · 📋 9 - 22% open · ⏱️ 30.10.2021):

	```
	git clone https://github.com/EthicalML/xai
	```
- [PyPi](https://pypi.org/project/xai) (📥 150 / month):
	```
	pip install xai
	```
</details>
<details><summary><b><a href="https://github.com/marcotcr/anchor">Anchor</a></b> (🥉15 ·  ⭐ 700 · 💤) - Code for High-Precision Model-Agnostic Explanations paper. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/marcotcr/anchor) (👨‍💻 10 · 🔀 97 · 📋 70 - 27% open · ⏱️ 17.11.2021):

	```
	git clone https://github.com/marcotcr/anchor
	```
- [PyPi](https://pypi.org/project/anchor_exp) (📥 1.2K / month):
	```
	pip install anchor_exp
	```
</details>
<details><summary><b><a href="https://github.com/aerdem4/lofo-importance">LOFO</a></b> (🥉14 ·  ⭐ 470) - Leave One Feature Out Importance. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/aerdem4/lofo-importance) (👨‍💻 3 · 🔀 53 · 📦 19 · 📋 18 - 11% open · ⏱️ 27.04.2022):

	```
	git clone https://github.com/aerdem4/lofo-importance
	```
- [PyPi](https://pypi.org/project/lofo-importance) (📥 450 / month):
	```
	pip install lofo-importance
	```
</details>
<details><summary><b><a href="https://github.com/interpretml/interpret-text">interpret-text</a></b> (🥉14 ·  ⭐ 320) - A library that incorporates state-of-the-art explainers for.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/interpretml/interpret-text) (👨‍💻 17 · 🔀 57 · 📋 49 - 67% open · ⏱️ 06.12.2021):

	```
	git clone https://github.com/interpretml/interpret-text
	```
- [PyPi](https://pypi.org/project/interpret-text) (📥 66 / month):
	```
	pip install interpret-text
	```
</details>
<details><summary>Show 18 hidden projects...</summary>

- <b><a href="https://github.com/bmabey/pyLDAvis">pyLDAvis</a></b> (🥈29 ·  ⭐ 1.6K · 💀) - Python library for interactive topic model visualization... <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/tensorflow/lucid">Lucid</a></b> (🥈27 ·  ⭐ 4.4K · 💀) - A collection of infrastructure and tools for research in.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/reiinakano/scikit-plot">scikit-plot</a></b> (🥈27 ·  ⭐ 2.2K · 💀) - An intuitive library to add plotting functionality to.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/TeamHG-Memex/eli5">eli5</a></b> (🥈25 ·  ⭐ 2.5K · 💀) - A library for debugging/inspecting machine learning classifiers and.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/deepchecks/deepchecks">Deep Checks</a></b> (🥈25 ·  ⭐ 1.6K) - Test Suites for Validating ML Models & Data. Deepchecks is.. <code>❗Unlicensed</code>
- <b><a href="https://github.com/raghakot/keras-vis">keras-vis</a></b> (🥉24 ·  ⭐ 2.9K · 💀) - Neural network visualization toolkit for keras. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/ModelOriented/DALEX">DALEX</a></b> (🥉24 ·  ⭐ 1.1K) - moDel Agnostic Language for Exploration and eXplanation. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
- <b><a href="https://github.com/parrt/random-forest-importances">random-forest-importances</a></b> (🥉22 ·  ⭐ 500 · 💀) - Code to compute permutation and drop-column.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/oracle/Skater">Skater</a></b> (🥉20 ·  ⭐ 1K) - Python Library for Model Interpretation/Explanations. <code><a href="https://tldrlegal.com/search?q=UPL-1.0">❗️UPL-1.0</a></code>
- <b><a href="https://github.com/andosa/treeinterpreter">TreeInterpreter</a></b> (🥉20 ·  ⭐ 710 · 💀) - Package for interpreting scikit-learns decision tree.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/dssg/aequitas">aequitas</a></b> (🥉19 ·  ⭐ 480 · 💀) - Bias and Fairness Audit Toolkit. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/tensorflow/fairness-indicators">fairness-indicators</a></b> (🥉19 ·  ⭐ 260) - Tensorflows Fairness Evaluation and Visualization.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/tensorflow/model-card-toolkit">model-card-toolkit</a></b> (🥉17 ·  ⭐ 280) - a tool that leverages rich metadata and lineage.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/MisaOgura/flashtorch">FlashTorch</a></b> (🥉16 ·  ⭐ 670 · 💀) - Visualization toolkit for neural networks in PyTorch! Demo --. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/explainX/explainx">ExplainX.ai</a></b> (🥉15 ·  ⭐ 320 · 💀) - Explainable AI framework for data scientists. Explain & debug any.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/SAP/contextual-ai">contextual-ai</a></b> (🥉13 ·  ⭐ 80 · 💤) - Contextual AI adds explainability to different stages of.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/suinleelab/attributionpriors">Attribution Priors</a></b> (🥉10 ·  ⭐ 99 · 💀) - Tools for training explainable models using.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/intuit/bias-detector">bias-detector</a></b> (🥉10 ·  ⭐ 38) -  <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
</details>
<br>

## Vector Similarity Search (ANN)

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for Approximate Nearest Neighbor Search and Vector Indexing/Similarity Search._

🔗&nbsp;<b><a href="https://github.com/erikbern/ann-benchmarks">ANN Benchmarks</a></b> ( ⭐ 2.9K)  - Benchmarks of approximate nearest neighbor libraries in Python.

<details><summary><b><a href="https://github.com/milvus-io/milvus">Milvus</a></b> (🥇36 ·  ⭐ 11K) - Vector database for scalable similarity search and AI applications. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/milvus-io/milvus) (👨‍💻 210 · 🔀 1.4K · 📥 32K · 📋 5.2K - 4% open · ⏱️ 09.06.2022):

	```
	git clone https://github.com/milvus-io/milvus
	```
- [PyPi](https://pypi.org/project/pymilvus) (📥 34K / month):
	```
	pip install pymilvus
	```
- [Docker Hub](https://hub.docker.com/r/milvusdb/milvus) (📥 970K · ⭐ 19 · ⏱️ 13.05.2022):
	```
	docker pull milvusdb/milvus
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/faiss">Faiss</a></b> (🥇34 ·  ⭐ 17K) - A library for efficient similarity search and clustering of dense vectors. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/facebookresearch/faiss) (👨‍💻 98 · 🔀 2.6K · 📦 650 · 📋 1.8K - 9% open · ⏱️ 17.05.2022):

	```
	git clone https://github.com/facebookresearch/faiss
	```
- [PyPi](https://pypi.org/project/pymilvus) (📥 34K / month):
	```
	pip install pymilvus
	```
- [Conda](https://anaconda.org/conda-forge/faiss) (📥 350K · ⏱️ 09.02.2022):
	```
	conda install -c conda-forge faiss
	```
</details>
<details><summary><b><a href="https://github.com/spotify/annoy">Annoy</a></b> (🥈32 ·  ⭐ 9.9K) - Approximate Nearest Neighbors in C++/Python optimized for memory usage.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/spotify/annoy) (👨‍💻 81 · 🔀 1K · 📦 2.1K · 📋 340 - 10% open · ⏱️ 25.03.2022):

	```
	git clone https://github.com/spotify/annoy
	```
- [PyPi](https://pypi.org/project/annoy) (📥 1.3M / month):
	```
	pip install annoy
	```
- [Conda](https://anaconda.org/conda-forge/python-annoy) (📥 240K · ⏱️ 23.04.2022):
	```
	conda install -c conda-forge python-annoy
	```
</details>
<details><summary><b><a href="https://github.com/nmslib/nmslib">NMSLIB</a></b> (🥈31 ·  ⭐ 2.8K) - Non-Metric Space Library (NMSLIB): An efficient similarity search.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/nmslib/nmslib) (👨‍💻 48 · 🔀 390 · 📦 620 · 📋 400 - 14% open · ⏱️ 31.05.2022):

	```
	git clone https://github.com/nmslib/nmslib
	```
- [PyPi](https://pypi.org/project/nmslib) (📥 99K / month):
	```
	pip install nmslib
	```
- [Conda](https://anaconda.org/conda-forge/nmslib) (📥 54K · ⏱️ 15.04.2022):
	```
	conda install -c conda-forge nmslib
	```
</details>
<details><summary><b><a href="https://github.com/lmcinnes/pynndescent">PyNNDescent</a></b> (🥈30 ·  ⭐ 630 · 📈) - A Python nearest neighbor descent for approximate nearest.. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/lmcinnes/pynndescent) (👨‍💻 20 · 🔀 86 · 📦 1.7K · 📋 100 - 46% open · ⏱️ 09.06.2022):

	```
	git clone https://github.com/lmcinnes/pynndescent
	```
- [PyPi](https://pypi.org/project/pynndescent) (📥 3.6M / month):
	```
	pip install pynndescent
	```
- [Conda](https://anaconda.org/conda-forge/pynndescent) (📥 650K · ⏱️ 15.05.2022):
	```
	conda install -c conda-forge pynndescent
	```
</details>
<details><summary><b><a href="https://github.com/nmslib/hnswlib">hnswlib</a></b> (🥉28 ·  ⭐ 2K) - Header-only C++/python library for fast approximate nearest neighbors. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/nmslib/hnswlib) (👨‍💻 56 · 🔀 370 · 📦 240 · 📋 240 - 48% open · ⏱️ 16.04.2022):

	```
	git clone https://github.com/nmslib/hnswlib
	```
- [PyPi](https://pypi.org/project/hnswlib) (📥 330K / month):
	```
	pip install hnswlib
	```
- [Conda](https://anaconda.org/conda-forge/hnswlib) (📥 42K · ⏱️ 16.04.2022):
	```
	conda install -c conda-forge hnswlib
	```
</details>
<details><summary><b><a href="https://github.com/yahoojapan/NGT">NGT</a></b> (🥉20 ·  ⭐ 910) - Nearest Neighbor Search with Neighborhood Graph and Tree for High-.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/yahoojapan/NGT) (👨‍💻 13 · 🔀 92 · 📋 99 - 12% open · ⏱️ 03.06.2022):

	```
	git clone https://github.com/yahoojapan/NGT
	```
- [PyPi](https://pypi.org/project/ngt) (📥 17K / month):
	```
	pip install ngt
	```
</details>
<details><summary>Show 4 hidden projects...</summary>

- <b><a href="https://github.com/plasticityai/magnitude">Magnitude</a></b> (🥉23 ·  ⭐ 1.5K · 💀) - A fast, efficient universal vector embedding utility package. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/pixelogik/NearPy">NearPy</a></b> (🥉20 ·  ⭐ 710 · 💀) - Python framework for fast (approximated) nearest neighbour search in.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/kakao/n2">N2</a></b> (🥉19 ·  ⭐ 520 · 💀) - TOROS N2 - lightweight approximate Nearest Neighbor library which runs.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/facebookresearch/pysparnn">PySparNN</a></b> (🥉11 ·  ⭐ 900 · 💀) - Approximate Nearest Neighbor Search for Sparse Data in Python!. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
</details>
<br>

## Probabilistics & Statistics

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries providing capabilities for probabilistic programming/reasoning, bayesian inference, gaussian processes, or statistics._

<details><summary><b><a href="https://github.com/pyro-ppl/pyro">Pyro</a></b> (🥇33 ·  ⭐ 7.5K) - Deep universal probabilistic programming with Python and PyTorch. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pyro-ppl/pyro) (👨‍💻 130 · 🔀 890 · 📦 740 · 📋 960 - 19% open · ⏱️ 08.06.2022):

	```
	git clone https://github.com/pyro-ppl/pyro
	```
- [PyPi](https://pypi.org/project/pyro-ppl) (📥 320K / month):
	```
	pip install pyro-ppl
	```
- [Conda](https://anaconda.org/conda-forge/pyro-ppl) (📥 11K · ⏱️ 24.03.2022):
	```
	conda install -c conda-forge pyro-ppl
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/probability">tensorflow-probability</a></b> (🥇33 ·  ⭐ 3.7K) - Probabilistic reasoning and statistical analysis in.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/probability) (👨‍💻 450 · 🔀 940 · 📋 1.2K - 41% open · ⏱️ 07.06.2022):

	```
	git clone https://github.com/tensorflow/probability
	```
- [PyPi](https://pypi.org/project/tensorflow-probability) (📥 900K / month):
	```
	pip install tensorflow-probability
	```
- [Conda](https://anaconda.org/conda-forge/tensorflow-probability) (📥 59K · ⏱️ 09.06.2022):
	```
	conda install -c conda-forge tensorflow-probability
	```
</details>
<details><summary><b><a href="https://github.com/pgmpy/pgmpy">pgmpy</a></b> (🥈32 ·  ⭐ 2.1K) - Python Library for learning (Structure and Parameter), inference.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pgmpy/pgmpy) (👨‍💻 110 · 🔀 620 · 📥 150 · 📦 360 · 📋 760 - 25% open · ⏱️ 25.05.2022):

	```
	git clone https://github.com/pgmpy/pgmpy
	```
- [PyPi](https://pypi.org/project/pgmpy) (📥 86K / month):
	```
	pip install pgmpy
	```
</details>
<details><summary><b><a href="https://github.com/GPflow/GPflow">GPflow</a></b> (🥈32 ·  ⭐ 1.6K) - Gaussian processes in TensorFlow. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/GPflow/GPflow) (👨‍💻 77 · 🔀 410 · 📦 370 · 📋 750 - 14% open · ⏱️ 07.06.2022):

	```
	git clone https://github.com/GPflow/GPflow
	```
- [PyPi](https://pypi.org/project/gpflow) (📥 29K / month):
	```
	pip install gpflow
	```
- [Conda](https://anaconda.org/conda-forge/gpflow) (📥 12K · ⏱️ 24.05.2022):
	```
	conda install -c conda-forge gpflow
	```
</details>
<details><summary><b><a href="https://github.com/cornellius-gp/gpytorch">GPyTorch</a></b> (🥈31 ·  ⭐ 2.8K) - A highly efficient and modular implementation of Gaussian Processes.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/cornellius-gp/gpytorch) (👨‍💻 93 · 🔀 410 · 📦 600 · 📋 1.1K - 24% open · ⏱️ 03.06.2022):

	```
	git clone https://github.com/cornellius-gp/gpytorch
	```
- [PyPi](https://pypi.org/project/gpytorch) (📥 190K / month):
	```
	pip install gpytorch
	```
- [Conda](https://anaconda.org/conda-forge/gpytorch) (📥 36K · ⏱️ 14.12.2021):
	```
	conda install -c conda-forge gpytorch
	```
</details>
<details><summary><b><a href="https://github.com/hmmlearn/hmmlearn">hmmlearn</a></b> (🥈31 ·  ⭐ 2.5K) - Hidden Markov Models in Python, with scikit-learn like API. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/hmmlearn/hmmlearn) (👨‍💻 40 · 🔀 660 · 📦 1.3K · 📋 380 - 12% open · ⏱️ 24.05.2022):

	```
	git clone https://github.com/hmmlearn/hmmlearn
	```
- [PyPi](https://pypi.org/project/hmmlearn) (📥 240K / month):
	```
	pip install hmmlearn
	```
- [Conda](https://anaconda.org/conda-forge/hmmlearn) (📥 120K · ⏱️ 12.02.2022):
	```
	conda install -c conda-forge hmmlearn
	```
</details>
<details><summary><b><a href="https://github.com/rlabbe/filterpy">filterpy</a></b> (🥈30 ·  ⭐ 2.3K) - Python Kalman filtering and optimal estimation library. Implements.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/rlabbe/filterpy) (👨‍💻 42 · 🔀 500 · 📦 1.4K · 📋 200 - 21% open · ⏱️ 03.06.2022):

	```
	git clone https://github.com/rlabbe/filterpy
	```
- [PyPi](https://pypi.org/project/filterpy) (📥 690K / month):
	```
	pip install filterpy
	```
- [Conda](https://anaconda.org/conda-forge/filterpy) (📥 100K · ⏱️ 05.05.2020):
	```
	conda install -c conda-forge filterpy
	```
</details>
<details><summary><b><a href="https://github.com/jmschrei/pomegranate">pomegranate</a></b> (🥈28 ·  ⭐ 2.9K) - Fast, flexible and easy to use probabilistic modelling in Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jmschrei/pomegranate) (👨‍💻 65 · 🔀 530 · 📦 700 · 📋 660 - 7% open · ⏱️ 21.02.2022):

	```
	git clone https://github.com/jmschrei/pomegranate
	```
- [PyPi](https://pypi.org/project/pomegranate) (📥 38K / month):
	```
	pip install pomegranate
	```
- [Conda](https://anaconda.org/conda-forge/pomegranate) (📥 87K · ⏱️ 16.11.2021):
	```
	conda install -c conda-forge pomegranate
	```
</details>
<details><summary><b><a href="https://github.com/twopirllc/pandas-ta">pandas-ta</a></b> (🥈28 ·  ⭐ 2.6K) - Technical Analysis Indicators - Pandas TA is an easy to use.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/twopirllc/pandas-ta) (👨‍💻 44 · 🔀 570 · 📦 680 · 📋 400 - 13% open · ⏱️ 07.06.2022):

	```
	git clone https://github.com/twopirllc/pandas-ta
	```
- [PyPi](https://pypi.org/project/pandas-ta) (📥 67K / month):
	```
	pip install pandas-ta
	```
- [Conda](https://anaconda.org/conda-forge/pandas-ta) (📥 970 · ⏱️ 05.10.2021):
	```
	conda install -c conda-forge pandas-ta
	```
</details>
<details><summary><b><a href="https://github.com/SALib/SALib">SALib</a></b> (🥉26 ·  ⭐ 600) - Sensitivity Analysis Library in Python. Contains Sobol, Morris, FAST, and.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/SALib/SALib) (👨‍💻 37 · 🔀 180 · 📋 270 - 14% open · ⏱️ 05.06.2022):

	```
	git clone https://github.com/SALib/SALib
	```
- [PyPi](https://pypi.org/project/salib) (📥 140K / month):
	```
	pip install salib
	```
- [Conda](https://anaconda.org/conda-forge/salib) (📥 82K · ⏱️ 04.09.2021):
	```
	conda install -c conda-forge salib
	```
</details>
<details><summary><b><a href="https://github.com/bambinos/bambi">bambi</a></b> (🥉25 ·  ⭐ 780) - BAyesian Model-Building Interface (Bambi) in Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/bambinos/bambi) (👨‍💻 26 · 🔀 85 · 📦 28 · 📋 250 - 16% open · ⏱️ 09.06.2022):

	```
	git clone https://github.com/bambinos/bambi
	```
- [PyPi](https://pypi.org/project/bambi) (📥 5.6K / month):
	```
	pip install bambi
	```
- [Conda](https://anaconda.org/conda-forge/bambi) (📥 8.4K · ⏱️ 07.06.2022):
	```
	conda install -c conda-forge bambi
	```
</details>
<details><summary><b><a href="https://github.com/baal-org/baal">Baal</a></b> (🥉19 ·  ⭐ 600) - Library to enable Bayesian active learning in your research or labeling.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/baal-org/baal) (👨‍💻 14 · 🔀 54 · 📋 76 - 25% open · ⏱️ 20.05.2022):

	```
	git clone https://github.com/ElementAI/baal
	```
- [PyPi](https://pypi.org/project/baal) (📥 710 / month):
	```
	pip install baal
	```
- [Conda](https://anaconda.org/conda-forge/baal) (📥 1.7K · ⏱️ 04.05.2022):
	```
	conda install -c conda-forge baal
	```
</details>
<details><summary>Show 10 hidden projects...</summary>

- <b><a href="https://github.com/pymc-devs/pymc">PyMC3</a></b> (🥇37 ·  ⭐ 6.7K) - Probabilistic Programming in Python: Bayesian Modeling and.. <code>❗Unlicensed</code>
- <b><a href="https://github.com/raphaelvallat/pingouin">pingouin</a></b> (🥈28 ·  ⭐ 1.1K) - Statistical package in Python based on Pandas. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
- <b><a href="https://github.com/pydata/patsy">patsy</a></b> (🥉27 ·  ⭐ 830 · 💤) - Describing statistical models in Python using symbolic formulas. <code>❗Unlicensed</code>
- <b><a href="https://github.com/blei-lab/edward">Edward</a></b> (🥉26 ·  ⭐ 4.7K · 💀) - A probabilistic programming language in TensorFlow. Deep.. <code>❗Unlicensed</code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/uber/orbit">Orbit</a></b> (🥉24 ·  ⭐ 1.4K) - A Python package for Bayesian forecasting with object-oriented.. <code>❗Unlicensed</code>
- <b><a href="https://github.com/maximtrp/scikit-posthocs">scikit-posthocs</a></b> (🥉20 ·  ⭐ 240) - Multiple Pairwise Comparisons (Post Hoc) Tests in Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/pyro-ppl/funsor">Funsor</a></b> (🥉20 ·  ⭐ 190) - Functional tensors for probabilistic programming. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/stan-dev/pystan">PyStan</a></b> (🥉20 ·  ⭐ 190) - PyStan, a Python interface to Stan, a platform for statistical modeling... <code><a href="http://bit.ly/3hkKRql">ISC</a></code>
- <b><a href="https://github.com/mattjj/pyhsmm">pyhsmm</a></b> (🥉18 ·  ⭐ 510 · 💀) -  <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/thu-ml/zhusuan">ZhuSuan</a></b> (🥉15 ·  ⭐ 2.1K · 💀) - A probabilistic programming library for Bayesian deep learning,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
</details>
<br>

## Adversarial Robustness

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for testing the robustness of machine learning models against attacks with adversarial/malicious examples._

<details><summary><b><a href="https://github.com/Trusted-AI/adversarial-robustness-toolbox">ART</a></b> (🥇33 ·  ⭐ 3K) - Adversarial Robustness Toolbox (ART) - Python Library for Machine Learning.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/Trusted-AI/adversarial-robustness-toolbox) (👨‍💻 100 · 🔀 810 · 📦 230 · 📋 680 - 12% open · ⏱️ 04.06.2022):

	```
	git clone https://github.com/Trusted-AI/adversarial-robustness-toolbox
	```
- [PyPi](https://pypi.org/project/adversarial-robustness-toolbox) (📥 6.7K / month):
	```
	pip install adversarial-robustness-toolbox
	```
- [Conda](https://anaconda.org/conda-forge/adversarial-robustness-toolbox) (📥 10K · ⏱️ 04.06.2022):
	```
	conda install -c conda-forge adversarial-robustness-toolbox
	```
</details>
<details><summary><b><a href="https://github.com/QData/TextAttack">TextAttack</a></b> (🥈31 ·  ⭐ 2K · 📈) - TextAttack is a Python framework for adversarial attacks, data.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/QData/TextAttack) (👨‍💻 52 · 🔀 240 · 📦 79 · 📋 210 - 14% open · ⏱️ 08.06.2022):

	```
	git clone https://github.com/QData/TextAttack
	```
- [PyPi](https://pypi.org/project/textattack) (📥 8.9K / month):
	```
	pip install textattack
	```
- [Conda](https://anaconda.org/conda-forge/textattack) (📥 2.9K · ⏱️ 29.06.2021):
	```
	conda install -c conda-forge textattack
	```
</details>
<details><summary><b><a href="https://github.com/cleverhans-lab/cleverhans">CleverHans</a></b> (🥈29 ·  ⭐ 5.5K · 💤) - An adversarial example library for constructing attacks,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/cleverhans-lab/cleverhans) (👨‍💻 130 · 🔀 1.3K · 📦 330 · 📋 450 - 5% open · ⏱️ 23.09.2021):

	```
	git clone https://github.com/cleverhans-lab/cleverhans
	```
- [PyPi](https://pypi.org/project/cleverhans) (📥 1.4K / month):
	```
	pip install cleverhans
	```
- [Conda](https://anaconda.org/conda-forge/cleverhans) (📥 3.1K · ⏱️ 29.07.2021):
	```
	conda install -c conda-forge cleverhans
	```
</details>
<details><summary><b><a href="https://github.com/bethgelab/foolbox">Foolbox</a></b> (🥈29 ·  ⭐ 2.2K) - A Python toolbox to create adversarial examples that fool neural networks.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/bethgelab/foolbox) (👨‍💻 32 · 🔀 390 · 📦 300 · 📋 350 - 5% open · ⏱️ 25.05.2022):

	```
	git clone https://github.com/bethgelab/foolbox
	```
- [PyPi](https://pypi.org/project/foolbox) (📥 2.6K / month):
	```
	pip install foolbox
	```
- [Conda](https://anaconda.org/conda-forge/foolbox) (📥 6.1K · ⏱️ 30.04.2021):
	```
	conda install -c conda-forge foolbox
	```
</details>
<details><summary><b><a href="https://github.com/MadryLab/robustness">robustness</a></b> (🥉19 ·  ⭐ 700) - A library for experimenting with, training and evaluating neural.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/MadryLab/robustness) (👨‍💻 13 · 🔀 140 · 📦 78 · 📋 74 - 24% open · ⏱️ 14.02.2022):

	```
	git clone https://github.com/MadryLab/robustness
	```
- [PyPi](https://pypi.org/project/robustness) (📥 1.1K / month):
	```
	pip install robustness
	```
- [Conda](https://anaconda.org/conda-forge/robustness) (📥 3.6K · ⏱️ 30.04.2021):
	```
	conda install -c conda-forge robustness
	```
</details>
<details><summary><b><a href="https://github.com/advboxes/AdvBox">AdvBox</a></b> (🥉16 ·  ⭐ 1.2K) - Advbox is a toolbox to generate adversarial examples that fool neural.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/advboxes/AdvBox) (👨‍💻 19 · 🔀 240 · 📋 38 - 21% open · ⏱️ 15.05.2022):

	```
	git clone https://github.com/advboxes/AdvBox
	```
- [PyPi](https://pypi.org/project/advbox) (📥 30 / month):
	```
	pip install advbox
	```
</details>
<details><summary>Show 3 hidden projects...</summary>

- <b><a href="https://github.com/BorealisAI/advertorch">advertorch</a></b> (🥉21 ·  ⭐ 1.1K) - A Toolbox for Adversarial Robustness Research. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/textflint/textflint">textflint</a></b> (🥉16 ·  ⭐ 560) - Unified Multilingual Robustness Evaluation Toolkit for Natural.. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
- <b><a href="https://github.com/airbnb/artificial-adversary">Adversary</a></b> (🥉14 ·  ⭐ 370 · 💀) - Tool to generate adversarial text examples and test machine.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
</details>
<br>

## GPU Utilities

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries that require and make use of CUDA/GPU system capabilities to optimize data handling and machine learning tasks._

<details><summary><b><a href="https://github.com/cupy/cupy">CuPy</a></b> (🥇38 ·  ⭐ 6.1K) - NumPy & SciPy for GPU. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/cupy/cupy) (👨‍💻 300 · 🔀 570 · 📥 32K · 📦 1.1K · 📋 1.7K - 20% open · ⏱️ 06.06.2022):

	```
	git clone https://github.com/cupy/cupy
	```
- [PyPi](https://pypi.org/project/cupy) (📥 26K / month):
	```
	pip install cupy
	```
- [Conda](https://anaconda.org/conda-forge/cupy) (📥 1.5M · ⏱️ 01.06.2022):
	```
	conda install -c conda-forge cupy
	```
- [Docker Hub](https://hub.docker.com/r/cupy/cupy) (📥 55K · ⭐ 7 · ⏱️ 26.05.2022):
	```
	docker pull cupy/cupy
	```
</details>
<details><summary><b><a href="https://github.com/rapidsai/cudf">cuDF</a></b> (🥇30 ·  ⭐ 4.8K) - cuDF - GPU DataFrame Library. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/rapidsai/cudf) (👨‍💻 240 · 🔀 600 · 📋 4.6K - 15% open · ⏱️ 09.06.2022):

	```
	git clone https://github.com/rapidsai/cudf
	```
- [PyPi](https://pypi.org/project/cudf) (📥 1.5K / month):
	```
	pip install cudf
	```
</details>
<details><summary><b><a href="https://github.com/NVIDIA/apex">Apex</a></b> (🥈28 ·  ⭐ 6.4K) - A PyTorch Extension: Tools for easy mixed precision and distributed.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/NVIDIA/apex) (👨‍💻 93 · 🔀 960 · 📦 1K · 📋 970 - 56% open · ⏱️ 31.05.2022):

	```
	git clone https://github.com/NVIDIA/apex
	```
- [Conda](https://anaconda.org/conda-forge/nvidia-apex) (📥 87K · ⏱️ 06.04.2022):
	```
	conda install -c conda-forge nvidia-apex
	```
</details>
<details><summary><b><a href="https://github.com/wookayin/gpustat">gpustat</a></b> (🥈28 ·  ⭐ 2.9K) - A simple command-line utility for querying and monitoring GPU status. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/wookayin/gpustat) (👨‍💻 13 · 🔀 220 · 📦 1.9K · 📋 82 - 24% open · ⏱️ 31.05.2022):

	```
	git clone https://github.com/wookayin/gpustat
	```
- [PyPi](https://pypi.org/project/gpustat) (📥 640K / month):
	```
	pip install gpustat
	```
- [Conda](https://anaconda.org/conda-forge/gpustat) (📥 130K · ⏱️ 24.11.2020):
	```
	conda install -c conda-forge gpustat
	```
</details>
<details><summary><b><a href="https://github.com/rapidsai/cuml">cuML</a></b> (🥈28 ·  ⭐ 2.8K) - cuML - RAPIDS Machine Learning Library. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/rapidsai/cuml) (👨‍💻 150 · 🔀 400 · 📋 2K - 32% open · ⏱️ 03.06.2022):

	```
	git clone https://github.com/rapidsai/cuml
	```
- [PyPi](https://pypi.org/project/cuml) (📥 720 / month):
	```
	pip install cuml
	```
</details>
<details><summary><b><a href="https://github.com/arrayfire/arrayfire">ArrayFire</a></b> (🥈27 ·  ⭐ 3.8K) - ArrayFire: a general purpose GPU library. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/arrayfire/arrayfire) (👨‍💻 81 · 🔀 490 · 📥 2.4K · 📋 1.5K - 15% open · ⏱️ 06.06.2022):

	```
	git clone https://github.com/arrayfire/arrayfire
	```
- [PyPi](https://pypi.org/project/arrayfire) (📥 560 / month):
	```
	pip install arrayfire
	```
</details>
<details><summary><b><a href="https://github.com/NVIDIA/DALI">DALI</a></b> (🥉24 ·  ⭐ 3.9K) - A GPU-accelerated library containing highly optimized building blocks.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/NVIDIA/DALI) (👨‍💻 74 · 🔀 490 · 📋 1.2K - 14% open · ⏱️ 09.06.2022):

	```
	git clone https://github.com/NVIDIA/DALI
	```
</details>
<details><summary><b><a href="https://github.com/rapidsai/cugraph">cuGraph</a></b> (🥉24 ·  ⭐ 1K) - cuGraph - RAPIDS Graph Analytics Library. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/rapidsai/cugraph) (👨‍💻 86 · 🔀 200 · 📋 830 - 10% open · ⏱️ 08.06.2022):

	```
	git clone https://github.com/rapidsai/cugraph
	```
- [PyPi](https://pypi.org/project/cugraph) (📥 140 / month):
	```
	pip install cugraph
	```
- [Conda](https://anaconda.org/conda-forge/libcugraph) (📥 7.4K · ⏱️ 29.04.2021):
	```
	conda install -c conda-forge libcugraph
	```
</details>
<details><summary><b><a href="https://github.com/BlazingDB/blazingsql">BlazingSQL</a></b> (🥉21 ·  ⭐ 1.8K · 💤) - BlazingSQL is a lightweight, GPU accelerated, SQL engine for.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/BlazingDB/blazingsql) (👨‍💻 49 · 🔀 170 · 📋 710 - 17% open · ⏱️ 30.09.2021):

	```
	git clone https://github.com/BlazingDB/blazingsql
	```
- [Conda](https://anaconda.org/blazingsql/blazingsql-protocol) (📥 940 · ⏱️ 11.11.2019):
	```
	conda install -c blazingsql blazingsql-protocol
	```
</details>
<details><summary><b><a href="https://github.com/KomputeProject/kompute">Vulkan Kompute</a></b> (🥉20 ·  ⭐ 870) - General purpose GPU compute framework built on Vulkan to.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/KomputeProject/kompute) (👨‍💻 19 · 🔀 61 · 📥 160 · 📦 3 · 📋 170 - 31% open · ⏱️ 27.05.2022):

	```
	git clone https://github.com/KomputeProject/kompute
	```
- [PyPi](https://pypi.org/project/kp) (📥 100 / month):
	```
	pip install kp
	```
</details>
<details><summary><b><a href="https://github.com/rapidsai/cusignal">cuSignal</a></b> (🥉19 ·  ⭐ 600) - GPU accelerated signal processing. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/rapidsai/cusignal) (👨‍💻 38 · 🔀 92 · 📋 130 - 11% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/rapidsai/cusignal
	```
</details>
<details><summary>Show 7 hidden projects...</summary>

- <b><a href="https://github.com/inducer/pycuda">PyCUDA</a></b> (🥈26 ·  ⭐ 1.3K) - CUDA integration for Python, plus shiny features. <code>❗Unlicensed</code>
- <b><a href="https://github.com/anderskm/gputil">GPUtil</a></b> (🥉22 ·  ⭐ 870 · 💀) - A Python module for getting the GPU status from NVIDA GPUs using.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/fbcotter/py3nvml">py3nvml</a></b> (🥉21 ·  ⭐ 200) - Python 3 Bindings for NVML library. Get NVIDIA GPU status inside your.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/lebedov/scikit-cuda">scikit-cuda</a></b> (🥉20 ·  ⭐ 900) - Python interface to GPU-powered libraries. <code>❗Unlicensed</code>
- <b><a href="https://github.com/nicolargo/nvidia-ml-py3">nvidia-ml-py3</a></b> (🥉16 ·  ⭐ 81 · 💀) - Python 3 Bindings for the NVIDIA Management Library. <code>❗Unlicensed</code>
- <b><a href="https://github.com/Santosh-Gupta/SpeedTorch">SpeedTorch</a></b> (🥉13 ·  ⭐ 660 · 💀) - Library for faster pinned CPU - GPU transfer in Pytorch. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/stas00/ipyexperiments">ipyexperiments</a></b> (🥉9 ·  ⭐ 150) - jupyter/ipython experiment containers for GPU and.. <code>❗Unlicensed</code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code>
</details>
<br>

## Tensorflow Utilities

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries that extend TensorFlow with additional capabilities._

<details><summary><b><a href="https://github.com/tensorflow/addons">TF Addons</a></b> (🥇36 ·  ⭐ 1.5K) - Useful extra functionality for TensorFlow 2.x maintained by.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/addons) (👨‍💻 190 · 🔀 520 · 📦 6.6K · 📋 900 - 21% open · ⏱️ 06.06.2022):

	```
	git clone https://github.com/tensorflow/addons
	```
- [PyPi](https://pypi.org/project/tensorflow-addons) (📥 1.3M / month):
	```
	pip install tensorflow-addons
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/hub">tensorflow-hub</a></b> (🥇35 ·  ⭐ 3.1K) - A library for transfer learning by reusing parts of.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/hub) (👨‍💻 90 · 🔀 1.6K · 📦 12K · 📋 640 - 2% open · ⏱️ 27.05.2022):

	```
	git clone https://github.com/tensorflow/hub
	```
- [PyPi](https://pypi.org/project/tensorflow-hub) (📥 6.1M / month):
	```
	pip install tensorflow-hub
	```
- [Conda](https://anaconda.org/conda-forge/tensorflow-hub) (📥 63K · ⏱️ 18.04.2021):
	```
	conda install -c conda-forge tensorflow-hub
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/tensor2tensor">tensor2tensor</a></b> (🥈34 ·  ⭐ 12K) - Library of deep learning models and datasets designed to.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/tensor2tensor) (👨‍💻 240 · 🔀 3K · 📦 1.2K · 📋 1.2K - 45% open · ⏱️ 15.04.2022):

	```
	git clone https://github.com/tensorflow/tensor2tensor
	```
- [PyPi](https://pypi.org/project/tensor2tensor) (📥 12K / month):
	```
	pip install tensor2tensor
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/transform">TensorFlow Transform</a></b> (🥈33 ·  ⭐ 920) - Input pipeline framework. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/transform) (👨‍💻 27 · 🔀 180 · 📦 890 · 📋 180 - 15% open · ⏱️ 07.06.2022):

	```
	git clone https://github.com/tensorflow/transform
	```
- [PyPi](https://pypi.org/project/tensorflow-transform) (📥 3.4M / month):
	```
	pip install tensorflow-transform
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/datasets">TensorFlow Datasets</a></b> (🥈32 ·  ⭐ 3.3K) - TFDS is a collection of datasets ready to use with.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/datasets) (👨‍💻 260 · 🔀 1.2K · 📋 960 - 35% open · ⏱️ 09.06.2022):

	```
	git clone https://github.com/tensorflow/datasets
	```
- [PyPi](https://pypi.org/project/tensorflow-datasets) (📥 1.2M / month):
	```
	pip install tensorflow-datasets
	```
- [Conda](https://anaconda.org/conda-forge/tensorflow-datasets) (📥 4.9K · ⏱️ 17.08.2021):
	```
	conda install -c conda-forge tensorflow-datasets
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/model-optimization">TF Model Optimization</a></b> (🥈32 ·  ⭐ 1.2K) - A toolkit to optimize ML models for deployment for.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/model-optimization) (👨‍💻 67 · 🔀 270 · 📦 1.8K · 📋 290 - 47% open · ⏱️ 16.05.2022):

	```
	git clone https://github.com/tensorflow/model-optimization
	```
- [PyPi](https://pypi.org/project/tensorflow-model-optimization) (📥 160K / month):
	```
	pip install tensorflow-model-optimization
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/io">TensorFlow I/O</a></b> (🥉27 ·  ⭐ 560) - Dataset, streaming, and file system extensions.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/io) (👨‍💻 94 · 🔀 210 · 📋 520 - 35% open · ⏱️ 17.05.2022):

	```
	git clone https://github.com/tensorflow/io
	```
- [PyPi](https://pypi.org/project/tensorflow-io) (📥 220K / month):
	```
	pip install tensorflow-io
	```
</details>
<details><summary><b><a href="https://github.com/qubvel/efficientnet">efficientnet</a></b> (🥉26 ·  ⭐ 2K · 💤) - Implementation of EfficientNet model. Keras and.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/qubvel/efficientnet) (👨‍💻 10 · 🔀 450 · 📥 240K · 📦 1K · 📋 110 - 48% open · ⏱️ 16.07.2021):

	```
	git clone https://github.com/qubvel/efficientnet
	```
- [PyPi](https://pypi.org/project/efficientnet) (📥 140K / month):
	```
	pip install efficientnet
	```
- [Conda](https://anaconda.org/anaconda/efficientnet) (📥 100 · ⏱️ 14.01.2022):
	```
	conda install -c anaconda efficientnet
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/neural-structured-learning">Neural Structured Learning</a></b> (🥉26 ·  ⭐ 920) - Training neural models with structured signals. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/neural-structured-learning) (👨‍💻 33 · 🔀 170 · 📦 240 · 📋 64 - 6% open · ⏱️ 01.06.2022):

	```
	git clone https://github.com/tensorflow/neural-structured-learning
	```
- [PyPi](https://pypi.org/project/neural-structured-learning) (📥 17K / month):
	```
	pip install neural-structured-learning
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/cloud">TensorFlow Cloud</a></b> (🥉23 ·  ⭐ 330) - The TensorFlow Cloud repository provides APIs that.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/cloud) (👨‍💻 27 · 🔀 69 · 📦 150 · 📋 81 - 67% open · ⏱️ 24.03.2022):

	```
	git clone https://github.com/tensorflow/cloud
	```
- [PyPi](https://pypi.org/project/tensorflow-cloud) (📥 150K / month):
	```
	pip install tensorflow-cloud
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/compression">TF Compression</a></b> (🥉22 ·  ⭐ 620) - Data compression in TensorFlow. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/compression) (👨‍💻 14 · 🔀 210 · 📋 84 - 2% open · ⏱️ 07.06.2022):

	```
	git clone https://github.com/tensorflow/compression
	```
- [PyPi](https://pypi.org/project/tensorflow-compression) (📥 1.6K / month):
	```
	pip install tensorflow-compression
	```
</details>
<details><summary><b><a href="https://github.com/PAIR-code/saliency">Saliency</a></b> (🥉18 ·  ⭐ 790) - Framework-agnostic implementation for state-of-the-art saliency.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PAIR-code/saliency) (👨‍💻 15 · 🔀 160 · 📦 29 · ⏱️ 13.05.2022):

	```
	git clone https://github.com/PAIR-code/saliency
	```
- [PyPi](https://pypi.org/project/saliency) (📥 460 / month):
	```
	pip install saliency
	```
</details>
<details><summary><b><a href="https://github.com/geffy/tffm">tffm</a></b> (🥉18 ·  ⭐ 780) - TensorFlow implementation of an arbitrary order Factorization Machine. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/geffy/tffm) (👨‍💻 10 · 🔀 180 · 📦 11 · 📋 40 - 45% open · ⏱️ 17.01.2022):

	```
	git clone https://github.com/geffy/tffm
	```
- [PyPi](https://pypi.org/project/tffm) (📥 1.9K / month):
	```
	pip install tffm
	```
</details>
<details><summary>Show 2 hidden projects...</summary>

- <b><a href="https://github.com/keras-team/keras-preprocessing">Keras-Preprocessing</a></b> (🥉22 ·  ⭐ 1K · 📉) - Utilities for working with image data, text data, and.. <code>❗Unlicensed</code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/taehoonlee/tensornets">TensorNets</a></b> (🥉21 ·  ⭐ 1K · 💀) - High level network definitions with pre-trained weights in.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
</details>
<br>

## Jax Utilities

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries that extend Jax with additional capabilities._

<details><summary><b><a href="https://github.com/patrick-kidger/equinox">equinox</a></b> (🥇23 ·  ⭐ 590) - Callable PyTrees and filtered transforms = neural networks in.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://jax.readthedocs.io/en/latest/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/patrick-kidger/equinox) (👨‍💻 7 · 🔀 32 · 📦 20 · 📋 47 - 10% open · ⏱️ 06.06.2022):

	```
	git clone https://github.com/patrick-kidger/equinox
	```
- [PyPi](https://pypi.org/project/equinox) (📥 1.4K / month):
	```
	pip install equinox
	```
</details>
<details><summary>Show 1 hidden projects...</summary>

- <b><a href="https://github.com/ucl-bug/jaxdf">jaxdf</a></b> (🥉9 ·  ⭐ 50) - A JAX-based research framework for writing differentiable.. <code><a href="http://bit.ly/37RvQcA">❗️LGPL-3.0</a></code> <code><img src="https://jax.readthedocs.io/en/latest/_static/favicon.png" style="display:inline;" width="13" height="13"></code>
</details>
<br>

## Sklearn Utilities

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries that extend scikit-learn with additional capabilities._

<details><summary><b><a href="https://github.com/scikit-learn-contrib/imbalanced-learn">imbalanced-learn</a></b> (🥇34 ·  ⭐ 5.9K) - A Python Package to Tackle the Curse of Imbalanced.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/scikit-learn-contrib/imbalanced-learn) (👨‍💻 63 · 🔀 1.1K · 📦 11K · 📋 500 - 7% open · ⏱️ 16.05.2022):

	```
	git clone https://github.com/scikit-learn-contrib/imbalanced-learn
	```
- [PyPi](https://pypi.org/project/imbalanced-learn) (📥 2.8M / month):
	```
	pip install imbalanced-learn
	```
- [Conda](https://anaconda.org/conda-forge/imbalanced-learn) (📥 220K · ⏱️ 16.05.2022):
	```
	conda install -c conda-forge imbalanced-learn
	```
</details>
<details><summary><b><a href="https://github.com/scikit-learn-contrib/category_encoders">category_encoders</a></b> (🥇34 ·  ⭐ 2K) - A library of sklearn compatible categorical variable.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/scikit-learn-contrib/category_encoders) (👨‍💻 52 · 🔀 350 · 📦 3.5K · 📋 240 - 24% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/scikit-learn-contrib/category_encoders
	```
- [PyPi](https://pypi.org/project/category_encoders) (📥 4.1M / month):
	```
	pip install category_encoders
	```
- [Conda](https://anaconda.org/conda-forge/category_encoders) (📥 160K · ⏱️ 02.06.2022):
	```
	conda install -c conda-forge category_encoders
	```
</details>
<details><summary><b><a href="https://github.com/koaning/scikit-lego">scikit-lego</a></b> (🥈26 ·  ⭐ 830) - Extra blocks for scikit-learn pipelines. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/koaning/scikit-lego) (👨‍💻 51 · 🔀 87 · 📦 50 · 📋 240 - 8% open · ⏱️ 05.06.2022):

	```
	git clone https://github.com/koaning/scikit-lego
	```
- [PyPi](https://pypi.org/project/scikit-lego) (📥 14K / month):
	```
	pip install scikit-lego
	```
- [Conda](https://anaconda.org/conda-forge/scikit-lego) (📥 19K · ⏱️ 06.06.2022):
	```
	conda install -c conda-forge scikit-lego
	```
</details>
<details><summary><b><a href="https://github.com/iskandr/fancyimpute">fancyimpute</a></b> (🥈25 ·  ⭐ 1.1K · 💤) - Multivariate imputation and matrix completion.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/iskandr/fancyimpute) (👨‍💻 12 · 🔀 160 · 📦 1.2K · 📋 110 - 0% open · ⏱️ 21.10.2021):

	```
	git clone https://github.com/iskandr/fancyimpute
	```
- [PyPi](https://pypi.org/project/fancyimpute) (📥 16K / month):
	```
	pip install fancyimpute
	```
</details>
<details><summary><b><a href="https://github.com/guofei9987/scikit-opt">scikit-opt</a></b> (🥈24 ·  ⭐ 3.3K) - Genetic Algorithm, Particle Swarm Optimization, Simulated.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/guofei9987/scikit-opt) (👨‍💻 14 · 🔀 760 · 📦 78 · 📋 150 - 27% open · ⏱️ 08.04.2022):

	```
	git clone https://github.com/guofei9987/scikit-opt
	```
- [PyPi](https://pypi.org/project/scikit-opt) (📥 2.4K / month):
	```
	pip install scikit-opt
	```
</details>
<details><summary><b><a href="https://github.com/trent-b/iterative-stratification">iterative-stratification</a></b> (🥉22 ·  ⭐ 650) - scikit-learn cross validators for iterative.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/trent-b/iterative-stratification) (👨‍💻 7 · 🔀 62 · 📦 210 · 📋 19 - 21% open · ⏱️ 06.06.2022):

	```
	git clone https://github.com/trent-b/iterative-stratification
	```
- [PyPi](https://pypi.org/project/iterative-stratification) (📥 2.9M / month):
	```
	pip install iterative-stratification
	```
</details>
<details><summary><b><a href="https://github.com/yzhao062/combo">combo</a></b> (🥉20 ·  ⭐ 580 · 💤) - (AAAI 20) A Python Toolbox for Machine Learning Model.. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code> <code>xgboost</code></summary>

- [GitHub](https://github.com/yzhao062/combo) (🔀 99 · 📦 460 · 📋 13 - 76% open · ⏱️ 02.10.2021):

	```
	git clone https://github.com/yzhao062/combo
	```
- [PyPi](https://pypi.org/project/combo) (📥 39K / month):
	```
	pip install combo
	```
</details>
<details><summary><b><a href="https://github.com/scikit-learn-contrib/DESlib">DESlib</a></b> (🥉16 ·  ⭐ 400) - A Python library for dynamic classifier and ensemble selection. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/scikit-learn-contrib/DESlib) (👨‍💻 14 · 🔀 57 · 📦 26 · 📋 140 - 11% open · ⏱️ 07.06.2022):

	```
	git clone https://github.com/scikit-learn-contrib/DESlib
	```
- [PyPi](https://pypi.org/project/deslib) (📥 560 / month):
	```
	pip install deslib
	```
</details>
<details><summary>Show 9 hidden projects...</summary>

- <b><a href="https://github.com/rasbt/mlxtend">MLxtend</a></b> (🥇34 ·  ⭐ 4K) - A library of extension and helper modules for Pythons data.. <code>❗Unlicensed</code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/scikit-multilearn/scikit-multilearn">scikit-multilearn</a></b> (🥈25 ·  ⭐ 750 · 💀) - A scikit-learn based module for multi-label et. al... <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/TeamHG-Memex/sklearn-crfsuite">sklearn-crfsuite</a></b> (🥉22 ·  ⭐ 400 · 💀) - scikit-learn inspired API for CRFsuite. <code>❗Unlicensed</code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/scikit-learn-contrib/lightning">sklearn-contrib-lightning</a></b> (🥉21 ·  ⭐ 1.6K) - Large-scale linear classification, regression and.. <code>❗Unlicensed</code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/mathurinm/celer">celer</a></b> (🥉20 ·  ⭐ 140) - Fast solver for L1-type problems: Lasso, sparse Logisitic regression,.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/scikit-learn-contrib/skope-rules">skope-rules</a></b> (🥉19 ·  ⭐ 460 · 💀) - machine learning with logical rules in Python. <code>❗Unlicensed</code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/skggm/skggm">skggm</a></b> (🥉16 ·  ⭐ 200) - Scikit-learn compatible estimation of general graphical models. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/amueller/dabl">dabl</a></b> (🥉15 ·  ⭐ 110 · 💤) - Data Analysis Baseline Library. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/scikit-tda/scikit-tda">scikit-tda</a></b> (🥉14 ·  ⭐ 350) - Topological Data Analysis for Python. <code>❗Unlicensed</code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code>
</details>
<br>

## Pytorch Utilities

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries that extend Pytorch with additional capabilities._

<details><summary><b><a href="https://github.com/KevinMusgrave/pytorch-metric-learning">PML</a></b> (🥇33 ·  ⭐ 4.5K) - The easiest way to use deep metric learning in your application. Modular,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/KevinMusgrave/pytorch-metric-learning) (👨‍💻 24 · 🔀 540 · 📦 270 · 📋 360 - 13% open · ⏱️ 30.05.2022):

	```
	git clone https://github.com/KevinMusgrave/pytorch-metric-learning
	```
- [PyPi](https://pypi.org/project/pytorch-metric-learning) (📥 2.9M / month):
	```
	pip install pytorch-metric-learning
	```
- [Conda](https://anaconda.org/metric-learning/pytorch-metric-learning) (📥 7.1K · ⏱️ 28.05.2022):
	```
	conda install -c metric-learning pytorch-metric-learning
	```
</details>
<details><summary><b><a href="https://github.com/huggingface/accelerate">accelerate</a></b> (🥇33 ·  ⭐ 2.5K) - A simple way to train and use PyTorch models with multi-.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/huggingface/accelerate) (👨‍💻 44 · 🔀 170 · 📦 580 · 📋 230 - 10% open · ⏱️ 08.06.2022):

	```
	git clone https://github.com/huggingface/accelerate
	```
- [PyPi](https://pypi.org/project/accelerate) (📥 3M / month):
	```
	pip install accelerate
	```
- [Conda](https://anaconda.org/conda-forge/accelerate) (📥 2.5K · ⏱️ 23.05.2022):
	```
	conda install -c conda-forge accelerate
	```
</details>
<details><summary><b><a href="https://github.com/PyTorchLightning/lightning-flash">lightning-flash</a></b> (🥇29 ·  ⭐ 1.5K) - Your PyTorch AI Factory - Flash enables you to easily.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PyTorchLightning/lightning-flash) (👨‍💻 70 · 🔀 160 · 📦 82 · 📋 460 - 6% open · ⏱️ 06.06.2022):

	```
	git clone https://github.com/PyTorchLightning/lightning-flash
	```
- [PyPi](https://pypi.org/project/lightning-flash) (📥 7.7K / month):
	```
	pip install lightning-flash
	```
- [Conda](https://anaconda.org/conda-forge/lightning-flash) (📥 2K · ⏱️ 12.05.2022):
	```
	conda install -c conda-forge lightning-flash
	```
</details>
<details><summary><b><a href="https://github.com/jettify/pytorch-optimizer">pytorch-optimizer</a></b> (🥈27 ·  ⭐ 2.4K · 💤) - torch-optimizer -- collection of optimizers for.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/jettify/pytorch-optimizer) (👨‍💻 25 · 🔀 240 · 📦 610 · 📋 45 - 35% open · ⏱️ 11.11.2021):

	```
	git clone https://github.com/jettify/pytorch-optimizer
	```
- [PyPi](https://pypi.org/project/torch_optimizer) (📥 48K / month):
	```
	pip install torch_optimizer
	```
- [Conda](https://anaconda.org/conda-forge/torch-optimizer) (📥 1.7K · ⏱️ 31.10.2021):
	```
	conda install -c conda-forge torch-optimizer
	```
</details>
<details><summary><b><a href="https://github.com/rtqichen/torchdiffeq">torchdiffeq</a></b> (🥈23 ·  ⭐ 4.1K) - Differentiable ODE solvers with full GPU support and.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/rtqichen/torchdiffeq) (👨‍💻 20 · 🔀 710 · 📦 260 · 📋 170 - 21% open · ⏱️ 22.04.2022):

	```
	git clone https://github.com/rtqichen/torchdiffeq
	```
- [PyPi](https://pypi.org/project/torchdiffeq) (📥 6.8K / month):
	```
	pip install torchdiffeq
	```
- [Conda](https://anaconda.org/conda-forge/torchdiffeq) (📥 5.4K · ⏱️ 03.06.2021):
	```
	conda install -c conda-forge torchdiffeq
	```
</details>
<details><summary><b><a href="https://github.com/dreamquark-ai/tabnet">TabNet</a></b> (🥈23 ·  ⭐ 1.7K) - PyTorch implementation of TabNet paper :.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/dreamquark-ai/tabnet) (👨‍💻 19 · 🔀 350 · 📋 220 - 6% open · ⏱️ 23.03.2022):

	```
	git clone https://github.com/dreamquark-ai/tabnet
	```
- [PyPi](https://pypi.org/project/pytorch-tabnet) (📥 18K / month):
	```
	pip install pytorch-tabnet
	```
- [Conda](https://anaconda.org/conda-forge/pytorch-tabnet) (📥 590 · ⏱️ 30.12.2021):
	```
	conda install -c conda-forge pytorch-tabnet
	```
</details>
<details><summary><b><a href="https://github.com/rusty1s/pytorch_sparse">PyTorch Sparse</a></b> (🥈23 ·  ⭐ 650) - PyTorch Extension Library of Optimized Autograd Sparse.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/rusty1s/pytorch_sparse) (👨‍💻 25 · 🔀 89 · 📋 180 - 16% open · ⏱️ 18.05.2022):

	```
	git clone https://github.com/rusty1s/pytorch_sparse
	```
- [PyPi](https://pypi.org/project/torch-sparse) (📥 22K / month):
	```
	pip install torch-sparse
	```
- [Conda](https://anaconda.org/conda-forge/pytorch_sparse) (📥 92K · ⏱️ 08.06.2022):
	```
	conda install -c conda-forge pytorch_sparse
	```
</details>
<details><summary><b><a href="https://github.com/BloodAxe/pytorch-toolbelt">Pytorch Toolbelt</a></b> (🥈22 ·  ⭐ 1.2K) - PyTorch extensions for fast R&D prototyping and Kaggle.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/BloodAxe/pytorch-toolbelt) (👨‍💻 7 · 🔀 97 · 📋 24 - 8% open · ⏱️ 05.06.2022):

	```
	git clone https://github.com/BloodAxe/pytorch-toolbelt
	```
- [PyPi](https://pypi.org/project/pytorch_toolbelt) (📥 6.9K / month):
	```
	pip install pytorch_toolbelt
	```
</details>
<details><summary><b><a href="https://github.com/tristandeleu/pytorch-meta">Torchmeta</a></b> (🥈21 ·  ⭐ 1.6K · 💤) - A collection of extensions and data-loaders for few-shot.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tristandeleu/pytorch-meta) (👨‍💻 12 · 🔀 210 · 📦 90 · 📋 130 - 32% open · ⏱️ 20.09.2021):

	```
	git clone https://github.com/tristandeleu/pytorch-meta
	```
- [PyPi](https://pypi.org/project/torchmeta) (📥 4.6K / month):
	```
	pip install torchmeta
	```
</details>
<details><summary><b><a href="https://github.com/rwightman/gen-efficientnet-pytorch">EfficientNets</a></b> (🥈21 ·  ⭐ 1.5K · 💤) - Pretrained EfficientNet, EfficientNet-Lite, MixNet,.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/rwightman/gen-efficientnet-pytorch) (👨‍💻 5 · 🔀 190 · 📦 110 · 📋 53 - 3% open · ⏱️ 08.07.2021):

	```
	git clone https://github.com/rwightman/gen-efficientnet-pytorch
	```
- [PyPi](https://pypi.org/project/geffnet) (📥 15K / month):
	```
	pip install geffnet
	```
</details>
<details><summary><b><a href="https://github.com/lucidrains/performer-pytorch">Performer Pytorch</a></b> (🥈21 ·  ⭐ 840) - An implementation of Performer, a linear attention-based.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/lucidrains/performer-pytorch) (👨‍💻 6 · 🔀 110 · 📦 46 · 📋 76 - 43% open · ⏱️ 02.02.2022):

	```
	git clone https://github.com/lucidrains/performer-pytorch
	```
- [PyPi](https://pypi.org/project/performer-pytorch) (📥 17K / month):
	```
	pip install performer-pytorch
	```
</details>
<details><summary><b><a href="https://github.com/lucidrains/reformer-pytorch">reformer-pytorch</a></b> (🥉20 ·  ⭐ 1.7K · 💤) - Reformer, the efficient Transformer, in Pytorch. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/lucidrains/reformer-pytorch) (👨‍💻 10 · 🔀 240 · 📋 120 - 11% open · ⏱️ 06.11.2021):

	```
	git clone https://github.com/lucidrains/reformer-pytorch
	```
- [PyPi](https://pypi.org/project/reformer-pytorch) (📥 3.4K / month):
	```
	pip install reformer-pytorch
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/higher">Higher</a></b> (🥉20 ·  ⭐ 1.4K · 💤) - higher is a pytorch library allowing users to obtain higher.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/facebookresearch/higher) (👨‍💻 9 · 🔀 100 · 📦 150 · 📋 99 - 49% open · ⏱️ 26.10.2021):

	```
	git clone https://github.com/facebookresearch/higher
	```
- [PyPi](https://pypi.org/project/higher) (📥 23K / month):
	```
	pip install higher
	```
</details>
<details><summary><b><a href="https://github.com/harvardnlp/pytorch-struct">Torch-Struct</a></b> (🥉20 ·  ⭐ 1K) - Fast, general, and tested differentiable structured prediction.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/harvardnlp/pytorch-struct) (👨‍💻 16 · 🔀 81 · 📋 54 - 44% open · ⏱️ 30.01.2022):

	```
	git clone https://github.com/harvardnlp/pytorch-struct
	```
- [PyPi](https://pypi.org/project/torch-struct) (📥 72K / month):
	```
	pip install torch-struct
	```
</details>
<details><summary><b><a href="https://github.com/rusty1s/pytorch_scatter">torch-scatter</a></b> (🥉20 ·  ⭐ 1K) - PyTorch Extension Library of Optimized Scatter Operations. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/rusty1s/pytorch_scatter) (👨‍💻 20 · 🔀 120 · 📋 260 - 8% open · ⏱️ 31.05.2022):

	```
	git clone https://github.com/rusty1s/pytorch_scatter
	```
- [PyPi](https://pypi.org/project/torch-scatter) (📥 28K / month):
	```
	pip install torch-scatter
	```
- [Conda](https://anaconda.org/conda-forge/pytorch_scatter) (📥 81K · ⏱️ 21.03.2022):
	```
	conda install -c conda-forge pytorch_scatter
	```
</details>
<details><summary><b><a href="https://github.com/google-research/torchsde">torchsde</a></b> (🥉20 ·  ⭐ 990 · 💤) - Differentiable SDE solvers with GPU support and efficient.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/google-research/torchsde) (👨‍💻 5 · 🔀 100 · 📦 15 · 📋 49 - 16% open · ⏱️ 26.07.2021):

	```
	git clone https://github.com/google-research/torchsde
	```
- [PyPi](https://pypi.org/project/torchsde) (📥 850 / month):
	```
	pip install torchsde
	```
- [Conda](https://anaconda.org/conda-forge/torchsde) (📥 9.7K · ⏱️ 12.07.2021):
	```
	conda install -c conda-forge torchsde
	```
</details>
<details><summary><b><a href="https://github.com/geohot/tinygrad">tinygrad</a></b> (🥉19 ·  ⭐ 6K) - You like pytorch? You like micrograd? You love tinygrad!. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/geohot/tinygrad) (👨‍💻 59 · 🔀 600 · 📦 2 · 📋 96 - 9% open · ⏱️ 09.06.2022):

	```
	git clone https://github.com/geohot/tinygrad
	```
</details>
<details><summary><b><a href="https://github.com/szagoruyko/pytorchviz">pytorchviz</a></b> (🥉18 ·  ⭐ 2.3K · 💤) - A small package to create visualizations of PyTorch execution.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/szagoruyko/pytorchviz) (👨‍💻 6 · 🔀 230 · 📦 680 · 📋 57 - 36% open · ⏱️ 15.06.2021):

	```
	git clone https://github.com/szagoruyko/pytorchviz
	```
</details>
<details><summary><b><a href="https://github.com/abhishekkrthakur/tez">Tez</a></b> (🥉17 ·  ⭐ 1K) - Tez is a super-simple and lightweight Trainer for PyTorch. It also.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/abhishekkrthakur/tez) (🔀 130 · 📦 27 · 📋 32 - 46% open · ⏱️ 05.06.2022):

	```
	git clone https://github.com/abhishekkrthakur/tez
	```
- [PyPi](https://pypi.org/project/tez) (📥 730 / month):
	```
	pip install tez
	```
</details>
<details><summary><b><a href="https://github.com/parrt/tensor-sensor">Tensor Sensor</a></b> (🥉16 ·  ⭐ 640) - The goal of this library is to generate more helpful.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/parrt/tensor-sensor) (👨‍💻 4 · 🔀 33 · 📦 7 · 📋 23 - 34% open · ⏱️ 07.04.2022):

	```
	git clone https://github.com/parrt/tensor-sensor
	```
- [PyPi](https://pypi.org/project/tensor-sensor) (📥 1.8K / month):
	```
	pip install tensor-sensor
	```
- [Conda](https://anaconda.org/conda-forge/tensor-sensor) (📥 340 · ⏱️ 11.12.2021):
	```
	conda install -c conda-forge tensor-sensor
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/madgrad">madgrad</a></b> (🥉14 ·  ⭐ 760) - MADGRAD Optimization Method. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/facebookresearch/madgrad) (👨‍💻 2 · 🔀 52 · 📦 25 · 📋 8 - 12% open · ⏱️ 10.03.2022):

	```
	git clone https://github.com/facebookresearch/madgrad
	```
- [PyPi](https://pypi.org/project/madgrad) (📥 7.7K / month):
	```
	pip install madgrad
	```
</details>
<details><summary>Show 11 hidden projects...</summary>

- <b><a href="https://github.com/Cadene/pretrained-models.pytorch">pretrainedmodels</a></b> (🥇30 ·  ⭐ 8.5K · 💀) - Pretrained ConvNets for pytorch: NASNet, ResNeXt,.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/sksq96/pytorch-summary">pytorch-summary</a></b> (🥈26 ·  ⭐ 3.6K · 💀) - Model summary in PyTorch similar to `model.summary()`.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/lukemelas/EfficientNet-PyTorch">EfficientNet-PyTorch</a></b> (🥈23 ·  ⭐ 7K · 💀) - A PyTorch implementation of EfficientNet and.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/asappresearch/sru">SRU</a></b> (🥈23 ·  ⭐ 2K · 💀) - Training RNNs as Fast as CNNs (https://arxiv.org/abs/1709.02755). <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/GRAAL-Research/poutyne">Poutyne</a></b> (🥈21 ·  ⭐ 520) - A simplified framework and utilities for PyTorch. <code><a href="http://bit.ly/37RvQcA">❗️LGPL-3.0</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/adobe/antialiased-cnns">Antialiased CNNs</a></b> (🥉20 ·  ⭐ 1.5K · 💤) - pip install antialiased-cnns to improve stability and.. <code><a href="https://tldrlegal.com/search?q=CC%20BY-NC-SA%204.0">❗️CC BY-NC-SA 4.0</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/Luolc/AdaBound">AdaBound</a></b> (🥉19 ·  ⭐ 2.9K · 💀) - An optimizer that trains as fast as Adam and as good as SGD. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/lucidrains/lambda-networks">Lambda Networks</a></b> (🥉17 ·  ⭐ 1.5K · 💀) - Implementation of LambdaNetworks, a new approach to.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/karpathy/micrograd">micrograd</a></b> (🥉15 ·  ⭐ 2.1K · 💀) - A tiny scalar-valued autograd engine and a neural net library.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/achaiah/pywick">Pywick</a></b> (🥉13 ·  ⭐ 370 · 💤) - High-level batteries-included neural network training.. <code>❗Unlicensed</code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/TorchDrift/TorchDrift">TorchDrift</a></b> (🥉12 ·  ⭐ 220 · 💤) - Drift Detection for your PyTorch Models. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
</details>
<br>

## Database Clients

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for connecting to, operating, and querying databases._

🔗&nbsp;<b><a href="https://github.com/ml-tooling/best-of-python#database-clients">best-of-python - DB Clients</a></b> ( ⭐ 2.2K)  - Collection of database clients for python.

<br>

## Others

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/scipy/scipy">scipy</a></b> (🥇49 ·  ⭐ 9.7K) - Ecosystem of open-source software for mathematics, science, and engineering. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/scipy/scipy) (👨‍💻 1.3K · 🔀 4.1K · 📥 350K · 📦 520K · 📋 8.2K - 17% open · ⏱️ 09.06.2022):

	```
	git clone https://github.com/scipy/scipy
	```
- [PyPi](https://pypi.org/project/scipy) (📥 45M / month):
	```
	pip install scipy
	```
- [Conda](https://anaconda.org/conda-forge/scipy) (📥 24M · ⏱️ 20.05.2022):
	```
	conda install -c conda-forge scipy
	```
</details>
<details><summary><b><a href="https://github.com/streamlit/streamlit">Streamlit</a></b> (🥇38 ·  ⭐ 19K) - Streamlit The fastest way to build data apps in Python. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/streamlit/streamlit) (👨‍💻 140 · 🔀 1.7K · 📦 310 · 📋 2.4K - 23% open · ⏱️ 09.06.2022):

	```
	git clone https://github.com/streamlit/streamlit
	```
- [PyPi](https://pypi.org/project/streamlit) (📥 960K / month):
	```
	pip install streamlit
	```
</details>
<details><summary><b><a href="https://github.com/yzhao062/pyod">PyOD</a></b> (🥇36 ·  ⭐ 5.7K) - A Comprehensive and Scalable Python Library for Outlier Detection (Anomaly.. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/yzhao062/pyod) (👨‍💻 39 · 🔀 1.1K · 📦 1.3K · 📋 250 - 47% open · ⏱️ 13.05.2022):

	```
	git clone https://github.com/yzhao062/pyod
	```
- [PyPi](https://pypi.org/project/pyod) (📥 470K / month):
	```
	pip install pyod
	```
- [Conda](https://anaconda.org/conda-forge/pyod) (📥 23K · ⏱️ 13.05.2022):
	```
	conda install -c conda-forge pyod
	```
</details>
<details><summary><b><a href="https://github.com/deepchem/deepchem">DeepChem</a></b> (🥇34 ·  ⭐ 3.7K) - Democratizing Deep-Learning for Drug Discovery, Quantum Chemistry,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/deepchem/deepchem) (👨‍💻 190 · 🔀 1.3K · 📦 100 · 📋 1.4K - 29% open · ⏱️ 06.06.2022):

	```
	git clone https://github.com/deepchem/deepchem
	```
- [PyPi](https://pypi.org/project/deepchem) (📥 8.8K / month):
	```
	pip install deepchem
	```
- [Conda](https://anaconda.org/conda-forge/deepchem) (📥 10K · ⏱️ 19.01.2022):
	```
	conda install -c conda-forge deepchem
	```
</details>
<details><summary><b><a href="https://github.com/simonw/datasette">Datasette</a></b> (🥇33 ·  ⭐ 6.2K) - An open source multi-tool for exploring and publishing data. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/simonw/datasette) (👨‍💻 64 · 🔀 400 · 📥 39 · 📦 670 · 📋 1.3K - 26% open · ⏱️ 31.05.2022):

	```
	git clone https://github.com/simonw/datasette
	```
- [PyPi](https://pypi.org/project/datasette) (📥 240K / month):
	```
	pip install datasette
	```
- [Conda](https://anaconda.org/conda-forge/datasette) (📥 4.5K · ⏱️ 24.03.2022):
	```
	conda install -c conda-forge datasette
	```
</details>
<details><summary><b><a href="https://github.com/PaddlePaddle/PaddleHub">PaddleHub</a></b> (🥇32 ·  ⭐ 8K) - Awesome pre-trained models toolkit based on PaddlePaddle.(300+.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1M" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PaddlePaddle/PaddleHub) (👨‍💻 61 · 🔀 1.6K · 📥 570 · 📦 810 · 📋 1.1K - 40% open · ⏱️ 15.04.2022):

	```
	git clone https://github.com/PaddlePaddle/PaddleHub
	```
- [PyPi](https://pypi.org/project/paddlehub) (📥 15K / month):
	```
	pip install paddlehub
	```
</details>
<details><summary><b><a href="https://github.com/HIPS/autograd">Autograd</a></b> (🥈31 ·  ⭐ 5.8K) - Efficiently computes derivatives of numpy code. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/HIPS/autograd) (👨‍💻 51 · 🔀 790 · 📦 3.5K · 📋 370 - 39% open · ⏱️ 08.04.2022):

	```
	git clone https://github.com/HIPS/autograd
	```
- [PyPi](https://pypi.org/project/autograd) (📥 1.3M / month):
	```
	pip install autograd
	```
- [Conda](https://anaconda.org/conda-forge/autograd) (📥 210K · ⏱️ 25.07.2019):
	```
	conda install -c conda-forge autograd
	```
</details>
<details><summary><b><a href="https://github.com/online-ml/river">River</a></b> (🥈31 ·  ⭐ 3.4K · 📈) - Online machine learning in Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/online-ml/river) (👨‍💻 80 · 🔀 380 · 📦 120 · 📋 370 - 2% open · ⏱️ 09.06.2022):

	```
	git clone https://github.com/online-ml/river
	```
- [PyPi](https://pypi.org/project/river) (📥 9K / month):
	```
	pip install river
	```
- [Conda](https://anaconda.org/conda-forge/river) (📥 9K · ⏱️ 09.12.2021):
	```
	conda install -c conda-forge river
	```
</details>
<details><summary><b><a href="https://github.com/scikit-learn-contrib/hdbscan">hdbscan</a></b> (🥈30 ·  ⭐ 2.2K) - A high performance implementation of HDBSCAN clustering. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/scikit-learn-contrib/hdbscan) (👨‍💻 78 · 🔀 380 · 📦 1.4K · 📋 430 - 63% open · ⏱️ 02.05.2022):

	```
	git clone https://github.com/scikit-learn-contrib/hdbscan
	```
- [PyPi](https://pypi.org/project/hdbscan) (📥 410K / month):
	```
	pip install hdbscan
	```
- [Conda](https://anaconda.org/conda-forge/hdbscan) (📥 1.1M · ⏱️ 11.02.2022):
	```
	conda install -c conda-forge hdbscan
	```
</details>
<details><summary><b><a href="https://github.com/nicodv/kmodes">kmodes</a></b> (🥈30 ·  ⭐ 1K) - Python implementations of the k-modes and k-prototypes clustering.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/nicodv/kmodes) (👨‍💻 21 · 🔀 370 · 📦 1.2K · 📋 150 - 10% open · ⏱️ 09.05.2022):

	```
	git clone https://github.com/nicodv/kmodes
	```
- [PyPi](https://pypi.org/project/kmodes) (📥 370K / month):
	```
	pip install kmodes
	```
- [Conda](https://anaconda.org/conda-forge/kmodes) (📥 9.7K · ⏱️ 15.04.2022):
	```
	conda install -c conda-forge kmodes
	```
</details>
<details><summary><b><a href="https://github.com/adapter-hub/adapter-transformers">adapter-transformers</a></b> (🥈30 ·  ⭐ 850) - Huggingface Transformers + Adapters =. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code>huggingface</code></summary>

- [GitHub](https://github.com/adapter-hub/adapter-transformers) (👨‍💻 1.3K · 🔀 140 · 📦 77 · 📋 190 - 31% open · ⏱️ 08.06.2022):

	```
	git clone https://github.com/Adapter-Hub/adapter-transformers
	```
- [PyPi](https://pypi.org/project/adapter-transformers) (📥 42K / month):
	```
	pip install adapter-transformers
	```
</details>
<details><summary><b><a href="https://github.com/gradio-app/gradio">Gradio</a></b> (🥈29 ·  ⭐ 7.4K) - Wrap UIs around any model, share with anyone. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/gradio-app/gradio) (👨‍💻 79 · 🔀 460 · 📦 1 · 📋 750 - 22% open · ⏱️ 09.06.2022):

	```
	git clone https://github.com/gradio-app/gradio
	```
- [PyPi](https://pypi.org/project/gradio) (📥 240K / month):
	```
	pip install gradio
	```
</details>
<details><summary><b><a href="https://github.com/serge-sans-paille/pythran">Pythran</a></b> (🥈29 ·  ⭐ 1.7K) - Ahead of Time compiler for numeric kernels. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/serge-sans-paille/pythran) (👨‍💻 66 · 🔀 170 · 📦 150 · 📋 750 - 13% open · ⏱️ 09.06.2022):

	```
	git clone https://github.com/serge-sans-paille/pythran
	```
- [PyPi](https://pypi.org/project/pythran) (📥 350K / month):
	```
	pip install pythran
	```
- [Conda](https://anaconda.org/conda-forge/pythran) (📥 240K · ⏱️ 10.04.2022):
	```
	conda install -c conda-forge pythran
	```
</details>
<details><summary><b><a href="https://github.com/wireservice/agate">agate</a></b> (🥈29 ·  ⭐ 1.1K · 💤) - A Python data analysis library that is optimized for humans instead of.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/wireservice/agate) (👨‍💻 49 · 🔀 140 · 📦 950 · 📋 640 - 1% open · ⏱️ 15.07.2021):

	```
	git clone https://github.com/wireservice/agate
	```
- [PyPi](https://pypi.org/project/agate) (📥 4.3M / month):
	```
	pip install agate
	```
- [Conda](https://anaconda.org/conda-forge/agate) (📥 84K · ⏱️ 16.07.2021):
	```
	conda install -c conda-forge agate
	```
</details>
<details><summary><b><a href="https://github.com/pyjanitor-devs/pyjanitor">pyjanitor</a></b> (🥈29 ·  ⭐ 930) - Clean APIs for data cleaning. Python implementation of R package Janitor. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pyjanitor-devs/pyjanitor) (👨‍💻 100 · 🔀 150 · 📦 180 · 📋 470 - 21% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/pyjanitor-devs/pyjanitor
	```
- [PyPi](https://pypi.org/project/pyjanitor) (📥 24K / month):
	```
	pip install pyjanitor
	```
- [Conda](https://anaconda.org/conda-forge/pyjanitor) (📥 120K · ⏱️ 22.11.2021):
	```
	conda install -c conda-forge pyjanitor
	```
</details>
<details><summary><b><a href="https://github.com/mars-project/mars">Mars</a></b> (🥈28 ·  ⭐ 2.4K) - Mars is a tensor-based unified framework for large-scale data.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/mars-project/mars) (👨‍💻 45 · 🔀 300 · 📋 1.1K - 16% open · ⏱️ 09.06.2022):

	```
	git clone https://github.com/mars-project/mars
	```
- [PyPi](https://pypi.org/project/pymars) (📥 33K / month):
	```
	pip install pymars
	```
</details>
<details><summary><b><a href="https://github.com/PennyLaneAI/pennylane">PennyLane</a></b> (🥈28 ·  ⭐ 1.4K) - PennyLane is a cross-platform Python library for differentiable.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/PennyLaneAI/pennylane) (👨‍💻 100 · 🔀 370 · 📥 60 · 📋 680 - 21% open · ⏱️ 09.06.2022):

	```
	git clone https://github.com/PennyLaneAI/PennyLane
	```
- [PyPi](https://pypi.org/project/pennylane) (📥 13K / month):
	```
	pip install pennylane
	```
- [Conda](https://anaconda.org/conda-forge/pennylane) (📥 1.4K · ⏱️ 01.05.2022):
	```
	conda install -c conda-forge pennylane
	```
</details>
<details><summary><b><a href="https://github.com/SeldonIO/alibi-detect">alibi-detect</a></b> (🥈28 ·  ⭐ 1.3K) - Algorithms for outlier, adversarial and drift detection. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/SeldonIO/alibi-detect) (👨‍💻 16 · 🔀 140 · 📦 92 · 📋 240 - 32% open · ⏱️ 08.06.2022):

	```
	git clone https://github.com/SeldonIO/alibi-detect
	```
- [PyPi](https://pypi.org/project/alibi-detect) (📥 16K / month):
	```
	pip install alibi-detect
	```
</details>
<details><summary><b><a href="https://github.com/trevorstephens/gplearn">gplearn</a></b> (🥈28 ·  ⭐ 1.1K) - Genetic Programming in Python, with a scikit-learn inspired API. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/trevorstephens/gplearn) (👨‍💻 10 · 🔀 200 · 📦 250 · 📋 190 - 17% open · ⏱️ 03.05.2022):

	```
	git clone https://github.com/trevorstephens/gplearn
	```
- [PyPi](https://pypi.org/project/gplearn) (📥 5.8K / month):
	```
	pip install gplearn
	```
- [Conda](https://anaconda.org/conda-forge/gplearn) (📥 2.4K · ⏱️ 04.05.2022):
	```
	conda install -c conda-forge gplearn
	```
</details>
<details><summary><b><a href="https://github.com/google/trax">Trax</a></b> (🥈27 ·  ⭐ 6.9K) - Trax Deep Learning with Clear Code and Speed. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/google/trax) (👨‍💻 78 · 🔀 700 · 📦 57 · 📋 210 - 41% open · ⏱️ 07.06.2022):

	```
	git clone https://github.com/google/trax
	```
- [PyPi](https://pypi.org/project/trax) (📥 4.7K / month):
	```
	pip install trax
	```
</details>
<details><summary><b><a href="https://github.com/tableau/TabPy">TabPy</a></b> (🥈27 ·  ⭐ 1.3K) - Execute Python code on the fly and display results in Tableau visualizations:. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/tableau/TabPy) (👨‍💻 46 · 🔀 470 · 📦 91 · 📋 290 - 3% open · ⏱️ 31.03.2022):

	```
	git clone https://github.com/tableau/TabPy
	```
- [PyPi](https://pypi.org/project/tabpy) (📥 23K / month):
	```
	pip install tabpy
	```
- [Conda](https://anaconda.org/anaconda/tabpy-client) (📥 2.9K · ⏱️ 02.05.2022):
	```
	conda install -c anaconda tabpy-client
	```
</details>
<details><summary><b><a href="https://github.com/scikit-learn-contrib/metric-learn">metric-learn</a></b> (🥈27 ·  ⭐ 1.2K) - Metric learning algorithms in Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/scikit-learn-contrib/metric-learn) (👨‍💻 22 · 🔀 220 · 📦 210 · 📋 160 - 27% open · ⏱️ 11.03.2022):

	```
	git clone https://github.com/scikit-learn-contrib/metric-learn
	```
- [PyPi](https://pypi.org/project/metric-learn) (📥 20K / month):
	```
	pip install metric-learn
	```
- [Conda](https://anaconda.org/conda-forge/metric-learn) (📥 5.9K · ⏱️ 02.07.2020):
	```
	conda install -c conda-forge metric-learn
	```
</details>
<details><summary><b><a href="https://github.com/sepandhaghighi/pycm">pycm</a></b> (🥉26 ·  ⭐ 1.2K) - Multi-class confusion matrix library in Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/sepandhaghighi/pycm) (👨‍💻 17 · 🔀 100 · 📦 150 · 📋 180 - 6% open · ⏱️ 27.04.2022):

	```
	git clone https://github.com/sepandhaghighi/pycm
	```
- [PyPi](https://pypi.org/project/pycm) (📥 36K / month):
	```
	pip install pycm
	```
</details>
<details><summary><b><a href="https://github.com/ContinualAI/avalanche">avalanche</a></b> (🥉25 ·  ⭐ 950) - Avalanche: an End-to-End Library for Continual Learning based on PyTorch. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/ContinualAI/avalanche) (👨‍💻 57 · 🔀 150 · 📦 9 · 📋 510 - 11% open · ⏱️ 09.06.2022):

	```
	git clone https://github.com/ContinualAI/avalanche
	```
- [PyPi](https://pypi.org/project/avalanche-lib) (📥 730 / month):
	```
	pip install avalanche-lib
	```
</details>
<details><summary><b><a href="https://github.com/MaxHalford/prince">Prince</a></b> (🥉24 ·  ⭐ 810) - Python factor analysis library (PCA, CA, MCA, MFA, FAMD). <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/MaxHalford/prince) (👨‍💻 12 · 🔀 140 · 📦 210 · 📋 110 - 35% open · ⏱️ 28.12.2021):

	```
	git clone https://github.com/MaxHalford/prince
	```
- [PyPi](https://pypi.org/project/prince) (📥 76K / month):
	```
	pip install prince
	```
- [Conda](https://anaconda.org/conda-forge/prince-factor-analysis) (📥 10K · ⏱️ 30.04.2021):
	```
	conda install -c conda-forge prince-factor-analysis
	```
</details>
<details><summary><b><a href="https://github.com/rasbt/biopandas">BioPandas</a></b> (🥉24 ·  ⭐ 470) - Working with molecular structures in pandas DataFrames. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/rasbt/biopandas) (👨‍💻 10 · 🔀 98 · 📦 110 · 📋 43 - 39% open · ⏱️ 13.05.2022):

	```
	git clone https://github.com/rasbt/biopandas
	```
- [PyPi](https://pypi.org/project/biopandas) (📥 4.2K / month):
	```
	pip install biopandas
	```
- [Conda](https://anaconda.org/conda-forge/biopandas) (📥 110K · ⏱️ 13.05.2022):
	```
	conda install -c conda-forge biopandas
	```
</details>
<details><summary><b><a href="https://github.com/ljvmiranda921/pyswarms">PySwarms</a></b> (🥉23 ·  ⭐ 930 · 💤) - A research toolkit for particle swarm optimization in Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/ljvmiranda921/pyswarms) (👨‍💻 43 · 🔀 300 · 📦 170 · 📋 200 - 1% open · ⏱️ 23.06.2021):

	```
	git clone https://github.com/ljvmiranda921/pyswarms
	```
- [PyPi](https://pypi.org/project/pyswarms) (📥 7.5K / month):
	```
	pip install pyswarms
	```
</details>
<details><summary><b><a href="https://github.com/minrk/findspark">findspark</a></b> (🥉22 ·  ⭐ 440) - Find pyspark to make it importable. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/minrk/findspark) (👨‍💻 15 · 🔀 67 · 📦 2.5K · 📋 22 - 50% open · ⏱️ 11.02.2022):

	```
	git clone https://github.com/minrk/findspark
	```
- [PyPi](https://pypi.org/project/findspark) (📥 2.4M / month):
	```
	pip install findspark
	```
- [Conda](https://anaconda.org/conda-forge/findspark) (📥 650K · ⏱️ 11.02.2022):
	```
	conda install -c conda-forge findspark
	```
</details>
<details><summary><b><a href="https://github.com/airbnb/streamalert">StreamAlert</a></b> (🥉21 ·  ⭐ 2.7K · 💤) - StreamAlert is a serverless, realtime data analysis.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/airbnb/streamalert) (👨‍💻 33 · 🔀 320 · 📋 340 - 24% open · ⏱️ 04.11.2021):

	```
	git clone https://github.com/airbnb/streamalert
	```
</details>
<details><summary><b><a href="https://github.com/astroML/astroML">AstroML</a></b> (🥉20 ·  ⭐ 830) - Machine learning, statistics, and data mining for astronomy and.. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/astroML/astroML) (👨‍💻 30 · 🔀 270 · 📋 140 - 37% open · ⏱️ 17.05.2022):

	```
	git clone https://github.com/astroML/astroML
	```
- [PyPi](https://pypi.org/project/astroML) (📥 1.4K / month):
	```
	pip install astroML
	```
- [Conda](https://anaconda.org/conda-forge/astroml) (📥 29K · ⏱️ 02.03.2022):
	```
	conda install -c conda-forge astroml
	```
</details>
<details><summary><b><a href="https://github.com/pykale/pykale">pykale</a></b> (🥉18 ·  ⭐ 340) - Knowledge-Aware machine LEarning (KALE): accessible machine learning.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pykale/pykale) (👨‍💻 16 · 🔀 46 · 📋 87 - 3% open · ⏱️ 18.05.2022):

	```
	git clone https://github.com/pykale/pykale
	```
- [PyPi](https://pypi.org/project/pykale) (📥 44 / month):
	```
	pip install pykale
	```
</details>
<details><summary><b><a href="https://github.com/yzhao062/SUOD">SUOD</a></b> (🥉18 ·  ⭐ 320) - (MLSys 21) An Acceleration System for Large-scare Unsupervised Heterogeneous.. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/yzhao062/SUOD) (🔀 41 · 📦 430 · 📋 9 - 66% open · ⏱️ 11.04.2022):

	```
	git clone https://github.com/yzhao062/SUOD
	```
- [PyPi](https://pypi.org/project/suod) (📥 34K / month):
	```
	pip install suod
	```
</details>
<details><summary><b><a href="https://github.com/eltonlaw/impyute">impyute</a></b> (🥉18 ·  ⭐ 320 · 💤) - Data imputations library to preprocess datasets with missing data. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/eltonlaw/impyute) (👨‍💻 11 · 🔀 44 · 📦 140 · 📋 64 - 42% open · ⏱️ 06.11.2021):

	```
	git clone https://github.com/eltonlaw/impyute
	```
- [PyPi](https://pypi.org/project/impyute) (📥 3.6K / month):
	```
	pip install impyute
	```
</details>
<details><summary><b><a href="https://github.com/SforAiDl/KD_Lib">KD-Lib</a></b> (🥉17 ·  ⭐ 390) - A Pytorch Knowledge Distillation library for benchmarking and.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/SforAiDl/KD_Lib) (👨‍💻 6 · 🔀 34 · 📋 58 - 20% open · ⏱️ 18.05.2022):

	```
	git clone https://github.com/SforAiDl/KD_Lib
	```
- [PyPi](https://pypi.org/project/KD-Lib) (📥 140 / month):
	```
	pip install KD-Lib
	```
</details>
<details><summary><b><a href="https://github.com/jmschrei/apricot">apricot</a></b> (🥉16 ·  ⭐ 420 · 💤) - apricot implements submodular optimization for the purpose of.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jmschrei/apricot) (👨‍💻 4 · 🔀 40 · 📥 10 · 📦 27 · 📋 25 - 28% open · ⏱️ 18.11.2021):

	```
	git clone https://github.com/jmschrei/apricot
	```
- [PyPi](https://pypi.org/project/apricot-select) (📥 290 / month):
	```
	pip install apricot-select
	```
</details>
<details><summary>Show 26 hidden projects...</summary>

- <b><a href="https://github.com/sympy/sympy">SymPy</a></b> (🥇42 ·  ⭐ 9.3K) - A computer algebra system written in pure Python. <code>❗Unlicensed</code>
- <b><a href="https://github.com/carla-simulator/carla">carla</a></b> (🥈29 ·  ⭐ 7.8K · 💤) - Open-source simulator for autonomous driving research. <code>❗Unlicensed</code>
- <b><a href="https://github.com/inducer/pyopencl">pyopencl</a></b> (🥈28 ·  ⭐ 890) - OpenCL integration for Python, plus shiny features. <code>❗Unlicensed</code>
- <b><a href="https://github.com/explosion/cython-blis">Cython BLIS</a></b> (🥈28 ·  ⭐ 190) - Fast matrix-multiplication as a self-contained Python.. <code>❗Unlicensed</code>
- <b><a href="https://github.com/deepmind/pysc2">pysc2</a></b> (🥈27 ·  ⭐ 7.5K · 💀) - StarCraft II Learning Environment. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/uber/causalml">causalml</a></b> (🥈27 ·  ⭐ 3.1K) - Uplift modeling and causal inference with machine learning.. <code>❗Unlicensed</code>
- <b><a href="https://github.com/tensorly/tensorly">tensorly</a></b> (🥈27 ·  ⭐ 1.2K) - TensorLy: Tensor Learning in Python. <code>❗Unlicensed</code>
- <b><a href="https://github.com/JustGlowing/minisom">minisom</a></b> (🥈27 ·  ⭐ 1.1K) - MiniSom is a minimalistic implementation of the Self Organizing.. <code><a href="https://tldrlegal.com/search?q=CC-BY-3.0">❗️CC-BY-3.0</a></code>
- <b><a href="https://github.com/annoviko/pyclustering">pyclustering</a></b> (🥈27 ·  ⭐ 970 · 💀) - pyclustring is a Python, C++ data mining library. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/datalad/datalad">datalad</a></b> (🥈27 ·  ⭐ 320) - Keep code, data, containers under control with git and git-annex. <code>❗Unlicensed</code>
- <b><a href="https://github.com/cleanlab/cleanlab">cleanlab</a></b> (🥉26 ·  ⭐ 3.5K) - The standard data-centric AI package for data quality and machine.. <code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code>
- <b><a href="https://github.com/facebookresearch/AugLy">AugLy</a></b> (🥉24 ·  ⭐ 4.5K) - A data augmentations library for audio, image, text, and video. <code>❗Unlicensed</code>
- <b><a href="https://github.com/modAL-python/modAL">modAL</a></b> (🥉23 ·  ⭐ 1.7K · 💀) - A modular active learning framework for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/Project-MONAI/MONAILabel">MONAILabel</a></b> (🥉23 ·  ⭐ 250) - MONAI Label is an intelligent open source image labeling and.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/flennerhag/mlens">mlens</a></b> (🥉21 ·  ⭐ 740 · 💀) - ML-Ensemble high performance ensemble learning. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/vecxoz/vecstack">vecstack</a></b> (🥉21 ·  ⭐ 660 · 💀) - Python package for stacking (machine learning technique). <code>❗Unlicensed</code>
- <b><a href="https://github.com/ml-tooling/opyrator">opyrator</a></b> (🥉20 ·  ⭐ 2.6K · 💀) - Turns your machine learning code into microservices with web API,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/kLabUM/rrcf">rrcf</a></b> (🥉19 ·  ⭐ 380 · 💀) - Implementation of the Robust Random Cut Forest algorithm for anomaly.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/alegonz/baikal">baikal</a></b> (🥉17 ·  ⭐ 590 · 💀) - A graph-based functional API for building complex scikit-learn.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/EpistasisLab/scikit-rebate">scikit-rebate</a></b> (🥉16 ·  ⭐ 360 · 💀) - A scikit-learn-compatible Python implementation of.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/pandas-ml/pandas-ml">pandas-ml</a></b> (🥉16 ·  ⭐ 290 · 💀) - pandas, scikit-learn, xgboost and seaborn integration. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/facebookresearch/NeuralCompression">NeuralCompression</a></b> (🥉14 ·  ⭐ 260) - A collection of tools for neural compression enthusiasts. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/solegalli/feature_engine">Feature Engine</a></b> (🥉14 ·  ⭐ 18 · 💤) - Feature engineering package with sklearn like functionality. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/jrieke/traingenerator">traingenerator</a></b> (🥉13 ·  ⭐ 1.2K · 💀) - A web app to generate template code for machine learning. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/dstackai/dstack">dstack</a></b> (🥉12 ·  ⭐ 45 · 🐣) - dstack: continuous training in the cloud. <code>❗Unlicensed</code>
- <b><a href="https://github.com/Palashio/nylon">nylon</a></b> (🥉10 ·  ⭐ 77 · 💤) - An intelligent, flexible grammar of machine learning. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
</details>

---

## Related Resources

- [**Papers With Code**](https://paperswithcode.com): Discover ML papers, code, and evaluation tables.
- [**Sotabench**](https://sotabench.com): Discover & compare open-source ML models.
- [**Google Dataset Search**](https://toolbox.google.com/datasetsearch): Dataset search engine by Google.
- [**Dataset List**](https://www.datasetlist.com/): List of the biggest ML datasets from across the web.
- [**Awesome Public Datasets**](https://github.com/awesomedata/awesome-public-datasets): A topic-centric list of open datasets.
- [**Best-of lists**](https://best-of.org): Discover other best-of lists with awesome open-source projects on all kinds of topics.
- [**best-of-python-dev**](https://github.com/ml-tooling/best-of-python-dev): A ranked list of awesome python developer tools and libraries.
- [**best-of-web-python**](https://github.com/ml-tooling/best-of-web-python): A ranked list of awesome python libraries for web development.

## Contribution

Contributions are encouraged and always welcome! If you like to add or update projects, choose one of the following ways:

- Open an issue by selecting one of the provided categories from the [issue page](https://github.com/ml-tooling/best-of-ml-python/issues/new/choose) and fill in the requested information.
- Modify the [projects.yaml](https://github.com/ml-tooling/best-of-ml-python/blob/main/projects.yaml) with your additions or changes, and submit a pull request. This can also be done directly via the [Github UI](https://github.com/ml-tooling/best-of-ml-python/edit/main/projects.yaml).

If you like to contribute to or share suggestions regarding the project metadata collection or markdown generation, please refer to the [best-of-generator](https://github.com/best-of-lists/best-of-generator) repository. If you like to create your own best-of list, we recommend to follow [this guide](https://github.com/best-of-lists/best-of/blob/main/create-best-of-list.md).

For more information on how to add or update projects, please read the [contribution guidelines](https://github.com/ml-tooling/best-of-ml-python/blob/main/CONTRIBUTING.md). By participating in this project, you agree to abide by its [Code of Conduct](https://github.com/ml-tooling/best-of-ml-python/blob/main/.github/CODE_OF_CONDUCT.md).

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg)](https://creativecommons.org/licenses/by-sa/4.0/)
