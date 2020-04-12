# Recognition of cancer cells

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/80x15.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a> due to the fact that the data is licensed this way and also under the Apache License 2.0

Data science project. The neural network model categorizes different cancerous skin changes. The data used to train the model is from [Kaggle](https://www.kaggle.com/kmader/skin-cancer-mnist-ham10000?fbclid=IwAR0JBQA56h2px1Uzw8rxmv-4QTMT_1bnOx395MLhgX3timx6Xw6VYFMIS4g). Our solution is basen on [this kernel](https://www.kaggle.com/sid321axn/step-wise-approach-cnn-model-77-0344-accuracy)

## Project structure

- `data/` - contains all of the data we found in [Kaggle](https://www.kaggle.com/kmader/skin-cancer-mnist-ham10000?fbclid=IwAR0JBQA56h2px1Uzw8rxmv-4QTMT_1bnOx395MLhgX3timx6Xw6VYFMIS4g) and created for training and testing reasons
- `clean/` - contains all notebooks we used to analyze the data and scripts that clean the data and prepare it for further machine learning
- `model/` - contains all notebooks and scripts used to define and train our neural network model

## Development

To run the project you should install all dependencies first. To do it in a clean manner install all of them in [the virtualenv](https://uoa-eresearch.github.io/eresearch-cookbook/recipe/2014/11/26/python-virtual-env/?fbclid=IwAR3dsp4A_Rl_VfkR1El1OIiTwzGj0E4eHdcsjg2L7OHMCdR0Vk5urq1LWwM). If you haven't got it, make sure that your `pip` is in version `3.7` or greater and run:
```bash
pip install virtualenv
```

After doing that run these commands before changing the code to open the virtual environment and install dependencies:
```bash
virtualenv .env # This command you should run only for the first time to create your virtual environment

source .env/bin/activate 
pip install -r requirements.txt
```

After making your changes update the dependencies list and close the virtual environment before submitting the pull request:
```bash
pip freeze > requirements.txt
deactivate
``` 

Then commit your changes and submit a pull request! 

## Contributors 

- [Michał Herjan](https://github.com/Argo123)
- [Franciszek Pogodziński](https://github.com/franpog859)
- [Paulina Urbaś](https://github.com/paulinaurbas)

