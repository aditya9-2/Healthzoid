### Healthzoid using Convolution Neural Networks and Machine Learning



## Acknowledgements

Covid 19

- [Joseph Paul Cohen and Paul Morrison and Lan Dao. COVID-19 image data collection, arXiv, 2020](https://github.com/ieee8023/covid-chestxray-dataset)
- [Jordan Micah Bennett](https://github.com/JordanMicahBennett/SMART-CT-SCAN_BASED-COVID19_VIRUS_DETECTOR/)
  Brain tumour
- [Kaggle Dataset](https://www.kaggle.com/code/ucrkmveri/brain-tumour-detection-using-vgg16/data)
  Breast Cancer
- [Kaggle Dataset](https://www.kaggle.com/datasets/yasserh/breast-cancer-dataset)
  Alzheimer
- [Kaggle Dataset](https://www.kaggle.com/datasets/sachinkumar413/alzheimer-mri-dataset)
  Diabetes
- [Kaggle Dataset](https://www.kaggle.com/datasets/mathchi/diabetes-data-set)
  Pneumonia
- [Kaggle Dataset](https://www.kaggle.com/code/amyjang/tensorflow-pneumonia-classification-on-x-rays/)
  Heart Disease
- [Kaggle Dataset](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset)
  Parkinson's
- [Kaggle Dataset](https://www.kaggle.com/datasets/vikasukani/parkinsons-disease-data-set)

## Appendix

Healthzoid is 8-in-1 multi-disease detection system. It supports prediction for brain tumour, breast cancer, alzheimer, diabetes, pneumonia, heart disease, and Parkinson's disease.
It is a machine learning, deep learning enabled medical system. It has the potential to decrease the ongoing activity to doctors for prediction of a disease.

1. It is a cost-optimized model -- you can detect wheter you have a chronic disease at you leisure, just sitting at home.
2. Prevention is always better than cure -- due to people's lifestyles in the modern society, catching a chronic disease like diabeteshas become quite common. To prevent and find out earlier whether you have got a disease.
3. We plan to implement IOT in this project and further retrain our models for a more better and accurate understanding.

## Authors

- [@aditya9-2](https://github.com/aditya9-2)
- [@Projato](https://github.com/Projato)
- [@Apexecti](https://github.com/apexecti)

## Demo

https://prnt.sc/4fSXiuhoELMF

https://prnt.sc/TkVKfc6KhqoE

https://prnt.sc/kpVsK5yViMf1

## Run Locally

Create a conda environment

```bash
  conda create -n healthzoid python=3.9
```

Go to the project directory

```bash
  cd healthzoid
```

Install dependencies

```bash
  conda activate healthzoid
  pip install opencv-python numpy tensorflow sklearn imutils flask xgboost
```

You can use conda too.

Start the server

```bash
  flask run
```
## License

[MIT](https://choosealicense.com/licenses/mit/)
