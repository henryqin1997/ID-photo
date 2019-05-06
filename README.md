# ID-photo
Try to build a Neural Network to change a person's photo into ID photo. For both interest and practice.

If using deeplab and tensorflow, linux is preferred rather than mac os. Mac will have following error:
```
Traceback (most recent call last):
  File "/Users/qin/anaconda3/lib/python3.6/site-packages/tensorflow/python/pywrap_tensorflow.py", line 41, in <module>
    from tensorflow.python.pywrap_tensorflow_internal import *
  File "/Users/qin/anaconda3/lib/python3.6/site-packages/tensorflow/python/pywrap_tensorflow_internal.py", line 28, in <module>
    _pywrap_tensorflow_internal = swig_import_helper()
  File "/Users/qin/anaconda3/lib/python3.6/site-packages/tensorflow/python/pywrap_tensorflow_internal.py", line 24, in swig_import_helper
    _mod = imp.load_module('_pywrap_tensorflow_internal', fp, pathname, description)
  File "/Users/qin/anaconda3/lib/python3.6/imp.py", line 243, in load_module
    return load_dynamic(name, filename, file)
  File "/Users/qin/anaconda3/lib/python3.6/imp.py", line 343, in load_dynamic
    return _load(spec)
ImportError: dlopen(/Users/qin/anaconda3/lib/python3.6/site-packages/tensorflow/python/_pywrap_tensorflow_internal.so, 10): Library not loaded: @rpath/libcublas.8.0.dylib
  Referenced from: /Users/qin/anaconda3/lib/python3.6/site-packages/tensorflow/python/_pywrap_tensorflow_internal.so
  Reason: image not found
```
and the solution can be found at:
  https://github.com/tensorflow/tensorflow/issues/19720    answered by IRonJ   
