# ohbm-handson-test
explains how to reproduce my awesome publication

1. "code" includes python scripts
2. "data" includes thicknessdata from 259 subjects

# install the required python packages with pip

```
pip install -r requirements.txt
```

# clone and install the brainstat

```
git clone https://github.com/MICA-MNI/BrainStat.git
cd BrainStat
python3 setup.py build
python3 setup.py install --user
```

# running the code
navigate to the "code" directory firstly and run the "analysis_01.py" script. 

```
$ cd code
$ python3 analysis_01.py
```

