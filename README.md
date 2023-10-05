# emotion-detection
# Emotion detection using deep learning

## Introduction

* To install the required packages, run `pip install -r requirements.txt`.


* Download the FER-2013 dataset inside the `src` folder.
* ## Data Preparation (optional)

* The [original FER2013 dataset in Kaggle](https://www.kaggle.com/deadskull7/fer2013) 

* If you want to train this model, use:  

```bash
cd src
python emotions.py --mode train
```

* pre-trained model from [here](https://drive.google.com/file/d/1FUn0XNOzf-nQV7QjbBPA6-8GLoHNNgv-/view?usp=sharing) 

```bash
cd src
python emotions.py --mode display
```

* The folder structure is of the form:  
  src:
  * data (folder)
  * `emotions.py` (file)
  * `haarcascade_frontalface_default.xml` (file)
  * `model.h5` (file)



