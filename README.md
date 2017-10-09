## A Tensorflow_Win (Python 3.x) Version of BichenWu's Tensorflow Implementation of SqueezeDet

Totally Based on this project:
https://github.com/BichenWuUCB/squeezeDet

### 2017.10.09
A few py2-py3 changes to make it working on Windows 10.

#### 1. import error in Python 3.x
Such as :
```python
# from kitti_model_config import kitti_model_config
from config.kitti_model_config import kitti_model_config
```

#### 2. ',' in Exception Statement
```python
# except Exception, e:
except Exception as e:
```

#### 3. cPickle
```python
# import cPickle
import pickle as cPickle
```

#### 4. print
```python
# print something
print (something)
```
