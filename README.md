# Tensorflow Notes

```bash
$ pip install --upgrade tensorflow
$ pip freeze | grep tensorflow
## tensorflow==1.1.0
```

To run jupyter notebooks.

```bash
pip install jupyter
```

These are various things I needed to install to run the example notebooks properly.

```bash
pip install pandas
pip install sklearn
pip install matplotlib
pip install sklearn
pip install scipy
pip install -U scikit-learn
pip install h5py
pip install pillow
```

I've installed using virtualenv following the instructions [here](https://www.tensorflow.org/install/install_mac).  

Added this function to my bash profile so I can start the tensorflow shell with `tf`.

```bash
# Start tensorflow shell
function tf {
    source ~/tensorflow/bin/activate
}
```
