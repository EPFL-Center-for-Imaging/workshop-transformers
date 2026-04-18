![EPFL Center for Imaging logo](https://imaging.epfl.ch/resources/logo-for-gitlab.svg)
# Fine-Tuning Machine Learning Models with the `transformers` Library

This workshop introduces a workflow for training custom machine learning models using the `transformers` library from HuggingFace. It walks through:

- Running pre-trained models from the HuggingFace Hub
- Loading and working with image datasets
- Fine-tuning and evaluating an image classifier
- Deploying the model as a small web app

## Installation

Make sure to have a working [Python setup](https://epfl-center-for-imaging.github.io/python-setup/). Install the packages listed in [requirements.txt](./requirements.txt):

```bash
pip install -r requirements.txt
```

The requirements include [`transformers`](https://pypi.org/project/transformers/), [`datasets`](https://pypi.org/project/datasets/), and a few other scientific Python libraries.

## Quick start

Open the notebook [intro_model_finetuning.ipynb](./intro_model_finetuning.ipynb) and follow the instructions.

## License

This workshop material is distributed under the terms of the [BSD-3](http://opensource.org/licenses/BSD-3-Clause) license.
