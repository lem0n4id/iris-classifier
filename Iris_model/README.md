# Iris classifier

Check out [iris_classifier.ipyb](iris_classifier.ipyb) for the code

Iris dataset - [iris.csv](iris.csv)


## Instructions to load the model

```
import pickle
f = open('my_model.pickle', 'rb')
model = pickle.load(f)
f.close()
```