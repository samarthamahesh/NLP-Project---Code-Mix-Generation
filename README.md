# Code Mix Generation (Project)

*Multilinguals_1394*

*Sriharshitha Bondugula (2018111013)*

*Samartha S M (2018101094)*

Mentor - Prashant Kodali

### How to execute the code

There are different jupyter notebook files in the src directory for different models.

To open any jupyter notebook file,

```python
$ cd src
$ jupyter notebook model<N>.py
```

where, N is the model ID as mentioned below,

N = 1 : Baseline model

N = 2 : Improved model 1 (using unk tokens)

N = 3 : Improved model 2 (using language information)

N = 4 : Improved model 3 (using both language information and unk tokens)

Some variables will have to be set in the jupyter notebook file before running the cells

**Dataset path**: File path which contains the dataset (separate for train and test set)

**Model path**: File path where you want to store the model instance

Outputs are in the folder /outputs.
> Saved models in /outputs/models

> Outputs of corresponding models in /outputs/model_id

### Related Links

Dataset link: https://iiitaphyd-my.sharepoint.com/:f:/g/personal/prashant_kodali_research_iiit_ac_in/EsSRXSdygL5DmyTaV-2oWxcB9t7NHA9oB5_ugYwp_HftYA?e=2iaTE1

Model checkpoints link: https://drive.google.com/file/d/187annbuwDM-N2xpMztZ0rtiOJXQMDP1w/view?usp=sharing
