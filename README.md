# Recognition of cancer cells

Data science project. The neural network model categorizes different cancerous skin changes. The data used to train the model is from [Kaggle](https://www.kaggle.com/kmader/skin-cancer-mnist-ham10000?fbclid=IwAR0JBQA56h2px1Uzw8rxmv-4QTMT_1bnOx395MLhgX3timx6Xw6VYFMIS4g)

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

