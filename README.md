To load the data, you can use

```python
data = np.load(npz_path)
X_train, y_train, X_test, y_test = data['X_train'], data['y_train'], data['X_test'], data['y_test']
```
